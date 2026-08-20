# Thinking Method Skills

一组面向 Codex/Agent 工作流的中文 Skill，提炼自 Kenneth Lee 在软件架构、概念空间、技术调查、教学与战略等主题中的方法，并吸收 Keven 关于 AI 时代元认知的补充观点。

## 包含内容

- `kenneth-lee-concept-space`：建立概念、边界、关系和不变量。
- `kenneth-lee-mainline-logic`：寻找目标、逻辑根、主链和闭包。
- `kenneth-lee-architecture-decisions`：把目标落实为架构决策、数据结构和接口。
- `kenneth-lee-adaptive-strategy`：在不确定环境中保留战术自由度和转向条件。
- `kenneth-lee-model-investigation`：用可证伪模型和分层证据调查陌生技术。
- `kenneth-lee-semantic-writing`：写出能收缩决策空间的技术文档。
- `kenneth-lee-logic-chain-teaching`：通过现实主线、知识连接和迁移练习教学。
- `metacognitive-ai-collaboration`：监控判断来源，让 AI 参与红队、验证和模型更新。

完整的方法总览、语料覆盖口径和使用边界见 [AUTHOR_THINKING_MODEL.md](AUTHOR_THINKING_MODEL.md)。

## 使用

将需要的 Skill 目录复制到 Codex Skill 目录，或在项目的 Agent 配置中引用对应的 `SKILL.md`。每个 Skill 均包含：

- `SKILL.md`：触发条件、工作流程、检查项与输出契约；
- `agents/openai.yaml`：界面元数据；
- `references/evidence.md`：方法依据和来源边界。

## 来源与边界

- Kenneth Lee 原始文章来自 [Kenneth-Lee/MySummary](https://github.com/Kenneth-Lee/MySummary)。原仓库声明仅供个人阅读且保留全部权利；本仓库仅提供方法转述和外部来源定位，不复制文章正文。
- 元认知部分另参考 Keven 的[《AI 时代为什么元认知最重要》](https://kvenux.github.io/keven-blog/posts/metacognition-ai-era/)，并与 Kenneth Lee 的观点分开标注。
- 这些 Skill 是工作方法，不代表原作者背书，也不保证原文中的历史技术判断在当前仍然有效。
- 本仓库未附开源许可证；除非相应权利人另行许可，不应将来源内容视为已获开源授权。
