# UX Requirement Review

**用户体验需求评估 · v0.6.0-preview.5 · Agent Skill preview**

[简体中文](README.zh-CN.md) · [Scope](docs/SCOPE.en.md) · [Skill entrypoint](ux-requirement-review/SKILL.md) · [Contributing](CONTRIBUTING.md) · [License](LICENSE.md)

UX Requirement Review (UXRR) is a bilingual Agent Skill for **reasoning about UX requirements**. It helps UX researchers, product managers, designers and related practitioners distinguish user goals, specified interactions, causal assumptions, task contexts and evidence limits. It also makes relevant UX research and human-factors perspectives accessible to non-specialists.

The Skill provides **preliminary professional analysis**, not empirical validation, formal requirement approval, legal/safety certification or project execution.

## How it works

- **Start with the user and the task.** Identify who is affected, what they are trying to accomplish, and which experience friction or opportunity matters.
- **Separate goals, means and explanations.** Investigating an experience symptom is legitimate even when the underlying cause is not yet known.
- **Use evidence carefully.** Distinguish reported observations, established facts, hypotheses, strongest reasonable counterexamples and critical unknowns.
- **Be concise first.** For complex requests, provide a short numbered overview; users can request “Expand 2” or “Expand all” to examine selected dimensions.
- **Use proportionate caution.** When material decisions depend on unverified facts, identify what should be checked before relying on the output. Avoid repetitive disclaimers.

The **single bilingual discovery entrypoint** is [`ux-requirement-review/SKILL.md`](ux-requirement-review/SKILL.md). Detailed professional reference files are maintained as paired Chinese and English Markdown documents.

## Install

[Download the Agent Skill ZIP](downloads/UX-Requirement-Review-v0.6.0-preview.5-agent-skill.zip), extract it, and place the complete `ux-requirement-review/` directory in a compatible Agent Skills location.

Alternatively, clone this repository and copy the `ux-requirement-review/` directory. Discovery paths and invocation behavior depend on the client; no cross-platform compatibility is implied.

## Feedback and boundaries

Use [GitHub Issues](https://github.com/RagnTec/UX-Requirement-Review-Skill/issues) for de-identified feedback about reasoning, applicability, clarity and evidence boundaries. See the [English](docs/SCOPE.en.md) / [Chinese](docs/SCOPE.zh-CN.md) scope and [contribution guidelines](CONTRIBUTING.md).

For broader study planning or UX decision support, the independently maintained [User Experience Decision Advisor（用户体验决策顾问，UXDA）](https://github.com/RagnTec/User-Experience-Decision-Advisor) is a separate Skill. There is no automatic handoff or execution.

**Privacy:** Do not submit confidential briefs, personal identifiers, participant records or unauthorized materials. The quality of an assessment depends on the evidence provided and its applicable context.

**License:** [MIT](LICENSE.md). This preview does not claim tested decision accuracy, operational acceptance or regulatory compliance.
