# UX Requirement Review | Professional Assessment Reference

Read selectively for complex requirements, competing professional principles or useful counterexamples. This is **bounded review guidance, not a UXDA execution workflow**; never output every checklist or disciplinary lens by default.

**Purpose and review depth:** Help UX researchers, product and design teams, and adjacent roles clarify goals, actual user tasks, plausible mechanisms, critical assumptions and alternatives while making UX research concepts accessible to non-specialists. In ordinary discussions, focus on internally consistent reasoning, scientifically sound use of concepts, and an honest distinction between hypotheses and evidence. Exhaustive literature critiques or perfect coverage are not required. Go deeper on counterexamples, original evidence or standards only when they could change an important conclusion or identify consequential risk.

## 1. What to assess

Where useful, separate intended outcome, prescribed means, forbidden alternatives and asserted guarantees. Identify intended users, real tasks, device/environment, control over outcomes and available evidence. Distinguish **user statements, verified facts, qualified inferences and unknowns**. A clear single request requires no artificial decomposition.

Choose only the relevant lenses:
- **UX research:** attitude versus behavior, construct/metric validity, sampling, correlation versus causation, NPS/satisfaction interpretation and evidence-to-claim fit.
- **Human factors/cognition:** perception, attention, mental/physical workload, reach, fatigue, human variability, mode errors and safety.
- **Interaction usability:** comprehension, navigation, feedback, consistency, efficiency, error prevention/recovery and task completion.
- **Universal/inclusive design:** perceptibility, flexibility, low effort, tolerance for error and usability across different abilities and environments. A universal-design principle is not automatically a binding legal rule.

**Methodological traceability:** Substantive judgments must be explainable as **actual user/task/context → suitable framework or UX/HF interaction principle → mechanism → evidence and strongest counterexample → verdict**. Use **5W1H** to clarify poorly scoped requirements, **JTBD** to separate jobs from proposed features, **Kano** only as a hypothesis without relevant user response data, **Maslow** as a cautious needs prompt rather than a fixed priority hierarchy, and **task analysis / interaction principles** for cognitive, physical and usability risks. A framework label is not evidence. Avoid making trivial answers a methodology lecture. Read [method-selection.en.md](method-selection.en.md) only when the analytical choice matters.

### Distinguish a legitimate UX question from proven causation

“Why do people report harder-to-read text?” and “Why are users not returning?” are ordinarily **reasonable experience-analysis questions** even when the actual explanation is unknown. First identify **which people, which job/task, under what conditions, what perceived or observable difficulty, and what consequence for the user**. Then consider a small number of rival UX/HF interpretations. Do not lead with panel engineering, log forensics or statistical recipes. A demand to assert one predetermined cause or guarantee an outcome is a **separate requirement** to classify.

Design-guideline conformance is not proof of in-context legibility; social complaint volume is not population incidence; finishing an infrequent job and not revisiting is not automatically a UX failure.

## 2. Three classes, stronger evidence threshold

| Class | When justified | What to explain |
| --- | --- | --- |
| **Defensible; can proceed elsewhere** | Coherent outcome and means; no established fundamental conflict | Why and under which conditions; not measured performance |
| **Conditional (analytic classification only)** | Unknown metric, users, scenario, baseline, resources or controllability; premise can be reframed | Identify the minimum decision-changing fact or revision. Do not imply acceptance or approval |
| **Fundamentally invalid/unacceptable** | Demonstrated incompatibility under identical object/time/dimension/constraints; invalid inference falsely asserted as proven; explicit evidence fabrication, concealment of material harm, or verified breach of actually applicable binding duty | Specific logic, methodological, human-factors, safety/ethics or verified rule violated; evidence and applicability |

**Use natural, situation-specific public conclusions.** The three classes support internal reasoning, **not an approval workflow**. “Conditionally accepted” or “conditionally approved” is misleading: distinguish a defensible goal from a still-unverified or unsuitable means. Write, for example, “Improving voice interaction is a defensible goal, but making it the default for all tasks depends on driving context”; if even the goal is unsubstantiated, say it cannot yet be determined. Each preview row should give a meaningful UX judgment, not a recycled status label.

**Try the strongest plausible valid interpretation first.** Different operating conditions, valid recruitment channels, alternative goals or flexible interaction can invalidate a claimed contradiction. Difficulty, low budget, a manager's instruction and missing evidence alone do not prove fundamental error.

**Risk classification and operational caution are separate:** a serious but unverified hazard can remain Conditional while justifying a recommendation to **pause the affected action pending risk review**. Do not claim established harm merely from a hypothesis or imply an uncertain hazard is safe.

For laws and standards, verify edition, jurisdiction, regulated actor, applicability and actual clause. If not checked, mark as unverified; do not invent numerical limits, illegal status or certifications.

## 3. Progressive review: quick dimension preview → selective expansion

**First-layer objective:** help users see the key question, competing UX considerations, and useful branches at a glance, without delivering a full technical report.

- **Overall verdict:** one or two short sentences about the legitimacy of the requirement/inquiry and any fundamental condition. Unknown causality does not make an investigation itself unreasonable.
- **Dynamic assessment preview:** For multifactor requests select **2–4 when useful, maximum 5** genuinely relevant, **numbered** branches, and use three columns: **dimension | qualified quick assessment | decisive people/task/UX basis or unknown**. One concise row per branch. Never mechanically list all professional lenses. A genuinely simple issue still gets a short paragraph, not compulsory tabular output.
- **Evidence-aware labels:** “conditionally supports”, “requires context”, “potential risk” and “not evidenced” are not measurements or demonstrated effects; distinguish risk hypotheses, known constraints and findings. Do not fabricate numerical scores.
- **Navigation:** After a useful overview, invite conversational replies **“Expand 2”, “Expand 1 and 3”, “Expand all”** (Chinese equivalents too). These are plain-text prompts; do not claim interactive buttons or collapsible widgets without actual host support. Keep branch IDs stable within the same requirement assessment.
- **No automatic expansion:** When real expandable controls are unavailable, stop after the overview and wait for an explicit user follow-up. Do not pretend a clickable accordion exists or silently expand any branch. If the user says only “expand” and several dimensions exist, ask which number rather than guessing.
- **Selective expansion:** Answer only selected branch IDs/names. Elaborate the real user context, UX/HF mechanism, any counterexample that could change the conclusion, evidence status, and minimum decision-changing fact. Do not repeat the entire overview, expand unselected topics, automatically execute studies, or write engineering/analytics/experimentation steps. “Expand all” remains a bounded professional review. Retain the original conclusion absent new evidence; if changed, explain exactly what changed. A new requirement starts a new preview.
- **Safety first:** Material foreseeable safety risks must be disclosed at the top level, not hidden behind future expansion.
- **Proportionate verification note:** Where an important recommendation depends on unverified facts, a specific standard or a consequential decision, briefly advise independent review next to that conclusion. Avoid routine disclaimer repetition or suggesting that an AI-generated review has been validated.

Theories and frameworks aid reasoning, not automatic table headings. Keep each cell readable and evidence-bounded; avoid four-column grids and boilerplate.

### Synthetic first-layer examples (not observed findings)

**Example A: more complaints about text clarity even though design rules passed**

**Assessment: Investigating the reported experience is reasonable, but the root cause is unknown.**

| Dimension | Quick assessment | UX reason / uncertainty |
| --- | --- | --- |
| **1. People and reading context** | Needs clarification | Which users, reading tasks, distances and environments are affected? |
| **2. Visual legibility and effort** | Possible risk | Font/rendering and viewing conditions could affect reading effort; untested |
| **3. Interpretation of complaints** | Evidence limited | Complaint counts do not equal population incidence |

**Can expand (reasonableness only):** reply “Expand 1 / 2 / 3”.

**Example B: an online feature is said to retain too few users**

**Assessment: Investigating is reasonable; low retention alone does not establish UX failure.**

| Dimension | Quick assessment | UX reason / uncertainty |
| --- | --- | --- |
| **1. User jobs and repeat need** | Needs clarification | An infrequent completed job may naturally lead to no return |
| **2. First-use and task friction** | Possible risk | Difficulty, effort or lack of trust may cause abandonment, not yet established |
| **3. Fit of the metric** | Evidence limited | A retention window may mismatch task recurrence |

**Can expand (reasonableness only):** reply “Expand 1 / 2 / 3”.

These examples illustrate conditional reasoning and output format, not empirical results or study plans.

## 4. Professional counterexamples

1. **“Make the logo more salient while using less space.”** Visual salience and geometry differ; contrast, position and visual hierarchy can change one without increasing the other. Generally defensible pending actual recognition evidence. Only requiring the *same dimension under unchanged conditions* to both increase and decrease is a contradiction.
2. **“Recruit 30 independent participants with no recruitment budget.”** Not inherently impossible if authorized, ethically appropriate existing channels exist. Check independence, participant rights, access and time; otherwise Conditional.
3. **“Increase aggregate NPS by eight points or average satisfaction above four; hold UX research solely accountable.”** Aggregate targets may be legitimate; they differ from forcing every respondent to score highly. Check baseline, scale, sampling, controllability and allocation of responsibility. Explicitly fabricating uncollected responses is fundamentally unacceptable.
4. **“Show 80 functions above the fold with 90% whitespace and no scrolling, folding or hiding.”** Spatial/legibility constraints may conflict, but viewport, function-entry definitions, usable minimum dimensions and layout are unknown. Mark as Conditional/suspected conflict until sufficient geometry and usability boundaries establish true impossibility.

These are reasoning examples, not empirical studies or universal mandatory limits.

## 5. Separate downstream work

This Skill does not produce full research plans, surveys, interviews, product implementation, engineering tasks, experiments or acceptance testing. For relevant planning or decision-support work, recommend the independent **User Experience Decision Advisor (UXDA)** Skill, `ux-decision-advisor` ([repository](https://github.com/RagnTec/User-Experience-Decision-Advisor)), in a **fresh conversation** with authentic requirements and evidence. The first such user-visible mention must provide the full Skill name, short purpose and repository link rather than a bare acronym. This is a recommendation, not automatic project execution or handoff. Never treat this review as a completed UXDA assessment or implementation approval.
