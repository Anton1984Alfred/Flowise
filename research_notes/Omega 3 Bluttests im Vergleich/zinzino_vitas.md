# Zinzino BalanceTest & Vitas AS (Oslo): methodology, accuracy, independence (state: Nov 2026)

> **Research limitation, read first:** In this session, direct page fetching (WebFetch/curl) was blocked for every relevant host (zinzino.com, zinzinowebstorage.blob.core.windows.net, vitas.no, link.springer.com, lipidworld.biomedcentral.com, forskningsparken.no, detoxhouse.com.au, PubMed/EuropePMC). All findings below come from search-engine result extracts of the cited pages, not from reading the full texts. Exact quotes and numbers should be spot-checked before final publication, especially the Methods and Declarations sections of the two *Lipids in Health and Disease* papers, which are the most important primary sources. Labels used below: **[MANUFACTURER]** = Zinzino/Vitas or reseller claim; **[INDEPENDENT]** = regulator, journalist, peer-reviewed or third-party source; **[COI]** = source with a conflict of interest, e.g. a competitor or an author tied to Zinzino.

---

## 1. Sample collection: DBS card, stabiliser, drying, shipping, stability, rejection

### Takeaway
The BalanceTest is a finger-prick whole-blood dried blood spot (DBS) on a Whatman® filter-paper card. The user puts at least 3 free-falling drops per circle on the card, dries it flat at room temperature for at least 10 minutes, and seals it in an aluminium/foil bag (with desiccant, according to some listings) for posting to Vitas in Oslo. On arrival Vitas stores samples at 4 °C and analyses them within one week. I found no public source that says whether the Zinzino card is pre-treated with an antioxidant such as BHT, or that gives a validated shipping-stability window or formal rejection criteria.

### Cited Findings
- **[MANUFACTURER]** Zinzino's Australian product leaflet says the fingertip blood sample goes on **Whatman® filter paper**, and that "VITAS Analytical Services" in Norway anonymously analyses the percentage content of **11 fatty acids, "which together represent approximately 98% of the fatty acids in the blood."** The leaflet does not mention BHT or the GC method. — [Zinzino BalanceTest leaflet en-AU (PDF, via reseller)](https://detoxhouse.com.au/wp-content/uploads/2025/10/ZinzinoBalanceTest-en-AU.pdf)
- **[MANUFACTURER]** Instructions in manufacturer-linked sheets: squeeze the finger gently once, then place **"several, minimum 3, free dripping blood drops" on each marked circle**, and **keep the card flat at room temperature for at least 10 minutes** to dry. The kit contents are "1 Blood-spot Sample Card, 1 Sample return envelope". — [Zinzino BalanceTest product sheet en-ZA](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-ZA.pdf); [Zinzino BalanceTest leaflet en-AU](https://detoxhouse.com.au/wp-content/uploads/2025/10/ZinzinoBalanceTest-en-AU.pdf)
- **[MANUFACTURER]** The Zinzino US product page says that if one drop does not cover the circle, a further drop should be added straight away. — [Zinzino US BalanceTest product page](https://zinzino.com/7784416705/US/en-US/products/Balance/309000)
- **[MANUFACTURER]** Some listings say the envelope goes into a **metal (foil) bag with desiccant** before shipping. — [search extract of reseller listings, e.g. omnimedica](https://omnimedica.com/en/products/balancetest)
- **[COI, peer-reviewed, authors linked to Zinzino/Vitas]** The 2025 *Lipids in Health and Disease* paper based on BalanceTest data describes the workflow as follows: cards were **air-dried horizontally at room temperature for ≥10 min, then sealed in an aluminium bag** until shipment to Vitas in Oslo. On arrival, **samples were stored at 4 °C and analysed within one week**. — [Torrissen et al. 2025, Lipids Health Dis 24:260](https://link.springer.com/article/10.1186/s12944-025-02676-6)
- **[THIRD-PARTY, non-Zinzino]** An unaffiliated guide recommends 15 minutes of drying and 4–5 drops. It warns that insufficient blood volume, contamination, improper drying or delayed posting can compromise results. These figures are not Zinzino's official ones. — [biohackeralliance.com BalanceTest guide 2026](https://biohackeralliance.com/insights/zinzino-balance-test)
- **[MANUFACTURER, affiliate]** An affiliate page says the DBS sample is "scientifically proven to be as accurate as a venous blood sample" for fatty acid analysis. It names no study. — [zlifedrinks.com (Zinzino affiliate)](https://zlifedrinks.com/zinzino/home-health-tests/balance/)
- **[INDEPENDENT, general DBS science]** Background on why a stabiliser matters:
  - BHT on chromatography paper protected PUFAs in DBS from degradation **for up to 8 weeks at room temperature**. — [Metherel et al. 2013, Lipids Health Dis (PMC3599643)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3599643/)
  - Patent family WO2013104025 (PCT/AU2013/000021, Australian priority AU2012900110A; status "ceased" for the WO publication) reports a **significant decline in EPA and DHA on papers treated with BHT alone**. It says BHT combined with an iron chelator (EDTA or ascorbic acid) on silica-gel paper kept EPA and DHA levels for about 2 months at ambient temperature. **This patent is not linked to Vitas in any source found.** — [Google Patents WO2013104025A1](https://patents.google.com/patent/WO2013104025A1)
  - A review extract says that on untreated cards, AA, EPA and DHA degrade significantly over 4 weeks at room temperature, and that antioxidant pre-treatment only partly mitigates this. — [search extract; related: Liu et al., long-term stabilisation of LCPUFA in DBS](https://www.researchgate.net/publication/268821985_A_method_for_long_term_stabilisation_of_long_chain_polyunsaturated_fatty_acids_in_dried_blood_spots_and_its_clinical_application)

### Inferences
- With no documented antioxidant pre-treatment and only a foil bag (plus desiccant) for protection, the results depend on transit time. Postal delays, heat or a sample left unposted for days could lower EPA and DHA readings, which would inflate the omega-6:3 and AA:EPA ratios. Vitas's "4 °C, analysed within 1 week" applies only after the sample arrives. The time on the user's side and in the post is not controlled.
- Whatman filter paper is standard DBS paper (for example Whatman 903). I could not confirm whether Zinzino's card is plain or chemically treated.

### Gaps
- Exact card type (e.g. Whatman 903 or a proprietary card), any BHT or other antioxidant/chelator pre-treatment, and whether the foil bag contains desiccant in all markets: none confirmed in an accessible primary source.
- Validated sample stability (days at room temperature, heat tolerance) for the Vitas BalanceTest method: no data found.
- Formal sample rejection criteria (e.g. too little blood, haemolysis or contamination, overlapping spots) and the replacement procedure: none found publicly.

---

## 2. Sample matrix: what exactly is measured

### Takeaway
Vitas measures the fatty-acid profile of **whole blood** (capillary DBS). Whole blood includes the fatty acids of plasma lipids, red cells and white cells. It is not the red-cell (erythrocyte) membrane fraction. Results are given as the **relative percentage of each fatty acid among the 11 measured fatty acids**, not as absolute concentrations.

### Cited Findings
- **[COI, peer-reviewed]** Both Zinzino/Vitas papers describe their data as **"whole-blood dried blood spot samples"** in the titles. — [Torrissen et al. 2025](https://link.springer.com/article/10.1186/s12944-025-02676-6); [Gisslevik et al. 2026, Lipids Health Dis](https://link.springer.com/article/10.1186/s12944-026-03071-5)
- **[MANUFACTURER]** The 11 fatty acids "together make up 100% of the analysed total". The results are therefore normalised to the sum of the 11 fatty acids. The AU leaflet alternatively says the 11 represent "approximately 98% of the fatty acids in the blood". — [Zinzino product sheet en-ZA](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-ZA.pdf); [mitocare.de reseller page](https://mitocare.de/en/products/zinzino-balance-test-set); [Zinzino leaflet en-AU](https://detoxhouse.com.au/wp-content/uploads/2025/10/ZinzinoBalanceTest-en-AU.pdf)
- **[RESELLER/DISTRIBUTOR, contradictory]** Some distributor and clinic pages wrongly describe the test as looking at "the long term membranes of your red blood cells" or as measuring RBC-membrane EPA and DHA. — [search extract; e.g. omega3health.us](https://omega3health.us/balance-test/); [ivhealthsunshinecoast.com.au](https://ivhealthsunshinecoast.com.au/services/omega-balance-consultation/)
- **[INDEPENDENT]** A clinical-trial record notes that whole-blood DBS fatty-acid results "ha[ve] to be corrected because [they are] affected by the lipid composition present in the plasma". This means they are more sensitive to recent meals than erythrocyte values. — [ClinicalTrials.gov NCT06916455](https://clinicaltrials.gov/study/NCT06916455)
- **[COI: competitor OmegaQuant]** In about 100 paired samples, OmegaQuant found **whole-blood EPA+DHA averaged about 4.24% versus about 6.2% in RBC**. From this it derives a mapping in which a whole-blood (Zinzino-type) value of about **2.4% corresponds to an Omega-3 Index of about 4%, and about 5.4% corresponds to about 8%**. This is OmegaQuant's own mapping, not a Zinzino figure. — [OmegaQuant, OmegaMatters Episode 48](https://omegaquant.com/omegamatters-ep-48/)
- **[INDEPENDENT]** "How to convert whole blood EPA + DHA into the O3I is well established in humans" (a veterinary DBS paper, by way of contrast). — [Derivation of the Omega-3 Index from DBS in dogs and cats (PMC9863621)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9863621/)

### Inferences
- **Key point for the comparison:** Omegametrix's HS-Omega-3 Index is by definition an erythrocyte measure (EPA+DHA as a percentage of erythrocyte fatty acids). Zinzino's figures are whole-blood percentages normalised to only 11 fatty acids. **The numbers are not directly interchangeable.** On the same blood, whole-blood EPA+DHA is systematically lower than RBC EPA+DHA (roughly ×1.45 according to the OmegaQuant data). Normalising to 11 instead of about 20–26 fatty acids pushes the percentages slightly upward.
- Whole blood contains plasma lipids, so recent intake (for example an oily-fish meal or a dose of oil shortly before sampling) has more influence than on the erythrocyte index. That makes "before/after" comparisons more sensitive to timing and fasting state.

### Gaps
- I could not confirm whether the "Omega-3 Index" Zinzino reports is raw whole-blood EPA+DHA or a value converted to an erythrocyte equivalent (see section 4). A quote attributed to Vitas ("we measure fatty acid levels directly in whole blood and report the results as a 'whole blood omega-3 index'") appeared in a search extract, but a follow-up search could not find its source page. Treat it as unverified.

---

## 3. Analytical method at Vitas: derivatisation, GC, column, internal standard, fatty-acid panel

### Takeaway
Public sources describe the Vitas method only as "established methods at the Vitas laboratory" for high-throughput DBS fatty-acid profiling, with a citation to an earlier method paper. No accessible source states the derivatisation chemistry, the GC detector (FID or MS), the column or the internal standard. The panel has **11 fatty acids**. The most consistent reconstruction is: palmitic C16:0, stearic C18:0, oleic C18:1n-9, linoleic C18:2n-6, γ-linolenic C18:3n-6, DGLA C20:3n-6, arachidonic C20:4n-6, α-linolenic C18:3n-3, EPA C20:5n-3, DPA C22:5n-3 and DHA C22:6n-3. That list needs verifying.

### Cited Findings
- **[COI, peer-reviewed]** In the 2025 paper, "fatty acid profiles obtained from DBS samples were analysed using **established methods at the Vitas laboratory**", with a citation to a prior method paper. The 2026 paper likewise says "the established whole-blood DBS fatty-acid method described previously [19]". — [Torrissen et al. 2025](https://link.springer.com/article/10.1186/s12944-025-02676-6); [Gisslevik et al. 2026 (ResearchGate)](https://www.researchgate.net/publication/415929230_Real-world_omega-3_supplementation_patterns_and_whole-blood_fatty-acid_biomarkers_a_cross-sectional_analysis_of_762150_dried_blood_spot_samples)
- **[MANUFACTURER, Vitas]** Vitas's fatty-acid service page cites "many years of experience in high-throughput fatty acid profile analyses from DBS". It accepts whole blood, plasma, serum and DBS, and lists **Tore Bolstad** as senior research scientist. In the accessible extract it gives no validation data. — [vitas.no: Fatty acid analytical services](https://www.vitas.no/analytical-services/biomarker-analytical-services/fatty-acid-analytical-services)
- **[MANUFACTURER]** Vitas describes itself as offering "high-quality, custom **chromatographic** analytical services". — [Zinzino-hosted "Vitas – Who we are" (2017)](https://zinzinowebstorage.blob.core.windows.net/financialdocuments/Vitas-Who%20we%20are-%202017-zz.pdf)
- **[RESELLER, probably wrong]** One third-party retailer says Vitas works in "liquid chromatography and biochemical analysis". Fatty-acid profiling is normally done by GC of fatty-acid methyl esters (FAMEs), so this attribution is unreliable. — [natural-supplements.eu (retailer)](https://natural-supplements.eu/en/zinzino-balance-test)
- **[MANUFACTURER] Fatty-acid panel:**
  - The Zinzino ZA product sheet lists palmitic, stearic, oleic and linoleic acids, DPA, DHA and EPA, with AA used for the AA index. — [Zinzino product sheet en-ZA](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-ZA.pdf)
  - A reseller additionally names α-linolenic, γ-linolenic and DGLA. — [mitocare.de](https://mitocare.de/en/products/zinzino-balance-test-set)
  - A Norwegian classified ad for a Vitas-analysed kit (brand not named) describes 11 fatty acids covering saturated, omega-9, omega-6 and omega-3 groups. Results are shown as a percentage of the total measured and compared with an average range. — [finn.no listing](https://www.finn.no/recommerce/forsale/item/399985485)
  - A sample report from 2020 exists ("ZINZINO BALANCE TEST REPORT … Date: 30.09.2020") but could not be opened. — [brainmarket.cz sample report PDF](https://www.brainmarket.cz/user/related_files/test.pdf)
- **[INDEPENDENT, reference method class]** Typical DBS FAME workflow, for context only (**not** confirmed as Vitas's method): direct transesterification in 14% BF₃/methanol with hexane at 95 °C for 60 min, then GC. Another non-Zinzino DBS study used an Agilent 6890A GC with FID. — [Metherel et al. 2013 (PMC3599643)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3599643/); [Dried blood spot technique in an oily-fish intervention, 2025](https://link.springer.com/article/10.1186/s12986-025-00983-4)
- **[INDEPENDENT]** The classic "drop of blood from a fingertip" direct-transesterification method (Marangoni, Colombo & Galli 2004, Anal Biochem) is the method lineage most DBS whole-blood profiling descends from. Co-author A. M. Rizzo of the Zinzino papers is from the Milan lipid group. This is context only; I could not confirm that it is the "[19]" method reference. — [ResearchGate: Marangoni et al. 2004](https://www.researchgate.net/publication/7474073_A_method_for_the_direct_evaluation_of_the_fatty_acid_status_in_a_drop_of_blood_from_a_fingertip_in_humans_Applicability_to_nutritional_and_epidemiological_studies)

### Inferences
- With only 11 fatty acids, the panel is narrower than research and clinical panels (the Omegametrix HS-Omega-3 Index reports about 26 fatty acids). Trans fats, omega-9 species other than oleic acid, C20:2n-6, C22:4n-6 (adrenic acid) and others are left out. Because percentages are normalised to the sum of the 11, values are not numerically comparable with labs using broader panels.
- The absence of any published methods detail (column, internal standard, CVs) in the accessible sources is itself a finding. The test is marketed as "high-precision", but the precision data are not publicly documented.

### Gaps
- I could not access the cited method reference ("[19]" in the 2026 paper) or the full Methods sections of the 2025 and 2026 papers. GC-FID versus GC-MS, column type (for example a highly polar cyanopropyl column), internal standard (for example C17:0 or C19:0 TG), methylation reagent, and intra- and inter-assay CVs all remain unconfirmed. **These need to be checked in the full-text Methods at [lipidworld.biomedcentral.com](https://lipidworld.biomedcentral.com/articles/10.1186/s12944-025-02676-6) before the final report.**
- The official, current list of the 11 fatty acids should be checked against the latest Zinzino product sheet. Sources differ (the ZA sheet does not name GLA, DGLA or ALA explicitly in the extract).

---

## 4. Reported metrics, formulas and target values

### Takeaway
The BalanceTest report gives six markers from the 11 fatty acids: Omega-6:3 balance (target < 3:1), Omega-3 Index (target ≥ 8%), Protection Value (0–100, target > 90), Cell-membrane fluidity (target < 4:1), Mental Strength (target < 1:1 per one source) and the AA index. All formulas come from Zinzino or reseller material. **No source documents a validated conversion from whole blood to an erythrocyte-equivalent Omega-3 Index**, even though the 8% target comes from the erythrocyte-based HS-Omega-3 Index literature.

### Cited Findings
- **[MANUFACTURER/RESELLER]** The six markers are the Omega-3 Index, Omega-6:3 Balance, Protection Value, Cell-membrane fluidity, Mental Strength and the AA index. — [consultingroom.com blog on the six markers](https://www.consultingroom.com/blog/the-six-zinzino-balancetest-markers-and-which-one-matters-most)
- **Omega-3 Index [MANUFACTURER/RESELLER]:** the sum of the EPA and DHA percentages. Zinzino's stated ideal is **at least 8%**, with higher values preferred. — [relax4health.com.au](https://relax4health.com.au/Article/Zinzino-Balance-Test-info-for-Omega-6-to-omega-3-Ratio); [consultingroom.com](https://www.consultingroom.com/blog/the-six-zinzino-balancetest-markers-and-which-one-matters-most)
- **Omega-6:3 balance [MANUFACTURER/RESELLER], conflicting definitions:**
  - One reseller summary gives the headline "Omega-6:3 Balance" as **AA ÷ EPA**, target **< 3:1**. — [consultingroom.com](https://www.consultingroom.com/blog/the-six-zinzino-balancetest-markers-and-which-one-matters-most); [relax4health.com.au](https://relax4health.com.au/Article/Zinzino-Balance-Test-info-for-Omega-6-to-omega-3-Ratio)
  - A separate "omega-6 ratio" input to the Protection Value is defined as **(DGLA + AA) × 100 / (DGLA + AA + EPA + DPA + DHA)**. — [reseller pages in result set: relax4health.com.au](https://relax4health.com.au/Article/Zinzino-Balance-Test-info-for-Omega-6-to-omega-3-Ratio); [biolimitless.com](https://biolimitless.com/shop/partner-products/balancetest-by-zinzino/)
  - The Zinzino-authored papers report the "n-6:n-3 ratio" and the "AA:EPA ratio" as **separate** variables. Zinzino's 2026 press release ("Test, don't guess!") highlights AA/EPA. — [Torrissen et al. 2025](https://lipidworld.biomedcentral.com/articles/10.1186/s12944-025-02676-6); [Zinzino press release 2026 (Cision)](https://news.cision.com/zinzino/r/test--don-t-guess--new-study-shows-why-measuring-more-than-the-omega-3-status-matters--and-highlight,c4411661)
- **Protection Value [MANUFACTURER]:** "each indicator value is given the same weight in a second calculation and assigned a value between 0 and 100, which is then divided by 3". The three indicators are the omega-6 ratio, the omega-3 (EPA+DHA) level and the balance value. The ideal is **> 90**. Zinzino itself says it "describes fatty acid protection level only, not health status". — [Zinzino BalanceTest product sheet en-GB](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-GB.pdf)
- **Cell-membrane fluidity [MANUFACTURER/RESELLER]:** **(palmitic + stearic) ÷ (EPA + DHA)**. A value **< 4:1** is said to indicate "sufficient fluidity". — [Zinzino product sheet en-ZA / reseller extracts](https://zinzinowebstorage.blob.core.windows.net/product-sheets/BalanceTest-en-ZA.pdf); [consultingroom.com](https://www.consultingroom.com/blog/the-six-zinzino-balancetest-markers-and-which-one-matters-most)
- **Mental Strength [RESELLER]:** **AA ÷ (EPA + DHA)**, which should be **below 1:1** for "sufficient and balanced supply… to the brain and nervous system". — [relax4health.com.au](https://relax4health.com.au/Article/Zinzino-Balance-Test-info-for-Omega-6-to-omega-3-Ratio); [biolimitless.com](https://biolimitless.com/shop/partner-products/balancetest-by-zinzino/)
- **AA index [RESELLER]:** AA as a percentage of the total fatty acids measured. — [consultingroom.com](https://www.consultingroom.com/blog/the-six-zinzino-balancetest-markers-and-which-one-matters-most)
- **[INDEPENDENT news, quoting Zinzino]** In Nettavisen, Zinzino said the test is not meant to frighten. According to the article extract, the company also said most authorities put a healthy omega-3 level above 6% but not above 10–12%. — [Nettavisen](https://www.nettavisen.no/nyheter/tjener-milliarder-pa-den-omstridte-helsetesten-zinzino-skaper-frykt-som-ikke-er-reell/s/5-95-2968720)
- **[COI, peer-reviewed]** Population whole-blood DBS "n-3 levels" in BalanceTest data: the highest means were **Ghana 5.4 ± 2.0, Japan 5.1 ± 1.8 and Nigeria 4.6 ± 1.7** (percentages). Continent explained only 0.7% of the variance (partial η² = 0.007). — [Torrissen et al. 2025](https://link.springer.com/article/10.1186/s12944-025-02676-6)
- **[INDEPENDENT]** The standard Omega-3 Index is defined as EPA+DHA as a percentage of total fatty acids in **erythrocyte membranes**. — [scoping review (PMC9892774)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9892774/)

### Inferences
- If the reported "Omega-3 Index" were raw whole-blood EPA+DHA, the 8% target would be almost unreachable. Even the best-supplied countries in Zinzino's own dataset average about 5% whole-blood n-3, and OmegaQuant maps 5.4% whole blood to about 8% RBC. That would make most users "deficient" by construction and fit the reported "90% unbalanced" figure. If Zinzino instead applies an undisclosed conversion to an RBC equivalent, the conversion equation and its error should be disclosed. **Either way it is a transparency gap and highly relevant to the comparison with Omegametrix.**
- The Protection Value, Mental Strength and Membrane Fluidity scores are **proprietary constructs** with no peer-reviewed clinical validation found. "Mental Strength" in particular has no recognised biomarker basis.
- The targets (< 3:1, > 8%, > 90, < 4:1, < 1:1) are vendor thresholds, not clinical guideline cut-offs.

### Gaps
- Official Zinzino or Vitas documentation of the exact formula for each marker (especially the headline "Omega-6:3 balance" numerator and denominator), and whether the Omega-3 Index is converted from whole blood (and by which equation), was not found.
- The current (2026) report layout could not be checked. The only sample report found dates from 2020.

---

## 5. Accreditation and quality assurance (ISO/IEC 17025, GMP, proficiency testing)

### Takeaway
Vitas is consistently described, by Zinzino and itself, as a **"GMP-certified" contract laboratory**. A third-party directory says it holds a manufacturing authorisation from the Norwegian Medicines Agency. **No evidence was found that Vitas holds ISO/IEC 17025 (or ISO 15189) accreditation from Norsk akkreditering, let alone for the DBS fatty-acid method.** Searches of akkreditert.no turned up no Vitas entry. No participation in an external proficiency-testing or ring-trial scheme for DBS fatty acids could be confirmed.

### Cited Findings
- **[MANUFACTURER]** "All blood samples are independently managed and analyzed anonymously by **Vitas, a GMP-certified chemical analysis contract lab** based in Oslo, Norway." — [Zinzino: Are test results reliable?](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable); [Zinzino home health tests](https://www.zinzino.com/site/us/en-us/explore/home-health-tests)
- **[MANUFACTURER]** "Vitas is a GMP certified chemical analysis contract lab, with 25 years' [experience]" (2017 document). — [Vitas – Who we are 2017 (Zinzino-hosted PDF)](https://zinzinowebstorage.blob.core.windows.net/financialdocuments/Vitas-Who%20we%20are-%202017-zz.pdf)
- **[THIRD-PARTY directory]** VITAS AS "operates a GMP-certified facility and holds a **manufacturing authorization for medicinal products from the Norwegian Medicinal Agency**", and has processed **over two million DBS samples as of December 2024**. Not verified against the Norwegian Medicines Agency's register. — [Europages: VITAS AS](https://www.europages.co.uk/VITAS-AS/NOR028227-00101.html)
- **[MANUFACTURER]** Zinzino says the "test validity and accuracy are consistent with the most rigorous medical methods". — [Zinzino: Are test results reliable?](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable)
- **[INDEPENDENT]** Norsk akkreditering lists accredited labs with a scope document per accreditation number (TEST xxx / MED xxx) under NS-EN ISO/IEC 17025:2017 or ISO 15189. Targeted searches for Vitas returned only other organisations' scopes (e.g. TEST 076, TEST 049, MED/TEST 287), and **no Vitas entry**. — [akkreditert.no – Hvem er akkreditert](https://www.akkreditert.no/akkrediterte-organisasjoner/); [akkreditert.no – laboratorier](https://www.akkreditert.no/kundeside/laboratorier/)
- **[INDEPENDENT]** The only identified interlaboratory DBS fatty-acid comparison (Metherel et al., *Lipids* 2019;54:755–761; 5 labs; 19-FA standardised reporting; 5 and 8 outliers out of 91 measures) does not name the participating labs in its abstract. Authors include W. S. Harris (OmegaQuant), R. A. Gibson, J. T. Brenna, K. D. Stark and others. **Whether Vitas took part is unknown.** — [Metherel et al. 2019, Lipids](https://aocs.onlinelibrary.wiley.com/doi/abs/10.1002/lipd.12203)
- **[THIRD-PARTY]** A Vitas job ad describes the company as a private contract research laboratory in Forskningsparken, Oslo, offering pharma services, bioanalysis and DBS analysis. — [finn.no job ad Vitas AS](https://finn.no/401262373)
- **[INDEPENDENT]** Vitas is listed as a project partner in the University of Oslo-led **Lifebrain** consortium (an EU research project). — [Lifebrain: Vitas Ltd.](https://www.lifebrain.uio.no/about/project-partners/vitas-as/)

### Inferences
- "GMP-certified" (pharmaceutical Good Manufacturing Practice, relevant to pharma QC testing) is **not the same as ISO/IEC 17025 or ISO 15189 method accreditation** of a specific test. Neither the GMP status nor a manufacturing authorisation by itself shows that the BalanceTest DBS fatty-acid method has been externally assessed for accuracy. This contrasts with labs that cite a specific accreditation scope for their omega-3 method.
- The absence of any documented external quality assessment (EQA) or ring-trial participation for the DBS FA method is a notable gap for a test used on more than 1.7 million people.

### Gaps
- No confirmed ISO 17025 or 15189 accreditation number for Vitas, and no confirmed absence of one: akkreditert.no could not be queried directly. **Recommendation:** check the "Hvem er akkreditert" list on akkreditert.no manually for "Vitas".
- Exact scope of the GMP certificate or manufacturing authorisation (does it cover only pharma QC, or also the DBS work?) is not documented.
- Proficiency testing or ring trials (e.g. NIST Fatty Acid QAP, AOCS, OmegaQuant/Harris round robins): no evidence found either way.

---

## 6. Published validation and studies using Vitas DBS data (authors, funding)

### Takeaway
**No peer-reviewed validation of the Vitas BalanceTest DBS method against venous whole blood, plasma or erythrocytes was found** (no published CVs, correlation coefficients or bias). The main publications using Vitas data are two large retrospective analyses of the commercial BalanceTest database (2025 and 2026, *Lipids in Health and Disease*). Both are authored by Zinzino employees, a Zinzino-owned subsidiary and the Vitas CEO. They cite an earlier "established method" paper that I could not access. Independent DBS-versus-venous validations exist for other labs and methods, not for Vitas.

### Cited Findings
- **[COI, peer-reviewed]** **Torrissen M, Gisslevik E, Gundersen TE, Bolstad T, Eide O, Rizzo AM, et al. (2025).** "Global variations in omega-3 fatty acid status and omega-6:omega-3 ratios: insights from > 500,000 whole-blood dried blood spot samples." *Lipids Health Dis* 24:260 (August 2025). — [Springer](https://link.springer.com/article/10.1186/s12944-025-02676-6); [BMC](https://lipidworld.biomedcentral.com/articles/10.1186/s12944-025-02676-6)
  - Competing interests: Torrissen is affiliated with **BioActive Foods AS, which is owned by Zinzino Operations AB**. Gisslevik and Robertson are with **Zinzino Operations AB**. **T.G. (Thomas E. Gundersen) is CEO and co-founder of Vitas Analytical Services and a member of Zinzino's Scientific Advisory Board.** The authors state that analysis and interpretation were done "independently of commercial influence". — [Springer PDF](https://link.springer.com/content/pdf/10.1186/s12944-025-02676-6.pdf)
  - Zinzino's press release says the samples came from **Zinzino's BalanceTest database** and that the work was a collaboration between Zinzino's in-house team, its Scientific Advisory Board and "the independent analytical contract lab Vitas AS". — [Zinzino press release Aug 2025 (Mynewsdesk)](https://www.mynewsdesk.com/zinzino/pressreleases/new-study-unveils-global-snapshot-on-omega-3-deficiency-and-why-high-precision-testing-plus-an-enhanced-formula-can-close-the-gap-3399799); [PR Newswire UK](https://www.prnewswire.co.uk/news-releases/zinzino-ab-publ-new-study-unveils-global-snapshot-on-omega-3-deficiency--and-why-high-precision-testing-plus-an-enhanced-formula-can-close-the-gap-302532311.html)
  - Trade-press coverage framed the results as "widespread omega-3 deficiencies". — [NutraIngredients, 18 Sep 2025](https://www.nutraingredients.com/Article/2025/09/18/global-dried-blood-spot-analysis-reveals-widespread-omega-3-deficiencies/)
- **[COI, peer-reviewed]** **Gisslevik E (Zinzino Operations AB, Mölndal), Torrissen M, Rizzo AM, Gundersen TE, Eide O, Clayton P, Robertson C, et al. (2026).** "Real-world omega-3 supplementation patterns and whole-blood fatty-acid biomarkers: a cross-sectional analysis of **762,150** dried blood spot samples." *Lipids Health Dis* (2026). It is a retrospective analysis of samples submitted to a commercial fatty-acid profiling service from **2012–2023**. Competing interests: Zinzino Operations AB "markets omega-3 supplements and fatty-acid testing services related to the subject matter"; the Vitas CEO "performed the fatty-acid analyses used in this study". The authors state that no non-author company representative controlled the analyses or the decision to publish. — [Springer](https://link.springer.com/article/10.1186/s12944-026-03071-5); [ResearchGate](https://www.researchgate.net/publication/415929230_Real-world_omega-3_supplementation_patterns_and_whole-blood_fatty-acid_biomarkers_a_cross-sectional_analysis_of_762150_dried_blood_spot_samples)
  - Promoted by Zinzino as "Test, don't guess!", highlighting "distinct results among Zinzino Balance Concept users". — [Zinzino press release 2026 (Mynewsdesk)](https://www.mynewsdesk.com/zinzino/pressreleases/test-dont-guess-new-study-shows-why-measuring-more-than-the-omega-3-status-matters-and-highlights-distinct-results-among-zinzino-balance-concept-users-3473107); [PR Newswire UK](https://www.prnewswire.co.uk/news-releases/test-dont-guess-new-study-shows-why-measuring-more-than-the-omega-3-status-matters-and-highlights-distinct-results-among-zinzino-balance-concept-users-302912676.html)
- **[INDEPENDENT critique]** "No large-scale independent studies specifically validate the Zinzino Balance Test against health outcomes." — [biohackeralliance.com Zinzino review 2026](https://biohackeralliance.com/insights/zinzino-review-science-backed-omega-3-personalized-nutrition)
- **[INDEPENDENT, German secondary source]** The improvement in the ratio after 120 days that Zinzino publishes comes from company-internal evaluations and is not published in peer-reviewed journals. — [omega3-test.net (comparison site; possible COI)](https://www.omega3-test.net/vergleich/zinzino-erfahrungen-test.html)
- **[HISTORICAL]** Vitas's CEO was quoted as saying that "so far only Zinzino is using their blood spot testing services to validate the product". — [LongevityLive](https://longevitylive.com/anti-aging/zinzino-uses-a-blood-test-to-prove-whether-your-omega-supplements-work/)
- **[INDEPENDENT, non-Vitas DBS validation, for context]**
  - DBS versus wet venous blood in 10 fasting adults: no significant differences in relative percentages, except two fatty acids below 0.5%. — [PLEFA 2019 (common card versus wicking device)](https://www.plefa.com/article/S0952-3278(19)30052-3/abstract); [Univ. Waterloo thesis](https://uwspace.uwaterloo.ca/bitstreams/b822a52a-f9e9-4760-82f7-82bb78d53854/download)
  - Capillary DBS versus venous whole blood, plasma and erythrocytes in 50 subjects: the DBS profile was representative of venous blood for most fatty acids. — [Liu et al. (ResearchGate)](https://www.researchgate.net/publication/268821985_A_method_for_long_term_stabilisation_of_long_chain_polyunsaturated_fatty_acids_in_dried_blood_spots_and_its_clinical_application)
  - The Omega-3 Index can be measured in DBS (Harris/OmegaQuant method, not Vitas). — [Measurement of the Omega-3 Index in DBS (ResearchGate)](https://www.researchgate.net/publication/312131154_Measurement_of_the_Omega-3_Index_in_Dried_Blood_Spots)

### Inferences
- Everything published about BalanceTest/Vitas data is **industry-generated**: authored by Zinzino staff, a Zinzino subsidiary and the laboratory's CEO, using the company's commercial database. That does not make the data wrong, but it means **no independent analytical validation exists in the literature found**.
- The retrospective database papers say nothing about **individual-level analytical precision**, which is what matters for interpreting a before/after change in one person.

### Gaps
- The method validation reference (cited as "[19]" in 2026 and as a "prior method paper" in 2025) could not be identified or read. It is possibly an older Vitas or Galli-group paper. **Recommendation: open the reference lists of both open-access papers.**
- Intra- and inter-assay CVs, the correlation of Vitas DBS with venous erythrocytes, and bias for EPA, DHA and AA: none found.
- Funding statements of both papers: not visible in the extracts (only the competing-interest statements).

---

## 7. Ownership and conflicts of interest: Zinzino, Vitas, BioActive Foods, Faun

### Takeaway
**No source shows that Zinzino owns Vitas or holds a stake in it.** Vitas AS (org. no. 968655973) is a **privately owned** contract laboratory founded in **1994** as a spin-off from the University of Oslo's Institute of Nutrition. However, the relationship is close. **Vitas CEO and co-founder Thomas E. Gundersen sits on Zinzino's Scientific Advisory Board** and co-authors Zinzino's papers. Zinzino is a long-term (historically the first, possibly the main) DBS customer. Zinzino **does** own **BioActive Foods AS**, the Norwegian company behind the Balance concept and the employer of a lead author, and **Faun Pharma AS** (98.8%), a contract manufacturer. Zinzino's description of Vitas as an "independent" lab is therefore only partly accurate.

### Cited Findings
- **[MANUFACTURER, Vitas declaration]** "Vitas AS is a **privately owned GMP certified Contract Laboratory**… established in **1994 as a spin off from the Institute of Nutrition at the University of Oslo**". It is located at the Oslo Innovation Centre, Gaustadalléen 21, with **org. no. 968655973**. The declaration is signed by Thomas E. Gundersen and names Zinzino AB as a customer. — [Vitas declaration on sample destruction (Zinzino-hosted PDF)](https://zinzinowebstorage.blob.core.windows.net/filelibrary/Declaration-sample-destruction-Vitas-AS-EN.pdf)
- **[COI disclosure, peer-reviewed]** "T.G. is the CEO and co-founder of Vitas Analytical Services and serves as a member of Zinzino's scientific advisory board." — [Torrissen et al. 2025, Declarations](https://link.springer.com/content/pdf/10.1186/s12944-025-02676-6.pdf)
- **[COI disclosure, peer-reviewed]** Torrissen is affiliated with **Bioactive Foods AS, which is owned by Zinzino Operations AB**. — [Torrissen et al. 2025](https://link.springer.com/article/10.1186/s12944-025-02676-6)
- **[MANUFACTURER]** Zinzino calls Vitas a "long-term partner" and an "independent" contract lab. — [Zinzino: Are test results reliable?](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable); [Zinzino press release 2025](https://www.mynewsdesk.com/zinzino/pressreleases/new-study-unveils-global-snapshot-on-omega-3-deficiency-and-why-high-precision-testing-plus-an-enhanced-formula-can-close-the-gap-3399799)
- **[INDEPENDENT/THIRD-PARTY]** "Faun [Pharma] eies i dag av Zinzino, og det er her mange av Zinzino-produktene produseres." Zinzino's corporate history records its stake in Faun Pharma AS rising to **98.8%**. — [balancetest.no – om Zinzino](https://www.balancetest.no/om-zinzino); [Zinzino annual report (Cision PDF)](https://mb.cision.com/Public/10976/4339845/91f42d02e1ccfc69.pdf)
- **[THIRD-PARTY]** Vitas has specialised in recent years in biomarker analysis in DBS ("verdensledende på blodanalyse"). Other DBS partners exist, e.g. bodymarkers.com. — [Forskningsparken article on Vitas](https://www.forskningsparken.no/en/news/how-they-became-world-leaders-in-blood-analysis); [bodymarkers.com – om testen](https://bodymarkers.com/om-testen)

### Inferences
- The Vitas laboratory's single largest DBS client is very likely Zinzino: more than 1.7 million Zinzino tests reported, against more than 2 million DBS samples processed by Vitas by December 2024. Add the CEO's seat on Zinzino's advisory board and the joint publications, and Vitas is **economically dependent on and scientifically intertwined with** Zinzino, even without an equity link. A German-language report should describe it as "formally independent (no stake held by Zinzino found) but closely tied commercially and personally".

### Gaps
- Vitas's shareholder register: Brønnøysundregistrene or proff.no could not be queried. An equity link through individuals or holding companies is not ruled out.
- Whether Vitas also analyses competitors' tests (e.g. Eqology): no source found. The finn.no ad for a Vitas-analysed kit does not name the brand. **The Eqology researcher should check which lab Eqology uses.**
- When the Zinzino–Vitas partnership began: implied to date from around 2012 at the latest (the 2026 paper's data run from 2012), but no explicit start date was found.

---

## 8. Criticism: science, media, regulators, implausible results

### Takeaway
Scientific criticism targets the **omega-6:omega-3 ratio as a biomarker** (Harris 2006 and 2018; Calder; Risérus; Retterstøl) and the **"test-sell-retest" design within an MLM**, in which about 90% of people tested are told they are "unbalanced". Norwegian and Swedish media coverage in 2025–2026 was intensive, especially DN and Nettavisen in Norway and EFN in Sweden. **Mattilsynet (Norway) issued three decisions in 2026** after a March 2026 inspection: notified around April, adopted around 2 June 2026. Norway's health minister called the marketing of blood tests for children "unacceptable". **Konsumentverket (Sweden) issued an injunction on 20 March 2026**, backed by a SEK 1.5 million penalty. In Germany, a partner's Instagram post with health claims for BalanceOil was removed after a Verbraucherzentrale (Lebensmittelklarheit) complaint. Reports of implausible results are anecdotal only.

### Cited Findings
**Scientific critique of the ratio [INDEPENDENT]**
- Harris (2006): the n-6/n-3 ratio "may be of value in interpreting biomarker data", but "there are few human experimental and clinical trial data to support this view". Metrics based on n-3 fatty acids alone, especially EPA and DHA, "appear to hold the greatest promise". — [Harris 2006, PubMed 17045070](https://pubmed.ncbi.nlm.nih.gov/17045070/)
- Harris (2018), "The Omega-6:Omega-3 ratio: A critical appraisal and possible successor": the ratio cannot distinguish ALA from EPA and DHA, or LA from AA. The Omega-3 Index (RBC EPA+DHA) "has much to recommend it" as a successor. — [PubMed 29599053](https://pubmed.ncbi.nlm.nih.gov/29599053/)
- Counterpoint: in a 2023 cohort analysis, ratios such as EPA/AA and (EPA+DPA+DHA)/AA added risk prediction beyond age and sex. **AA-based ratios therefore carry some prognostic signal, unlike the broad n-6/n-3 ratio.** — [American Heart Journal 2023 (Aalborg Univ. repository PDF)](https://vbn.aau.dk/files/549842682/1-s2.0-S0002870323000893-main.pdf)
- Prof. **Kjetil Retterstøl** (University of Oslo) called the test misleading and likely to cause needless health anxiety ("fristende å kalle det et triks"). Prof. **Philip Calder** (Southampton) and Prof. **Ulf Risérus** (Uppsala) conclude there is **no scientific support for an ideal fatty-acid balance** of the kind Zinzino promotes. — [Nettavisen](https://www.nettavisen.no/nyheter/tjener-milliarder-pa-den-omstridte-helsetesten-zinzino-skaper-frykt-som-ikke-er-reell/s/5-95-2968720); [no.wikipedia: Zinzino](https://no.wikipedia.org/wiki/Zinzino)
- Prof. **Anne Spurkland** (Oslo) says the test results contribute to medicalisation ("sjukliggjøring"). — [DN: "Reagerer på Zinzinos balansekonsept"](https://www.dn.no/helse/zinzino/helse/dn-investor/reagerer-pa-zinzinos-balansekonsept-far-alle-piggene-ut/2-1-1964344)

**Media investigations [INDEPENDENT]**
- Nettavisen/Bergens Avisen (around April 2026): "Tjener milliarder på den omstridte helsetesten – Zinzino skaper frykt som ikke er reell". **More than 1.7 million people** have taken the test and **about 90% are told they are "out of balance"**. GPs and nutrition experts warn against it. — [Nettavisen](https://www.nettavisen.no/nyheter/tjener-milliarder-pa-den-omstridte-helsetesten-zinzino-skaper-frykt-som-ikke-er-reell/s/5-95-2968720)
- DN (Dagens Næringsliv), 2026 series:
  - "Mattilsynet slår ned på Zinzinos markedsføring: 'Alvorlig og klart brudd'". — [DN](https://www.dn.no/helse/zinzino/dn-investor/mattilsynet-slar-ned-pa-zinzinos-markedsforing-alvorlig-og-klart-brudd/2-1-1964123)
  - "Selger blodtester og helsekost for «ubalanserte» barn: – Det er jo helt sprøtt". Rikshospitalet paediatrician **Carina Saunders** called the marketing "deeply problematic". — [DN](https://www.dn.no/helse/markedsforing/zinzino/mattilsynet/selger-blodtester-og-helsekost-for-ubalanserte-barn-det-er-jo-helt-sprott/2-1-1975196)
  - "Helseministeren om Zinzinos blodtester for barn: – Uakseptabelt". Health minister **Jan Christian Vestre**: it is unacceptable to exploit parents' worry for their children. — [DN](https://www.dn.no/helse/markedsforing/jan-christian-vestre/zinzino/helseministeren-om-zinzinos-blodtester-for-barn-uakseptabelt/2-1-1976360)
  - "Mattilsynet fatter tre vedtak mot Zinzino". — [DN](https://www.dn.no/helse/zinzino/helse/mattilsynet/mattilsynet-fatter-tre-vedtak-mot-zinzino-alvorlig-og-klart-brudd/2-1-1997722)
- Sweden: EFN and Realtid reported in August 2025 that Konsumentverket (KO) criticised Zinzino for "serious violations" and "aggressive" marketing with "unpermitted claims". — [EFN: KO kritiserar kursrusaren](https://efn.se/ko-kritiserar-kursrusaren-allvarliga-overtradelser); [EFN: Myndighetens larm om Zinzino](https://efn.se/myndighetens-larm-om-zinzino-otillatna-pastaenden); [Realtid](https://www.realtid.se/marknader/larm-om-kursraket-och-smaspararfavorit-otillatna-pastaenden/)

**Regulatory actions [INDEPENDENT]**
- **Mattilsynet (Norway):** inspection in March 2026, which found breaches of the health-claims rules and misleading marketing. Three decisions were notified (around April 2026) and then adopted (Finansavisen, **2 June 2026**). Zinzino must **change all marketing that is misleading or may create fear** on websites and social media, with a focus on BalanceOil. A second decision concerns non-specific health claims. **Zinzino disagrees** and had a three-week appeal window. Sources conflict on the exact dates (April notice versus June decisions). — [Finansavisen 02.06.2026](https://www.finansavisen.no/handel/2026/06/02/8355621/mattilsynet-fatter-vedtak-mot-zinzino-alvorlig-og-klart-brudd); [DN](https://www.dn.no/helse/zinzino/helse/mattilsynet/mattilsynet-fatter-tre-vedtak-mot-zinzino-alvorlig-og-klart-brudd/2-1-1997722); [no.wikipedia](https://no.wikipedia.org/wiki/Zinzino)
- **Konsumentverket (Sweden):** **injunction ("föreläggande") against Zinzino AB on 20 March 2026** over improper health claims (e.g. a saffron product as a substitute for antidepressants; claims about BalanceOil in pregnancy), with a **SEK 1.5 million** conditional fine. Zinzino is held primarily responsible for its partners' marketing. One report mentions an earlier SEK 150,000 fine in August 2023 (unverified). — [Konsumentverket: Föreläggande mot Zinzino AB](https://www.konsumentverket.se/forelaggande/forelaggande-mot-zinzino-ab/); [BehindMLM](https://behindmlm.com/companies/sweden-norway-target-zinzino-illegal-medical-claims/)
- **Germany:** after a complaint to the Verbraucherzentrale portal Lebensmittelklarheit, a Zinzino partner's Instagram post promising concentration benefits for children from BalanceOil (not permitted under the EU Health Claims Regulation) was deleted. This concerns advertising, not the test itself. — [Lebensmittelklarheit.de](https://www.lebensmittelklarheit.de/produktmeldungen/beitrag-mit-massiven-gesundheitsversprechen-fuer-balanceoil-geloescht)

**Test-design and MLM critique [INDEPENDENT/THIRD-PARTY]**
- The main structural criticism is the conflict of interest: the same company sells the test and the product and profits from subscription renewals. Interpretation is done by the vendor itself, with no medical follow-up. — [verbraucherschutz.tv](https://verbraucherschutz.tv/zinzino-unserioes/); [williprokop.com](https://www.williprokop.com/zinzino-kritik-an-test-und-produkte-balance-oil-omega-3/)
- Claims that DBS accuracy is lower than venous analysis and that interpretation is simplified. — [maxfit.ee review](https://maxfit.ee/en/blog/omega-zinzino)

**Implausible or inconsistent results [ANECDOTAL]**
- A German blog reports that the BalanceTest is criticised because **identical results allegedly appeared for different people**. This is unverified, with no documentation found. — [williprokop.com](https://www.williprokop.com/zinzino-kritik-an-test-und-produkte-balance-oil-omega-3/); [bmtime.de](https://bmtime.de/zinzino-warnung-wie-serios-ist-das-unternehmen-wirklich/)

### Inferences
- The "before/after 120 days" design inside an MLM has a built-in incentive problem. The vendor sets non-standard targets (whole blood with an 8% target, a 3:1 ratio) that most people miss at baseline, sells the remedy, then retests in a lab tied to the vendor. Without published analytical CVs, users cannot tell whether a change exceeds measurement noise plus biological and dietary day-to-day variation (made larger by the plasma share of whole blood).
- The regulatory actions in 2026 concern **product marketing and health claims** (including fear-based messaging built on test results, and child-targeted testing), **not the analytical accuracy** of the Vitas assay. No regulator was found to have assessed the lab method itself.

### Gaps
- No NRK, VG, Aftenposten, SVT, DR or Stiftung Warentest/Öko-Test investigation of the BalanceTest itself, such as split-sample or blinded duplicate testing, was found. Danish media were not covered.
- The full texts of the DN, Nettavisen and Finansavisen articles are paywalled or were not fetched. Dates are approximate (DN articles around April–June 2026; Nettavisen around April 2026).
- Whether Zinzino appealed the Mattilsynet decisions, and the outcome: unknown.

---

## 9. Price and test flow (baseline test plus retest after 120 days)

### Takeaway
The concept is **baseline BalanceTest, then 120 days of BalanceOil, then a follow-up BalanceTest**. The 120 days are justified by the roughly 120-day lifespan of red blood cells, even though whole blood is measured. Results are anonymous via a test ID and are viewed online. German prices vary by channel: about **€189 retail and €133 at "Premier" (subscription) price**, according to one comparison site, with resale listings at about €40–100 (eBay about €60). Tests are often bundled with BalanceOil subscription kits.

### Cited Findings
- **[THIRD-PARTY]** The test reflects dietary habits over the past 120 days. The follow-up after 120 days is part of the concept. The published improvements come from company data. — [omega3-test.net Zinzino review (possible competitor site)](https://www.omega3-test.net/vergleich/zinzino-erfahrungen-test.html)
- **[THIRD-PARTY] Prices (Germany):** €189 single purchase, €133 Premier price (omega3-test.net); about €40–100 depending on channel (other blogs); one eBay offer at €60. — [omega3-test.net](https://www.omega3-test.net/vergleich/zinzino-erfahrungen-test.html); [eBay.de listing](https://www.ebay.de/itm/226071888597); [lifevital.net](https://www.lifevital.net/magazin/zinzino-erfahrungen-bewertungen/)
- **[MANUFACTURER]** The test is "confidential, anonymous", and samples are analysed anonymously by Vitas. — [Zinzino NO: BalanceTest](https://www.zinzino.com/site/no/nb-no/explore/our-balancetest/); [Zinzino: Are test results reliable?](https://www.zinzino.com/site/us/en-us/info/are-zinzino-test-results-reliable)
- **[MANUFACTURER, affiliate]** Collecting the sample takes a few minutes at home. — [looduspere.ee (reseller)](https://www.looduspere.ee/en/product/zinzino-balancetest-pohjalik-rasvhapete-analuus/)

### Inferences
- Because the matrix is whole blood (partly plasma, with a faster turnover than red cells), the 120-day rationale is only partly apt for whole blood. Part of any change will appear sooner. Conversely, recent intake on the day of sampling can bias the retest.

### Gaps
- The official 2026 Zinzino.de price for the stand-alone BalanceTest and the bundle prices could not be verified, because zinzino.com was not fetchable. Turnaround time (typically quoted as about 2–4 weeks) was not confirmed by any accessible source.

---

*Hosts that need to be allowed in the session's network settings to verify the open points: www.zinzino.com, zinzinowebstorage.blob.core.windows.net, www.vitas.no, link.springer.com, lipidworld.biomedcentral.com, www.akkreditert.no, www.forskningsparken.no, detoxhouse.com.au, pubmed.ncbi.nlm.nih.gov, www.dn.no.*
