# All Vaccines — Strep, Staph, Pneumonia, TB × Virology × Connected Biomes (2026-10-18)

*Built at Douglas's direction for The Mycelial Transposition. Manuscript reference, never medical advice. No treatment recommendations. No interpretation of any personal result.*

**Tier tags:** [D] = documented in the literature · [H] = his, filed as his · [H→D] = his with a documented foothold · [LOGIC] = inference with the steps shown · [GAP] = unknown.

---

## PART ONE — THE VACCINE INVENTORY

### 1. Streptococcus pneumoniae — the licensed five

Compositions verified against manufacturer and AAP listings in his 23-row comparison file (2026-10-17) — reused here, not re-derived [D]:

| Vaccine | Year | Type | Serotypes covered |
|---|---|---|---|
| PPSV23 (Pneumovax 23) | 1983 | Plain polysaccharide | 1, 2, 3, 4, 5, 6B, 7F, 8, 9N, 9V, 10A, 11A, 12F, 14, 15B, 17F, 18C, 19A, 19F, 20, 22F, 23F, 33F |
| PCV13 (Prevnar 13) | 2010 | Conjugate | 1, 3, 4, 5, 6A, 6B, 7F, 9V, 14, 18C, 19A, 19F, 23F |
| PCV15 (Vaxneuvance) | 2021 | Conjugate | PCV13 + 22F, 33F |
| PCV20 (Prevnar 20) | 2021/2023 | Conjugate | PCV13 + 8, 10A, 11A, 12F, 15B, 22F, 33F |
| PCV21 (Capvaxive) | 2024 | Conjugate | 3, 6A, 7F, 8, 9N, 10A, 11A, 12F, 15A, 15B, 15C, 16F, 17F, 19A, 20A, 22F, 23A, 23B, 24F, 31, 33F, 35B |

Notes [D]: PCV10 (Synflorix, GSK) is licensed outside the US (1, 4, 5, 6B, 7F, 9V, 14, 18C, 19F, 23F). PCV21 carries 20A, not 20 — cross-protection against serotype 20 not established [GAP]. Conjugate vaccines (PCVs) generate T-cell-dependent memory and work in infants; plain polysaccharide (PPSV23) does not [D].

### 2. Streptococcus pneumoniae — investigational (serotype-independent)

The licensed vaccines chase serotypes; the pipeline tries to escape the chase [D]:

- **PATH whole-cell vaccine (SPWCV / wSp):** inactivated whole-cell, alum-adjuvanted. Phase 1 complete in healthy adults — safe, well tolerated; elicited IgG to PspA and pneumolysin plus IL-17 T-cell responses [D — ijidonline.com]. Designed for serotype-independent coverage at low manufacturing cost [D].
- **Protein candidates:** pneumolysin toxoid (PlyD1), PhtD (histidine triad protein D), PcpA, PspA — tested Phase 1/2 by Sanofi and GSK, alone and co-administered with PCV10/PCV13 [D — PMC8620834]. A Phase 2b trial of pneumolysin toxoid + PhtD with PCV13 in Native American infants (NCT01545375) was immunogenic but showed no incremental efficacy against otitis media or lower respiratory infection [D — infectiousdiseaseadvisor.com].
- **Live vector:** recombinant attenuated *Salmonella* Typhi expressing PspA, oral single dose, Phase 1 (NCT01033409) [D — clinicaltrials.gov].
- **TH17 approach:** Malley/Genocea identified pneumococcal proteins stimulating TH17 cells → near-complete protection from upper-respiratory colonization in mice; human TH17 cells from volunteers responded [D — sciencedaily.com 2011]. Rationale: natural immunity clears bacteria from the upper tract via TH17/IL-17A, not antibodies [D].
- [LOGIC — steps: protein antigens are shared across all serotypes → serotype replacement cannot evade them → the "vaccines always one emergency behind" pattern from the reverse-engineering file breaks only if the target stops moving. The pipeline's bet is that the fixed point is the protein, not the capsule.]

### 3. Staphylococcus aureus — no licensed vaccine. The absence is data.

Three major failures, each instructive [D]:

- **StaphVAX (Nabi):** CP5/CP8 capsular polysaccharides conjugated to *P. aeruginosa* exoprotein A. Phase 3 in hemodialysis patients: ~57% efficacy at 40 weeks, collapsing to ~26% by 54 weeks. A second unpublished trial also failed [D — NEJM 2002; clinicalmicrobiologyandinfection.org].
- **V710 (Merck):** IsdB (iron surface determinant B) protein, unadjuvanted. Phase IIb/III in ~8,000 cardiothoracic surgery patients — halted by the data monitoring committee: no efficacy, and **higher multiorgan-failure deaths in vaccine recipients** (31 vs 17); among those who developed *S. aureus* infection, mortality was 5× higher in vaccinees (23.0 vs 4.2 per 100 person-years) [D — JAMA 2013; NEJM clinician summary]. Mechanism proposed: low pre-vaccination IL-2/IL-17, and anti-IsdB antibodies captured in reverse orientation by staphylococcal protein A (SpA) [D — PMC8294057].
- **SA4Ag (Pfizer, PF-06290510):** 4-antigen (CP5, CP8, ClfA, MntC). Phase 2b STRIVE trial in spinal-fusion surgery — discontinued Dec 2018 for **futility**; safe but no efficacy signal [D — Pfizer press release; Hassanzadeh et al., Clin Infect Dis 2023].
- **GSK3878858A:** 4-component candidate — "not progressing following futility analysis" per GSK's end-2024 pipeline update [D — amr.solutions].

Why it keeps failing [D]: murine protection doesn't translate to humans; *S. aureus* is normal flora with deep immune-evasion machinery; the field's own review concludes prevention-of-infection may be the wrong endpoint for a colonist — reduced severity may be the achievable goal [D — clinicalmicrobiologyandinfection.org].

[LOGIC — steps: the organism that most needs a vaccine (his "always a bacterial element") is the one with zero licensed vaccines and three instructive failures → the gap between need and tool is itself a finding for the book. His [H] thesis that staph resists the vaccine paradigm has this documented floor [H→D].]

### 4. Pneumonia-as-disease — vaccines that prevent pneumonia by preventing its causes

| Vaccine | Prevents | Pneumonia link [D] |
|---|---|---|
| Hib (conjugate) | *Haemophilus influenzae* type B | Hib was a leading cause of childhood bacterial pneumonia/meningitis before vaccination; conjugate vaccine sharply reduced invasive Hib disease [D] |
| Influenza (seasonal) | Influenza virus | Prevents the viral opener of lethal flu–pneumo synergy (Part Two) [D] |
| COVID-19 (mRNA/protein) | SARS-CoV-2 | Prevents viral pneumonia directly; severe COVID pneumonia drove 2020–21 mortality [D] |
| RSV: Abrysvo (Pfizer), Arexvy (GSK), mRESVIA (Moderna) | Respiratory syncytial virus | Licensed for older adults (60+; Arexvy also 50–74 at risk); Abrysvo also maternal — prevents RSV lower-respiratory disease, a pneumonia precursor [D] |
| Pertussis (DTaP/Tdap) | *Bordetella pertussis* | Prevents whooping cough; secondary bacterial pneumonia is a classic pertussis complication [D] |

Note: none of these is a "pneumonia vaccine" — pneumonia is the *showing*, and each vaccine acts upstream on a cause. That distinction is the book's five-tracks discipline (vaccine ≠ disease ≠ illness) in one table [H→D framing; the table is mine].

### 5. Tuberculosis — one licensed vaccine, a real pipeline

Built on his "TB Vaccines — BCG Strains, Serology, Mechanism (2026-10-17).md" — key points carried [D]:

- **BCG:** the only licensed TB vaccine (since 1921) — live attenuated *M. bovis*, five major substrains (Danish 1331, Tokyo 172-1, Pasteur 1173P2, Russian BCG-I, Moreau RDJ). Protection is T-cell/macrophage-mediated (IFN-γ), not antibody-mediated; strong against severe childhood TB, 0–80% variable against adult pulmonary TB [D].
- **M72/AS01E:** adjuvanted subunit (Gates Medical Research Institute + GSK). Phase 2b: ~50% efficacy against TB disease in infected adults — first vaccine to reach that level. Phase 3 (20,000 volunteers, South Africa/Kenya/Malawi/Zambia/Indonesia) completed enrollment; results expected **2028** [D — spotlightnsp.co.za, Mar 2026].
- **MTBVAC:** live attenuated *M. tuberculosis* (Biofabri/University of Zaragoza) — Phase 2b adults/adolescents, Phase 3 newborns [D].
- **VPM1002:** recombinant BCG — early trials showed similar immunogenicity to BCG with fewer injection-site events, but weaker on the hard endpoint (microbiologically confirmed disease) [D — medicalbrief.co.za].
- [GAP]: no licensed TB vaccine for adults as of Oct 2026; 2028 is the next decision point.

---

## PART TWO — THE VIROLOGY LAYER

### The lethal synergy: influenza × Streptococcus pneumoniae [D]

- **1918:** banked lung samples from the Spanish influenza pandemic (40–50 million dead) showed the vast majority had *S. pneumoniae* co-infection or secondary infection; one review puts ~95% of 1918 deaths down to flu–pneumo superinfection [D — sciencedaily.com; Frontiers in Immunology 2025].
- **Mechanism 1 — the dead-cell anchor:** PspA (pneumococcal surface protein A) was found to act as an adhesin specifically to *dead or dying* lung epithelial cells — missed for 30 years because researchers used healthy cell monolayers. Flu kills the cells; pneumo anchors to the corpses [D — Cell Reports, Orihuela & Briles, Univ. of Alabama Birmingham].
- **Mechanism 2 — immune sabotage:** influenza-induced type I interferon suppresses γδ-T-cell IL-17 production and neutrophil attractants (CXCL1/CXCL2), crippling early bacterial clearance; mice lacking type I IFN signaling survive better [D — J Clin Invest 2009; Infect Immun 2006].
- **Mechanism 3 — shared enzymes:** pneumococcal neuraminidases NanA/NanB support influenza replication; dual-acting neuraminidase inhibitors disrupt the synergy [D — PMC4800182].
- **The mouse datum from his files:** flu-infected co-colonized mice develop almost exclusively pneumococcal pneumonia — pneumococcus disperses while staph dispersal is inhibited [D — mBio 2017, per reverse-engineering file].

### The general pattern [D]

- Post-viral bacterial pneumonia is the rule, not the exception: RSV and influenza both precede bacterial pneumonia; the major secondary invaders are *S. pneumoniae*, *S. aureus*, group B strep, and *H. influenzae* [D — Frontiers in Immunology 2025].
- His virus-marker thesis [H]: "viruses are indicators/markers of infection that grow when sick and shrink when better." Filed as his; the documented foothold is the synergy literature above — virus first, bacteria second, in that order, repeatedly [H→D].
- His California-serogroup/Jamestown Canyon work [H]: filed as his; touches this layer only as his thesis that viruses mark the bacterial/fungal showing — no documented Jamestown Canyon–pneumococcus link is claimed here [GAP — honestly marked].

---

## PART THREE — THE CONNECTED BIOMES

### The nasopharynx — the shared apartment [D]

The nasopharynx is colonized in healthy people by *S. pneumoniae*, *H. influenzae*, and *Moraxella catarrhalis*; the nasal cavity holds *Staphylococcus* spp. including *S. aureus* [D — microbiology references]. The documented interaction map (PMC4801059):

| Pair | Interaction | Mechanism [D] |
|---|---|---|
| Pneumo × *S. aureus* | **Antagonism** | Pneumococcal hydrogen peroxide; immune-mediated competition |
| Pneumo × *H. influenzae* | Synergism AND antagonism | Nutrient provision, biofilms, β-lactamase (synergy); H₂O₂, desialylation (antagonism) |
| Pneumo × *M. catarrhalis* | Both | Passive antibiotic protection (synergy); H₂O₂ (antagonism) |

- In children: pneumo, Hib, and *M. catarrhalis* positively associate with each other — and each is **negatively** associated with *S. aureus* [D — PMC3474735]. PCV7 vaccination reduced pneumococcal colonization [D — same study].
- [LOGIC — steps: pneumo and staph antagonize each other in the nasopharynx via H₂O₂ → the same H₂O₂ drives 19F capsule mutation (reverse-engineering file: "one molecule, two wars") → the weapon against the competitor is also the engine of the serotype's evolution. His [H] "bacterial element" framing has a documented mechanism wearing it.]

### The lung — the low-density frontier [D]

- The lower airway was thought sterile; 16S sequencing revealed a low-density lung microbiome dominated by *Prevotella*, *Veillonella*, *Streptococcus* [D].
- The upper airway seeds the lower airway continuously; pneumonia associates with nasal dysbiosis and single-species overgrowth [D — PMC9748710].
- Typical pneumonia pathogens (*S. pneumoniae*, *S. aureus*, *K. pneumoniae*, *H. influenzae*) are often *residents* of the lower-airway ecosystem — disease is overgrowth/dysbiosis, not invasion from outside [D — same].

### The gut–lung axis [D]

- Gut and lung mucosa function as a single aerodigestive immune system; gut disruption changes airway immune tone [D — PMC6221463].
- Mechanism: bacterial short-chain fatty acids (e.g., butyrate) suppress IFN-γ and IL-17 T-cell function — the same IL-17 axis that clears pneumococcus from the upper tract (Part One, §2) [D — same review].
- [LOGIC — steps: gut SCFAs suppress IL-17 → IL-17 is the documented clearance mechanism for pneumococcal colonization → gut dysbiosis can disarm the lung's anti-pneumo defense without the lung ever being touched. The axis is documented; the clinical weight is [GAP].]

### Skin and nares — staph's home [D]

- *S. aureus* persistently colonizes the anterior nares in ~20–30% of people, intermittently in more; skin is the other reservoir [D — standard microbiology].
- Decolonization (mupirocin/chlorhexidine) reduces surgical-site infection — the clinical lever that exists *because* no vaccine does [D].

### His colonist framing [H]

His "embedded immune system" / body-made-of-colonists thesis: filed as his. The documented foothold: every biome above shows the "pathogens" as residents first, disease as a change in the resident community's behavior — colonization is the default state, illness the exception [H→D]. The book's claim beyond that (colonists as immune system proper) remains his to evidence.

---

## PART FOUR — SYNTHESIS: WHAT THE FULL INVENTORY SHOWS

1. **The scoreboard:** pneumo — 5 licensed + active pipeline. Pneumonia's causes — 5 licensed. TB — 1 licensed (1921) + pipeline to 2028. Staph aureus — **0 licensed, 3 major failures, 1 discontinued for futility.** The organism with no vaccine is the one his thesis keeps circling [LOGIC — the inventory's shape is the finding].
2. **The failure pattern:** every staph vaccine that reached late trials either faded (StaphVAX), harmed (V710), or showed nothing (SA4Ag). The field's own conclusion: vaccinating against a *colonist* may need a different endpoint than vaccinating against an *invader* [D]. That sentence belongs in the book nearly verbatim.
3. **The virus always opens:** flu → pneumo (1918, PspA dead-cell anchor, IFN sabotage); RSV/flu → bacterial pneumonia generally. No licensed vaccine in this inventory acts on the *pairing* — each acts on one partner [D].
4. **The apartment is shared:** nasopharynx residents interact — antagonism (pneumo vs staph, H₂O₂) and synergism (pneumo + Hib, biofilms) — before any disease exists. Vaccines that remove one resident (PCV7) measurably change the others (staph colonization doubled) [D — mBio 2017, per reverse-engineering file]. The biome is the unit the vaccines disturb.
5. **Serotypes are chemistry; vaccines are history:** the four PCV generations read as a fossil record of emergencies (reverse-engineering file); the pipeline's escape attempt is to target proteins instead of capsules. TB's story rhymes: one century-old whole-organism vaccine, protection in T cells not antibodies, pipeline aimed at 2028 [D].

**Builder's extra (mine, labeled):** the inventory suggests the book's ch 6 rule in a new form — *count the vaccines per organism and you can read the organism's relationship to medicine*: many vaccines = the invader paradigm works; zero vaccines = the colonist paradigm is missing. Staph aureus is the proof that the paradigm, not the effort, is the gap.

---

## Sources (findable again)

- Vaccine compositions: his 23-row comparison file (2026-10-17), verified vs manufacturer/AAP listings.
- TB: his "TB Vaccines — BCG Strains, Serology, Mechanism (2026-10-17).md"; M72/AS01E: spotlightnsp.co.za (Mar 2026); AdisInsight trial profile (updated Jul 2026); ERS monograph chapter 12.
- Staph failures: NEJM 2002 (StaphVAX); JAMA 2013;309:1368-1378 (V710); clinicalmicrobiologyandinfection.org review; PMC8294057 (V710 mechanisms); Pfizer Dec 2018 press release + Hassanzadeh et al., CID 2023 (STRIVE); amr.solutions (GSK3878858A).
- Pneumo pipeline: ijidonline.com (PATH SPWCV); PMC8620834 (protein candidates table); clinicaltrials.gov NCT01545375 (Phase 2b protein + PCV13); NCT01033409 (Salmonella-PspA); sciencedaily.com 2011 (TH17/Malley).
- Virology: sciencedaily.com 2021 (PspA dead-cell adhesion, Cell Reports); frontiersin.org 10.3389/fimmu.2025.1654821 (synergy editorial); J Clin Invest 2009;119:1910-1920 (type I IFN); PMC4800182 (NanA/NanB); mBio 2017 (co-colonized mice, via reverse-engineering file).
- Biomes: PMC4801059 (nasopharynx interaction table); PMC3474735 (child co-colonization); PMC6221463 (lung microbiome + gut–lung axis); PMC9748710 (airway/lung microbiome review).
