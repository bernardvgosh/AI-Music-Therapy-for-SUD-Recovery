# Phase 2 — Search Strategy and Eligibility Criteria

**Study:** Exploring the Use of Artificial Intelligence and Music-Based Therapy in Supporting Individuals with Substance Use Disorder
**Researcher:** Bernard G. · **Prepared:** 21 August 2026 · **Status:** draft for supervisor sign-off
**Method:** PRISMA-ScR scoping review

This document finalises the search strings, eligibility criteria, and appraisal plan sketched in `Research_Strategy.md` §6, so they are ready to run once the protocol skeleton is signed off. It does not reopen any locked decision from Phase 1 — population scope, synthesis approach, and review design are inherited unchanged.

---

## 1. Eligibility criteria (PCC framework)

| Element | Criterion |
|---|---|
| **Population** | People with a substance use disorder (SUD), any severity (DSM-5-TR mild/moderate/severe, or equivalent ICD-11 criteria), any substance. Alcohol use disorder (AUD) receives particular attention as the sub-population with the densest AI literature, but is not the anchor — SUD-wide is the default scope, and any substance-specific restriction is flagged on use. General population or non-clinical samples are excluded unless a study explicitly stratifies SUD outcomes within a mixed sample. |
| **Concept** | (a) Music therapy delivered by a credentialed music therapist, broader music-based interventions (MBIs), or consumer music listening — kept terminologically distinct at extraction; **and/or** (b) AI-enabled tools: affective computing, recommender systems, conversational agents/chatbots, machine-learning prediction models, just-in-time adaptive interventions (JITAIs), digital therapeutics. Studies must address at least one of the four pillars (emotional regulation, craving reduction, self-expression, personalised recovery support). |
| **Context** | Prevention, treatment, or recovery settings (inpatient, outpatient, residential, community, or fully remote/app-based), where the intervention is positioned as an adjunct to — not a replacement for — professional care. No geographic restriction. |
| **Study designs** | RCTs and controlled trials; observational and cohort studies (including EMA/sensor-based designs); feasibility, pilot, and mixed-methods studies; qualitative studies; conceptual, perspective, and protocol papers. A scoping review is intentionally inclusive of design — narrow systematic-review-style restriction to RCTs only would exclude most of the AI literature, which is still at the feasibility/protocol stage (see Research_Strategy §4.2). |
| **Date range** | 1 January 2015 – present. Rationale: captures the modern digital-therapeutics and machine-learning wave in behavioural health while giving enough runway to include landmark reviews (Hohmann et al., 2017; Ghetti et al., 2022) that themselves synthesise earlier primary literature. Older primary studies reached via citation-chasing from an included review may be added and flagged as pre-dating the window. |
| **Language** | English only, full text obtainable via institutional access. Records excluded on language or access grounds are counted and reported in the PRISMA-ScR flow diagram as a stated limitation — not silently dropped. |
| **Exclusions** | Editorials/opinion pieces with no argued position or evidence base; conference abstracts with no retrievable full text; animal studies; studies of music or AI tools with no connection to SUD populations, prevention, treatment, or recovery outcomes. |

---

## 2. Boolean search strings

Three concept blocks — **Population**, **Intervention**, and **Outcome** — combined with `AND` within a search; terms within a block combined with `OR`. Truncation (`*`) and adjacency operators adapted per-database syntax (see §3).

Three separate searches are run rather than one combined string, because the AI×music×SUD intersection is expected to be very thin (a locked decision — see Research_Strategy §3): a single combined string would under-recall both halves of the literature this review needs to characterise independently.

### 2.1 Population block (used in all three searches)

```
("substance use disorder*" OR "substance misuse" OR "drug dependence" OR
 "drug addiction" OR addiction OR "opioid use disorder*" OR
 "alcohol use disorder*" OR "alcohol dependence" OR "substance abuse" OR
 "polysubstance use")
```

### 2.2 Search A — Music-only

```
Population AND
("music therapy" OR "music-based intervention*" OR "music medicine" OR
 "music listening" OR "receptive music therapy" OR songwriting OR
 "lyric analysis" OR "music-assisted" OR "guided imagery and music")
AND
(craving OR relapse OR "emotion* regulation" OR "self-expression" OR
 "treatment retention" OR engagement OR recovery OR abstinence OR
 "coping skill*")
```

### 2.3 Search B — AI-only

```
Population AND
("artificial intelligence" OR "machine learning" OR "deep learning" OR
 "affective computing" OR "recommender system*" OR "conversational agent*" OR
 chatbot OR "digital therapeutic*" OR "just-in-time adaptive intervention*" OR
 JITAI OR "ecological momentary assessment" OR "natural language processing" OR
 "large language model*" OR "predictive model*")
AND
(craving OR relapse OR "emotion* regulation" OR "self-expression" OR
 "treatment retention" OR engagement OR recovery OR abstinence OR
 personali?ation OR "lapse prediction")
```

### 2.4 Search C — AI-plus-music

```
Population AND
("music therapy" OR "music-based intervention*" OR "music listening" OR
 "music medicine")
AND
("artificial intelligence" OR "machine learning" OR "affective computing" OR
 "recommender system*" OR "conversational agent*" OR "digital therapeutic*" OR
 "generative AI" OR "generative music")
```

*(Search C is expected to return the smallest, most directly relevant pool — screen it first, then use the terms it surfaces to sanity-check A and B.)*

---

## 3. Database-specific adaptation notes

| Database | Notes |
|---|---|
| PubMed/MEDLINE | Combine free-text terms above with MeSH headings: `Substance-Related Disorders[Mesh]`, `Music Therapy[Mesh]`, `Artificial Intelligence[Mesh]`. Use `[tiab]` for title/abstract free-text terms alongside MeSH. |
| PsycINFO (via EBSCO/Ovid) | Map to APA Thesaurus terms (`Substance Use Disorders`, `Music Therapy`) where available; combine with free-text as above. |
| Cochrane Library | Search CENTRAL and CDSR together; Cochrane's own MT/SUD reviews (e.g., Ghetti et al., 2022) will already surface — use their included-study lists for citation-chasing. |
| CINAHL | Similar subject-heading mapping to PsycINFO; strong for nursing/allied-health-delivered music interventions. |
| IEEE Xplore / ACM Digital Library | Drop the Population block's clinical-severity terms (poor recall in CS venues); keep `substance use` OR `addiction` OR `recovery` paired with the Intervention block. Expect noisier results — screen abstracts liberally. |
| Scopus / Web of Science | Full three-block string works well; use as cross-check for coverage gaps between the biomedical and computational indices. |
| RILM / music-therapy outlets (*Journal of Music Therapy*, *Nordic Journal of Music Therapy*, *The Arts in Psychotherapy*) | Hand-search recent volumes/tables of contents in addition to database queries — indexing lag is common in these smaller venues. |
| Google Scholar | Citation-chasing and grey-literature discovery only, not a primary index (per Research_Strategy §6). Use to trace forward/backward citations of the eight verified anchor citations. |

---

## 4. Screening and appraisal (unchanged from scaffolding, restated for completeness)

1. **Deduplicate** across all database exports (e.g., via reference manager or Covidence-style tool).
2. **Two-stage screening:** title/abstract, then full text, against the eligibility criteria in §1. Log every exclusion with a reason.
3. **Report** counts at each stage in a PRISMA-ScR flow diagram.
4. **Appraisal tools**, matched to design: Cochrane RoB 2 (RCTs), AMSTAR-2 (existing systematic/Cochrane reviews), CASP (qualitative studies). For AI-tool studies specifically, also appraise validation status, dataset provenance/representativeness, and whether claims were tested in an SUD population rather than borrowed from an adjacent one (per Research_Strategy §6).
5. **Chart data** into a matrix keyed to the four pillars, tagging every finding *established* / *emerging* / *speculative*.

---

## 5. PROSPERO registration

Scoping reviews are not currently eligible for PROSPERO registration (PROSPERO accepts systematic reviews with a health-related outcome, not scoping reviews). Register instead via the **Open Science Framework (OSF)** registries, which accept scoping-review protocols, or note non-registration explicitly in the eventual methods section with the PROSPERO-ineligibility rationale. Confirm current PROSPERO eligibility rules at submission time, as policies are periodically revised.

---

## 6. Open items for supervisor sign-off

- [ ] Confirm date range (2015–present) is acceptable, or adjust
- [ ] Confirm study-design inclusiveness (RCT through conceptual/perspective papers) matches supervisor's expectations for a scoping review
- [ ] Confirm English-only restriction, or specify additional languages to include
- [ ] Sign off on the three-search-string structure (music-only / AI-only / AI-plus-music) before running searches
- [ ] Confirm OSF registration (or explicit non-registration note) as the PROSPERO substitute
