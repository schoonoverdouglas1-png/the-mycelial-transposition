# Reverse-Engineered — Every Serotype × Vaccine × Disease × Biofilm Connection (2026-10-18)

*Built at Douglas's commission for The Mycelial Transposition. Manuscript reference — never medical advice. No treatment recommendations. No interpretation of any personal result: his panel values appear below as quoted numbers only, nothing more; what they mean is Kelsey Meyer's call.*

## Tier tags — read first

- **[D]** documented in the literature (source class named; full citations live in the 23-row comparison file and the co-pathogen cross-link map — this file reuses, not re-derives)
- **[H]** his — Douglas's thesis, filed as his, his to evidence
- **[LOGIC]** AI-derived inference — his commission explicitly asked for vague-but-logical connections; every [LOGIC] carries its explicit logic chain in the same entry, step by step, so the derivation is visible. Never presented as documented.
- **[GAP]** unknown — honestly marked, his to fill

## The method: reverse-engineering outward from the serotype

Forward direction: vaccine → serotype list → disease. Reverse direction, this file: **serotype → what the record attaches to it** (vaccines that name it, disease names it carries, biofilms it builds, resistance it wears, staph it meets) → then the triangle (strep–staph–pneumonia) reassembled from the pieces. The serotype is the fixed point; everything else moves around it.

## Vaccine compositions [D] — stated once, referenced per row

- **PPSV23** (1983): 1, 2, 3, 4, 5, 6B, 7F, 8, 9N, 9V, 10A, 11A, 12F, 14, 15B, 17F, 18C, 19A, 19F, 20, 22F, 23F, 33F
- **PCV15** (2021): 1, 3, 4, 5, 6A, 6B, 7F, 9V, 14, 18C, 19A, 19F, 22F, 23F, 33F
- **PCV20** (2021/2023): 1, 3, 4, 5, 6A, 6B, 7F, 8, 9V, 10A, 11A, 12F, 14, 15B, 18C, 19A, 19F, 22F, 23F, 33F
- **PCV21** (2024): 3, 6A, 7F, 8, 9N, 10A, 11A, 12F, 15A, 15B, 15C, 16F, 17F, 19A, 20A, 22F, 23A, 23B, 24F, 31, 33F, 35B

## New documented anchors (tonight's research)

- **Biofilm architecture groups** [D — Allegrucci et al. 2006, J Bacteriol, PMC1428403]: serotypes build measurably different biofilms. Group I (strongest): type 3 (biomass 121.57), type 23; Group II: types 18, 6, 9, 11, 14; Group III (thinnest): type 19. Serotype 3 is the strongest biofilm former measured; the 19-family the weakest-structured.
- **CST vs IST** [D — Weinberger, PMC3425340]: colonizing serotypes vs invasive serotypes are distinct biological strategies, defined by capsule. Prediction on record: serotype replacement after vaccination favors **larger, metabolically cheaper capsules**.
- **Dispersion modulation** [D — mBio 2017, PMC5760742]: in dual *S. pneumoniae*–*S. aureus* biofilms under viral-like conditions, the pneumococcus disperses and staph dispersal is **inhibited**; flu-infected co-colonized mice developed almost exclusively **pneumococcal** pneumonia. Post-PCV, cocolonization rates **increased**.
- **Biofilm as mutation engine** [D — PMC2566003]: serotype 19F biofilms generate capsule variants (cps19F SNPs); mutation frequency **55-fold higher** in biofilms; H2O2 (SpxB) drives it — the same H2O2 that kills *S. aureus*.

---

## The 23 serotypes, reverse-engineered

### Serotype 1 — his value quoted: 0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21.
- **Disease names [D]:** epidemic meningitis (African meningitis belt), empyema; outbreak lists.
- **Biofilm [D]:** capsule thickens under stress (CRH study, with 3/19A/23F); architecture group unmeasured [GAP].
- **Resistance [D]:** generally susceptible; not an MDR serotype.
- **Strep↔staph↔pneumonia [D]:** species-level library applies; no serotype-specific staph data.
- **[LOGIC] — the lone-wolf strategy.** Chain: (a) highly invasive yet rarely carried [D] → it does not live in the biofilm/carriage niche; (b) generally susceptible [D] → it carries no resistance armor; (c) PCV21 (adult-focused, 2024) dropped it while keeping 3, 7F, 19A, 22F, 33F [D] → the newest vaccine judged it the lesser adult threat. Therefore: serotype 1 survives by epidemic spread, not persistence — no carriage, no biofilm, no resistance. Three survival strategies exist in this file (persist, armor, erupt); serotype 1 is the eruption one.

### Serotype 2 — his value quoted: 0.3 mcg/mL
- **Vaccines [D]:** PPSV23 only. The conjugates never picked it up.
- **Disease names [D]:** historical; outbreak lists. Rare in modern disease.
- **Biofilm:** thin [GAP].
- **Resistance [D]:** not an MDR serotype.
- **Strep↔staph↔pneumonia [D]:** D39 (serotype 2) is the lab workhorse; the Smith within-host influenza–pneumo kinetics model ran on D39 [D-serotype].
- **[LOGIC] — the museum-piece problem.** Chain: (a) D39 is serotype 2 [D]; (b) the foundational flu–pneumo coinfection model was built on D39 [D]; (c) serotype 2 is nearly extinct in modern disease [D]. Therefore: the mechanistic map of viral–pneumococcal pneumonia was drawn from a serotype patients almost never meet. Every serotype-specific claim about "how the virus opens the door" inherits this bias — the door was studied on a door nobody uses anymore.

### Serotype 3 — his value quoted: <0.1 mcg/mL
- **Vaccines [D]:** all four — PPSV23, PCV15, PCV20, PCV21.
- **Disease names [D]:** adult pneumonia (most prevalent strain, 18-country review), invasive disease, empyema, meningitis, otitis media; the vaccine-failure serotype (26.9–40% of PCV13 failures).
- **Biofilm [D]:** Group I — the strongest biofilm architecture measured (biomass 121.57, thickest) [D]; biofilm-five with *S. aureus* (Sempere 2024) [D]; capsule shed from the surface inhibits antibody-mediated killing [D]; 428% capsule vs. reference in mucoid isolates [D].
- **Resistance [D]:** PSSP 100% — fully penicillin-susceptible. Breakthrough is capsule biology, not resistance.
- **Strep↔staph↔pneumonia [D]:** biofilm-five; PCV13 serum reduces its biofilm but not the staph's [D]; A66.1 + influenza → vaccine protection collapses to 30–40% survival [D-serotype].
- **[LOGIC] — three defeats at once.** Chain: (a) named in all four vaccines yet persists at pre-vaccine incidence [D]; (b) sheds its capsule so antibodies cannot grip [D]; (c) builds the strongest biofilms measured [D]. Therefore: serotype 3 defeats vaccination three independent ways — shed the target, out-build the shelter, out-last the pressure. The vaccine names it four times; it answers each time differently.
- **[LOGIC] — the capsule IS the resistance.** Chain: (a) PSSP 100%, zero resistance machinery [D]; (b) yet the most vaccine-evasive serotype in the file [D]. Therefore: serotype 3 proves survival never required the resistance machine — a thick, sheddable capsule plus a strong biofilm is a complete defense without a single resistance gene. His "resistance" thesis must reckon with the serotype that wins unarmed.

### Serotype 4 — his value quoted: 0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21.
- **Disease names [D]:** invasive disease, pneumonia, adult meningitis via bloodstream (48% mortality); PCV7-era.
- **Biofilm:** thin [GAP].
- **Resistance [D]:** generally susceptible.
- **Strep↔staph↔pneumonia [D]:** Sharma-Chawla 2016 head-to-head under influenza — serotype 4: pneumonia 58%→100%, bacteremia 21%→90%, mortality 0%→79% [D-serotype]; ICI-class, overrepresented in post-viral pneumonia (Song) [D-serotype].
- **[LOGIC] — the serotype for which the virus matters most.** Chain: (a) the largest flu-driven mortality amplification measured (0→79%) [D]; (b) highly invasive, rarely carried [D] → the virus is its carriage substitute. Therefore: without influenza, serotype 4 is containable; with it, catastrophic. "Post-viral pneumonia" as a disease name belongs to serotype 4 more than any other in this file — the virus is not a cofactor here, it is the condition of possibility.

### Serotype 5 — his value quoted: <0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21.
- **Disease names [D]:** outbreaks (with 1), meningitis belt; >30% of Gambian invasive disease with serotype 1 [D].
- **Biofilm:** thin [GAP].
- **Resistance [D]:** generally susceptible.
- **Strep↔staph↔pneumonia [D]:** ICI-class, post-viral overrepresentation (Song) [D-serotype].
- **[LOGIC] — the traveling pair.** Chain: (a) serotypes 1 and 5 co-caused >30% of Gambian invasive disease [D]; (b) both highly invasive, rarely carried, both ICI-class [D]. Therefore: 1 and 5 are a traveling pair — same niche (crowded settings: camps, prisons, shelters), same epidemic-not-carriage strategy. They move through populations, not individuals; the disease name is "outbreak."

### Serotype 6B — his value quoted: 0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21.
- **Disease names [D]:** otitis media (top-4 pre-PCV), carriage, pneumonia. The carriage specialist.
- **Biofilm [D]:** Group II architecture (type 6) [D].
- **Resistance [D]:** classic MDR — Spain6B-2; PSSP 8.7% / PISP 78.3% / PRSP 13%.
- **Strep↔staph↔pneumonia [D]:** species-level library; PCV7 clearance doubled staph colonization in children [D].
- **[LOGIC] — the ear is the resistance school.** Chain: (a) carriage specialist = longest residence in the nasopharynx [D]; (b) otitis media = the most antibiotic-treated childhood disease [D]; (c) classic MDR clone [D]. Therefore: carriage duration × antibiotic exposure = resistance. 6B lives longest where the drugs are used most, so it learned the most. Resistance is not randomly distributed across serotypes — it follows the prescription pad.
- **[LOGIC] — the niche-reshuffle debt.** Chain: (a) PCV7 cleared 6B and its siblings [D]; (b) staph nasal colonization doubled in children afterward (10.1% vs 5.0%) [D]. Therefore: removing the carriage specialist did not empty the niche — it handed it to staph. Every vaccine in this file carries a staph debt.

### Serotype 7F — his value quoted: 0.2 mcg/mL
- **Vaccines [D]:** all four — PPSV23, PCV15, PCV20, PCV21.
- **Disease names [D]:** invasive disease, meningitis; named among top vaccine-failure serotypes (with 3, 19A).
- **Biofilm:** thin [GAP].
- **Resistance [D]:** generally susceptible; not an MDR serotype.
- **Strep↔staph↔pneumonia [D]:** ICI-class, post-viral overrepresentation [D-serotype].
- **[LOGIC] — inclusion ≠ control.** Chain: (a) in all four vaccines [D]; (b) among the most common vaccine-failure serotypes [D]. Therefore: the vaccine list and the controlled-disease list are different lists. 7F is the proof — named everywhere, stopped nowhere fully. The file's honest version of his "the vaccine names the serotypes, and the serotypes rename themselves."

### Serotype 8 — his value quoted: 0.7 mcg/mL
- **Vaccines [D]:** PPSV23, PCV20, PCV21. Not in PCV15.
- **Disease names [D]:** emerging adult IPD (10–14.4%), pneumonia in adults; post-PCV replacement surge.
- **Biofilm:** thin [GAP].
- **Resistance [D]:** named in the resistance-associated group; per-drug rates thin [GAP].
- **Strep↔staph↔pneumonia [D]:** ICI-class, post-viral overrepresentation [D-serotype].
- **[LOGIC] — the predicted replacement.** Chain: (a) surged after PCV13 cleared the previous set [D]; (b) Weinberger's documented prediction: replacement favors larger, metabolically cheaper capsules [D]. Therefore: serotype 8 is what the theory said would come — the vaccine cleared the room and capsule economics chose the successor. Replacement is not random; it is predictable from the capsule ledger.

### Serotype 9N — his value quoted: 0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV21. Not in PCV15 or PCV20.
- **Disease names [D]:** adult invasive disease (5.1% of adult IPD post-PCV13).
- **Biofilm:** thin [GAP].
- **Resistance [D]:** clones generally susceptible (CC669N); not a typical MDR serotype.
- **Strep↔staph↔pneumonia [D]:** species-level library applies; no serotype-specific staph data.
- **[LOGIC] — the orphan rescue.** Chain: (a) skipped by PCV15 and PCV20 [D]; (b) picked up by PCV21, the adult-focused 2024 vaccine [D]; (c) 5.1% of adult IPD [D]. Therefore: the adult vaccines went back to the PPSV23 archive for the orphans — 9N's value was always as an adult killer; it took an adult-designed vaccine to recognize it. Same structural pattern as 17F: the rescue pair.

### Serotype 9V — his value quoted: 0.4 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21.
- **Disease names [D]:** otitis media, invasive disease, pneumonia.
- **Biofilm [D]:** Group II architecture (type 9) [D].
- **Resistance [D]:** classic resistant — PSSP 21.4% / PISP 35.7% / PRSP 42.9%; classic MDR.
- **Strep↔staph↔pneumonia [D]:** ICI-class, overrepresented in post-viral pneumonia (9V/9A, Song) [D-serotype].
- **[LOGIC] — the triple-threat template.** Chain: (a) classic resistant [D]; (b) invasive disease documented [D]; (c) Group II biofilm architecture [D]. Therefore: 9V carries resistance, invasiveness, and biofilm competence in one capsule — no trade-off required. The file's proof that a serotype doesn't have to choose between armor, invasion, and shelter.

### Serotype 10A — his value quoted: 1.6 mcg/mL
- **Vaccines [D]:** PPSV23, PCV20, PCV21. Not in PCV15.
- **Disease names [D]:** emerging pediatric IPD, often severe in children; post-PCV replacement.
- **Biofilm:** thin [GAP].
- **Resistance [D]:** penicillin-nonsusceptible 0%; erythromycin 25%; MDR 0%. Documented susceptible.
- **Strep↔staph↔pneumonia [D]:** species-level library.
- **[LOGIC] — virulence without armor.** Chain: (a) severe pediatric invasive disease documented [D]; (b) penicillin-nonsusceptible 0%, MDR 0% [D]. Therefore: 10A proves invasive disease never needed the resistance machine — the capsule alone can be enough. (His value quoted above; no reading made — boundary held.)

### Serotype 11A — his value quoted: 0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV20, PCV21. Not in PCV15.
- **Disease names [D]:** severe adult IPD; otitis-media-associated; replacement.
- **Biofilm [D]:** Group II architecture (type 11) [D].
- **Resistance [D]:** resistant clone CC156 — penicillin, amoxicillin, co-trimoxazole; oral-pen nonsusc 20%, erythromycin 40%.
- **Strep↔staph↔pneumonia [D]:** species-level library.
- **[LOGIC] — the second coat-change.** Chain: (a) CC156 previously associated with vaccine serotypes [D]; (b) now found wearing the 11A capsule [D]; (c) 19A did the same, from 19F [D]. Therefore: the resistance lives in the clone, the capsule is the disguise — the second documented instance. "Borrowed armor" twice over: genes borrowed (mosaic pbp), capsule borrowed (switch). The pattern repeats, so it is a mechanism, not an anecdote.

### Serotype 12F — his value quoted: 0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV20, PCV21. Not in PCV15.
- **Disease names [D]:** adult meningitis; outbreaks in crowded settings; adult IPD (5.9% post-PCV13).
- **Biofilm:** thin [GAP].
- **Resistance [D]:** some resistant clones (Tn5252-family transposons); generally susceptible.
- **Strep↔staph↔pneumonia [D]:** ICI-class, overrepresented in post-viral pneumonia (Song) [D-serotype].
- **[LOGIC] — the crowd serotype.** Chain: (a) outbreak-associated in crowded settings — camps, prisons, shelters [D]; (b) ICI-class post-viral [D]; (c) adult meningitis [D]. Therefore: 12F moves through populations like 1 and 5 — the third member of the outbreak set. Its disease name is not a tissue but a setting: "crowd."

### Serotype 14 — his value quoted: 0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21. One of the original PCV7 seven (2000).
- **Disease names [D]:** meningitis (#1 pre-PCV7 in Europe and Brazil), otitis media (top-4), invasive disease.
- **Biofilm [D]:** biofilm-five with *S. aureus* (Sempere 2024) [D-serotype]; Group II architecture (type 14 — max thickness 110.55 μm, roughness 0.331: tall but uneven) [D].
- **Resistance [D]:** classic MDR — clone CC230; PSSP 35% / PISP 50% / PRSP 15%; among the four predominant MDR serotypes (58.97% of the MDR pool).
- **Strep↔staph↔pneumonia [D]:** biofilm-five; PCV13 serum reduces its biofilm but not the staph's [D].
- **[LOGIC] — the resistance outlasts the vaccine.** Chain: (a) in the first conjugate vaccine, 2000 [D]; (b) still classic MDR a quarter-century later [D]. Therefore: twenty-five years of direct vaccine pressure did not dent the resistance machine. The capsule was named and targeted; the pbp genes didn't care. Resistance and vaccine coverage are independent variables — 14 proves it.
- **[LOGIC] — architecture, not just mass.** Chain: (a) type 14 biofilm: tallest max thickness in Group II but highest roughness [D]; (b) biofilm-five member with staph [D]. Therefore: 14's biofilm is tall but uneven — and it is the one staph shares. The inference, marked as such: biofilm *shape* may govern the mixed-species question as much as biofilm mass. Untested — the experiment is obvious.

### Serotype 15B — his value quoted: 0.4 mcg/mL
- **Vaccines [D]:** PPSV23, PCV20, PCV21. Not in PCV15.
- **Disease names [D]:** meningitis and otitis media in children; severe IPD in children and adults; replacement.
- **Biofilm:** thin [GAP].
- **Resistance [D]:** oral-penicillin nonsusceptible 51.7% — highest among the PCV20-unique set; erythromycin 62.1%; penicillin/macrolide non-susceptible.
- **Strep↔staph↔pneumonia [D]:** species-level library.
- **[LOGIC] — the replacement that arrived armed.** Chain: (a) post-PCV replacement serotype [D]; (b) 51.7% oral-penicillin nonsusceptibility — the highest in its replacement cohort, where 8/12F/22F arrived susceptible [D]. Therefore: unlike its fellow replacements, 15B didn't need to evolve resistance after arriving — it came armed. Two replacement strategies exist in this file: arrive clean and adapt (8), or arrive resistant (15B).

### Serotype 17F — his value quoted: 0.2 mcg/mL
- **Vaccines [D]:** PPSV23, PCV21. Not in PCV15 or PCV20.
- **Disease names [D]:** PPSV23-era serotype; modern profile thin [GAP].
- **Biofilm:** thin [GAP].
- **Resistance [D]:** two PNSP isolates in one surveillance set; otherwise thin [GAP].
- **Strep↔staph↔pneumonia [D]:** species-level library.
- **[LOGIC] — the rescue pair, low confidence (marked).** Chain: (a) identical vaccine pattern to 9N — skipped by PCV15/PCV20, picked up by PCV21 [D]. Therefore: probably the same story (adult-threat orphan rescued late) — but the disease literature is too thin to confirm. The logic is structural; the content is [GAP]. Filed as the weakest [LOGIC] in the file, honestly.

### Serotype 18C — his value quoted: 0.5 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21. One of the original PCV7 seven.
- **Disease names [D]:** meningitis; highly invasive in children (Portugal, OR 4.76).
- **Biofilm [D]:** biofilm-five with *S. aureus* (Sempere 2024) [D-serotype]; Group II architecture (type 18) [D].
- **Resistance [D]:** PSSP 100% — fully penicillin-susceptible; not a classic resistant serotype.
- **Strep↔staph↔pneumonia [D]:** biofilm-five; ICI-class, post-viral overrepresentation [D-serotype].
- **[LOGIC] — shelter without armor.** Chain: (a) sits in mixed biofilms with *S. aureus* [D]; (b) PSSP 100% — zero resistance [D]; (c) highly invasive in children [D]. Therefore: 18C proves the biofilm is shelter, not just a resistance bunker — a fully susceptible serotype holds the mixed biofilm and still invades. Invasiveness, biofilm, and resistance are three independent dials; 18C turns two of them.

### Serotype 19A — his value quoted: 0.3 mcg/mL
- **Vaccines [D]:** all four — PPSV23, PCV15, PCV20, PCV21.
- **Disease names [D]:** post-PCV7 replacement IPD (predominant in children and the elderly); major otopathogen; hemolytic uremic syndrome; pneumonia (fatal triple case with hMPV + *M. pneumoniae*).
- **Biofilm [D]:** biofilm-five with *S. aureus* (Sempere 2024) [D-serotype]; capsule thickens under stress (CRH study, with 1/3/23F) [D].
- **Resistance [D]:** MDR clone ST320 — oral-penicillin nonsusc 93.3%, ceftriaxone 53.3%, erythromycin 93.3%, clindamycin 80%; resistant to penicillin, cotrimoxazole, carbapenem, macrolide, tetracycline; evolved from MDR 19F (Taiwan19F-ST236) by capsular switch — ST320 is a double-locus variant of ST236 [D]; 43.7% of US penicillin-nonsusceptible IPD was 19A by 2008 (CDC ABCs) [D].
- **Strep↔staph↔pneumonia [D]:** biofilm-five; fatal triple detection [D-serotype].
- **[LOGIC] — the complete reverse-engineering (the file's centerpiece chain).** Chain: (a) PCV7 (2000) covered 19F, not 19A [D]; (b) 19F's MDR clone Taiwan19F-ST236 survived the vaccine [D]; (c) the clone switched capsule to 19A, becoming ST320 [D]; (d) 19A expanded into the emptied niche, MDR intact [D]; (e) PCV13 (2010) had to add 19A [D]; (f) 19A now sits in all four vaccines and remains MDR [D]. Therefore: every step is documented and the chain runs end to end — the vaccine removes the capsule, the genes persist, the capsule changes, the vaccine chases. This single serotype is the entire thesis in miniature: the medicine is the fixed point, the disease moves around it.

### Serotype 19F — his value quoted: 0.3 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21. One of the original PCV7 seven.
- **Disease names [D]:** otitis media (leading pre-PCV), carriage, pneumonia, invasive disease. The carriage specialist.
- **Biofilm [D]:** biofilm-five with *S. aureus* [D-serotype]; Group III — the thinnest architecture measured (type 19) [D]; its biofilms generate capsule variants (cps19F SNPs) at 55-fold increased mutation frequency, H2O2-driven [D].
- **Resistance [D]:** classic MDR — PSSP 19% / PISP 57.1% / PRSP 23.8%; 42% MDR in a US adult study.
- **Strep↔staph↔pneumonia [D]:** biofilm-five; Sharma-Chawla head-to-head under influenza: pneumonia 91%→100%, bacteremia 0%→33%, mortality 0%→63% [D-serotype] — less dramatic than serotype 4's amplification, because the carrier was already everywhere.
- **[LOGIC] — the mutation engine, not the fortress.** Chain: (a) thinnest biofilm architecture measured, yet the carriage specialist [D]; (b) its biofilms generate capsule variants at 55× the planktonic mutation rate [D]. Therefore: 19F's biofilm was never a fortress — it's a workshop. Thin shelter, fast evolution. The carriage niche rewards mutation speed over wall thickness — and 19A is what walked out of that workshop wearing a new capsule.
- **[LOGIC] — one molecule, two wars.** Chain: (a) H2O2 (SpxB) drives the capsule-variant formation in the biofilm [D]; (b) H2O2 is also the documented weapon that kills *S. aureus* [D]. Therefore: the same molecule wages the staph war and mutates the capsule — offense and evolution in one chemistry. His "one thing does many things" instinct has a documented molecule.

### Serotype 20 — his value quoted: 0.3 mcg/mL
- **Vaccines [D]:** PPSV23 only. (PCV21 carries 20A; cross-protection against serotype 20 not established [GAP].)
- **Disease names [D]:** outbreak lists.
- **Biofilm:** thin [GAP].
- **Resistance:** not established [GAP].
- **Strep↔staph↔pneumonia [D]:** species-level library.
- **[LOGIC] — the unpicked (low confidence, marked).** Chain: (a) with serotype 2, the only PPSV23 serotypes no conjugate ever picked up [D]. Therefore: either judged low-threat or technically difficult — the file cannot distinguish. Filed alongside 17F as the thinnest [LOGIC] entries, honestly.

### Serotype 22F — his value quoted: 0.3 mcg/mL
- **Vaccines [D]:** all four — PPSV23, PCV15, PCV20, PCV21.
- **Disease names [D]:** emerging adult IPD (8.2% in ≥65 post-PCV13); prominent non-vaccine serotype for IPD worldwide in the post-PCV era.
- **Biofilm:** thin [GAP].
- **Resistance [D]:** penicillin-nonsusceptible 0%; clones generally susceptible; MDR 0%.
- **Strep↔staph↔pneumonia [D]:** species-level library.
- **[LOGIC] — the clean replacement.** Chain: (a) emerged post-PCV13 with zero resistance [D]; (b) PPSV23 effectiveness against it measured at 88% (Denmark) — the highest in the file [D]. Therefore: not every replacement is an emergency — 22F rose clean, and the oldest vaccine handles it best. The counterweight to 19A in this file: replacement without armor is possible, and the 1983 archive already covers it.

### Serotype 23F — his value quoted: 0.1 mcg/mL
- **Vaccines [D]:** PPSV23, PCV15, PCV20. Not in PCV21. One of the original PCV7 seven.
- **Disease names [D]:** otitis media (top-4), carriage, pneumonia; Ghana meningitis outbreak (2 cases).
- **Biofilm [D]:** Group I — second-strongest architecture measured (biomass 80.48, type 23) [D]; capsule thickens under stress (CRH study) [D].
- **Resistance [D]:** classic resistant — Spain23F-1; PSSP 3.8% / PISP 73.1% / PRSP 23.1%.
- **Strep↔staph↔pneumonia [D]:** species-level library. Not in the biofilm-five — notable (see below).
- **[LOGIC] — the complete package.** Chain: (a) classic colonizer = longest niche residence [D]; (b) second-strongest biofilm architecture measured [D]; (c) Spain23F-1, classic resistant [D]. Therefore: 23F is where carriage + biofilm + resistance coincide in one serotype — the full set. If this file had to nominate the serotype that best embodies "the colonist that won't leave and can't be killed," it is 23F.
- **[LOGIC] — the conspicuous absence.** Chain: (a) Group I biofilm — stronger architecture than four of the five biofilm-five members [D]; (b) not in Sempere's tested five [D]. Therefore: either untested with staph or tested and negative — the file cannot distinguish [GAP]. The strongest biofilm-former among the resistant set has no documented staph pairing: the single most obvious missing experiment in this file.

### Serotype 33F — his value quoted: 0.5 mcg/mL
- **Vaccines [D]:** all four — PPSV23, PCV15, PCV20, PCV21.
- **Disease names [D]:** pediatric IPD post-PCV13 (North America); non-PCV13 serotypes including 33F responsible for 73–92% of IPD-related deaths in children in England and Wales after PCV13 [D].
- **Biofilm:** thin [GAP].
- **Resistance [D]:** erythromycin 100% nonsusceptible (OR 11.1); oral-penicillin 33.3%; ceftriaxone 0%.
- **Strep↔staph↔pneumonia [D]:** species-level library.
- **[LOGIC] — the vaccine list is one emergency behind.** Chain: (a) drove post-PCV13 pediatric IPD deaths as a non-PCV13 serotype [D]; (b) PCV15 (2021) then picked it up [D]. Therefore: the vaccine list is always dated — it names the last emergency. 33F killed first, got listed after. Read the four vaccine compositions in date order and you read an obituary column, not a prevention plan.
- **[LOGIC] — armor with gaps.** Chain: (a) erythromycin 100% nonsusceptible [D]; (b) ceftriaxone 0% nonsusceptible [D]. Therefore: resistance is drug-specific, never general — 33F's armor has gaps a cephalosporin walks through. "Resistant" is never a complete sentence; the file must always ask "to what."

---

## Part 2 — Vaccine → disease-name map (reverse-engineered)

The vaccines are named for the organism ("pneumococcal"), not for any disease. The disease names live one level down, attached to serotypes. Reversed outward:

- **PCV7 (2000): 4, 6B, 9V, 14, 18C, 19F, 23F** → disease names: otitis media (6B, 19F, 23F, 14), meningitis (14, 18C, 4), carriage (6B, 19F, 23F), pneumonia (4, 9V). The children's set: ears, brains, and the nose they live in.
- **PCV13 additions (1, 5, 7F, 3, 6A, 19A)** → epidemic meningitis (1, 5), the persister (3), the replacement (19A), vaccine failure (3, 7F, 19A), adult pneumonia (3).
- **PCV15 additions (22F, 33F)** → adult IPD, pediatric replacement deaths.
- **PCV20 additions (8, 10A, 11A, 12F, 15B)** → adult severe IPD, outbreaks, pediatric severe IPD, the armed replacement (15B).
- **PCV21 (2024)** → adult severe disease + the orphan rescue (9N, 17F).
- **PPSV23 (1983)** → the archive: all of the above plus the never-conjugated (2, 20).

**[LOGIC] — the fossil record.** Chain: (a) each vaccine generation's serotype list is dated [D]; (b) each list was assembled in response to the failures of the previous one — 19A after PCV7, 33F after PCV13 [D]. Therefore: read the compositions in date order and you read the history of what frightened the field: 2000 = children's ears and meningitis; 2010 = the replacement and the persister; 2021 = adult invasive disease; 2024 = adult severe disease. The disease names moved first; the capsule numbers followed. The "disease names of vaccines" he asked for are this list — the vaccine is named for the bug, but its contents are named for the emergencies.

## Part 3 — The strep–staph–pneumonia triangle, reverse-engineered

**Documented edges [D]:** H2O2 warfare (pneumo→staph, SpxB); negative carriage association (aOR 0.53–0.67); PCV7 clearance doubled staph colonization in children; stable dual-species biofilms; dispersion modulation under viral conditions (pneumo disperses, staph inhibited — mBio 2017); flu-infected co-colonized mice → almost exclusively pneumococcal pneumonia; cocolonization rates rose post-PCV; throat co-carriage 7% during ARI with no negative interaction in the oropharynx.

**[LOGIC] — the triangle's third corner is the syringe.** Chain: (a) PCV7 cleared its seven serotypes [D]; (b) staph nasal colonization doubled in children [D]; (c) pneumo–staph cocolonization rates increased post-PCV [D]. Therefore: every pneumococcal vaccine is a staph intervention in reverse. The triangle isn't strep–staph–pneumonia — it's strep–staph–vaccine. Remove one corner's serotypes and the other corner expands into the room. His niche-thinking holds at the population level, documented.

**[LOGIC] — the virus picks the winner.** Chain: (a) dual biofilm + viral-like conditions → pneumococcus disperses, staph dispersal inhibited [D]; (b) flu-infected co-colonized mice developed almost exclusively pneumococcal pneumonia [D]. Therefore: in the co-colonized airway, influenza doesn't merely "open the door" — it selects which bacterium walks through. The post-flu pneumonia pathogen is decided at the biofilm, before the lung. "Secondary bacterial pneumonia" has a selection step nobody names.

**[LOGIC] — eighteen empty cells.** Chain: (a) only 5 of 23 serotypes have documented direct staph interaction [D]; (b) the other 18 inherit the species-level library [D]. Therefore: the triangle is documented at species resolution and empty at serotype resolution. The reverse-engineering maps the edges that exist and marks the empty cells as the work ahead — with 23F (strongest resistant biofilm, no staph data) as the most conspicuous absence and 14 (tall rough biofilm, staph-positive) as the shape to compare it against.

## Part 4 — The soy angle (dictated Oct 18 — his [H], tested)

His claim, his words: *"soy polysaccharide is part of the chemistry and is related to the saccharides of the different serotypes."* [H]

**The firm foothold [D]:** pneumococcal serotypes ARE defined by capsular polysaccharide chemistry — the capsule's sugar structure is the serotype. That part was never in doubt.

**Soy in the manufacturing [D]:**
- EP patent 2894225 (capsular polysaccharide production): serotypes cultivated "in a general medium such as a **soy-based medium**" — serotypes 1, 2, 3, 4, 5, 6A, 6B, 7F, 9N, 9V, 14, 18C, 19A, 19F, 22F, 23F, 33F named.
- PMC5625727 (pilot PCV-13): 13 serotypes fermented in "**customized soy peptone/yeast medium** recipes."
- US patents 20140099337 / 9981035 / 20150038685: "**each pneumococcal polysaccharide serotype is grown in a soy-based medium**," then purified (centrifugation, precipitation, ultrafiltration, chromatography), chemically activated, and conjugated to carrier protein.
- Frontiers 2024 (serotype 14 CPS optimization): feed medium with **200 g/L soy peptone** investigated.

**Soy polysaccharide chemistry [D]:** soluble soybean polysaccharide — pectin-like, galacturonan backbone (homogalacturonan α-1,4 + rhamnogalacturonan α-1,2-rhamnose/α-1,4-galacturonic acid), branched β-1,4-galactan and α-1,3/α-1,5-arabinan chains (Maeda 2000; Nakamura 2002). Monomers: galactose, arabinose, rhamnose, galacturonic acid, glucose, xylose, fucose, mannose. Capsular polysaccharides: repeating oligosaccharide units up to 8 residues (Jones 2005).

**[LOGIC] — soy is upstream of every capsule.** Chain: (a) every pneumococcal vaccine's polysaccharides are grown in soy-based medium [D]; (b) the purified product of that culture is the capsular polysaccharide [D]. Therefore: his "part of the chemistry" holds at the manufacturing level — soy broth is literally upstream of every capsule in every vial. The chemistry of the vaccine begins in soy.

**The honest boundary [GAP]:** soy peptone is a nitrogen source for growth — the record does not show soy saccharides incorporated into capsular polysaccharides; the bacterium synthesizes its own capsule from its own enzymes. Shared monomers (galactose, glucose, arabinose appear in both soy and various capsules) = shared bricks, different buildings. The "related" holds at the monomer level; anything stronger is [GAP] — his to evidence.

## Part 5 — His theses, tested against the reverse-engineering

- **"Relationship between methicillin resistance and each serotype and penicillin"** [H→D]: per-serotype penicillin nonsusceptibility documented across 10 of 23; same target class (PBPs) as mecA/PBP2a. The floor is documented; the elevation is his.
- **"Fungal based upon their methicillin resistance"** [H]: no documented leg anywhere in this file. His to evidence.
- **"All MRSA serotypes are fungal"** [H]: MRSA documented as *Staphylococcus aureus*, a bacterium; staph has no serotypes [D]. Stands as his, unmoved by the record.
- **"There's always a bacterial element"** [H]: every resistance machine, every biofilm, every warfare chemical (H2O2, gliotoxin, catalase), every capsular switch in this file is bacterial machinery [D]. The file's furniture is his thesis's furniture.
- **Soy claim** [H]: manufacturing leg documented [D]; structural-incorporation leg [GAP].

## Part 6 — GAP ledger

1. 17F modern disease profile; 20/20A cross-protection.
2. The per-serotype fungal/yeast column — still entirely empty across all 23.
3. Serotype-specific staph interaction beyond the biofilm-five (23F the conspicuous absence).
4. His 46 panel cells (his screenshots, his readings).
5. His pneumococcal vaccination history (dates, products).
6. Levofloxacin per-serotype susceptibility — thin throughout.
7. Soy-saccharide incorporation into capsules — no record either way.
8. The bare-[D] audit trail (standing, inherited from the 23-row file).
9. Biofilm architecture for serotypes beyond 3, 6, 9, 11, 14, 18, 19, 23 (Allegrucci groups only).

## Builder's extra (mine, labeled)

The reverse-engineering inverts its own premise: I started from the serotype and found it to be the one label that survives everything. Vaccines rename the threat list around it. Antibiotics select the clones beneath it. Viruses pick which capsule disperses. Biofilms shelter whichever capsule holds the niche. Soy broth grows all of them. The capsule number is the constant; the vaccine lists, the drug choices, the disease names, even the manufacturing medium move around it. His "rotation" thesis, stated from the other side: the serotype doesn't rotate around the medicine — the medicine rotates around the serotype.

## Closing line

Twenty-three serotypes, four vaccines, two resistance machines, one biofilm library, one triangle with eighteen empty cells, one soy broth upstream of everything. The names are Latin, the showing is American, the resistance is documented, the logic chains are labeled, the fungal is his — and the interpretation belongs to Kelsey, Monday.
