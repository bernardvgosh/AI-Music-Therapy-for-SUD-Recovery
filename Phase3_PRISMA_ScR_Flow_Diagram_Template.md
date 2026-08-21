# Phase 3 — PRISMA-ScR Flow Diagram Template

**Study:** Exploring the Use of Artificial Intelligence and Music-Based Therapy in Supporting Individuals with Substance Use Disorder
**Researcher:** Bernard G. · **Prepared:** 21 August 2026 · **Status:** template — counts to be filled in once searches are run
**Method:** PRISMA-ScR (Tricco et al., 2018), Item 14 — Selection of Sources of Evidence

This document is the counting/reporting scaffold for Phase 3 (Search, Screening & Appraisal). It implements PRISMA-ScR Item 14 exactly as specified in Tricco et al. (2018, *Annals of Internal Medicine*, 169:467–473, https://doi.org/10.7326/M18-0850): *"Give numbers of sources of evidence screened, assessed for eligibility, and included in the review, with reasons for exclusions at each stage, ideally using a flow diagram."*

It is a **template with placeholder counts (`n = ___`)** — nothing here is invented data. Fill in real numbers only as each stage is actually completed, and keep this file version-controlled so the audit trail of what was excluded, and why, survives to the methods section.

---

## 0. Why three parallel intakes

Per `Phase2_Search_Strategy_and_Eligibility.md` §2, this review runs **three separate Boolean searches** — music-only, AI-only, and AI-plus-music — rather than one combined string, because the three-way intersection is expected to be thin (a locked design decision; see `Research_Strategy_AI_Music_Therapy_SUD.md` §5). The standard PRISMA-ScR diagram assumes a single intake stream; this template extends it with three parallel identification columns that converge at deduplication, so the eventual flow diagram stays honest about how many records came from each search rather than obscuring it in one merged number.

---

## 1. Identification

| Source | Search A: Music-only (n=) | Search B: AI-only (n=) | Search C: AI-plus-music (n=) |
|---|---:|---:|---:|
| PubMed/MEDLINE | | | |
| PsycINFO | | | |
| Cochrane Library (CENTRAL + CDSR) | | | |
| CINAHL | | | |
| IEEE Xplore | | | |
| ACM Digital Library | | | |
| Scopus | | | |
| Web of Science | | | |
| RILM / music-therapy outlets (hand search) | | | |
| **Subtotal per search** | **n = ___** | **n = ___** | **n = ___** |

**Additional records identified through other sources** (citation-chasing from the eight verified anchor citations, Google Scholar grey-literature search, supervisor/expert recommendation): **n = ___**

**Total records identified (all searches + other sources): n = ___**

---

## 2. Screening

```
Records identified through database searching        Additional records identified
(Search A + B + C combined)                          through other sources
        n = ___                                              n = ___
              │                                                │
              └───────────────────┬────────────────────────────┘
                                   ▼
                  Records after duplicates removed
                            n = ___
                                   │
                                   ▼
                    Records screened (title/abstract)
                            n = ___
                                   │
                     ┌─────────────┴─────────────┐
                     ▼                            ▼
         Records excluded at                Records advancing to
         title/abstract stage                full-text assessment
              n = ___                              n = ___
```

**Duplicate removal method:** [name reference manager / tool used, e.g. Zotero, Covidence, EndNote]

**Title/abstract screening:** two-stage per `Phase2_Search_Strategy_and_Eligibility.md` §4. State here whether screening was single-reviewer (typical for a thesis-scale scoping review) or dual-reviewer with a reconciliation step, since this affects how the methods section describes rigor.

---

## 3. Eligibility (full-text assessment)

```
Full-text sources assessed for eligibility
            n = ___
                  │
     ┌────────────┴─────────────┐
     ▼                          ▼
Full-text sources          Full-text sources excluded, with reasons
excluded                          n = ___
   n = ___                              │
                    ┌────────────────────┼────────────────────┬─────────────────────┐
                    ▼                    ▼                    ▼                     ▼
          Wrong population      Wrong concept        Wrong context/design    Not retrievable /
          (not SUD, or SUD      (no music-based or   (not prevention,        language, or other
          outcomes not          AI element per       treatment, or           exclusion (per
          stratified)           §1 concept            recovery setting;      Phase2 doc §1)
             n = ___            criteria)             design outside §1's        n = ___
                                    n = ___             admitted list)
                                                            n = ___
```

Record every full-text exclusion with its specific reason — PRISMA-ScR requires this at minimum at the full-text level (per the Item 14 tip sheet). Keep a companion screening log (spreadsheet or reference-manager tags) mapping each excluded citation to one of the reason categories above; this diagram reports the counts, the log carries the citation-level detail.

---

## 4. Included

```
Sources included in the scoping review
              n = ___
                    │
        ┌───────────┴───────────┐
        ▼                       ▼
Sources contributing        Sources identified via
primarily to the            citation-chasing / hand-search
music pillar,                only (not from the three
AI pillar, or both               Boolean searches)
     n = ___                          n = ___
```

**Total sources included, charted into the pillar-keyed evidence matrix (`Phase4_Evidence_Extraction_Matrix.md`): n = ___**

---

## 5. Reporting checklist (before this is finalised for the methods section)

- [ ] Every box above has a real count, not a placeholder
- [ ] Every full-text exclusion has a logged reason (not just a subtotal)
- [ ] The three-search structure (A/B/C) is either preserved in the final diagram or explicitly collapsed with a note explaining why, so a reader can still trace provenance
- [ ] Counts reconcile: Identification total = Screening intake; Screening advances = Eligibility intake; Eligibility advances + citation-chased additions = Included total
- [ ] A rendered flow-diagram graphic (e.g., via the PRISMA2020 R/Shiny tool, adapted for ScR, or a simple diagramming tool) is produced from these final numbers for the thesis figure
- [ ] Supervisor has reviewed the exclusion-reason categories in §3 for completeness before full-text screening begins at scale
