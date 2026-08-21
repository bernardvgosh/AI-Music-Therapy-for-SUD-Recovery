# Phase 4 — Pillar-Keyed Evidence Extraction Matrix

**Study:** Exploring the Use of Artificial Intelligence and Music-Based Therapy in Supporting Individuals with Substance Use Disorder
**Researcher:** Bernard G. · **Prepared:** 21 August 2026 · **Status:** template — to be populated during data charting (Phase 3→4 handoff)
**Method:** PRISMA-ScR data charting (Item 10–11), keyed to the four-pillar conceptual framework

This document operationalises `Research_Strategy_AI_Music_Therapy_SUD.md` §2's instruction — *"state which pillar(s) [a source] addresses, which mechanism is proposed, what outcome is measured, and how strong the evidence for that link is"* — into a structured charting form. Complete one row per included source (from `Phase3_PRISMA_ScR_Flow_Diagram_Template.md` §4) as full-text appraisal happens, rather than retrospectively, so the synthesis in Phase 4 draws on a consistent record rather than re-reading papers from memory.

---

## 1. How to use this matrix

- **One row per included source.** If a single source addresses multiple pillars (expected — the pillars are "analytically distinct but empirically entangled," per Research_Strategy §2), duplicate the row or use the multi-select Pillar column; do not force a source into a single pillar if it genuinely spans more than one.
- **Complete columns 1–11 at charting time**, immediately after appraisal, while the paper is fresh — not in a batch at the end.
- **The Evidence Strength column is not a vibe check.** Use the three-tier definition from Research_Strategy §6 exactly:
  - **Established** — consistent RCT or meta-analytic support
  - **Emerging** — early trials, cohort studies, or feasibility/pilot work
  - **Speculative** — a proposed mechanism with no direct evidence yet in an SUD population
- **AI-specific columns (9–11)** apply only to sources involving an AI/ML tool; leave blank (not "N/A" — blank is faster to filter) for music-only sources.

---

## 2. Extraction columns

| # | Column | What to record |
|---|---|---|
| 1 | Citation (author, year) | Short form; full reference lives in the master bibliography |
| 2 | Pillar(s) | Emotional regulation / Craving reduction / Self-expression / Personalised support (select all that apply) |
| 3 | Population | SUD substance(s) studied, severity if reported, sample size, setting |
| 4 | Intervention/tool | Music therapy / MBI / consumer listening / affective computing / recommender / conversational agent / JITAI / predictive model / digital therapeutic — name the specific tool or technique |
| 5 | Study design | RCT / controlled trial / observational-cohort / feasibility-pilot / mixed-methods / qualitative / conceptual-perspective |
| 6 | Proposed mechanism | The causal story the study argues for (e.g., "affect-adaptive playlisting reduces perceived stress, which reduces craving urge") |
| 7 | Outcome measured | The actual dependent variable(s) — be precise about whether it's self-reported craving, biomarker, retention, engagement, etc., since mechanism ≠ outcome |
| 8 | Evidence strength | Established / Emerging / Speculative (see definitions above) |
| 9 | AI validation status *(AI sources only)* | Has the tool been validated in a peer-reviewed, out-of-sample way, or is this a proof-of-concept? |
| 10 | Dataset provenance *(AI sources only)* | Was the model trained/tested on an SUD-specific population, or borrowed/adapted from an adjacent population (e.g., general mental health)? |
| 11 | Deployment/regulatory status *(AI sources only)* | Research prototype / FDA-cleared digital therapeutic / commercially deployed consumer app / unclear |
| 12 | Craving-cue paradox relevance | Does this source bear on music-as-trigger as well as music-as-soothing? (Y/N + note) |
| 13 | Ethical flags | Any of the five standing constraints (adjunct framing, data privacy, equity of access, over-reliance risk, craving-cue paradox) raised explicitly by this source |
| 14 | Risk-of-bias / appraisal tool used | RoB 2 / AMSTAR-2 / CASP + summary judgement |
| 15 | Notes / verbatim quotes for later citation | Anything worth quoting directly in the synthesis chapter, with page number |

---

## 3. Blank working table

*(Duplicate this table into a spreadsheet — e.g., Google Sheets or Excel — for actual charting; this Markdown table is the schema reference and a place to seed the first few rows by hand. Column numbers above map 1:1 to columns below.)*

| Citation | Pillar(s) | Population | Intervention/tool | Design | Mechanism | Outcome | Strength | AI validation | Dataset provenance | Deployment status | Craving-cue relevance | Ethical flags | Appraisal | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Ghetti et al. (2022) | Craving reduction; Emotional regulation | SUD-broad, 21 RCTs, ~1,984 pts | Music therapy + standard care | Meta-analysis (Cochrane) | MT engagement → affect regulation → reduced craving urge | Craving (various instruments, pooled) | Established | | | | N — anchors the *soothing* side of the paradox | Adjunct framing | AMSTAR-2 (it is the review being appraised, not appraising primary studies) | Moderate-certainty evidence; the anchor for the craving pillar |
| Silverman et al. (2023) | Craving reduction | SUD-broad, systematic review of induced-craving studies | Music listening (consumer + clinical) | Systematic review | Conditioned associative cue → craving induction | Self-reported/physiological craving response to music cues | Emerging (review of a mixed-quality primary evidence base) | | | | Y — central citation for the craving-cue paradox | Craving-cue paradox (central) | AMSTAR-2 | Anchors the "music is not unambiguously protective" caveat throughout |
| Moniz-Lewis et al. (2025) | Personalised support; Ethics (cross-cutting) | Alcohol use disorder, narrative perspective | AI/LLM tools in alcohol research broadly | Conceptual/perspective | Not a single mechanism — surveys applications | N/A (perspective piece) | Speculative (frames the field, not a tested claim) | Mixed across cited studies | Mixed | Mixed | N | Over-reliance risk; equity of access | N/A (perspective, not appraised for bias) | Good orienting read for Phase 4 introduction to the AI-in-SUD landscape |
| *(add rows as sources are charted)* | | | | | | | | | | | | | | |

---

## 4. Roll-up view (populate once charting is substantially complete)

A second, smaller table for the synthesis chapter — one row per pillar, summarising the state of evidence across all charted sources. This is the direct input to Phase 4's narrative synthesis (Research_Strategy §8, Phase 5 "Synthesis").

| Pillar | # sources (music) | # sources (AI) | # sources (both) | Established findings | Emerging findings | Speculative findings | Key contradiction/gap |
|---|---:|---:|---:|---|---|---|---|
| Emotional regulation | | | | | | | |
| Craving reduction | | | | | | | The craving-cue paradox itself — music as soothing (Ghetti) vs. music as trigger (Silverman) |
| Self-expression | | | | | | | |
| Personalised support | | | | | | | |

---

## 5. Handoff notes

- This matrix is the direct input to the narrative synthesis described in `Research_Strategy_AI_Music_Therapy_SUD.md` §8 ("Synthesise pillar by pillar, then across pillars, surfacing mechanisms, gaps, and contradictions").
- Keep this file (or its spreadsheet counterpart) under version control alongside the PRISMA-ScR flow diagram — together they are the full audit trail from search to synthesis that a thesis examiner or supervisor may ask to see.
- Do not skip columns 9–11 for AI sources even when the answer is "unclear" — an honest "unclear" is itself a finding about the maturity of the field, consistent with the evidence-grading philosophy in Research_Strategy §6.
