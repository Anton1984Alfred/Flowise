# Verification round: Vitas AS (Oslo) DBS omega-3 test used by Zinzino (BalanceTest) and Eqology (state: 23 Nov 2026)

> **Access log, read first.** Labels: **[FULL-TEXT VERIFIED]** = I downloaded and read the full primary text in this session. **[SNIPPET-ONLY]** = search-engine snippet or summary, or carried over from the earlier round, not checked against the full text.
> - Read in full: Torrissen et al. 2025 via PMC (PMC12335782); zinzino.com DE/US BalanceTest pages; Zinzino product sheets de-DE (PDF created 6 Oct 2026) and en-GB (footer "en-EU 2026-08-24"); the CE/IVD declaration PDF that Zinzino links; three Vitas letters hosted on Zinzino's file storage (zinzinowebstorage.blob.core.windows.net); the akkreditert.no registry (every listing page).
> - Blocked:
>   - **link.springer.com**: the egress proxy refused with HTTP 403, twice, so it is not actually allowed in this session.
>   - **lipidworld.biomedcentral.com**: reachable, but returns a JavaScript "Client Challenge" page instead of the article.
>   - **europepmc.org**: Cloudflare "Just a moment" challenge.
>   - **pubmed.ncbi.nlm.nih.gov**: reCAPTCHA.
>   - **www.vitas.no**: "ws_closed_mid_exchange" (tunnel closed before the exchange completed), twice, about a minute apart.
>   - **eqology.com**: www.eqology.com answers with a 302 to the bare domain eqology.com, which the proxy refuses with 403 (not on the allow-list).
>   - **cdn.zinzino.com**: failed.
>   - **knowledge.lancashire.ac.uk** (UCLan repository): 403.
>   - The WebFetch tool could not resolve link.springer.com or lipidworld.biomedcentral.com (ENOTFOUND). Only curl through the proxy worked.
> - **Consequence:** the 2026 Gisslevik paper (not in PMC per the NCBI ID converter: "Identifier not found in PMC") and all eqology.com pages remain **snippet-only**.

---

## 1. Methods and Declarations of the two Lipids in Health and Disease papers (Torrissen 2025; Gisslevik 2026)

### Takeaway
**[FULL-TEXT VERIFIED] for 2025.** The Torrissen 2025 paper describes the method as follows:
- **Sample:** Whatman 903 card in an aluminium-laminate pouch with calcium-chloride desiccant. No antioxidant is mentioned.
- **Shipping and storage:** ambient-temperature shipping; storage at 4 °C on arrival; analysis within one week.
- **Methylation:** direct methylation with 0.5 M sodium methoxide (20 min, 50 °C), then hexane extraction.
- **GC:** GC-FID on an Agilent 8890 with a Thermo TR-FAME column (30 m × 0.25 mm × 0.25 µm).
- **Identification:** peaks identified only against an external FAME reference mix. **No internal standard is mentioned.**
- **Quantification:** each fatty acid is reported as area-% of the sum of 11 fatty acids.
- **n-3 level:** the raw whole-blood EPA+DHA %. There is **no conversion to an erythrocyte equivalent**, and the paper states that absolute values "cannot be directly equated" with RBC values.
- **Precision and QC:** **no CV, precision or QC data** are reported.
- **"Established methods at the Vitas laboratory [45]":** reference [45] is a general best-practice guideline (Brenna et al. 2018), not a Vitas validation paper.
- **Funding:** none declared.
- **Competing interests:** all eight authors are tied to Zinzino or Vitas.

**[SNIPPET-ONLY] for 2026.** The Methods and Declarations of the Gisslevik 2026 paper could not be read. The claim "8% RBC ≈ 5.7–6.7% whole blood" could not be verified.

### Cited Findings

**Torrissen et al. 2025, Lipids Health Dis 24:260. All points below are [FULL-TEXT VERIFIED] at [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/).**

- **Citation and licence:** "Lipids Health Dis. 2025 Aug 9;24:260. doi: 10.1186/s12944-025-02676-6". Received 18 Feb 2025, accepted 18 Jul 2025. Licence CC BY-NC-ND 4.0. Torrissen and Gisslevik "contributed equally". — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Authors and affiliations (verbatim affiliation list):**
  - Martina Torrissen: Bioactive Foods AS, Vestby, Norway
  - Emmalee Gisslevik: Zinzino Operations AB, Mölndal, Sweden
  - Thomas E Gundersen and Tore Bolstad: Vitas AS, Oslo, Norway
  - Ola Eide: Akobe AS, Viken, Norway
  - Angela Maria Rizzo: Department of Pharmacological and Biomolecular Sciences, University of Milan
  - Paul Clayton: Institute of Interdisciplinary Medicine, Moscow, Russia
  - Colin Robertson (corresponding author): Zinzino Operations AB and University of Central Lancashire, Preston, UK
  
  — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Study design:** "This observational study employed a self-administered DBS fatty acid screening test analysed at the Vitas laboratory in Oslo, Norway. The home-based fingerstick collection method and test kits were distributed by Zinzino Operations (Sweden) through diverse channels, including health practitioners, therapists, web shops, and other sales outlets." — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Exclusion of Zinzino-supplement users:** "individuals who reported consuming omega-3 supplements from Zinzino Operations (Sweden) were excluded from all analyses." — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Sample size, period and ethics:** "A total of 595,480 fatty acid profiles were included". Data were collected "from 1st of April 2012 to 27th of September 2023". Ethics: Joint Research Ethics Committee, University of Central Lancashire (HEALTH 01195). Consent was given by clicking "I agree" at the end of the questionnaire. — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Collection procedure and card:** "Participants received a pre-assembled sampling kit containing: (i) a single-use lancet, (ii) a Whatman 903 filter card, and (iii) and an aluminium-laminate pouch pre-loaded with calcium-chloride desiccant. After finger-prick collection, instructions were to allow the card to air-dry horizontally at room temperature for a minimum of 10 min before placing it into the aluminium bag and seal it … Samples were shipped at ambient temperature by regular post within the Nordic region or via consolidated express air transport (≤ 48 h) from hubs at remote locations." Stability is supported only by citing [44] (Metherel, Henao & Stark, Lipids 2013, "EPA and DHA levels in whole blood decrease more rapidly when stored at –20 °C as compared with room temperature, 4 and –75 °C"). **No antioxidant (e.g. BHT) is mentioned anywhere in the paper.** — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Storage, extraction, methylation and GC (verbatim):** "Fatty acid profiles obtained from DBS samples were analysed using established methods at the Vitas laboratory [45]. Upon arrival at the laboratory, DBS samples were stored at 4 °C prior to analysis within one week. The DBS samples were methylated with 0.5 M sodium methoxide for 20 min at 50 °C to facilitate fatty acid methyl ester (FAME) formation. FAMEs were then extracted into hexane [46] and analysed by gas chromatography–flame ionization detection (Agilent Technologies, 8890) with a TR–FAME column (length, 30 m; internal diameter, 0.25 mm; and film thickness, 0.25 μm; Thermo–Fisher Scientific)." — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Standards and quantified fatty acids (verbatim):** "Eleven fatty acids were identified as the major components of whole blood and quantified using gas chromatography. Each FAME was identified by comparing retention time to the external FAME reference standard (USP – FAME standard mixture, Merk). Fatty acid values are expressed as the percentage area of the total identified FAMEs, calculated as the sum of the 11 quantified fatty acids. The measured and identified fatty acids were: palmitic acid (PA, 16:0), stearic acid (SA, 18:0), oleic acid (OA, 18:1 n-9), LA, γ-linolenic acid (GLA, 18:3 n-6), ALA, dihomo-γ-linolenic acid (DGLA, 20:3 n-6), AA, EPA, docosapentaenoic acid (DPA, 22:5 n-3), and DHA." **No internal standard is named.** A text search of the full paper for "internal standard", "coefficient of variation", "CV", "precision" (other than statistical CIs), "quality control", "repeatab" and "reproducib" found **no analytical precision or QC data**. — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Definition of the n-3 level ("Omega-3 Index"):** "Whole blood n-3 fatty acid levels, herein referred to as "n-3 levels," were defined as the sum of EPA and DHA percentages … the total n-6:n-3 ratio was calculated as the sum of the measured n-6 fatty acids (LA, GLA, DGLA, AA) divided by the sum of the measured n-3 fatty acids (ALA, EPA, DPA, DHA)." **No equation converts whole-blood values to an RBC equivalent**; values are raw whole-blood area-%. — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Whole blood versus RBC:**
  - "While direct comparisons with RBC-based studies are not feasible due to differences in the biological compartments measured, … absolute values from these two measurement methods cannot be directly equated."
  - The introduction asserts that DBS "correlates well with red blood cell (RBC) measures like the omega-3 index (O3I) [36–39]". The cited works are Harris & Polreis 2016 (OmegaQuant DBS method), Harris et al. 2022 (dogs and cats), Barnes et al. 2021 and Schuchardt et al. 2023 (UK Biobank). **None of these is Vitas data.**
  
  — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Results, whole-blood EPA+DHA (Table 3, mean (SD)):**
  - Continents: North America 2.8 (1.5), Africa 3.3 (1.4), South America 3.5 (1.4), Europe 3.6 (1.5), Oceania 3.7 (1.4), Asia 3.8 (1.6).
  - European subregion: Northern Europe 4.2 (1.5).
  - Countries with ≥35 samples ranged "from 2.4 to 5.4%"; the highest was Ghana at 5.4 ± 2.0.
  - BMI analysis: normal-weight supplement users 4.7% versus normal-weight non-users 3.6%.
  - Supplement users versus non-users: "+ 1.0% mean difference".
  - Median total n-6:n-3 ratio by continent: "6.2:1 to 8.8:1".
  
  — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Limitations stated by the authors:**
  - "While home collection and ambient shipping may introduce some random variability in PUFA measurements, such variability is unlikely to systematically bias the results because random errors tend to cancel out with large sample sizes … the risk of degradation is mitigated through rapid transport and optimized packaging procedures, including sealed aluminium-laminate pouches with calcium chloride desiccant … [78]".
  - Reference [78] is "Li X, et al. Effects of the incorporation of calcium chloride on the physical and oxidative stability of filled hydrogel particles. Foods. 2022", a food-science paper, not a DBS study.
  - Repeat testers could not be excluded.
  
  — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Funding (verbatim):** "This study did not receive any funding from public, commercial, or not-for-profit organizations." — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Competing interests (verbatim):** "M.T. is affiliated with Bioactive Foods AS, a company owned by Zinzino Operations AB. C.R. and E.G. are directly affiliated with Zinzino Operations AB. T.G. is the CEO and co-founder of Vitas Analytical Services and serves as a member of Zinzino's scientific advisory board. T.B. is affiliated with Vitas Analytical Services. P.C., and A.M.R. are consultants on Zinzino's Scientific Advisory Board. While these affiliations may represent potential competing interests, the study was conducted objectively, and the data analysis and interpretation were performed independently of any commercial influence." — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Author contributions (verbatim):** "O.E. conceptualized the study. Methodology was developed by O.E., T.G., T.B., M.T., and E.G. M.T. and E.G. were responsible for software development and validation. … Project administration was overseen by C.R." — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **Data availability:** "not publicly available due to proprietary data restrictions but are available from the corresponding author upon reasonable request." — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)

**Gisslevik et al. 2026 ("Real-world omega-3 supplementation patterns … 762,150 dried blood spot samples")**
- **[SNIPPET-ONLY]** Bibliographic details:
  - Authors: Gisslevik E, Torrissen M, Rizzo AM, Gundersen TE, Eide O, Clayton P, Robertson C.
  - Design: retrospective cross-sectional analysis of 762,150 whole-blood DBS samples submitted to a commercial fatty-acid profiling service, 2012–2023, comparing three real-world supplementation-exposure groups, with a focus on EPA+DHA and AA/EPA.
  - A search summary gives October 2026 as the publication month.
  
  — [Springer (not fetchable: proxy 403)](https://link.springer.com/article/10.1186/s12944-026-03071-5); [ResearchGate record (host not allowed)](https://www.researchgate.net/publication/415929230_Real-world_omega-3_supplementation_patterns_and_whole-blood_fatty-acid_biomarkers_a_cross-sectional_analysis_of_762150_dried_blood_spot_samples)
- **[SNIPPET-ONLY, from earlier round]** Method:
  - Uses "the established whole-blood DBS fatty-acid method described previously [19]": whole-blood total fatty acids transesterified to FAMEs, extracted into hexane and analysed by GC-FID.
  - DBS whole-blood values showed "strong correspondence" with erythrocyte and plasma/serum measures; no numbers appear in the snippet.
  
  — [Springer](https://link.springer.com/article/10.1186/s12944-026-03071-5)
- **[SNIPPET-ONLY, from earlier round]** Competing interests: Zinzino Operations AB "markets omega-3 supplements and fatty-acid testing services related to the subject matter", and the Vitas CEO "performed the fatty-acid analyses used in this study". No non-author company representative controlled the analyses or the decision to publish. The funding statement was not visible in any snippet. — [Springer](https://link.springer.com/article/10.1186/s12944-026-03071-5)
- **[SNIPPET-ONLY, NOT VERIFIED] "8% RBC ≈ 5.7–6.7% whole blood":**
  - The only trace is an earlier-round ResearchGate snippet, recorded in omegametrix.md line 171.
  - This round's searches produced only a search-engine paraphrase: the paper "notes that whole-blood EPA+DHA values are generally lower than corresponding erythrocyte percentages, so an erythrocyte Omega-3 Index of 8% may broadly correspond to lower whole-blood values", with no conversion formula given.
  - The exact wording, the 5.7–6.7% range, its derivation and the cited source could **not** be confirmed.
  
  — [ResearchGate record](https://www.researchgate.net/publication/415929230_Real-world_omega-3_supplementation_patterns_and_whole-blood_fatty-acid_biomarkers_a_cross-sectional_analysis_of_762150_dried_blood_spot_samples)
- **[FULL-TEXT VERIFIED, negative]** The NCBI PMC ID converter returns "Identifier not found in PMC" for 10.1186/s12944-026-03071-5. A PMC title search also returned no match. — [NCBI ID converter API](https://pmc.ncbi.nlm.nih.gov/tools/idconv/api/v1/articles/?ids=10.1186/s12944-026-03071-5&format=json)

### Inferences
- **Methods gaps.** The published Vitas method has no internal standard (external standard only), and quantification is by normalised area-% of only 11 FAMEs. No precision data are given. As a result, the published record contains no information on analytical repeatability, which is the variable that matters for an individual before/after test.
- **The 8 % target is out of reach on this scale.** The paper itself treats its values as raw whole-blood EPA+DHA and says they cannot be equated with RBC values. Yet in the 2025 dataset no country mean reaches 5.5 % whole blood, and even normal-weight supplement users average 4.7 %. Zinzino's ≥ 8 % whole-blood "Omega-3 index WB" reference (see Q5) therefore sits above the mean of every country in Zinzino's own published database. If the unverified 2026 statement (8 % RBC ≈ 5.7–6.7 % WB) is accurate, it would mean the company's own scientists put the RBC-8 % equivalent well below the 8 % the consumer report uses as its reference.
- **Stability evidence is thin.** The degradation risk from ambient shipping is argued with a hydrogel food-chemistry citation, not with DBS stability data for the Vitas card and method.

### Gaps
- **2026 paper, full text not read:**
  - Methods: any changes versus 2025, any internal standard, any QC/CV data.
  - Exact wording and source of the "8 % RBC ≈ 5.7–6.7 % WB" statement.
  - Funding statement and author affiliations.
  - Identity of reference "[19]".
  - Needed: access to link.springer.com (currently proxy 403) or lipidworld.biomedcentral.com without the JavaScript challenge.
- Whether the Whatman 903 card described in the paper is the same as the "RDA Spot" collection card in Zinzino's current CE declaration (see Q5).

---

## 2. The cited Vitas method reference and its validation data

### Takeaway
**[FULL-TEXT VERIFIED] (reference list of the 2025 paper).** The "established methods at the Vitas laboratory" are referenced to **[45] Brenna JT et al. 2018, "Best practices for the design, laboratory analysis, and reporting of trials involving fatty acids" (Am J Clin Nutr)**. This is a generic methodological guideline, **not a Vitas validation study**. The hexane-extraction step cites [46], Risé et al. 2007 (PLEFA), and mail stability cites [44], Metherel et al. 2013. **No Vitas-specific publication with CVs, recovery, card stability or a DBS-versus-venous/RBC comparison is cited, and none was found by search.** The 2026 paper's "[19]" could not be identified because that paper was not readable.

### Cited Findings
- **[FULL-TEXT VERIFIED]** The 2025 paper's reference list reads:
  - "44. Metherel A, Henao JA, Stark K. EPA and DHA levels in whole blood decrease more rapidly when stored at – 20 C as compared with room temperature, 4 and – 75 C. Lipids. 2013;48(11):1079–91."
  - "45. Brenna JT, et al. Best practices for the design, laboratory analysis, and reporting of trials involving fatty acids. Am J Clin Nutr. 2018;108(2):211–27."
  - "46. Rise P, et al. Fatty acid composition of plasma, blood cells and whole blood: relevance for the assessment of the fatty acid status in humans. Prostaglandins Leukot Essent Fatty Acids. 2007;76(6):363–9."
  
  — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **[FULL-TEXT VERIFIED]** The DBS-versus-RBC correlation claimed in the introduction cites:
  - "[36] Harris WS, Polreis J. Measurement of the omega-3 index in dried blood spots. Ann Clin Lab Res. 2016" (OmegaQuant).
  - "[37] Harris WS, et al. Derivation of the omega-3 index from EPA and DHA analysis of dried blood spots from dogs and cats … 2022".
  - [38] Barnes 2021 and [39] Schuchardt 2023.
  
  These are third-party methods, not Vitas data. — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **[FULL-TEXT VERIFIED]** Related Milan-group method papers are cited only in the Discussion and not as the Vitas method: "49. Marangoni F, Colombo C, Galli C. A method for the direct evaluation of the fatty acid status in a drop of blood from a fingertip in humans … Anal Biochem. 2004" and "55. Rizzo AM, et al. A rapid method for determining arachidonic: eicosapentaenoic acid ratios in whole blood lipids: correlation with erythrocyte membrane ratios … Lipids Health Dis. 2010". — [PMC12335782](https://pmc.ncbi.nlm.nih.gov/articles/PMC12335782/)
- **[SNIPPET-ONLY]** A search for a Gundersen/Bolstad/Vitas DBS fatty-acid validation paper returned only the two database papers and unrelated DBS validations. The search summary concluded that "the original validation study isn't among them". — [search result set incl. Springer PDF of Torrissen 2025](https://link.springer.com/content/pdf/10.1186/s12944-025-02676-6.pdf)
- **[FULL-TEXT VERIFIED, Zinzino claim, no citation]** "Es ist wissenschaftlich bewiesen, dass ein DBS-Test für die Analyse von Fettsäuren genauso exakt wie eine venöse Blutprobe ist." ("It is scientifically proven that a DBS test for fatty-acid analysis is exactly as accurate as a venous blood sample.") No study is named. — [Zinzino DE BalanceTest product page](https://www.zinzino.com/shop/site/de/de-de/products/shop/home-health-tests/309000); [Zinzino product sheet de-DE (PDF)](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-de-DE.pdf)
- **[FULL-TEXT VERIFIED, Zinzino claim]** "Samples are independently analyzed by Vitas Analytical Services using validated laboratory methods." Neither the validation nor its data are referenced. — [Zinzino US: home health tests](https://www.zinzino.com/site/us/en-us/explore/home-health-tests)

### Inferences
- The only method citation for "established methods at the Vitas laboratory" is a generic best-practice paper. So, as far as the public record shows, **the Vitas whole-blood DBS method has no peer-reviewed validation report** giving CVs, recovery, linearity, card or shipping stability, or agreement with venous whole blood or RBC. Zinzino's "validated methods" and "scientifically proven … as exact as venous blood" claims are not backed by any Vitas-specific citation.
- Brenna et al. 2018 itself recommends reporting method details and QC, such as internal standards and precision. By that yardstick, the 2025 paper's omission of internal-standard and precision data is noteworthy. This is my inference from the title and scope of [45]; I did not read the full text of Brenna 2018 in this session.

### Gaps
- Identity and content of reference "[19]" in Gisslevik 2026. It could be Torrissen 2025 or another paper; this is unknown.
- Any internal Vitas validation report: not public.
- I did not read the full texts of Brenna 2018 or Risé 2007 in this session. Their scope is inferred from their titles.

---

## 3. Norsk akkreditering registry (akkreditert.no): does Vitas AS (org. no. 968655973) hold an accreditation?

### Takeaway
**[FULL-TEXT VERIFIED]: No.** None of the 155 accreditations listed on akkreditert.no for testing laboratories (TEST), medical laboratories (MED/TEST), GLP or biobank belongs to Vitas AS. The site search for "vitas" returns "0 treff" (0 hits). **There is no TEST or MED number for Vitas, and therefore no accredited scope.** The organisation number 968655973 is confirmed as Vitas AS's from Vitas's own letterhead.

### Cited Findings
- **[FULL-TEXT VERIFIED]** Registry coverage (I downloaded every listing page, 23 Nov 2026):
  - "Laboratorier": "Antall treff i databasen: 103" (103 hits in the database).
  - "Medisinske lab": 47 hits.
  - GLP: 4 hits.
  - Biobank: 1 hit.
  - Searching all pages for "vitas" returned **0** occurrences.
  
  — [akkreditert.no: Hvem er akkreditert (Laboratorier)](https://www.akkreditert.no/akkrediterte-organisasjoner/?scope=Labs); [Medisinske lab](https://www.akkreditert.no/akkrediterte-organisasjoner/?scope=MedLab); [GLP](https://www.akkreditert.no/akkrediterte-organisasjoner/?scope=Glp)
- **[FULL-TEXT VERIFIED]** Site search result: "Ditt søk etter « vitas » resulterte i 0 treff." ("Your search for 'vitas' gave 0 hits.") A search for "968655973" also gave no matching hit. — [akkreditert.no search "vitas"](https://www.akkreditert.no/sok/?q=vitas)
- **[FULL-TEXT VERIFIED]** Context: the GLP-registered facilities are VESO AS (GLP 002), Schlumberger Norge AS (GLP 006), Norsk institutt for vannforskning (GLP 007) and Stiftelsen NILU (GLP 012). The registry does list accredited Norwegian food, feed and marine-lipid labs, e.g. Eurofins Food & Feed Testing Norway AS (TEST 001), Nofima AS (TEST 045), Havforskningsinstituttet (TEST 050), Hofseth BioCare ASA (TEST 329) and Kappa Bioscience AS (TEST 326), but not Vitas. — [akkreditert.no: Laboratorier](https://www.akkreditert.no/akkrediterte-organisasjoner/?scope=Labs); [GLP](https://www.akkreditert.no/akkrediterte-organisasjoner/?scope=Glp)
- **[FULL-TEXT VERIFIED]** Vitas letterhead: "Thomas E. Gundersen … Oslo Innovation Centre, Gaustadalléen 21, N-0349 Oslo … Org #: 968655973". — [Vitas "Declaration of Independence" 2015 (PDF on Zinzino storage)](https://zinzinowebstorage.blob.core.windows.net/financialdocuments/DeclarationofIndependence_VItas_AS-2017_ZZ_EN.pdf); [Vitas "Destruction of samples" 2023 (PDF)](https://zinzinowebstorage.blob.core.windows.net/filelibrary/Declaration-sample-destruction-Vitas-AS-EN.pdf)
- **[SNIPPET-ONLY, earlier round]** NutraIngredients reported on 14 Jan 2026 that a different Vitas DBS assay (tryptophan, kynurenine, IPA for Zinzino's gut test) was "being prepared for ISO 17025 accreditation". — [NutraIngredients Q&A](https://www.nutraingredients.com/Article/2026/01/14/qa-zinzino-bets-on-blood-for-gut-health/)
- **[SNIPPET-ONLY]** A Forskningsparken article from 2023 quotes Vitas's head of Pharma Services: Vitas is one of few companies in Norway holding a manufacturing licence for medicines, which it calls GMP certification. This was not verified against the Norwegian Medicines Agency's register. — [Forskningsparken: The Control Tower of Pharmaceuticals](https://www.forskningsparken.no/en/news/legemidlenes-kontrolltarn)

### Inferences
- "GMP-certified" refers to a pharmaceutical manufacturing licence and inspection regime, not to accreditation of the DBS fatty-acid test method under ISO/IEC 17025 or ISO 15189. As of 23 Nov 2026, the public Norwegian accreditation register lists **no** accreditation of any kind for Vitas AS. Any claim that the Zinzino or Eqology omega-3 analysis is "ISO 17025 accredited" (made e.g. by the partner site omega3-test.net, see eqology.md) is contradicted by the registry.

### Gaps
- The registry shows only current accreditations. Historical, suspended or withdrawn accreditations, if any, are not visible.
- Accreditation by a non-Norwegian body (e.g. a foreign EA member) cannot be excluded from this registry alone, but no such claim was found.
- The scope of Vitas's GMP manufacturing authorisation was not verified in the Norwegian Medicines Agency's register, which was outside the allowed hosts.

---

## 4. What Vitas publicly states (vitas.no): DBS fatty-acid analysis, quality system, proficiency testing, sample volumes

### Takeaway
I could not read vitas.no: the connection was closed mid-exchange twice. The Vitas self-descriptions I could read in full are the Vitas letters and brochure hosted on Zinzino's file storage (2015, 2017, 2023). They claim **GMP certification**, chromatographic expertise and high DBS throughput. They say **nothing about ISO 17025 or 15189, proficiency testing or external quality assessment, or method precision**. Sample-volume figures: about 10,000 DBS samples per month in 2017 (Vitas); over 2 million DBS samples by December 2024 (third-party directory, snippet); 1,964,407 BalanceTests to date (Zinzino, Nov 2026).

### Cited Findings
- **[FULL-TEXT VERIFIED] Vitas "Who we are" (PDF dated 19 Jun 2017):**
  - "Vitas is a GMP certified chemical analysis contract lab, with 25 years' experience in providing high quality, custom chromatographic analytical service".
  - "The laboratory is equipped with advanced HPLC, GC, UV Spectrometry, Florescent Assays, ELISA, various mass spectrometric and other modern high-end techniques."
  - "The high throughput DBS facility currently receives, analyses and reports approximately 10 000 DBS sample every month. It is expected that this number will increase to 15 000/ month within the end of 2017. Within the next five years, Vitas envisage to perform more than 1 million DBS samples annually."
  - "By serving multiple Norwegian fish oil producers in lipid analysis … quality control and medicinal development".
  
  — [Vitas – Who we are 2017 (Zinzino-hosted PDF)](https://zinzinowebstorage.blob.core.windows.net/financialdocuments/Vitas-Who_we_are-%202017-zz.pdf)
- **[FULL-TEXT VERIFIED] Vitas "Declaration of Independence" (Oslo, 8 Sep 2015):** "Vitas AS is a privately owned GMP certified Contract Laboratory. The company was established in 1994 as a spin off from the Institute of Nutrition at the University of Oslo … Vitas AS declares that we are an independent privately owned company, that we conduct all analyses for Zinzino AB and its affiliates and report all results without bias, and are under no influence of our customers and their commercial interests." — [Declaration of Independence (PDF)](https://zinzinowebstorage.blob.core.windows.net/financialdocuments/DeclarationofIndependence_VItas_AS-2017_ZZ_EN.pdf)
- **[FULL-TEXT VERIFIED] Vitas "Destruction of samples" (Oslo, 17 Apr 2023):** "Zinzinos customers send blood samples as dried blood spots to Vitas in Oslo by regular mail or by express courier transport. Upon receipt samples are registered and analysed for the agreed biomarkers only. The sample is kept for 7 days post analysis to be able to do conformational analysis in case of customer complaint. The sample is then … destroyed by high temperature disintegration. This procedure is described in Vitas internal SOPs." — [Destruction of samples (PDF)](https://zinzinowebstorage.blob.core.windows.net/filelibrary/Declaration-sample-destruction-Vitas-AS-EN.pdf)
- **[FULL-TEXT VERIFIED] Zinzino describing Vitas (Nov 2026):**
  - "Vitas, a GMP-certified chemical analysis contract lab based in Oslo, Norway, providing high-quality, custom chromatographic analytical services since 1994 … The company has been a collaborative partner to the World Health Organization."
  - "1,964,407 BalanceTests performed to date".
  - The en-GB product sheet adds the footnote: "Vitas AS' contribution is limited to the chemical analysis of each dried blood spot (DBS) test, performed in accordance with applicable quality standards." No standard is named.
  
  — [Zinzino: Are test results reliable?](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable); [Zinzino: home health tests](https://www.zinzino.com/site/us/en-us/explore/home-health-tests); [Zinzino product sheet en-GB (PDF, 2026-08-24)](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-GB.pdf)
- **[SNIPPET-ONLY, earlier round]** The vitas.no fatty-acid service page cites "many years of experience in high-throughput fatty acid profile analyses from DBS". It accepts whole blood, plasma, serum and DBS, and names Tore Bolstad as senior research scientist. No validation data appear in the snippet. — [vitas.no: Fatty acid analytical services](https://www.vitas.no/analytical-services/biomarker-analytical-services/fatty-acid-analytical-services)
- **[SNIPPET-ONLY, third party]** Europages says VITAS AS "operates a GMP-certified facility and holds a manufacturing authorization for medicinal products from the Norwegian Medicinal Agency" and has processed "over two million DBS samples as of December 2024". — [Europages: VITAS AS](https://www.europages.co.uk/VITAS-AS/NOR028227-00101.html)
- **[SNIPPET-ONLY]** A search for vitas.no content on ISO 17025 or proficiency testing found nothing. The search summary: "I found no statement from Vitas on ISO/IEC 17025 accreditation or on the proficiency testing it takes part in." — [search result set incl. Forskningsparken](https://www.forskningsparken.no/en/news/legemidlenes-kontrolltarn)

### Inferences
- The public Vitas narrative is about GMP, chromatographic heritage, independence and throughput. External quality assessment, proficiency-test participation and method accreditation are absent. Combined with Q3, the only documented quality framework is GMP plus internal SOPs.
- Throughput rose from about 120,000 per year (2017) to a reported cumulative of over 2 million DBS samples by the end of 2024. Most of the Zinzino volume (about 1.96 million BalanceTests) is therefore handled by this single lab.

### Gaps
- Current vitas.no text on quality systems, proficiency testing, sample volumes and any accreditation is unread. Re-try once www.vitas.no is reachable; the failure was a tunnel/TLS error, not a policy 403.
- No evidence either way of participation in DBS fatty-acid ring trials (e.g. the Metherel et al. 2019 interlab study, AOCS, or NIST).

---

## 5. zinzino.com: BalanceTest pages, FAQ and product sheets (fatty acids, formulas, targets, CE/IVD, whole blood vs RBC, price)

### Takeaway
**[FULL-TEXT VERIFIED].**
- **What is measured:** Zinzino now openly states that Vitas measures **whole blood** and reports a "**whole blood omega-3 index**" (marker label "Omega-3 index WB"). It keeps the RBC-derived reference of **≥ 8 %** and applies **no conversion**.
- **Panel:** 11 fatty acids, normalised to 100 %.
- **Marker names:** the 2026 en-GB sheet renamed the markers: Fatty acid score, Omega-3 index WB, Omega-6:3 ratio, Fatty acid fluidity ratio, Cognitive fatty acid index and Omega-6 (AA) level WB. The German product page and German sheet (Oct 2026) still use the old names (Schutzwert, Omega-3-Index, Omega-6:3-Balance, Zellmembran-Fluidität, Mentale Stärke, AA-Index). The formulas are identical.
- **"Omega-6:3" ratio:** defined as **AA/EPA**, target < 3:1.
- **German price:** 189 € retail, 133 € "Premier-Preis".
- **CE/IVD statements are inconsistent:**
  - German sheet: IVD Directive 98/79/EG.
  - en-GB sheet: IVDR 2017/746 plus ISO 13485.
  - The linked declaration of conformity covers only a **Class A sample-collection card** made by UAB "RDA Spot" (Vilnius). It does not cover the analysis.

### Cited Findings
- **The 11 fatty acids (official list):** "Palmitic acid(PA), Stearic acid(SA), Oleic acid(OA), Linoleic(LA), Alpha- Linolenic acid(ALA), Gamma-linolenic acid(GLA), DihomoGamma- linolenic acid(DHGLA), Arachidonic acid(AA), Eicosapentaenoic acid(EPA), Docosapentaenoic acid(DPA), and Docosahexaenoic acid(DHA)." This matches the 2025 paper. — [Zinzino: Are test results reliable?](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable)
- **Normalisation and coverage:**
  - "VITAS Analytical Services in Norway will anonymously analyze the percentage content of 11 fatty acids, which together represent approximately 98% of the fatty acids in the blood."
  - "11 fatty acids are analyzed and the total sum of their amounts is considered 100%. For the following 6 values, we use 7 of the fatty acids."
  
  — [Zinzino product sheet en-GB (PDF)](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-GB.pdf)
- **Whole blood versus RBC (FAQ, verbatim; this verifies a quote the earlier round could not find):** "Different companies measure different Omega-3 values and calculate the values differently and thus there will not be the same final values even if you use the same laboratory that analyzes the tests. At Vitas, we measure fatty acid levels directly in whole blood and report the results as a "whole blood omega-3 index." This means the percentage we provide represents the concentration of Omega-3 fatty acids across all components of the blood, including red blood cells, white blood cells, and plasma." — [Zinzino DE: BalanceTest (FAQ section, English text)](https://www.zinzino.com/site/de/de-de/explore/balance-test)
- **WB labelling of markers:**
  - "3. Omega-3 Index WB*" and "6. Omega-6-Gehalt (AA) WB*" with the footnote "* Misst Fettsäuren im Vollblut (WB), das heißt in allen Bestandteilen des Blutes." ("Measures fatty acids in whole blood (WB), i.e. in all components of the blood.")
  - English version: "* Measures fatty acids in whole blood (WB), which means all parts of the blood."
  
  — [Zinzino DE: BalanceTest](https://www.zinzino.com/site/de/de-de/explore/balance-test); [Zinzino US: BalanceTest](https://www.zinzino.com/site/us/en-us/explore/balance-test)
- **Marker definitions and targets, current en-GB sheet (Aug 2026):**
  - **Fatty acid score** (formerly Protection Value): "The Fatty acid score is calculated based on 3 recognized markers; 1. … Omega-6 ratio … (DGLA + AA) × 100 / (DGLA + AA + EPA + DPA + DHA) 2. … Omega-3 level is the sum of EPA + DHA 3. The Omega-6:3 ratio is calculated as Omega-6 (AA) / Omega-3 (EPA). Each indicator value is given the same weight in a second calculation and assigned a value between 0 and 100, which is then divided by 3 … The Fatty acid score is intended to be above 90. This does not provide information about the person's health status". The 0–100 scoring function for each indicator is **not disclosed**.
  - **Omega-3 index WB:** "the summary of the percentage values for the two marine Omega-3 fatty acids EPA and DHA in the analyzed blood sample. The reference level is at least 8%, while higher values such as 10% may also be shown in the report."
  - **Omega-6:3 ratio:** "calculated by dividing the percent value of AA by the percent value of EPA (AA / EPA) … If this ratio is above 3:1, a change in diet may be considered."
  - **Fatty acid fluidity ratio** (formerly Cell membrane fluidity): "(PA + SA) / (EPA + DHA) … If the Fatty acid fluidity ratio is below 4:1, it indicates a lower relative level of saturated fatty acids compared with EPA and DHA".
  - **Cognitive fatty acid index** (formerly Mental strength): "AA / (EPA + DHA) … The value should be below 1:1 … The Cognitive fatty acid index provides information about selected fatty acids and does not assess cognitive function, mental health, learning, memory, or mood."
  - **Omega-6 (AA) level WB:** "Average values are in the range of 6.5 to 9.5%."
  
  — [Zinzino product sheet en-GB (PDF)](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-GB.pdf)
- **German product page and German sheet (PDF created 6 Oct 2026), old marker names, same formulas:**
  - "Omega-3-Index … Der ideale kombinierte Spiegel liegt bei mindestens 8 %, wobei höhere Werte im Bereich von 10 % wünschenswert sind." ("The ideal combined level is at least 8 %, with higher values around 10 % desirable.")
  - "Omega-6:3-Balance … (AA/EPA) … sollte vorzugsweise unter 3:1 liegen" ("should preferably be below 3:1").
  - "Zellmembran-Fluidität … (PA+SA) / (EPA+DHA) … unter 4:1".
  - "Mentale Stärke … AA / (EPA+DHA) … unter 1:1".
  - "Schutzwert … idealerweise über 90" ("ideally above 90").
  - "AA-Index … Gute Durchschnittswerte liegen im Bereich von 6,5 bis 9,5 %. Der optimale Zielwert liegt bei 8,3 %." ("Good average values are 6.5–9.5 %. The optimal target is 8.3 %.")
  - Footnote in the German sheet: "*Wenn Ihre ersten Ergebnisse eine Omega-6:3-Balance von 3:1 oder besser aufweisen, kontaktieren Sie Zinzino, da Sie in diesem Fall das Balance-Produkt nicht benötigen." ("If your first results show an Omega-6:3 balance of 3:1 or better, contact Zinzino, because in that case you do not need the Balance product.")
  
  — [Zinzino DE: BalanceTest product page](https://www.zinzino.com/shop/site/de/de-de/products/shop/home-health-tests/309000); [Zinzino product sheet de-DE (PDF)](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-de-DE.pdf)
- **CE/IVD statements, conflicting:**
  - **German page and sheet:** "Der zertifizierte Zinzino Trockenbluttest entspricht der Europäischen Richtlinie über In-vitro-Diagnostika (IVD) 98/79/EG … weshalb das Kit auch das CE-Zeichen aufweist." ("The certified Zinzino dried blood test complies with the European IVD Directive 98/79/EC … which is why the kit also bears the CE mark.") Also: "Der Zinzino-Test ist ein zugelassenes in-Vitro-Diagnostikum für die persönliche Blutabnahme zuhause." ("The Zinzino test is an approved in-vitro diagnostic for personal blood sampling at home.") — [DE product page](https://www.zinzino.com/shop/site/de/de-de/products/shop/home-health-tests/309000)
  - **en-GB sheet:** "The Zinzino Dried Blood Spot Test complies with the requirements of Regulation (EU) 2017/746 on in vitro diagnostic medical devices (IVDR) and is manufactured under a quality management system certified to ISO 13485." — [en-GB sheet (PDF)](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-GB.pdf)
  - **German explore page:** "Alle Gesundheitstest-Kits im Zinzino-Portfolio sind CE-gekennzeichnet." ("All health-test kits in the Zinzino portfolio are CE-marked.") — [DE explore page](https://www.zinzino.com/site/de/de-de/explore/balance-test)
  - **Linked document "CE-IVD-Bulleri-Group" (PDF dated 13 May 2022, e-signed 11 Nov 2022):** "JSC "RDA Spot" hereby declares … that the following IVD medical device complies with the requirements of Regulation (EU) 2017/746 … Name Dried Blood Spot Sample Collection Card; Model RDA001C … Purpose For collection of dried blood spot samples and their delivery to the laboratory; Classification Class A; Rule Annex VIII Rule 5 … quality management system, certified according to the requirements of the ISO 13485 standard." Address: UAB "RDA Spot", Vilnius, Lithuania. — [CE-IVD declaration (PDF)](https://zinzinowebstorage.blob.core.windows.net/filelibrary/CE-IVD-Bulleri-Group.pdf)
- **Accuracy claims:**
  - "The test validity and accuracy are consistent with the most rigorous medical methods." — [Zinzino: Are test results reliable?](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable)
  - "Every dried blood sample is independently analyzed by Vitas Analytical Services, a Norwegian GMP-certified laboratory with extensive analytical experience using validated methods". — [DE explore page FAQ](https://www.zinzino.com/site/de/de-de/explore/balance-test)
- **Sales framing:** "97% of the people who take the BalanceTest discover Omega-6:3 ratios that are out of balance until they start using or switch to BalanceOil+." — [Zinzino: Are test results reliable?](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable)
- **Time frame and turnaround:**
  - "Due to the life span of blood cells (up to 120 days), the values provide insights into your longer-term diet." — [en-GB sheet](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-GB.pdf)
  - Results "After 10-21 days" — [US page](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable)
  - "Es dauert 10–20 Tage" ("It takes 10–20 days") — [DE product page](https://www.zinzino.com/shop/site/de/de-de/products/shop/home-health-tests/309000)
  - No fasting is required: "You don't need to fast before." — [DE explore page FAQ](https://www.zinzino.com/site/de/de-de/explore/balance-test)
- **Handling:** fill each circle by free-falling drops; dry "mindestens 10 Minuten … bei Raumtemperatur in einer horizontalen Position" ("at least 10 minutes at room temperature, horizontal"); card into the paper envelope, then into the "Metallbeutel" (metal bag); "Das Trockenmitteltütchen darf dabei nicht entfernt werden" ("do not remove the desiccant sachet"); the user pays postage. The card is described as "Whatman®-Filterpapier". — [DE product page](https://www.zinzino.com/shop/site/de/de-de/products/shop/home-health-tests/309000)
- **German price (23 Nov 2026):** "BalanceTest – Selbsttest zur Analyse von Fettsäuren im Blut – Einmaliger Kauf 189 € … Premier-Preis 133 € … Retail Preis 189 €" (one-off purchase 189 €; "Premier price" 133 €; retail price 189 €). — [Zinzino DE: BalanceTest 309000](https://www.zinzino.com/shop/site/de/de-de/products/shop/home-health-tests/309000)

### Inferences
- Zinzino now explicitly reports a **whole-blood** Omega-3 index ("WB"), but keeps the **≥ 8 % reference** that originates from the erythrocyte HS-Omega-3 Index. Zinzino's own published database shows country means of only 2.4–5.4 % whole blood (Q1). Applying the RBC cut-off to unconverted whole-blood values structurally classifies almost every tester as below target. That fits the "97 % out of balance" sales claim. It is a methodological mismatch, not a disclosed calibration.
- The headline "Omega-6:3 ratio" is **AA/EPA**, not total n-6:n-3. The 2025 paper reports both, and the database medians for AA/EPA are about 9.6–23 (Q1). The < 3:1 target therefore refers to an AA/EPA scale on which only heavy supplementers land. It is not comparable to the "n-6:n-3" figures given by other labs.
- **CE claim.** The only conformity document Zinzino publishes is a Class A, self-declared IVDR declaration for a blood-collection card from a Lithuanian manufacturer. It does not cover Vitas's analysis, the algorithms or the interpretation. The German materials still cite the superseded Directive 98/79/EC. "Certified" and "approved IVD" overstate what a self-declared Class A sample-collection-card DoC means. That last point is my interpretation, not a regulator finding.
- **Rebranding of markers.** "Mental strength" became "Cognitive fatty acid index" with an explicit disclaimer, "Protection value" became "Fatty acid score", and "AA optimum 8.3 %" was dropped. Read together with the new disclaimers, this suggests a 2026 regulatory clean-up of health-claim language in English-language materials. The German pages still carry the old wording.

### Gaps
- Exact 0–100 scoring functions behind the Fatty acid score / Schutzwert: not disclosed.
- A current (2026) sample result report from zinzinotest.com was not obtained.
- Whether the RDA Spot RDA001C card uses Whatman 903 paper (as the 2025 paper says) is not stated.
- The relation between "Bulleri Group" (the file name) and RDA Spot is unexplained.

---

## 6. eqology.com: test pages and manuals (lab, fatty acids, metrics, whole blood vs RBC, handling, turnaround, EUR price)

### Takeaway
**Not fetchable in this round.** www.eqology.com redirects (302) to the bare domain eqology.com, which the proxy refuses with 403 because it is not on the allow-list. Everything below is therefore **[SNIPPET-ONLY]**, mostly carried over from eqology.md.
- **Lab:** consistently Vitas AS, Oslo.
- **Panel:** 11 fatty acids.
- **Metrics:** Omega-3 Index (≥ 8 %) and an omega-6:omega-3 / AA:EPA ratio, with inconsistent targets (< 3:1 versus ≤ 5:1).
- **Results:** shown on omegaratiotest.com after 20–25 working days.
- **Price:** about 85–88 € single (AT and FR shops), 64–66 € premium-customer price.
- **Matrix:** no Eqology statement about whole blood was found. Eqology's own presentation justifies the 4-month retest with the 120-day RBC lifespan.

### Cited Findings
- **[SNIPPET-ONLY]** Eqology test manual: "The blood sample on the filter paper is extracted and analysed according to international standards for omega fatty acid testing by Vitas AS Laboratory in Oslo, Norway." — [Eqology Omega-3 Test Manual EN (PDF)](https://eqology.com/media/home/PresentationsAndBrochures/Omega-3_Test_&_Vitamin_K2+D3_Test_Manuals/Omega-3_Test_Manual_EN.pdf); [DE version](https://eqology.com/media/home/PresentationsAndBrochures/Omega-3_Test_&_Vitamin_K2+D3_Test_Manuals/Omega-3_Test_Manual_DE.pdf)
- **[SNIPPET-ONLY]** "personal fatty acid profile of the 11 most important fatty acids in our blood" plus omega-6:omega-3 ratio and Omega-3 Index. — [Eqology Omega-3 Test kit info (HU/EN)](https://eqology.com/hu/en/lifestyle/theme/eqology-omega-3-test-kit-more-info)
- **[SNIPPET-ONLY]** Brochure "First Look 2023": tests analysed by "our independent laboratory partner VITAS AS Laboratory in Oslo, Norway". The 2023 presentation recommends a retest after 4 months "as the life span of a red blood cell (erythrocyte) is 120 days". — [First Look 2023 EN (PDF)](https://eqology.com/media/home/PresentationsAndBrochures/First_Look_Brochures/First_Look_2023_EN_web.pdf); [FL presentation 2023 EN (PDF)](https://eqology.com/media/home/PresentationsAndBrochures/First_Look_Presentations/FL_presentation_2023_EN.pdf)
- **[SNIPPET-ONLY]** Results portal omegaratiotest.com; 20–25 working days on current pages, versus 15–20 in about 2019–2022. — [Eqology FAQ (GB)](https://eqology.com/gb/eq-faq); [Eqology Omega-3 Test kit (BE)](https://eqology.com/be/eqology-omega-3-test-kit)
- **[SNIPPET-ONLY]** Prices:
  - Austrian shop: 88 € total, premium-customer price 66 €. — [Eqology AT](https://eqology.com/at/eqology-omega-3-test-kit)
  - French shop (this round's search summary): 85 € normal price, 64 € premium. — [Eqology FR: Omega-3 Test](https://eqology.com/fr/product/nos-produits-fr/eq-omega-3-test-kit-fr)
  - The German eqology.com/de price was **not** found in any snippet.
- **[SNIPPET-ONLY]** Eqology calls it a "self-screening test intended for informational purposes only". — [Eqology PL](https://eqology.com/pl/eqology-omega-3-test-kit)
- **[SNIPPET-ONLY, partner report, 14 May 2025]** "EQ Omega Ratio Test": Omega-3 Index 5.6 %, ratio 9.2:1; "Omega-3 Index niedriger als 4 erhöhtes Risiko für Herz-Kreislauferkrankungen" ("Omega-3 Index below 4: increased risk of cardiovascular disease"). — [energyvital.de (PDF)](https://www.energyvital.de/media/3d/dd/27/1750080513/EQ%20Omega%20Ratio%20Test.pdf?ts=1750080513)

### Inferences
- Eqology and Zinzino share the same lab and the same 11-fatty-acid count. It is very likely that Eqology's "Omega-3 Index" is the same raw whole-blood EPA+DHA % that Vitas produces (Q1, Q5), judged against the RBC-derived 8 % target. Unlike Zinzino, Eqology does not appear (in the snippets) to label it "whole blood". It even frames the retest around RBC lifespan. This could not be checked against current full text.

### Gaps
- Every Eqology item is unverified against full text. Specifically missing:
  - the current German price;
  - the current test manual wording on handling (desiccant or foil bag);
  - exact formulas for the omega-6:3 ratio (AA/EPA or total n-6/n-3);
  - any whole-blood or RBC statement;
  - any CE/IVD statement.
  
  These require **eqology.com** (bare domain) to be allowed in the session's network settings, in addition to www.eqology.com, which only redirects.
