# Requirement Analysis Framework Selection and Evidence Controls

**Scope:** bounded, independent requirement reasonableness review using UX research, cognitive/physical human factors, interaction usability, and universal design. This is a method-selection aid, not an actual Kano survey, interviews, user testing, UXDA project/decision workflow, or implementation plan. Read when the brief requires task, motivation, feature-value, or safety/inference analysis; do not preload for trivial queries.

## 1. Common professional reasoning chain

**User's actual brief → specified users and context → user goal/job → relevant model or UX/HF principle → mechanism and strongest plausible counterexample → evidence status/boundaries → defensible / conditional / fundamentally invalid.**

At minimum, separate business KPI from user goal, imposed design solution from underlying job, and desired outcome from established observation. Use **one primary fit-for-purpose framework**, optionally a supporting interaction/HF mechanism. Explicitly distinguish user statements, verified sources, qualified inference and missing data. A theory suggests what to examine; it does **not** substitute for evidence that it happened in a particular product or population.

**Default presentation:** For complaints about legibility, abandonment or retention, lead with affected **people, jobs, context, pain and human-facing outcomes** before considering technology or measurement. A request to understand a problem can be reasonable without established causal proof; do not reclassify the request as Conditional just because a cause is not yet known. This Skill's first layer remains a concise bounded UX/HF judgment, not device diagnostics, analytics or experiments. Actual execution belongs to the separate UXDA Skill.

## 2. Model selection: questions and evidentiary limits

| Question | Suitable tool | What it supports | What it does NOT establish |
| --- | --- | --- | --- |
| Who experiences what, when, where, why and how? | **5W1H** + context-of-use description | Clarifies roles, task, trigger, environment, goal, proposed approach and missing facts | A **questioning heuristic**, not an empirically validated psychological law or proof the brief is valid |
| What progress does the user actually seek beyond the specified feature? | **JTBD (Jobs to Be Done)** | Forms a context-specific account of desired progress, substitutes, barriers and completion criteria | Cannot treat the team's imagined job as observed user motivation; needs relevant research |
| Is a feature must-be, performance-related, attractive or indifferent? | **Kano model** | Hypothesizes categories; supports actual classification only with relevant target-user responses (e.g. paired functional/dysfunctional items) or comparable properly grounded data | No intuitive “must-be” or “delighter” label masquerading as measured classification; not a universal priority rank |
| Could security, belonging, autonomy or related psychological needs matter? | **Maslow needs hierarchy (limited exploratory lens)** | Sensitizing prompt to possibly missing motivational dimensions | No strict five-level ordering or automatic product priority inference; limited empirical support for strict hierarchical claims |
| Which steps, cognitive/physical requirements and errors matter? | **Task analysis (e.g., HTA)** plus human-factors mechanisms | Clarifies task structure, workload pathways, likely failure points and testable risk hypotheses | Does not establish actual error rates, gaze data, workload measurements or causal effects |
| Does interaction support specified tasks and foreseeable users? | **ISO 9241-11:2018 / ISO 9241-110:2020** relevant concepts/principles | Checks context-specific effectiveness, efficiency, satisfaction and task suitability, self-descriptiveness, expectations, learnability, controllability, error robustness and engagement | Does not by itself certify a particular design, measure user performance, or establish a binding jurisdictional violation |

These are **different kinds of resources**: 5W1H clarifies, JTBD frames the user's job, Kano classifies attributes with evidence, Maslow can only cautiously inspire hypotheses, task analysis and ISO concepts frame observable interaction risks. Pick the approach that actually changes the judgment; do not recite all frameworks.

## 3. Worked example: separating goal, solution and guarantee

Brief: “Put every function on the home screen so users find everything instantly, and guarantee a significant satisfaction increase.”

- **5W1H:** Whose home screen? On what device and viewport, which tasks, how many functions, and what measurable definition of “instantly”? Missing details are conditional, not proof of impossibility.
- **JTBD:** Is the user's job quick access to frequent actions, discovering available features, or staying oriented in a high-consequence task? Distinct jobs can imply different solutions. These are hypotheses until user evidence supports them.
- **Task analysis / interaction principles:** More visible entries may increase search/choice load, but may also speed direct access for certain users. Evaluate actual task flow and information structure; “fewer items is always better” is unjustified.
- **Evidence gate:** An observed statistically significant increase requires valid design, baseline and measurements. It may be a *future objective*, not an achieved result; a directive to fabricate significant findings without observations is fundamentally unacceptable.
- **Kano:** Without a target-user study, do not assert the home-screen functions are must-be or attractive qualities. **Maslow is not decision-relevant in this case, so skip it.**

Result: improved task access is a defensible goal; the all-features-home-screen mechanism is Conditional pending user/device/task constraints; guaranteed significant satisfaction should be reframed as a falsifiable target rather than an established result.

## 4. Traceable primary/authoritative references

- ISO 9241-11:2018, *Usability: Definitions and concepts*: https://www.iso.org/standard/63500.html
- ISO 9241-110:2020, *Interaction principles*: https://www.iso.org/standard/75258.html
- ISO 9241-210:2019, *Human-centred design for interactive systems*: https://www.iso.org/standard/77520.html
- Christensen, Hall, Dillon & Duncan (2016), *Know Your Customers’ “Jobs to Be Done”*: https://hbr.org/2016/09/know-your-customers-jobs-to-be-done
- Kano et al. (1984), *Attractive Quality and Must-Be Quality*: https://doi.org/10.20684/quality.14.2_147
- Wahba & Bridwell (1976), *Maslow Reconsidered*: https://doi.org/10.1016/0030-5073(76)90038-6

These describe frameworks/limits; they are **not evidence that a given user's requirement has been observed to succeed or fail**. Before asserting a legal or mandatory-standard violation, independently establish version, jurisdiction, regulated party, scope and applicable clause. Never invent empirical participants, Kano distributions, measurements or normative requirements.
