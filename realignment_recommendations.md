# Recommended Realignments — PSHS-CARC OPCR

**Status: proposals only. Not applied.** The FY2025 alignments in
`opcr_fy2025_alignments.json` keep every strategy and sub-strategy the original document
cited; the only changes applied there were the plan-conformance corrections (pillar labels
and verbatim wording).

These recommendations concern how well the cited sub-strategies fit the indicators actually
sitting in each block. The program-to-indicator mapping is taken as settled and is not
questioned here. Authority for all citations: **DOST AO 017 s. 2023**, Strategic Plan
2023–2028.

Ordered by strength of case.

---

## R1 — D-2: sub-strategy does not describe what the indicator counts

**Strength: strong. Change confined to the sub-strategy; pillar, outcome and strategy unaffected.**

| | |
|---|---|
| Block | D-2 (Program D, indicator D.3) |
| Indicator | No. of administrative activities (training, audit, planning etc.) conducted |
| Currently cites | S18 index **1** — "Pursue appropriate mechanisms to achieve **an adequate number** of competent S&T human resources" |
| Recommended | S18 index **0** — "Strengthen DOST's internal capacities in responding to the stakeholders' needs by investing in **Human Resource Development and Management interventions** and in state-of-the-art applications, facilities, and equipment" |

The cited sub-strategy is about staffing levels — achieving an adequate *number* of S&T
personnel. The indicator counts activities, and its MOV lists the Health and Wellness Program
and 10K Team Trek, National Women's Month, the Safe Spaces Act lecture, PRAISE awarding,
internal audit consolidation, operational and budget planning, and GAD orientation. None of
these bear on headcount; all are HRD and management interventions, which is what index 0
names explicitly.

Index 2, "Advance gender and development mainstreaming efforts", covers several of the
activities the MOV tags as Gender and Development, but index 0 is the broader and correct
home for the indicator as worded.

```json
{ "strategy_number": 18, "sub_strategy_index": 0 }
```

---

## R2 — C-1: the two indicators want different sub-strategies

**Strength: moderate. Requires splitting one block into two; both stay under S19, so pillar and
outcome are unaffected.**

| | |
|---|---|
| Block | C-1 (Program C, indicators C.1 and C.2) |
| Currently cites | S19 index **1** for both — "Improve monitoring and evaluation mechanisms through evidence-based, participatory, and efficient planning and policy development processes" |

The cited sub-strategy reads well for **C.1 Budget Utilization Rate**, which is a monitoring
metric over planning and execution. It reads poorly for **C.2 No. of Campuses/Office compliant
to ISO certification**, which concerns a quality management system, not monitoring and
evaluation. S19 index 0 names that directly: "Adopt digital transformation and other **change
management** strategies that will provide **quality services, efficient processes**, and
timely, data-driven responses." The MOV for C.2 is the ISO 9001:2015 certificate and the
recertification and surveillance audit records — change management and quality assurance
throughout.

Recommended split:

| New block | Indicator | Citation |
|---|---|---|
| C-1 | C.1 Budget Utilization Rate | S19 index 1 (unchanged) |
| C-2 | C.2 ISO certification compliance | S19 index **0** |

Cost: Program C's alignment cell stops spanning both rows, so the printed form gains one
horizontal rule in the first three columns. The PSHSS Program cell still spans both.

---

## R3 — D-1: outreach beneficiaries sit awkwardly under Wealth Creation

**Strength: substantive but contested. This is the only recommendation that changes a pillar,
so it is the one most worth deferring to PSHSS.**

| | |
|---|---|
| Block | D-1 (Program D, indicators D.1 and D.2) |
| Currently cites | DOST Pillar 2: Wealth Creation / Outcome 2 / S5 index 2 — "Encourage and assist researchers and scientists to develop S&T-based innovations through different interventions such as the provision of grants for research and other STI-related programs, projects, and activities" |

**D.1 holds up.** Its MOV shows PEER Saliksik-Agapay research design workshops, curriculum
development writeshops, the Science Research Summit and the STEAM Research and Publication
Writing School — research capacity-building that S5's "other STI-related programs, projects
and activities" covers, with regional STEM teachers as participants.

**D.2 does not.** Its MOV is I-STEP UP SMART Mobile Lab, SIKHAY, DOST Review, STEM Promotion
in Abra and Atok, the NCE and STEM Promotional Caravan, and school outreach — science
promotion and public engagement aimed at elementary and secondary pupils. Reaching those
beneficiaries is not developing S&T-based innovations, and Wealth Creation is not the outcome
being pursued.

Two candidate homes, depending on how the campus reads the activity:

| Option | Citation | Rationale |
|---|---|---|
| **a** | Cross-cutting Strategies / Outcome 5 / S17 index 3 — "Encourage and generate public discourse and engagement on science, technology, and innovation information to raise public awareness and appreciation of science communication" | Treats outreach as science communication. Closest to what the activities are. |
| **b** | DOST Pillar 1: Human Well-Being / Outcome 1 / S1 index 3 — "Cultivate Science culture" | Treats outreach as culture-building. Shorter and broader, but overlaps Program B's promotion remit. |

Recommendation: **option a**, with the caveat below.

**Caveat worth weighing before adopting.** Moving D.2 to S17 puts it under the same strategy
as Program B's promotional indicators, and the two already draw on overlapping evidence — the
STEM promotion caravans appear in both B.2's municipality counts and D.2's beneficiary counts.
That is not double-counting, since the two indicators measure different things from the same
activities, but it does mean a reviewer would see one activity set justifying indicators in two
programs under one strategy. Leaving D.2 where it is avoids that appearance at the cost of a
weak alignment. This is a presentational trade-off for PSHSS to settle, not a technical one.

---

## Considered and not recommended

**B-1** cites S17 index 1, "Build and strengthen capacities on Science Communication, S&T
information generation, knowledge management, literacy, and promotion", while its indicators
measure reach and uptake — municipalities with NCE applicants, municipalities receiving
promotional activities. Index 3 (public discourse and awareness) arguably fits B.1 better. But
index 2, the other reach-flavoured option, is explicitly about reach "beyond physical
boundaries… maximizing the utilization of emergent information systems, media, and
communication platforms", and the campus's promotion is physical caravans. Index 1 is
defensible as naming the activity the campus actually conducts. **Leave as is.**

**B-2** needs nothing. Pillar 1 / Outcome 1 / S1 index 1 (FORWARD Framework) fits the freshmen
GWA indicator, and with Program A now at S1 index 0 the two blocks cite distinct sub-strategies
under the same strategy, which differentiates them cleanly.

**A-1** was resolved separately and is already applied: S1 index 0, "Raise the bar of Science,
Technology, Engineering, and Mathematics (STEM) education", under Pillar 1 / Outcome 1.

---

## If all recommendations were adopted

| Block | Program | Indicators | Citation |
|---|---|---|---|
| A-1 | A | A.1–A.7 | Pillar 1 / Outcome 1 / S1[0] *(applied)* |
| B-1 | B | B.1, B.2 | Cross-cutting / Outcome 5 / S17[1] *(unchanged)* |
| B-2 | B | B.3 | Pillar 1 / Outcome 1 / S1[1] *(unchanged)* |
| C-1 | C | C.1 | Cross-cutting / Outcome 5 / S19[1] *(unchanged)* |
| C-2 | C | C.2 | Cross-cutting / Outcome 5 / **S19[0]** — R2 |
| D-1 | D | D.1 | Pillar 2 / Outcome 2 / S5[2] *(unchanged)* |
| D-2 | D | D.2 | Cross-cutting / Outcome 5 / **S17[3]** — R3a |
| D-3 | D | D.3 | Cross-cutting / Outcome 5 / **S18[0]** — R1 |

Block count rises from six to eight; no indicator moves between programs.
