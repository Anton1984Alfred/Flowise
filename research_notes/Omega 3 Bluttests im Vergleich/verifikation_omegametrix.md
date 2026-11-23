# Verifikation Omegametrix HS-Omega-3 Index®: Primärquellen im Volltext

Stand: 23.11.2026. Diese Runde ergänzt und prüft die Notizen in `omegametrix.md`. Kennzeichnung je Fund:
- **[VT]** = Volltext bzw. Originaldokument selbst gelesen
- **[ABS]** = nur PubMed-Abstract gelesen
- **[SNIP]** = nur Suchauszug aus der Vorrunde, in dieser Runde nicht prüfbar

Zugriff in dieser Runde:
- omegametrix.eu: alle HTML-Seiten und PDFs abrufbar. Die DAkkS-Anlage ist ein Scan; ich habe sie als Bild gelesen.
- PubMed: abrufbar, zeitweise mit reCAPTCHA-Sperre.
- PMC: Die HTML-Artikelseiten zeigten eine reCAPTCHA-Sperre. Die Volltexte habe ich über die PMC-OAI-Schnittstelle (www.ncbi.nlm.nih.gov/pmc/oai) geholt. Zitiert wird jeweils die kanonische PMC-URL.
- Nicht erreichbar:
  - Europe PMC REST (www.ebi.ac.uk: Proxy 403; europepmc.org/webservices: 403)
  - link.springer.com (curl: JavaScript-Challenge; WebFetch: Host nicht freigegeben)
  - sciencedirect.com, omegaquant.com, dakks.de (nicht freigegeben)
- lipidworld.biomedcentral.com: kein einschlägiger Artikel identifiziert, daher nicht genutzt.

## 1. omegametrix.eu: Methode, Probenarten, Umrechnung Trockenblut, Stabilität/Ablehnung, 26 Fettsäuren, Befundparameter, Zielbereiche, Akkreditierung, Ringversuche, Preis

### Takeaway
Die Website bestätigt jetzt im Volltext:
- **Trockenblut (DBS) wird als Vollblut gemessen.** Mit einem **"gleitenden Korrekturfaktor"** wird es in einen erythrozytenäquivalenten "berechneten HS-Omega-3 Index®" umgerechnet. Omegametrix räumt selbst ein, dass dieser Wert "nicht so präzise" ist wie der aus EDTA-Blut. Gleichung, Faktor und Validierungsdaten werden nicht veröffentlicht.
- **DAkkS-Akkreditierung:** Urkundenanlage **D-ML-21960-01-00** nach **DIN EN ISO 15189:2024**, gültig ab 12.06.2025. Geltungsbereich: 26 Fettsäuren (%), GC-FID, Matrix **EDTA-Blut und Trockenblut**.
- **Direktpreis:** EDTA 67,54 €, Trockenblut-Set 74,74 € laut FAQ bzw. 74,24 € laut Seite "Testen lassen", jeweils abgerechnet nach GOÄ 2× Ziffer 3726.
- **Ringversuche:** Auf der Website steht dazu nichts.

### Cited Findings

**Methode und Matrix**
- [VT] "Das Messverfahren für die Analyse von EDTA-Blut und Trockenblut ist identisch, aber die Vorbereitung der Proben unterscheidet sich. Bei EDTA-Blutproben können wir die roten Blutkörperchen vom Plasma und dem Buffy Coat trennen, was bei Trockenblutproben nicht möglich ist. Trockenblut besteht also aus dem gesamten Blut. Die Zusammensetzung der Fettsäuren im Vollblut ist etwas anders als in roten Blutkörperchen, da die biologische Variabilität im Plasma höher ist. Deshalb erhalten wir beim HS-Omega-3 Index® aus Trockenblut leicht unterschiedliche Ergebnisse. Im Befund geben wir jedoch den berechneten HS-Omega-3 Index® an. Dafür wandeln wir das Ergebnis aus dem Vollblut mithilfe eines Korrekturfaktors in ein Ergebnis für die roten Blutkörperchen um. Aufgrund der höheren biologischen Variabilität ist das Ergebnis aus Trockenblut nicht so präzise wie das aus EDTA-Blut, bietet aber dennoch einen aussagekräftigen Richtwert." — [Omegametrix FAQ (DE)](https://www.omegametrix.eu/faq-2/). Englisch sinngleich ("we are able to use a correction factor to convert the result into one analogous to that of red blood cells … not quite as precise as that from EDTA blood"). — [Omegametrix FAQ (EN)](https://www.omegametrix.eu/en/faq/)
- [VT] Dokument "Einflussgrößen und Störfaktoren" (OM04-000a v1.0, gültig ab 26.03.2025): "Bei EDTA-Blut können die Fettsäuren in den Erythrozyten vom Plasma getrennt analysiert werden, während Trockenblut die Gesamtblutmatrix enthält. Dies führt zu systematischen Abweichungen, die durch einen **gleitenden Korrekturfaktor** ausgeglichen werden. Eine Verwechslung der Proben kann dennoch fehlerhafte Ergebnisse verursachen." — [OM04-000a PDF](https://www.omegametrix.eu/wp-content/uploads/2025/03/OM04-000a_v1.0_20250326_Einflussgroessen-und-Stoerfaktoren.pdf)
- [VT] Methodensteckbrief auf der Website: "Messtechnik: FID-Gaschromatographie / Matrix: Erythrozyten, Trockenblut / Verfahren: Omegametrix-Methode (OM04-000 v2.0 bzw. OM04-002 v3.1) / Analyt (Messgröße): 26 Fettsäuren (%)". — [Omegametrix: Fettsäuren verstehen](https://www.omegametrix.eu/fettsaeuren-verstehen/)
- [VT] Die 26 Fettsäuren decken laut Omegametrix "über 99 % der wesentlichen Fettsäuren in roten Blutkörperchen" ab. Nicht erfasst sind z. B. "sehr kurzkettige Fettsäuren, Fettsäuren mit einer ungeraden Zahl an Kohlenstoffatomen, sehr langkettige Fettsäuren, und auch verzweigtkettige Fettsäuren". — [FAQ (DE)](https://www.omegametrix.eu/faq-2/)
- [VT] Begründung für relative Prozentwerte statt mg/L: Absolutwerte bräuchten "einen Standard mit bekanntem Wert". Diese Standards seien "oft nicht sehr zuverlässig". Bei relativen Werten "gleichen sich Schwankungen im Standard oder in der Ausgangsmenge aus". — [FAQ (DE)](https://www.omegametrix.eu/faq-2/)
- [VT] Die Ergebnisse hingen "von zahlreichen sensiblen Faktoren ab, wie z. B. der Geometrie der Reaktionsgefäße oder der Auswertungsweise der Chromatogramme". Zum QM gehörten "Kontrollproben, Plausibilitätschecks, geeignete Standards, standardisierte Auswerteverfahren". — [Omegametrix: Über uns](https://www.omegametrix.eu/uber-uns/)
- [VT] Selbstauskunft: "niedrige biologische Variabilität, 1,3 %". Eine Quelle für diese Zahl wird nicht genannt. — [Über uns](https://www.omegametrix.eu/uber-uns/); EN: "(low biological variability, 1.3 %)" — [About us](https://www.omegametrix.eu/en/about-us/)

**Probenhandling, Stabilität, Ablehnung**
- [VT] EDTA-Weg (Anleitung OM07-007a v1.1, gültig ab 19.02.2025):
  - "ca. 2 mL EDTA-Blut", "Der Patient muss zum Zeitpunkt der Abnahme nicht nüchtern sein".
  - Versand "am Tag der Abnahme (!) über den normalen Postweg. Die Probe ist i. d. R. 7 – 10 Tage stabil."
  - "Wir beginnen die Analyse i. d. R. am Ankunftstag der Probe. Die Bearbeitungszeit beträgt ca. 2 Werktage."
  - Blutentnahmesystem und EDTA-Röhrchen gehören nicht zum Versandmaterial.
  — [EDTA-Anleitung PDF](https://www.omegametrix.eu/wp-content/uploads/2025/03/OM07-007a_v1.1_20250219_EDTA-Blutentnahme-und-Versand.pdf); [Testen lassen](https://www.omegametrix.eu/testen-lassen/)
- [VT] **Ablehnungskriterium EDTA:** Proben dürfen "nicht unter 0 °C gelagert werden". Beim Einfrieren und Auftauen platzen die Erythrozyten. Das zeigt sich "nach Zentrifugation … durch fehlende Phasenbildung … Diese EDTA-Blutproben werden verworfen und neues Probenmaterial wird vom Einsender eingefordert." — [OM04-000a PDF](https://www.omegametrix.eu/wp-content/uploads/2025/03/OM04-000a_v1.0_20250326_Einflussgroessen-und-Stoerfaktoren.pdf)
- [VT] **Trockenblut: Nüchternheit ist Pflicht.** "Bei Verwendung von Trockenblut sollte jedoch mindestens 10 Stunden vor der Blutentnahme gefastet werden". — [FAQ](https://www.omegametrix.eu/faq-2/). Begründung: "da im Labor bei der Aufbereitung von Trockenblutproben … eine Trennung der Erythrozyten vom restlichen Vollblut nicht möglich ist … können erhöhte Fettsäuren im Plasma das Ergebnis verfälschen". — [OM04-000a](https://www.omegametrix.eu/wp-content/uploads/2025/03/OM04-000a_v1.0_20250326_Einflussgroessen-und-Stoerfaktoren.pdf)
- [VT] Trockenblut-Handling: "die Kreise auf der Karte möglichst vollständig mit Blut zu füllen". Versand "am Ende der Woche" ist für beide Probenarten erlaubt. Bei der Registrierung im Laborportal werden die Seriennummer der Trockenblutkarte und das Abnahmedatum abgefragt. — [FAQ](https://www.omegametrix.eu/faq-2/)
- [VT] Ergebnis "normalerweise 48 Stunden nach Eingang der Probe". — [FAQ](https://www.omegametrix.eu/faq-2/); [Testen lassen](https://www.omegametrix.eu/testen-lassen/)

**Die 26 Fettsäuren (Wortlaut DAkkS-Anlage)**
- [VT] "Myristin (C14:0), Palmitin (C16:0), Trans-Palmitolein (C16:1n7t), Palmitolein (C16:1n7), Stearin (C18:0), Trans-Öl (C18:1t), Öl (C18:1n9), Trans-Linol (C18:2n6tt), Trans-Linol (C18:2n6ct), Trans-Linol (C18:2n6tc), Linol (C18:2n6), Arachin (C20:0), Gamma-Linolen (C18:3n6), Gondon (C20:1n9), Alpha-Linolen (C18:3n3), Eicosadien (C20:2n6), Behen (C22:0), Dihomo-Gamma-Linolen (C20:3n6), Arachidon (C20:4n6), Lignocerin (C24:0), Eicosapentaen (C20:5n3), Nervon (C24:1n9), Docosatetraen (C22:4n6), Docosapentaen-n6 (C22:5n6), Docosapentaen-n3 (C22:5n3), Docosahexaen (C22:6n3)". — [DAkkS-Anlage D-ML-21960-01-00 (PDF auf omegametrix.eu)](https://www.omegametrix.eu/wp-content/uploads/2025/07/20250612_Anlage_Akkreditierungsurkunde_15189_D-ML-21960-01-00.pdf). Dieselbe Liste steht gruppiert im [Musterbefund v2](https://www.omegametrix.eu/wp-content/uploads/2024/11/Omegametrix_Musterbefund_v2.pdf); dort sind die drei 18:2-trans-Isomere zu einer Zeile zusammengefasst.

**Befundparameter und Zielbereiche (Musterbefund v2, OM06-001a_v02)**
- [VT] Seite 1 enthält:
  - "Probenart" (im Muster: "Erythrozyten")
  - HS-Omega-3 Index® (Ziel "8 % – 11 %")
  - HS-Trans Index® (Ziel "<1.04 %")
  - AA:EPA (Ziel "nicht bekannt")
  - Vermerk "Medizinisch validierter Endbefund von Prof. Dr. med. C. von Schacky"
  
  Seite 5 zeigt das Chromatogramm. Seite 6 zeigt das vollständige Profil mit Gruppensummen und Bereichen. Diese Bereiche (z. B. ΣOmega-3 6,20–17,60 %, ΣOmega-6 22,50–36,30 %, ΣGesättigte 23,80–35,80 %, ΣTrans 0,10–1,30 %) leiten sich laut Fußnote "von ca. 25000 zufällig ausgewählten Messungen mit optimalen HS-Indices ab". — [Musterbefund v2 (DE)](https://www.omegametrix.eu/wp-content/uploads/2024/11/Omegametrix_Musterbefund_v2.pdf); [Sample report (EN)](https://www.omegametrix.eu/wp-content/uploads/2025/02/Samplereport_Omegametrix.pdf)
- [VT] Obergrenze: "Keinesfalls sollte der HS-Omega-3 Index® höher als 15 % sein". Für einzelne Fettsäuren gibt es keine Referenzbereiche, weil dafür Interventionsstudien und Sicherheitsnachweise fehlten. Das sei nur für EPA/DHA und die Trans-Fettsäuren erfolgt, für "die anderen 20 Fettsäuren" noch nicht. — [FAQ](https://www.omegametrix.eu/faq-2/)

**Akkreditierung**
- [VT] DAkkS-Anlage zur Urkunde **D-ML-21960-01-00** "nach DIN EN ISO 15189:2024":
  - Gültig ab 12.06.2025, ausgestellt am 12.06.2025
  - Inhaber und Standort: Omegametrix GmbH, Am Klopferspitz 19, 82152 Martinsried
  - Bereich: "Medizinische Laboratoriumsdiagnostik"
  - Untersuchungsgebiet: "Klinische Chemie"
  - Untersuchungsart: "Chromatographie (Gaschromatographie (GC)) [Flex A]"
  - Analyt: "26 Fettsäuren (%)"; Matrix: "EDTA-Blut, Trockenblut"; Technik: "GC-FID"
  - Flexibler Bereich: Neue Ausgabestände sind nur "ohne das Analyt, Matrix oder Untersuchungstechnik [zu verändern]" erlaubt. Die Liste der Verfahren sei "öffentlich verfügbar auf der Webpräsenz".
  — [DAkkS-Anlage (PDF)](https://www.omegametrix.eu/wp-content/uploads/2025/07/20250612_Anlage_Akkreditierungsurkunde_15189_D-ML-21960-01-00.pdf)
- [VT] Website: "Formalisiert wird unser Qualitätsmanagement von Anfang an gemäß DIN EN ISO 15189. Im ersten Quartal 2024 haben wir zudem die Akkreditierung durch die DAkkS erreicht." — [Über uns](https://www.omegametrix.eu/uber-uns/). Der Musterbefund schreibt: "Unsere Omegametrix-Methode ist nach der Norm DIN EN ISO 15189 akkreditiert". — [Musterbefund v2](https://www.omegametrix.eu/wp-content/uploads/2024/11/Omegametrix_Musterbefund_v2.pdf)
- [VT] **Ringversuche bzw. Eignungsprüfungen:** Auf keiner abgerufenen Seite und in keinem PDF gibt es Angaben zu Anbieter, Häufigkeit oder Ergebnissen (Suche nach "Ringversuch", "INSTAND", "RfB", "proficiency", "Eignungsprüfung" ohne Treffer). — [omegametrix.eu (DE/EN, alle Hauptseiten)](https://www.omegametrix.eu/)

**Preis (Direktbezug)**
- [VT] FAQ (DE und EN): "Die Kosten für die Analyse von EDTA-Blut liegen bei 67,54 €, darin sind die Portokosten enthalten. Bei der Analyse von Trockenblut liegen die Kosten bei 74,74 €, inklusive Portokosten und dem benötigten Material für einmalige Nutzung. Abgerechnet wird nach der Gebührenordnung für Ärzte (GOÄ) zweimal nach Ziffer 3726." Die Rechnung kommt etwa Mitte des Folgemonats nach der Analyse. — [FAQ (DE)](https://www.omegametrix.eu/faq-2/); [FAQ (EN)](https://www.omegametrix.eu/en/faq/)
- [VT] **Widerspruch auf derselben Website:** Die Seite "Testen lassen" nennt für das Blutentnahmeset "74,24 €" (DE und EN: "€74.24"). Der EDTA-Preis ist dort identisch (67,54 €). — [Testen lassen](https://www.omegametrix.eu/testen-lassen/); [Get tested](https://www.omegametrix.eu/en/get-tested/)

**Firma und Volumen**
- [VT] Impressum: Omegametrix GmbH, HRB München 165768, Geschäftsführer Prof. Dr. Clemens von Schacky, USt-IdNr. DE-252145389. Gegründet laut "Über uns" 2007. — [Impressum](https://www.omegametrix.eu/impressum/); [Über uns](https://www.omegametrix.eu/uber-uns/)
- [VT] Publikationsangaben schwanken je Dokument:
  - "über 420" (FAQ)
  - "Mehr als 430 … (Stand: Dezember 2024)" (Über uns)
  - "Mehr als 400 … (Stand: Januar 2024)" (Musterbefund)
  - "around 380" (Neth Heart J 2023)
  - Die PDF-Liste "Publications on HS-Omega-3 Index®, as of May 26, 2025" hat nach eigener Zählung rund 449 nummerierte Einträge. Darin stehen auch OmegaQuant-/Harris-Arbeiten (z. B. Nr. 2–4).
  
  — [Literaturliste PDF](https://www.omegametrix.eu/wp-content/uploads/2025/06/202505_Literatur.pdf); [Neth Heart J 2023, PMC10602979](https://pmc.ncbi.nlm.nih.gov/articles/PMC10602979/)
- [ABS] Probenvolumen (europäische Erythrozytenproben, Autoren von Schacky & Passow, beide Omegametrix): "In 2024, in 2.12% of 20,510 samples, IP-TFA were >1.04%; in 2025, in 4.47% of 27,834 samples; in January - June 2026, in 7.21% of 18,577 samples". — [von Schacky & Passow, Eur J Clin Nutr 2026, PMID 42661050](https://pubmed.ncbi.nlm.nih.gov/42661050/)

### Inferences
- Der DBS-Selbsttest ist ein **Vollblut-Test mit proprietärer Umrechnung**. "Gleitend" heißt vermutlich, dass der Faktor vom Messniveau abhängt (keine einfache Konstante). Die Formel ist nicht veröffentlicht. Für den Vergleich mit Zinzino/Eqology/OmegaQuant-DBS heißt das: Alle DBS-Anbieter, die einen "Omega-3 Index" ausgeben, rechnen Vollblut um. Omegametrix unterscheidet sich darin, dass sein DBS-Verfahren in den DAkkS-Geltungsbereich aufgenommen ist.
- Die Pflicht zum 10-stündigen Fasten nur beim DBS ist ein indirektes Eingeständnis: Die Plasmafraktion im Vollblut beeinflusst das Ergebnis. Händler-Kits, die das Fasten nicht deutlich nennen, wären fehleranfälliger.
- Die DAkkS-Anlage ist datiert auf den 12.06.2025 und bezieht sich auf die Normfassung 2024. Die Website nennt dagegen eine Akkreditierung "im ersten Quartal 2024". Am plausibelsten ist, dass die Anlage 2025 neu ausgestellt wurde (z. B. bei der Umstellung auf ISO 15189:2024). In der DAkkS-Datenbank selbst konnte ich das nicht prüfen.
- Dass der Befund ein Feld "Probenart" enthält, spricht dafür, dass DBS-Befunde als solche erkennbar sind. Gesehen habe ich nur ein Muster mit "Erythrozyten", keinen DBS-Musterbefund.
- Die GOÄ-Abrechnung (2× Nr. 3726) erklärt die "krummen" Preise. Für den Selbsttest gibt es also keinen klassischen Kaufpreis, sondern eine ärztliche Liquidation nach der Analyse.

### Gaps
- Die Gleichung bzw. der "gleitende Korrekturfaktor" für DBS → Erythrozyten und die Validierungsdaten (n, r, Bias, Limits of Agreement, CV für DBS) sind weder auf der Website noch in einer gefundenen Publikation offengelegt.
- Ablehnungskriterien für DBS (unvollständig gefüllte Kreise, Transportdauer, Temperatur) und die DBS-Stabilität sind nicht dokumentiert. Die 7 Tage aus der Vorrunde sind weiterhin nur eine Händlerangabe ([SNIP], Bodelight).
- Ob die Trockenblutkarte des Selbsttest-Kits beschichtet ist, steht nicht auf der Website. Für Studienkarten siehe Abschnitt 2 ("pre-treated with a stabilizer").
- DAkkS-Datenbankeintrag (Status, Erstakkreditierung 2024): dakks.de nicht erreichbar.
- Externe Ringversuche: keine Angaben von Omegametrix.

## 2. Peer-reviewte Methodenbeschreibungen der HS-Omega-3-Index-Analytik (Reagenz, GC, Säule, Standard, CVs, DBS-Umrechnung)

### Takeaway
In Volltexten von Studien, die bei Omegametrix gemessen wurden, steht durchgängig dieselbe Kurzbeschreibung:
- **Saure Umesterung** (das Reagenz wird nie genannt)
- **Shimadzu GC2010 mit 100-m-Säule SP2560 (Supelco)**, **Wasserstoff als Trägergas**
- Identifizierung über ein Standardgemisch (teils **GLC-727, Nu-Chek Prep**)
- **Response-Faktor-Korrektur**, Ergebnis in % der identifizierten Fettsäuren
- **CV für EPA+DHA "5 %"**, QC "nach DIN ISO 15189"

Ein interner Standard, getrennte Intra- und Inter-Assay-CVs und eine eigene Validierungspublikation fehlen. Für DBS beschreiben drei Studien Whatman-903-Filterpapier mit Stabilisator bzw. Antioxidans und eine "sliding correction factor". Als Beleg für die Korrektur zitieren sie nur ein Buchkapitel von 2013 (Harris, von Schacky, Park), nicht eine peer-reviewte Validierung.

### Cited Findings
- [VT] Standardtext (Bauchchirurgie-Studie, TUM 2025): "HS-Omega-3 Index® was measured via standardized gas chromatography in an external certified lab (OMEGAMETRIX GmbH) … Fatty acid methyl esters were obtained through transesterification of erythrocyte fatty acids and analyzed by GC using a GC2010 Gas Chromatograph (Shimadzu, Duisburg, Germany), equipped with an SP2560, 100 m column (Supelco, Bellefonte, PA, USA) and hydrogen as the carrier gas. Fatty acids were identified by comparing them to a reference standard specific to erythrocyte fatty acid profiles. The HS-Omega-3 Index® was determined by summing the concentrations of EPA and DHA, and expressing this sum as a percentage of the total fatty acids detected, after adjusting for response factors. The coefficient of variation for the combined EPA and DHA levels was 5%. The analysis followed stringent quality control protocols in accordance with DIN ISO 15 189 standards." Als Methodenquelle wird Köhler et al., Br J Nutr 2010 genannt. — [Int J Surg 2025, PMC12626584](https://pmc.ncbi.nlm.nih.gov/articles/PMC12626584/)
- [VT] Gleichlautend, mit dem Zusatz "a total of twenty-six specific fatty acids in erythrocytes after response factor correction. The coefficient of variation for EPA plus DHA was 5%. Analyses were quality-controlled according to DIN ISO 15189." Hinweis zum Interessenkonflikt: "Omegametrix® GmbH performed the analysis … free of charge." — [Akne-Querschnittsstudie, Life 2024, PMC11050840](https://pmc.ncbi.nlm.nih.gov/articles/PMC11050840/); [Akne-Interventionsstudie, J Cosmet Dermatol 2024, PMC13648905](https://pmc.ncbi.nlm.nih.gov/articles/PMC13648905/)
- [VT] Ko-Autor von Schacky (Langzeitfasten): "Via acid transesterification fatty acid methyl esters were generated from erythrocytes … GC2010 … SP2560, 100‐m column … To identify the fatty acids, the results were compared to a standard mixture of FA characteristic of erythrocytes. After a response factor correction … The variation coefficient for the Omega‐3 Index was 5%. DIN ISO 15189 was applied for quality control of the analyses." — [Gewecke et al., Eur J Clin Invest 2025, PMC12011679](https://pmc.ncbi.nlm.nih.gov/articles/PMC12011679/)
- [VT] Standard benannt: "by comparison with a known standard (GLC-727; Nuchek Prep, Elysian, MN, USA)". Erythrozyten wurden nach Zentrifugation (3000 rpm, 15 min) bei −80 °C gelagert und dann bei Omegametrix analysiert. — [Krill-Öl-Athletenstudie, Nutrients 2021, PMC8708578](https://pmc.ncbi.nlm.nih.gov/articles/PMC8708578/); ebenso "GLC-727, Nuchek Prep" in [van der Wurff et al., Eur J Nutr 2019, PMC6561989](https://pmc.ncbi.nlm.nih.gov/articles/PMC6561989/)
- [VT] **Trockenblut im Studienkontext (Omegametrix):**
  - "Whole blood was obtained from a finger prick with an automated lancet and directly transferred to a filter paper (Whatman 903, General Electric, Frankfurt, Germany) pre-treated with a stabilizer. Filter papers were shipped immediately to Omegametrix … Since the Omega-3 Index is defined as EPA + DHA in erythrocytes, it was calculated using a sliding correction factor. The coefficient of variation for EPA plus DHA typically is 5%." — [van der Wurff et al., Nutrients 2016, PMC4728627](https://pmc.ncbi.nlm.nih.gov/articles/PMC4728627/)
  - "blood was collected on filtre paper specially prepared with a proprietary antioxidant … after response factor correction and a correction for the fact that whole blood was used instead of erythrocytes". Belegt wird das mit Harris & von Schacky 2004 bzw. mit Harris, von Schacky & Park, "Standardizing methods for assessing omega-3 fatty acid biostatus", in: McNamara (Hrsg.), Nova Science 2013, S. 385–398. — [Eur J Nutr 2019, PMC6561989](https://pmc.ncbi.nlm.nih.gov/articles/PMC6561989/); [Studienprotokoll BMJ Open 2016, PMC4947785](https://pmc.ncbi.nlm.nih.gov/articles/PMC4947785/)
  - Kinderstudie (Wollongong): "Samples were stored on a filter paper provided by Omegametrix and were kept at −80 °C until they were shipped and sent on dry ice … To measure whole blood fatty acid concentrations … GC2010 … SP2560 … Results are expressed as the HS-Omega-3 Index ® … and calculated using a sliding correction factor. The coefficient of variation for the HS-Omega-3 Index ® is approximately 5%." — [Omega Kid Pilot, Nutrients 2021, PMC8539495](https://pmc.ncbi.nlm.nih.gov/articles/PMC8539495/)
- [VT] **Widersprüchliche Methodenbeschreibung mit von Schacky als Ko-Autor:** Die 7-Länder-Arbeit nennt als beteiligte Labors die "of Dr. Yongsoon Park (Seoul, Korea), Dr. Clemens von Schacky (Martinsried, Germany) and Dr. William Harris (Sioux Falls …)". Für alle wird dann beschrieben: "RBC were incubated at 100°C with boron trifluoride–methanol and hexane for 10 minutes … Twenty-one FAs were quantified … The analytical variability of EPA + DHA using the HS-Omega-3 Index ® method is 4.1%±1.9%". Das passt nicht zu den 26 Fettsäuren von Omegametrix und zu deren Formulierung "saure Umesterung". — [Schuchardt et al., PLEFA 2022, PMC10440636](https://pmc.ncbi.nlm.nih.gov/articles/PMC10440636/)
- [ABS] Die zitierte Quelle für "4,1 % ± 1,9 %" (Harris & Thomas 2010) berichtet dagegen einen **biologischen** Within-Subject-CV: "within-subject coefficients of variation were 4.1%+/-1.9%, 15.9%+/-6.4%, and 14.5%+/-8.4%" für Erythrozyten, Plasma und Plasma-Phospholipide (20 Probanden, wöchentlich über 6 Wochen). — [Harris & Thomas, Clin Biochem 2010, PMID 19733159](https://pubmed.ncbi.nlm.nih.gov/19733159/)
- [VT] von Schacky 2023: "The analytical variability of this standardised and robust method is 4%". Belegt mit Proc Nutr Soc 2020. — [Neth Heart J 2023, PMC10602979](https://pmc.ncbi.nlm.nih.gov/articles/PMC10602979/)
- [ABS] Originalarbeit Harris & von Schacky, Prev Med 2004;39:212–220: Das Abstract nennt nur "We conducted clinical and laboratory experiments to generate data necessary for the validation" und keine Laborparameter. Den Volltext (ScienceDirect) konnte ich nicht abrufen. — [PubMed 15208005](https://pubmed.ncbi.nlm.nih.gov/15208005/)
- [ABS] Köhler et al., Br J Nutr 2010 (die von Omegametrix-Studien zitierte Methodenreferenz): Das Abstract enthält keine Laborparameter, nur Ergebnisse. Der Index stieg von 4,37 ± 0,51 % auf 6,80 ± 1,45 %, mit "Interindividual variability in response … cv = 0.21". — [PubMed 20420756](https://pubmed.ncbi.nlm.nih.gov/20420756/)

### Inferences
- Die Omegametrix-Analytik ist in Studien nur als Kurzprotokoll dokumentiert. Eine vollständige, peer-reviewte Validierungsarbeit (Reagenz, Temperatur/Zeit, Temperaturprogramm, Response-Faktoren, Linearität, Intra- und Inter-Assay-CV, Richtigkeit) wurde nicht gefunden. Alle Studien wiederholen pauschal "CV 5 %".
- Ein interner Standard wird nirgends erwähnt. Das passt zur FAQ, die absolute Konzentrationen ablehnt und relative Flächenprozente bevorzugt.
- Der DBS-Korrekturfaktor beruht in der Literatur nur auf einem nicht peer-reviewten Buchkapitel (2013). Eine öffentliche Vergleichsstudie DBS gegen venöse Erythrozyten von Omegametrix fehlt. Bei OmegaQuant gibt es eine solche Studie (Harris & Polreis 2016, siehe `omegametrix.md`).
- Die 4,1-%-Angabe der 7-Länder-Arbeit ist wohl eine Fehlzuschreibung: biologische Variabilität wird dort als "analytical variability" bezeichnet. Außerdem passt die BF3-Beschreibung mit 21 Fettsäuren zu OmegaQuant, nicht nachweislich zu Omegametrix.

### Gaps
- Das genaue Derivatisierungsreagenz bei Omegametrix (z. B. methanolische HCl, Acetylchlorid oder BF3), Temperatur und Zeit sowie das GC-Temperaturprogramm: in keiner Volltextquelle genannt.
- Getrennte Intra- und Inter-Assay-CVs, niveauabhängige CVs und die DBS-spezifische Präzision von Omegametrix: nicht gefunden.
- Das Buchkapitel Harris/von Schacky/Park 2013 (Nova) war nicht zugänglich. Ob es die DBS-Korrekturgleichung enthält, ist offen.

## 3. von Schackys veröffentlichte Aussagen zur Vergleichbarkeit anderer Labormethoden (Vollblut, DBS, andere Panels)

### Takeaway
Von Schacky argumentiert gleichbleibend:
- Kleine Methodenunterschiede führen zu großen Ergebnisunterschieden.
- Ergebnisse nicht standardisierter Labors am Zielbereich 8–11 % zu messen, sei ein ethisches Problem.
- Erythrozyten seien wegen geringer biologischer Variabilität vorzuziehen.
- Sein Hauptbeleg ist ein Fünf-Labor-Vergleich mit einem Faktor 3,5 Unterschied. Dieser stammt aus dem Buchkapitel von 2013.

Zu DBS äußert er sich in den abrufbaren Volltexten nur indirekt ("as different from dried blood spots"). Die DBS-Aussagen im J Clin Lipidol 2025 bleiben ungeprüft.

### Cited Findings
- [ABS] Proc Nutr Soc 2020: "An omega-3 index is measured in many laboratories around the world; however, even small differences in analytical methods entail large differences in results. Nevertheless, results are frequently related to the target range of 8-11 %, defined for the original and scientifically validated method (HS-Omega-3 Index(®)), raising ethical issues, and calling for standardisation." — [von Schacky, Proc Nutr Soc 2020;79:381–387, PMID 32389149](https://pubmed.ncbi.nlm.nih.gov/32389149/)
- [VT] Nutrients 2014: "In fatty acid analysis, methods have a large impact on results: when one sample was sent to five different laboratories offering determination of an Omega-3 Index, results differed by a factor of 3.5 [34]. While results may be internally valid in one laboratory, a difference by a factor of 3.5 makes it impossible to compare results among laboratories. Therefore, the Omega-3 Index was renamed HS-Omega-3 Index ®. In contrast, the laboratories adhering to the HS-Omega-3 Index methodology perform regular proficiency testing, as mandated in routine Clinical Chemistry labs [34]. So far, the HS-Omega-3 Index is the only analytical procedure used in several laboratories." Referenz [34] ist das Buchkapitel Harris, von Schacky & Park 2013 (Nova). — [von Schacky, Nutrients 2014;6:799–814, PMC3942733](https://pmc.ncbi.nlm.nih.gov/articles/PMC3942733/)
- [VT] Neth Heart J 2023 (von Schacky, Kuipers, Pijl, Muskiet, Grobbee):
  - "It is widely used in Europe—it is identical to the method used in specific laboratories in the USA and Asia—and regularly subjected to rigorous proficiency testing [4]. Analysing the Omega‑3 Index with other methods has yielded different results [4]. Thus, while other methods may produce valid results within a study (internal validity), the standardised method produces results that are comparable with those generated using the same method in a different study (external validity)"
  - "A serious limitation is that laboratories provide results from other FA compartments (e.g. serum) or from non-standardised analyses of red blood cells that usually differ, sometimes substantially, from the results of standardised analyses of red blood cells [4]. Moreover, some laboratories relate the results they derive from non-standardised methods to the target range defined for the standardised analyses [4]. The consequence will be either over-ingestion or under-ingestion of EPA and DHA … providing results from non-standardised or harmonised analyses must be considered an ethical [issue]"
  - Zu Phospholipiden: "no standardised analytical method has been established for FAs in plasma phospholipids"
  - "Several laboratories, including large chains in Germany, have successfully adopted the standardised analytical method"
  
  — [Neth Heart J 2023;31:415–423, PMC10602979](https://pmc.ncbi.nlm.nih.gov/articles/PMC10602979/)
- [VT] Nutrients 2020 (Schwangerschaft): "neither in pregnant women nor in any other individual has an Omega-3 Index <2% ever been found in erythrocytes (as different from dried blood spots)". Außerdem: "As yet, no standardized analytical procedure has been suggested for any other fatty acid compartment." — [von Schacky, Nutrients 2020;12:898, PMC7230742](https://pmc.ncbi.nlm.nih.gov/articles/PMC7230742/)
- [VT] Nutrients 2017: "we compared only trials that used an identical analytical procedure … This analytical procedure, the HS-Omega-3 Index, is probably currently the most widely used, and we suggest it to be used in future investigations in order to make future results comparable to present results". — [Köhler, Heinrich, von Schacky, Nutrients 2017, PMC5490608](https://pmc.ncbi.nlm.nih.gov/articles/PMC5490608/)
- [VT] Website: "Andere Methoden ergeben andere Ergebnisse und erfassen oft weniger Fettsäuren und geben daher ein falsches und unvollständiges Bild." — [Über uns](https://www.omegametrix.eu/uber-uns/)
- [ABS-Metadaten] J Clin Lipidol 2025;19(2):208–214, "Assessing omega-3 fatty acids–critically weighing options and relevance": In PubMed ohne Abstract, Volltext (ScienceDirect) nicht erreichbar. Die Aussage aus der Vorrunde zur Vollblut-Variabilität "around 6%–7%" bleibt **[SNIP]**. — [PubMed 40050195](https://pubmed.ncbi.nlm.nih.gov/40050195/)
- [SNIP, nicht neu geprüft] Zitat "Eventually, we had to trademark it…" — [NutraIngredients 2019](https://www.nutraingredients.com/Article/2019/02/21/Lessons-from-the-Omega-3-Index-Why-accurate-testing-and-increasing-intake-is-a-matter-of-life-and-death/)

### Inferences
- Die Kernkritik "andere Methoden, anderer Nenner, nicht am Zielbereich messbar" ist in von Schackys peer-reviewten Volltexten klar belegt. Der zentrale empirische Beleg (Faktor 3,5) ist aber weder peer-reviewt noch datiert. Laborzahl und -identität sind nur aus dem Buchkapitel zu erfahren.
- Von Schacky grenzt DBS-Werte implizit ab ("as different from dried blood spots"), während Omegametrix selbst DBS mit Umrechnung anbietet und akkreditiert hat. Das ist dieselbe Spannung wie in `omegametrix.md`, jetzt mit Volltextbeleg.
- Die Aussage, die Methode sei "identical to the method used in specific laboratories in the USA and Asia", steht im Widerspruch zur Methodenbeschreibung der 7-Länder-Arbeit (21 vs. 26 Fettsäuren, siehe Abschnitt 2). Ob die Panels von OmegaQuant und Omegametrix heute tatsächlich identisch sind, ist nicht belegt.

### Gaps
- Der Volltext von J Clin Lipidol 2025 und der Volltext von Proc Nutr Soc 2020 (inklusive eventueller Details zu Ringversuchen) waren nicht abrufbar (ScienceDirect und Cambridge nicht freigegeben).
- Internist 2019 (Springer) war nicht abrufbar (JavaScript-Challenge bzw. Host nicht freigegeben).

## 4. Laborvergleiche mit Beteiligung von Omegametrix und deren Zahlen

### Takeaway
Ich habe keinen peer-reviewten Ringversuch gefunden, in dem Omegametrix namentlich mit numerischem Ergebnis auftaucht. Belegt sind nur:
- von Schackys Behauptung regelmäßiger Eignungsprüfungen, ohne Daten
- der Fünf-Labor-Vergleich mit "Faktor 3,5" (Labors ungenannt, Quelle Buchkapitel 2013)
- die OmegaQuant-Angabe "< 0,1 Prozentpunkte" Abweichung zu "OmegaMetrix" (weiter nur [SNIP], omegaquant.com gesperrt)

Die einzige publizierte DBS-Interlabor-Studie (Lipids 2019, fünf Labors) hatte laut Autorenaffiliationen keine Omegametrix-Beteiligung.

### Cited Findings
- [VT] "when one sample was sent to five different laboratories offering determination of an Omega-3 Index, results differed by a factor of 3.5". Labors und Jahr werden nicht genannt; Quelle ist das Buchkapitel Harris/von Schacky/Park 2013. — [Nutrients 2014, PMC3942733](https://pmc.ncbi.nlm.nih.gov/articles/PMC3942733/)
- [VT] "regularly subjected to rigorous proficiency testing". Anbieter und Ergebnisse werden nicht genannt. — [Neth Heart J 2023, PMC10602979](https://pmc.ncbi.nlm.nih.gov/articles/PMC10602979/)
- [ABS] Interlabor-Studie DBS:
  - Vollblut von zwei Personen (niedriger und hoher n-3-Status), 25 µL auf BHT-behandelten Streifen, verschickt an fünf Labors.
  - Bei "standardized" Reporting (19 Fettsäuren) sank der Interlabor-%CV für EPA von 8,6 % auf 6,0 % bzw. von 9,1 % auf 6,6 %, für DHA von 10,5 % auf 7,2 % bzw. von 10,5 % auf 6,6 %.
  - Autorenaffiliationen: University of Toronto, OmegaQuant (Sioux Falls), SAHMRI/University of Adelaide, UT Austin (Brenna), University of Waterloo, University of Rochester. **Omegametrix ist nicht darunter.**
  
  — [Metherel et al., Lipids 2019;54:755–761, PMID 31782523](https://pubmed.ncbi.nlm.nih.gov/31782523/)
- [ABS] Jackson & Harris 2022: "interlaboratory conversion factors from study-specific metrics to a common metric, red blood cell (RBC) DHA measured by OmegaQuant Analytics", für fünf publizierte und eine unpublizierte Schwangerschaftsstudie. Ob Omegametrix-Daten darunter sind, geht aus dem Abstract nicht hervor. — [PLEFA 2022, PMID 35390621](https://pubmed.ncbi.nlm.nih.gov/35390621/)
- [VT] 7-Länder-Datensatz: Daten der Labors von Park, von Schacky und Harris wurden als methodengleich gepoolt ("This removed potential inconsistencies arising from differences in laboratory methods"). Einen Vergleich derselben Proben zwischen den Labors berichtet die Arbeit nicht. — [PLEFA 2022, PMC10440636](https://pmc.ncbi.nlm.nih.gov/articles/PMC10440636/)
- [SNIP, Vorrunde; in dieser Runde nicht abrufbar, omegaquant.com vom Proxy blockiert] OmegaQuant-Methodendokument: Kreuzvalidierung u. a. mit "OmegaMetrix (Munich, Germany)", Abweichung < 0,1 Prozentpunkte vom OmegaQuant-Wert. Probenzahl und Jahr unbekannt. — [OmegaQuant PDF](https://omegaquant.com/wp-content/uploads/2013/09/omegaquant_methodological.pdf)

### Inferences
- Für Omegametrix existiert öffentlich nur die Behauptung von Laborvergleichbarkeit mit OmegaQuant, keine peer-reviewte Zahl. Für DBS gibt es nicht einmal eine Behauptung.
- Selbst unter standardisiertem Reporting liegen die Interlabor-CVs für EPA und DHA aus DBS bei etwa 6–7 % (Lipids 2019, ohne Omegametrix). Das liegt über dem pauschalen Intra-Labor-CV von 5 % und zeigt, wie groß Unterschiede zwischen Labors selbst unter guten Bedingungen bleiben.

### Gaps
- Kein publizierter Ringversuch (z. B. INSTAND, RfB, NIST FAQAP) mit Omegametrix-Ergebnis gefunden.
- Der Volltext des OmegaQuant-Querabgleichs und das Buchkapitel 2013 waren nicht zugänglich.
- Kein publizierter Vergleich von Omegametrix-DBS mit Vitas (Zinzino/Eqology) oder OmegaQuant-DBS.
