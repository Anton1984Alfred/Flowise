# KI-Telefonassistent – Machbarkeitsprüfung

Ziel: Ein KI-Assistent nimmt eingehende Anrufe (z. B. für die Garten- und Landschaftsbau Alfred GmbH) an, beantwortet Standardfragen, nimmt Anfragen/Aufträge auf und legt sie strukturiert ab (CRM, E-Mail, Kalender).

**Kurzfazit:** Machbar. Du musst Telefonie und Sprachverarbeitung nicht selbst bauen. Du setzt eine Voice-Agent-Plattform ein und verbindest sie mit deiner eigenen Logik (Wissen, CRM, Kalender). Ein belastbarer Prototyp ist in **1–3 Tagen** machbar, ein produktiv nutzbarer Assistent in **2–4 Wochen** nebenbei. Die laufenden Kosten liegen je nach Anbieter grob bei **0,10–0,30 € pro Gesprächsminute** plus Rufnummer.

---

## 1. Wie so ein System aufgebaut ist

```
Anrufer ──► Rufnummer (SIP/Telefonie) ──► Voice-Agent-Plattform ─────────────► Aktionen
            (Twilio, sipgate, Telekom)    • Spracherkennung (STT)               • Zoho CRM: Lead anlegen
            ggf. Rufumleitung             • LLM (Gesprächslogik)                • Kalender: Termin
            von bestehender Nummer        • Sprachausgabe (TTS)                 • E-Mail/Teams: Notiz
                                          • Unterbrechungen, Pausen             • Flowise: Wissen/RAG
```

Die drei harten Probleme sind **Latenz** (Antwort in unter ca. 1 s), **Barge-in** (der Anrufer unterbricht) und **Telefonie**. Diese löst die Plattform. Dein Mehrwert ist die **Geschäftslogik**: was der Assistent weiß, welche Daten er abfragt und wohin er sie schreibt.

## 2. Drei Wege im Vergleich

| Weg | Beispiele | Aufwand | Kontrolle | Wann sinnvoll |
|---|---|---|---|---|
| **A. Fertiger Anbieter (SaaS)** | fonio.ai, Telli, sipgate AI-Assistent, Aircall AI | Stunden | gering | Schnell starten, wenig Technik |
| **B. Voice-Plattform + eigene Logik** *(Empfehlung)* | Vapi, Retell AI, ElevenLabs Agents, Synthflow | Tage | hoch | Eigene Abläufe, CRM-Anbindung, eigener Prompt |
| **C. Komplett selbst bauen** | Twilio Media Streams + OpenAI Realtime / Pipecat / LiveKit Agents | Wochen | voll | Große Volumen, Kostenoptimierung, Entwicklerteam |

**Empfehlung: Weg B.** Die Plattform übernimmt Telefonie, Sprache und Latenz. Du konfigurierst Prompt, Stimme und Tools (Webhooks). Später lässt sich auf Weg C wechseln, wenn das Volumen es rechtfertigt.

## 3. Rolle von Flowise (dieses Repository)

Flowise eignet sich als **Gehirn bzw. Tool-Backend** hinter der Voice-Plattform, aber **nicht als Telefonie-Lösung**:

- Vorhanden: Speech-to-Text (`packages/components/src/speechToText.ts`: OpenAI Whisper, AssemblyAI, Azure, Groq, LocalAI) und Text-to-Speech (`packages/components/src/textToSpeech.ts`: OpenAI, ElevenLabs). Diese sind für den Chat-Widget-Einsatz gedacht und arbeiten runden-basiert, nicht in Echtzeit.
- Nicht vorhanden: Telefonie/SIP, Echtzeit-Audio-Streaming, Twilio-Anbindung.
- Nützlich: Agentflows mit Tools (`packages/components/nodes/tools/`: Google Calendar, Microsoft Outlook, Gmail, Microsoft Teams, Requests POST, MCP, Custom Tool), Vektorspeicher/RAG für Firmenwissen (Leistungen, Preise, Einzugsgebiet, FAQs) und die REST-API `/api/v1/prediction/{flowId}`.

**Sinnvolles Muster:** Die Voice-Plattform ruft bei Bedarf per Tool-Webhook einen Flowise-Flow auf, z. B. `wissen_abfragen(frage)` oder `anfrage_speichern(name, telefon, adresse, anliegen)`. Flowise erledigt RAG und das Schreiben ins CRM. Für das eigentliche Gespräch nutzt du das schnelle LLM der Plattform, nicht Flowise. So vermeidest du zusätzliche Latenz im Gesprächsfluss.

## 4. Bausteine (Tools, Repositories, Konnektoren)

**Telefonie / Rufnummer**
- Twilio: deutsche Nummern mit Adress- und Identitätsnachweis (Regulatory Bundle)
- sipgate: deutscher Anbieter mit API, einfach für Rufumleitung
- Alternativ: bestehende Firmennummer bei Nichterreichbarkeit oder nach X Sekunden auf die KI-Nummer umleiten (**empfohlen für den Start**)

**Voice-Agent-Plattformen (Weg B)**
- Vapi (vapi.ai): sehr flexibel, Custom-LLM- und Tool-Webhooks
- Retell AI (retellai.com): gute Latenz, einfache Oberfläche
- ElevenLabs Conversational AI / Agents: sehr gute deutsche Stimmen
- Synthflow: No-Code, sehr einfach

**Open-Source-Repositories (Weg C)**
- `pipecat-ai/pipecat`: Python-Framework für Voice-Agents (Twilio, Daily, viele STT/TTS/LLM)
- `livekit/agents`: Echtzeit-Voice-Agents inkl. SIP-Telefonie
- `twilio-samples/speech-assistant-openai-realtime-api-python`: Minimalbeispiel Twilio + OpenAI Realtime
- `FlowiseAI/Flowise` (dieses Repo): Wissen/RAG und Tool-Backend

**Sprache (STT/TTS/LLM)**
- STT: Deepgram (sehr schnell, gutes Deutsch), Azure Speech, Whisper
- TTS: ElevenLabs, Azure Neural Voices (DE), Cartesia
- LLM: Claude (Anthropic), GPT-4o/Realtime, Gemini. Für Telefonie sind schnelle Modelle wichtig.

**Konnektoren zu deinen Systemen**
- Zoho CRM: Lead/Kontakt anlegen, Notiz anhängen (per Zoho API oder Zoho Flow Webhook)
- Microsoft 365: Outlook-Kalender für Rückruf- oder Besichtigungstermine, Mail an das Büro, Teams-Nachricht
- Optional: Make.com, n8n oder Zapier als Klebeschicht zwischen Webhook und CRM ohne Code

**Skills / Wissen, das der Assistent braucht**
- Systemprompt: Rolle, Tonalität (Sie-Form, freundlich, kurz), Firmendaten, Öffnungszeiten
- Wissensbasis: Leistungen (Pflaster, Pflanzung, Pflege, Entwässerung …), Einzugsgebiet Essen und Umgebung, was *nicht* angeboten wird, keine Preiszusagen am Telefon
- Gesprächsleitfaden „Anfrage aufnehmen“: Name, Rückrufnummer, Adresse/Objekt, Art der Arbeit, Fläche/Umfang, gewünschter Zeitraum, Fotos per Mail/WhatsApp anfordern
- Eskalationsregeln: Notfall, Beschwerde, Bestandskunde mit laufender Baustelle → an einen Menschen weiterleiten oder dringenden Rückruf markieren

## 5. Aufwand

| Phase | Inhalt | Aufwand |
|---|---|---|
| Prototyp | Plattform-Account, Testnummer, Prompt, Stimme, Mail mit Gesprächszusammenfassung | 1–3 Tage |
| Integration | Zoho-CRM-Lead, Kalender, Wissensbasis (Flowise oder Plattform-KB) | 3–7 Tage |
| Test & Feinschliff | 30–50 Testanrufe, Dialekt/Lärm, Randfälle, Weiterleitung | 1 Woche |
| Betrieb | Gesprächsprotokolle prüfen, Prompt nachschärfen | ca. 1–2 h/Woche |

## 6. Laufende Kosten (grobe Richtwerte, vor Entscheidung beim Anbieter prüfen)

| Posten | ca. |
|---|---|
| Voice-Plattform inkl. STT/TTS/LLM | 0,08–0,25 €/Min |
| Telefonie (eingehend) | 0,01–0,03 €/Min |
| Rufnummer | 1–5 €/Monat |
| Fertige SaaS-Lösung (Weg A) | ca. 50–300 €/Monat Pauschale plus Minuten |

Beispiel: 300 Anrufe/Monat à 3 Min = 900 Min → etwa **90–250 €/Monat**.

## 7. Recht & Datenschutz (Deutschland/EU)

- **KI-Transparenz (EU AI Act, Art. 50):** Der Anrufer muss erfahren, dass er mit einer KI spricht. Das gehört in die Begrüßung.
- **Aufzeichnung (§ 201 StGB):** Gespräche nur mit Einwilligung aufzeichnen. Alternative: nur Transkript und Zusammenfassung speichern und in der Begrüßung darauf hinweisen.
- **DSGVO:** AVV mit allen Dienstleistern (Plattform, Telefonie, LLM), EU-Hosting bevorzugen, Löschfristen festlegen, Datenschutzerklärung ergänzen.
- **Keine verbindlichen Zusagen:** keine Preise oder Termine fest zusagen; nur „Anfrage aufgenommen, wir melden uns“.

## 8. Konkreter Startvorschlag

1. Account bei **Retell AI** oder **Vapi** (oder ElevenLabs Agents für die beste deutsche Stimme) anlegen und eine Testnummer holen.
2. Systemprompt und Gesprächsleitfaden „Anfrage aufnehmen“ schreiben (inkl. KI-Hinweis in der Begrüßung).
3. Tool/Webhook `anfrage_speichern` erst einmal auf eine E-Mail an das Büro legen (einfachste Version).
4. 20 Testanrufe führen, dann den Prompt nachschärfen.
5. Zoho CRM anbinden (Lead anlegen) und die Wissensbasis per Flowise-Flow ergänzen.
6. Rufumleitung der Firmennummer „bei Nichtannahme nach 20 s“ auf die KI-Nummer einrichten.
