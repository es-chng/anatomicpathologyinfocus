---
# ---- Base fields: the same for every article ----
title: "Margin Adequacy in Phyllodes Tumors Revisited: A Critical Interpretive Synthesis of 40 Studies and the Case Against a Universal 10-mm Rule"
authors:
  - given: "Ewe Seng"
    family: "Ch'ng"
    affiliation: "Universiti Sains Malaysia, Penang, Malaysia"
corresponding_email: "eweseng@usm.my"
volume: 1
issue: 1
order: 2
pages: "1-3"
published_date: 2026-09-24
licence: "CC BY 4.0"
# doi: is added automatically by the Zenodo workflow; no need to write it

# ---- Article type (file in _data/) and whether it is live ----
schema: schema-brief
status: published

# ---- Schema fields: the sections defined in _data/schema-brief.yml ----
article_type: "Evidence brief"

question: >-
  What margin width is actually required for benign, borderline, and malignant
  phyllodes tumors (PTs) of the breast, given that current guidelines range
  from "no tumor on ink" for benign lesions to a mandatory ≥10 mm margin for
  all grades?

background: >-
  PTs are rare fibroepithelial neoplasms (<1% of breast tumors) graded as
  benign, borderline, or malignant. Surgical excision is the principal
  treatment, but the relevance of negative margins and optimal margin width
  remains controversial, with wide variation in practice recommendations. The
  early NCCN recommendation of ≥10 mm for all PTs was based on limited
  retrospective data and was intended as a conservative safeguard; more recent
  guidelines from the UK Association of Breast Surgery recommend 3 mm for
  borderline and 5 mm for malignant PTs, whereas the College of American
  Pathologists and WHO decline to specify any distance. Inconsistent diagnostic
  definitions, varying margin terminology, and sparse quantitative evidence
  have prevented consensus. Because the available evidence is limited and
  heterogeneous, traditional meta-analysis cannot yield precise or
  generalizable recommendations. Rakha and colleagues therefore undertook a
  critical interpretive synthesis (CIS) of 40 single-cohort studies published
  between 2015 and 2025, supplemented by random-effects modeling, Monte Carlo
  resampling, appraisal of prior meta-analyses and guidelines, and
  multidisciplinary expert contextual review.

evidence:
  - source: "Rakha et al. (2026); CIS of 40 single-cohort studies, 2015–2025"
    finding: "No consensus emerged on a fixed margin width for borderline or malignant PTs. No significant differences in local recurrence (LR) risk or histologic upgrade on recurrence were observed between 10-, 5-, 3-, 2-, and 1-mm margins. Tumor biology was consistently a more accurate predictor of recurrence than margin width, and no incremental reduction in LR was seen with increasing margin width beyond 1 mm. Explicit millimetric cutoffs were uncommon: a 1-mm margin was recommended in 5 studies and a 2-mm margin in 4 studies; 9 studies favored ≥10 mm."
    limitation: "CIS lacks the rigor of a systematic review or meta-analysis; most studies dichotomized margins into greater-than or less-than a chosen cutoff, with the 'less than' group frequently combining 0 mm (positive), submillimetric, and intermediate (2–3 mm) margins, substantially limiting interpretability."
  - source: "Rakha et al. (2026); random-effects model (REM) of pooled recurrence"
    finding: "Pooled LR rates were 5.3% (95% CI 4.4–6.4) for benign, 12.5% (95% CI 10.3–15.1) for borderline, and 16.6% (95% CI 13.4–20.0) for malignant PTs, with substantial heterogeneity (I² = 58.6%, 52.1%, and 66.3%, respectively). Distant recurrence pooled at 14.0% (95% CI 11.6–16.7) and occurred almost exclusively in malignant PTs. Prediction intervals were wide across all groups (e.g., 6.7–35.6% for malignant LR), indicating that real-world recurrence rates may vary considerably."
    limitation: "Aggregate analysis did not adjust for censoring or time-to-event effects; follow-up duration and recurrence ascertainment varied substantially across studies, so some heterogeneity may reflect differences in follow-up intensity rather than margin-related effects."
  - source: "Rakha et al. (2026); Monte Carlo resampling analysis"
    finding: "When studies were randomly divided into two equal groups (1000 iterations), median differences in recurrence rates ranged from 0.8% to 2.5% with wide confidence intervals (e.g., 0.13–7.7% for malignant LR), demonstrating considerable between-study variability. If the included studies were uniform, repeated random allocation would yield a median difference close to 0 with a narrow CI; this was not observed."
    limitation: "Monte Carlo simulation tests robustness of the pooled estimate rather than providing a biologic or clinical threshold; narrow distributions would indicate data uniformity, which was not present."
  - source: "Rakha et al. (2026); upgrade rate and tumor size analyses"
    finding: "Across 8 studies (1482 patients), upgrade at recurrence occurred in approximately 3.0% of the overall borderline cohort; about one-quarter of recurrent borderline PTs recurred as malignant. Tumor size was an independent predictor of LR and correlated with mastectomy rates, but there was no evidence of a direct correlation between PT size and final margin status or upgrade rate."
    limitation: "Upgrade data were derived from a limited number of studies with varying definitions of recurrence versus new ipsilateral primary tumor, which remains a further potential source of variability in reported recurrence estimates."

recommendations:
  - "For benign PTs, complete excision of the lesion (e.g., with an intact pseudocapsule) is sufficient; margin width has not been shown to independently influence recurrence, and routine re-excision of positive or close margins is not recommended unless there is diagnostic uncertainty regarding grade or definite clinical or radiological evidence of residual disease."
  - "For borderline and malignant PTs, negative margins should be achieved, but a mandatory optimal width cannot be defined; a histological margin of ≥1 mm may represent a pragmatic lower boundary in selected clearly excised cases."
  - "The requirement for ≥10 mm margins for borderline and malignant PTs does not seem justified; no significant differences were observed between 10-, 5-, 3-, 2-, and 1-mm margins with respect to LR risk or histological upgrade on recurrence."
  - "A ≥1 mm margin should be viewed as a practice-supporting 'harm-reduction' consideration rather than an evidence-validated threshold; wider margins may still be appropriate for tumors with adverse features such as large size (>4 cm) or diffusely infiltrative borders, within a multidisciplinary framework."
  - "Re-excision decisions should consider initial margin width, tumor size, growth pattern (well defined vs infiltrative), primary vs recurrent disease, anatomical site, and patient preferences; routine immediate re-excision for small borderline or malignant PTs with close but negative margins may not be necessary."
  - "For malignant PTs, margin strategies analogous to soft-tissue sarcomas may be considered (e.g., a 5-mm margin without adjuvant radiation therapy or a 1-mm margin with adjuvant radiation therapy), while acknowledging that cosmesis is more relevant in breast surgery than in sarcomas of the extremities."
  - "Management should remain individualized according to tumor grade, size, breast volume, feasibility of re-excision, cosmetic impact, and multidisciplinary judgment; this study is an evidence synthesis rather than a guideline."

open_questions:
  - "Whether a single optimal margin clearance can ever be defined, given the limited high-quality evidence and multiple confounders including sampling thoroughness, evolving diagnostic criteria, and variable follow-up duration."
  - "How to distinguish true local recurrence from a new ipsilateral primary tumor, which represents a potential source of variability in reported recurrence estimates."
  - "Whether wider margins reduce LR in specific subgroups defined by adverse features such as large tumor size, infiltrative borders, or recurrent disease."
  - "The role and optimal selection criteria for adjuvant radiation therapy in malignant and borderline PTs, which is constrained by limited data and was beyond the scope of this synthesis."
  - "Whether the proposed refined WHO criteria for malignant PT and the distinction between cellular fibroadenoma and benign PT will alter recurrence estimates and margin recommendations in future cohorts."
  - "Whether large multicenter studies with standardized definitions, reporting, and comprehensive treatment and outcome data can confirm or refine these recommendations."

perspective: >-
  This synthesis makes a persuasive case that the long-standing ≥10 mm
  margin rule for phyllodes tumors is an artifact of limited retrospective
  data rather than a biologically grounded threshold. The finding that tumor
  biology—not margin width—is the dominant determinant of recurrence is
  clinically liberating: it argues against mutilating surgery for small,
  well-circumscribed borderline tumors while preserving caution for large or
  infiltrative lesions. The equal-voice interpretive model, though less
  rigorous than meta-analysis, is a defensible response to a literature that
  cannot support quantitative pooling: when 40 studies disagree, counting
  votes equally may be more honest than weighting by cohort size. The
  pathology-specific limitations the authors acknowledge are important—margin
  assessment in large tumors is vulnerable to undersampling, and a 1-mm
  clearance is neither routinely verifiable intraoperatively nor reliably
  reproducible on a microscopic slide. The proposed framework (Table 6) is
  appropriately modest: it offers practice-supporting guidance rather than
  pretending to be a guideline. The most useful contribution may be the
  emphasis on surgeon–pathologist communication: margin guidance must
  distinguish between the operative target at primary excision and the
  criteria that should prompt re-excision once final pathology is known. Until
  standardized multicenter data exist, individualized multidisciplinary
  decisions—not a fixed millimetric rule—should govern margin adequacy.

bottom_line: >-
  Across 40 studies, margin width beyond 1 mm did not consistently reduce
  recurrence in phyllodes tumors; tumor biology, not the 10-mm rule, drives
  local recurrence, so margins should be individualized by grade and features.

references:
  - "Rakha EA, Quinn C, Farshid G, et al. Margin Adequacy in Phyllodes Tumors Revisited: Reappraisal of the Evidence Base and Knowledge Gaps. Mod Pathol. 2026;39(9):101034. doi:10.1016/j.modpat.2026.101034"

conflicts_declared: false
last_reviewed: 2026-09-23

editorial_note: "Editor-only field: never shown on the site or in the PDF."
---
