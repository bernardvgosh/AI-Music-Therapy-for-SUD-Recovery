# Research Strategy, Plan, and Working Instructions

**Project:** Exploring the Use of Artificial Intelligence and Music-Based Therapy in Supporting Individuals with Drug Addiction and Substance Use Disorder
**Researcher:** Bernard G.
**Date prepared:** 8 June 2026

---

## 1. Purpose of this document

This document sets out a strategy, a phased plan, and a set of working instructions for the study. It is intended as a living reference: a place to anchor the research questions, the conceptual framework, the search and appraisal approach, the ethical commitments, and the standards for written output. It is not a finished literature review. Where it characterises the current state of evidence, it does so to orient the work and to flag where claims are well-supported versus emerging or contested; every such characterisation should be re-verified against primary sources before it enters the thesis or any publication.

A note on framing that runs through everything below. The study concerns a population that is clinically vulnerable and frequently stigmatised. AI tools and music-based interventions are treated throughout as *potential adjuncts* to evidence-based treatment, never as replacements for it. Language should be person-first ("people with a substance use disorder," not "addicts"), and the burden of proof for any therapeutic claim sits with the evidence, not with the appeal of the technology.

---

## 2. Conceptual framework: the four pillars

The study is organised around four functions that AI and music-based interventions might serve in recovery. These pillars are the organising spine for the literature, the methods, and the analysis. It is worth stating at the outset that they are analytically distinct but empirically entangled — an intervention that improves emotional regulation may, through that mechanism, reduce cravings — and part of the contribution of the work is to be precise about which outcomes are actually being measured.

**Pillar 1 — Emotional regulation.** The capacity to recognise, tolerate, and modulate affective states without recourse to substance use. Music-based work bears on this through mood induction, relaxation, and affect-focused therapeutic techniques; AI bears on it through affect detection (affective computing) and through systems that adapt content to a detected or reported emotional state.

**Pillar 2 — Craving reduction.** The attenuation of the urge to use. This is the pillar with the most direct clinical evidence on the music side, but it is also the pillar where music is most clearly double-edged, because music can act as a conditioned cue that *induces* craving. AI bears on it through lapse- and craving-prediction models and just-in-time adaptive interventions.

**Pillar 3 — Self-expression.** The use of creative and communicative activity to process experience, build insight, and rebuild identity beyond the "addict" role. Clinically this maps onto established music therapy techniques (songwriting, lyric analysis, improvisation); on the AI side it maps onto generative co-creation tools, which are largely unvalidated in this population.

**Pillar 4 — Personalised recovery support.** The tailoring of support to the individual over time — content, timing, intensity, and modality. This is where recommender systems, conversational agents, and machine-learning personalisation are most relevant, and also where the ethical stakes (privacy, equity, over-reliance) are highest.

For each substantive section of the study, the explicit instruction is: state which pillar(s) it addresses, which mechanism is proposed, what outcome is measured, and how strong the evidence for that link is.

---

## 3. Research questions

A workable structure is one overarching question with four pillar-aligned sub-questions and a cross-cutting ethical question. Refine the wording with your supervisor, but the logic should hold.

**Overarching:** In what ways, and with what evidentiary support, can artificial intelligence and music-based interventions function as adjuncts to professional treatment for people with substance use disorder?

- *RQ1 (Emotional regulation):* What is the evidence that music-based interventions and AI-enabled affective tools improve emotional regulation in people with SUD, and through what proposed mechanisms?
- *RQ2 (Craving):* What is the evidence that these tools reduce craving — and under what conditions might music instead act as a craving cue?
- *RQ3 (Self-expression):* How do music-based therapeutic techniques and AI co-creation tools support self-expression and identity reconstruction in recovery?
- *RQ4 (Personalisation):* How can AI personalise recovery support across time, and what are the limits and risks of doing so?
- *RQ5 (Ethics, cross-cutting):* What ethical, methodological, and equity considerations should govern the responsible development and study of these tools?

---

## 4. Orientation to the current evidence base

This section is a map, not a review. It exists so the plan is grounded in where the literature actually stands. Treat each claim as a starting hypothesis to be confirmed against primary sources.

### 4.1 Music-based interventions for SUD

A crucial terminological distinction must be maintained throughout: *music therapy* (MT) delivered by a credentialed music therapist within a treatment plan is not the same as *music-based interventions* (MBIs) more broadly, and neither is the same as *consumer music listening* via streaming apps. The evidence is strongest and most interpretable for the first category and weakest for the last.

The most authoritative synthesis on the clinical side is the Cochrane review by Ghetti and colleagues (2022), which pooled 21 randomised trials (around 1,984 participants) and reported moderate-certainty evidence of a medium-sized effect favouring music therapy added to standard care over standard care alone for substance craving. This is the single strongest evidence point in the field and the natural anchor for the craving pillar — though "moderate certainty" should be reported honestly, not inflated. Earlier and adjacent reviews (Hohmann et al., 2017; Megranahan & Lynskey, 2018) found beneficial effects on emotional and motivational outcomes, treatment participation, and readiness to change, but with substantial inconsistency across studies, heavy reliance on single-session designs, and a near-absence of longitudinal trials. The honest summary is: promising and improving, but heterogeneous and immature.

The decisive caveat for this study is that music is not unambiguously protective. A systematic review by Silverman and colleagues (2023) found that music can *induce* craving for substances including alcohol, cannabis, and nicotine by acting as a contextual cue, and qualitative work confirms that people in recovery are often acutely aware of songs and genres that function as drug cues. This means the craving pillar cannot be framed simply as "music reduces craving"; the more accurate framing is that music is a powerful affective and associative stimulus whose effect on craving is context-, person-, and content-dependent, and that therapeutic skill lies partly in working with that ambivalence rather than assuming benefit.

### 4.2 AI in SUD prevention, treatment, and recovery

The applied AI literature here is younger and more fragmented, weighted toward feasibility studies, protocols, and narrative reviews rather than confirmatory trials. Several strands are relevant. Machine-learning *lapse- and relapse-prediction* models built on ecological momentary assessment and smartphone or wearable data are an active area — for example, deep-learning models predicting non-prescribed opioid use and treatment retention (Heinz et al., 2025), and protocols pairing ML lapse-prediction with automated, personalised daily support messages for alcohol use disorder. *Generative AI and conversational agents* are being studied as accessible, around-the-clock information and support tools, but evaluations of their accuracy and safety on real drug-related questions are mixed and have prompted calls for clinical validation before deployment (Giorgi et al., 2024). Authoritative perspective pieces — notably Moniz-Lewis et al. (2025) in *Alcohol Research: Current Reviews* — frame AI's promise for equitable, scalable, compassionate care alongside serious ethical concerns, and should be read early.

The defensible overall characterisation is: real and accelerating activity, genuine promise especially for access and personalisation, but the evidence is largely emerging or speculative, with very few rigorously validated, clinically deployed tools to date.

### 4.3 Affective computing and music emotion recognition

The bridge between the AI and music halves of the study runs through affective computing — emotion recognition from facial, vocal, textual, or physiological signals — and music emotion recognition (MER), which underpins emotion-aware music recommendation. The literature here is technically rich but clinically cautious. Narrative reviews of affective computing for digital mental health report potential gains in engagement and personalisation but note that clinical validation remains limited. The MER literature flags structural limitations directly relevant to this study: annotation subjectivity creates a "ground-truth ceiling," emotional responses to music are idiosyncratic and vary by individual and culture, and cross-cultural and genre-specific shifts undermine any universal emotion-to-music mapping. The practical implication for the personalisation pillar is that a system inferring "this person feels X, so play Y" rests on shakier foundations than its interface suggests, and this gap between apparent and actual reliability is itself a finding worth foregrounding.

---

## 5. Methodological strategy

The right method depends on what kind of contribution this is — and that is a decision to settle with your supervisor before the search begins. Three viable designs, in rough order of how much new empirical work they require:

**Option A — Systematic or scoping review (recommended default for a thesis of this kind).** A structured synthesis of the evidence across the four pillars, reported against an established protocol (PRISMA for systematic reviews; PRISMA-ScR for scoping reviews). A *scoping* review is the more honest fit if the aim is to map a heterogeneous, emerging, cross-disciplinary field and identify gaps; a *systematic* review with narrow inclusion criteria is appropriate only if a sufficiently homogeneous body of trials exists for a defensible question (craving reduction via music therapy is the one pillar where this may be feasible). Pre-register the protocol (PROSPERO for systematic reviews) where eligible.

**Option B — Conceptual / theoretical synthesis with a proposed framework.** Build an integrative model of how AI and music-based interventions could map onto the four pillars, grounded in the evidence but contributing a framework rather than a pooled estimate. Lower empirical burden; contribution rests on the clarity and usefulness of the framework.

**Option C — Primary empirical study.** A small qualitative study (interviews with clinicians, music therapists, or — with heavy ethical safeguards — people in recovery), a feasibility/usability study of a tool, or a prototype evaluation. This carries the highest ethical and logistical load (see §7) and would require full ethics-board approval and likely clinical collaboration. Only pursue if scope, time, and supervision genuinely support it.

A common and defensible structure is a scoping review (Option A) that culminates in a proposed framework (Option B), with primary work reserved for future research. Whatever the choice, specify the design, justify it, and report it transparently.

---

## 6. Search and sourcing strategy

**Databases.** Cover the disciplinary spread: PubMed/MEDLINE and PsycINFO (addiction science, psychology, music therapy), Cochrane Library (trials and reviews), CINAHL (nursing/allied health), and for the computational side IEEE Xplore, ACM Digital Library, Scopus, and Web of Science. Use Google Scholar only for citation-chasing and grey-literature discovery, not as a primary index. RILM and Music Therapy–specific outlets (e.g., *Journal of Music Therapy*, *Nordic Journal of Music Therapy*, *The Arts in Psychotherapy*) catch work the biomedical databases miss.

**Search-term scaffolding.** Build Boolean strings from three concept blocks combined with AND, each block expanded with synonyms combined with OR:

- *Population:* "substance use disorder" OR addiction OR "drug dependence" OR "opioid use disorder" OR "alcohol use disorder" OR "substance misuse" (specify severity where relevant — mild/moderate/severe per DSM-5-TR — rather than treating SUD as monolithic).
- *Intervention:* "music therapy" OR "music-based intervention" OR "music medicine" OR "music listening" on one axis; "artificial intelligence" OR "machine learning" OR "affective computing" OR "recommender system" OR "conversational agent" OR chatbot OR "digital therapeutic" on the other. Run music-only, AI-only, and AI-plus-music searches separately; the intersection is small and you will need the broader pools to reason about each half.
- *Outcome:* craving OR "emotion regulation" OR relapse OR "self-expression" OR engagement OR "treatment retention" OR personalization.

**Inclusion / exclusion.** Pre-specify: study designs admitted, date range (the AI literature moves fast — favour recent work but anchor on landmark reviews), language, population (clinical SUD vs general), and the MT/MBI/consumer-listening distinction. Record decisions in a screening log and report counts in a PRISMA flow diagram.

**Appraisal.** Match the tool to the design — Cochrane Risk of Bias 2 for RCTs, AMSTAR-2 for existing reviews, and a recognised checklist (e.g., CASP) for qualitative work. For AI tools specifically, appraise not just outcomes but validation status, dataset provenance and representativeness, and whether claims have been tested in the target population rather than borrowed from adjacent ones.

**Evidence grading.** Tag every key finding with a strength-of-evidence label — for instance: *established* (consistent RCT/meta-analytic support), *emerging* (early trials or feasibility work), or *speculative* (proposed mechanism, no direct evidence in SUD). This labelling is not optional decoration; it is the spine of an honest contribution in a field prone to hype.

---

## 7. Ethical framework

Ethics is not a closing chapter; it is a design constraint that should shape the questions and methods from the start. The following concerns should be carried through the whole study and addressed explicitly wherever they bear on a claim.

- **Adjunct, not replacement.** State plainly and repeatedly that these tools supplement professional, evidence-based treatment (psychosocial therapy, FDA-approved medications for opioid and alcohol use disorder, mutual-help and community support). Nothing in the study should read as encouraging anyone to substitute a tool for care.
- **Data sensitivity and privacy.** Recovery data — location, physiological signals, voice, craving logs — is among the most sensitive personal data there is, and its disclosure can carry legal and social consequences for an already-stigmatised group. Examine how candidate tools collect, store, share, and secure data, and treat strong privacy protection as a requirement, not a feature.
- **Equity of access.** Tools that depend on smartphones, wearables, connectivity, and digital literacy can widen rather than narrow disparities. Ask consistently who is served and who is excluded by a given approach.
- **Risk of over-reliance and false reassurance.** Affect-detection and recommendation systems can present more certainty than they possess (see §4.3). Over-reliance on an automated tool — especially a conversational agent during a crisis — is a genuine safety concern. Note where a tool could give unsafe or inaccurate guidance and what safeguards (human oversight, escalation to crisis resources, clinical validation) are needed.
- **The craving-cue paradox.** Because music can trigger as well as soothe craving, any music-based or music-recommending tool carries a specific, foreseeable risk of harm. This deserves explicit treatment rather than a footnote.
- **If any primary research with people in recovery is contemplated,** it requires full ethics-board / IRB approval, informed consent procedures suited to a vulnerable population, a safeguarding and distress protocol, and clinical collaboration. Do not begin recruitment of any kind before approval is in place.

---

## 8. Phased plan

A sequence rather than a calendar; map it to your own timeline and milestones with your supervisor.

1. **Scoping and framing.** Lock the research questions, choose the design (§5), and read the orienting sources (the Cochrane MT review; a major AI-in-SUD perspective; an affective-computing-for-mental-health review). Output: a one-page protocol and refined questions.
2. **Protocol and registration.** Finalise search strings, inclusion/exclusion criteria, and appraisal tools; register the protocol if eligible. Output: written, version-controlled protocol.
3. **Search and screening.** Run searches across all databases, deduplicate, screen against criteria, log decisions. Output: PRISMA flow diagram and screening log.
4. **Appraisal and extraction.** Apply the appraisal tools; extract into a structured matrix keyed to the four pillars, with strength-of-evidence tags. Output: evidence table.
5. **Synthesis.** Analyse pillar by pillar, then across pillars; surface mechanisms, gaps, contradictions (notably the craving-cue paradox), and ethical themes. Output: synthesis notes and, if pursuing Option B, a draft framework.
6. **Writing.** Draft against the structure in §9; integrate ethics throughout rather than quarantining it. Output: full draft.
7. **Revision and verification.** Re-check every empirical claim against its primary source; confirm terminology precision; stress-test claims for overstatement. Output: verified final draft.

---

## 9. Instructions for written output

These are standing instructions for any drafting done for this project, by you or with assistance.

- **Register and form.** Academic register, prose-led. Use clear topic sentences and connected argument, not bullet lists, except where a list genuinely aids clarity (e.g., inclusion criteria, a results table).
- **Map to the pillars.** Each substantive section should make explicit which pillar it serves, the proposed mechanism, the outcome measured, and the strength of evidence.
- **Calibrate claims to evidence.** Distinguish established, emerging, and speculative findings in the prose itself ("moderate-certainty evidence indicates…" vs "preliminary feasibility work suggests…" vs "it has been proposed that…"). Never let an appealing mechanism stand in for demonstrated effect.
- **Terminological precision.** Maintain the music therapy / music-based intervention / consumer-listening distinction and the SUD severity distinctions every time they matter. Define terms on first use.
- **Person-first language** throughout.
- **Surface limitations proactively** — methodological caveats, thin or contested evidence, and the ethical concerns in §7 — rather than waiting to be asked. A limitations section is necessary but not sufficient; caveats belong next to the claims they qualify.
- **Verify before asserting.** Any empirical or factual claim about a current tool, study, or statistic must be checked against an up-to-date primary source, not reproduced from memory or from this document's orienting summaries.
- **Citation hygiene.** Cite primary sources, paraphrase rather than quote, and keep a single reference style consistent with your institution's requirement.

---

## 10. Risks and open questions to resolve early

- **Is the intersection literature large enough?** Studies that combine *both* AI and music-based intervention *in SUD specifically* may be very few. Decide early whether the study synthesises the two halves conceptually (drawing on each literature separately) or insists on the intersection (which may be too thin to support a review).
- **Which design?** (§5) — settle before searching.
- **Severity and substance specificity.** Will the study span all SUDs or focus (e.g., opioid or alcohol use disorder, where the AI literature is densest)? Narrowing improves rigour.
- **Where does primary data sit?** If none, say so and frame primary work as future research; if some, secure ethics approval and clinical collaboration first.

---

## Key orienting references

These are starting points identified during scoping, not a complete bibliography. Verify and expand each against the primary record.

- Ghetti, C., Chen, X.-J., Brenner, A. K., Hakvoort, L. G., Lien, L., Fachner, J., et al. (2022). Music therapy for people with substance use disorders. *Cochrane Database of Systematic Reviews*, 5: CD012576.
- Hohmann, L., Bradt, J., Stegemann, T., & Koelsch, S. (2017). Effects of music therapy and music-based interventions in the treatment of substance use disorders: A systematic review. *PLOS ONE*, 12(11): e0187363.
- Megranahan, K., & Lynskey, M. T. (2018). Do creative arts therapies reduce substance misuse? A systematic review. *The Arts in Psychotherapy*, 57, 50–58.
- Silverman, M. J., et al. (2023). Systematic review on music as a cue for substance craving. (Confirm full citation.)
- Moniz-Lewis, D. I. K., Kirouac, M., McCool, M. W., Schwebel, F. J., & Witkiewitz, K. (2025). Perspective on using artificial intelligence in alcohol research and treatment: Opportunities and ethical considerations. *Alcohol Research: Current Reviews*, 45(1).
- Giorgi, S., Isman, K., Liu, T., Fried, Z., Sedoc, J., & Curtis, B. (2024). Evaluating generative AI responses to real-world drug-related questions. *Psychiatry Research*, 339: 116058.
- Heinz, M. V., et al. (2025). A longitudinal observational study with ecological momentary assessment and deep learning to predict non-prescribed opioid use, treatment retention, and medication nonadherence among persons receiving medication treatment for opioid use disorder. *Journal of Substance Use and Addiction Treatment*, 173: 209685.
- De Freitas, J., & Cohen, I. G. (2024). The health risks of generative AI-based wellness apps. *Nature Medicine*.
- Narrative review of affective computing for digital mental health interventions (2025), *Frontiers in Digital Health* — for the affective-computing bridge and its validation limits.
