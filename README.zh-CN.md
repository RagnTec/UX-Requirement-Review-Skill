# 用户体验需求评估 | UX Requirement Review

**v0.6.0-preview.5 · Agent Skill 预览版**

[English](README.md) · [适用范围](docs/SCOPE.zh-CN.md) · [Skill 主入口](ux-requirement-review/SKILL.md) · [贡献说明](CONTRIBUTING.zh-CN.md) · [许可证](LICENSE.md)

UXRR 是面向用户研究、产品经理、交互设计及相关角色的双语需求合理性分析 Skill，帮助澄清用户目标、真实任务、指定设计手段、归因假设与证据边界，同时以易理解的方式介绍相关用户体验和人因研究视角。

它提供的是**基于现有信息的初步专业判断**，不是用户研究实证、正式需求审批、法规或安全认证，也不替代产品开发与验收。

## 核心能力

- **围绕用户与任务判断：** 先识别受影响人群、使用情境、真实体验负担及机会。
- **区分目标、手段和解释：** 体验问题值得调查，不意味着预设原因已被证实。
- **保持证据边界：** 区分事实、用户反馈、待验证假设、最强反例和关键未知信息。
- **渐进式表达：** 简单问题直接回答；复杂问题先给关键维度，再按需通过「展开 2」「展开全部」深入。
- **适度提醒：** 对安全、合规或重要业务决策所依赖的未知条件，提示进一步核实；不机械重复免责内容。

**唯一双语 Skill 入口：** [`ux-requirement-review/SKILL.md`](ux-requirement-review/SKILL.md)。中文与英文专业参考分别维护在 `references/` 目录。

## 安装

从仓库[获取完整 Skill ZIP](downloads/UX-Requirement-Review-v0.6.0-preview.5-agent-skill.zip)，解压后将完整的 `ux-requirement-review/` 目录放入兼容 Agent Skills 的安装位置；也可克隆仓库后复制该目录。不同客户端的 Skill 加载方式可能不同，不能默认所有平台行为一致。

## 反馈与使用边界

可通过 [GitHub Issues](https://github.com/RagnTec/UX-Requirement-Review-Skill/issues) 提交脱敏的需求案例和判断问题，重点反馈逻辑、证据使用、适用条件与表达清晰度。具体参见[适用范围](docs/SCOPE.zh-CN.md)和[贡献说明](CONTRIBUTING.zh-CN.md)。

进一步的研究方法、研究规划及方案决策支持可了解独立的 [User Experience Decision Advisor（用户体验决策顾问，UXDA）](https://github.com/RagnTec/User-Experience-Decision-Advisor)。两个 Skill 不自动调用或交接执行状态。

**隐私：** 请勿提交未授权的内部需求、参与者记录、个人身份信息或第三方受限素材。

**许可证：** [MIT](LICENSE.md)。当前为预览版本，不声称经过 Agent 功能验收或跨宿主兼容性验证。
