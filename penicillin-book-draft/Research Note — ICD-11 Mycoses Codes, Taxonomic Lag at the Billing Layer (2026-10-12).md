# Research Note — ICD-11 Mycoses Codes, Taxonomic Lag at the Billing Layer

**Filed:** 2026-10-12 · For local peer review alongside *The Mycelial Transposition* manuscript
**Source:** "The Past and Future of Fungal Diagnoses in Health Records: A Comparative Analysis and Harmonization of Mycoses ICD Codes" — *Journal of Fungi* 2026, 12(10), 752, published 8 October 2026 (UMKC / Children's Mercy Research Institute / UC Berkeley). Mapping study: 94 mycoses codes in ICD-9, 117 in ICD-10, 148 in ICD-11, cross-version bidirectional best-match mapping with manual verification.
**Link:**
- https://www.mdpi.com/2309-608X/12/10/752

## The study (in brief)

- The authors built a manually curated cross-version mapping of every mycoses ICD code across ICD-9, ICD-10, and ICD-11 (plus US clinical modifications), to support ICD-11 adoption in the US and accurate cohort identification in fungal research. They found codes were inconsistently consolidated within the mycoses section in all versions, with eponymous and outside-section codes requiring manual expert identification.
- **Taxonomy rewrote the billing vocabulary.** Molecular reclassification moved disease labels across code revisions: ICD-10 B48.4 "Penicilliosis" became ICD-11 1F2K "Talaromycosis" (Penicillium marneffei → Talaromyces marneffei); ICD-9 117.6 / ICD-10 B48.2 "Allescheriasis" became ICD-11 1F2H "Scedosporiosis"; "Candidiasis" (ICD-9/10) becomes "Candidosis" in ICD-11. The paper notes taxonomic reclassification also affects species-level extension codes for high-priority reportable pathogens such as Candidozyma auris (formerly Candida auris).
- **Names break longitudinal research.** Cross-version mapping revealed "distinct patterns of code continuity, expansion, and consolidation" — a polite way of saying a renamed organism is hard to follow through the record. Separate evidence the authors cite: in a US candidemia surveillance study, ~56% of blood-culture-confirmed candidemia cases (2019–2020) had no candidiasis-related ICD code in the EMR at all — under-coding that compounds any rename-driven discontinuity.
- The authors' own conclusion emphasizes "the importance of nomenclature consistency in science and medicine as molecular studies reclassify fungal pathogens."

## The nomenclature hook

- **A fourth layer of the adoption spectrum.** The manuscript already has the lab layer (the Oct 10 "Lab Reports the Name It Chooses" note) and the press layer (today's wastewater note). This adds the institutional/billing layer: ICD-11 *did* adopt the renames — Talaromycosis, Scedosporiosis, Candidosis — while the US still bills on ICD-10-CM. The adoption spectrum now spans lab, press, billing code, and national adoption, each moving at its own speed. That is a ch-6 specimen with chapter-mapping already half done: current name, legacy synonym, calibration setting (billing/reimbursement), action the label triggers (claim adjudication, cohort inclusion in research).
- **The "Candidiasis" → "Candidosis" shift is the thesis in miniature.** A single-vowel disease-name change that breaks every historical query for candidiasis cohorts in longitudinal studies — the lagging-record mechanism (names as lagging records, mechanism 2) operating through the record-keeping apparatus itself, not through any clinician's choice.
- **Connects to the anti-overreach guardrail.** The ~56% under-coding figure is the honest bound: a huge fraction of disease burden is invisible to code-based surveillance regardless of which name is used. Name adoption matters for those who code — and half the cases aren't coded at all. That is the crude-vs-adjusted honesty applied to surveillance data.
- **A sparring counter to carry into the peer-review questions.** A July 2026 CAP Today piece on evolving microbial nomenclature in the clinical lab argues the counter-thesis outright: name changes "driven primarily by phylogenetic data may offer limited clinical value while disrupting established diagnostic and treatment workflows," citing the Candida → Pichia/Debaryomyces/Torulopsis/Kluyveromyces split as the example. If the thesis claims names do work, this is the place where they plausibly do none. Worth a paragraph in the appendix B measurable-questions treatment: under what conditions does a rename *fail* to change practice? (https://www.captodayonline.com/what-the-evolving-microbial-nomenclature-means-for-the-clinical-microbiology-lab/)

## Honest caveats (do not drop these)

1. **Mapping study, not outcome study.** It shows codes moved and are hard to map across versions; it does not show that any rename improved or harmed care. Do not claim clinical benefit from adoption at the ICD layer.
2. **Best-match mapping is heuristic.** Cross-version pairs were scored by a heuristically weighted match-score algorithm with a minimum threshold, plus skip-link mapping — the mapping resource is the authors' construction, manually verified, but it is not an equivalence proof between codes.
3. **Extension codes excluded.** The paper explicitly excluded ICD-10/11 extension codes from analysis, so the Candidozyma auris species-level extension-code claim is the authors' contextual note, not a mapped result.
4. **The 56% under-coding figure is cited, not measured here** — it comes from a 2019–2020 US candidemia surveillance study the authors reference. Keep the attribution.
5. **Manuscript material only.** Filed for the nomenclature chapters — no bearing on personal treatment decisions; keep the manuscript frame strictly separate from med talk.
