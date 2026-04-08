# chat-skills

面向国男的情感聊天指南。

这是一个面向 AI 工具的 skill 仓库，目标是把恋爱聊天拆成可分析、可复用、可继续扩展的框架。

## Scope

仓库当前聚焦这些问题：

- 怎么开启一段不尴尬的聊天
- 怎么把天聊顺，而不是聊成审讯
- 怎么判断对方的投入、边界和窗口
- 怎么在合适的时候推进邀约
- 怎么在冷淡、误会或拒绝后体面收尾

## Principles

这个仓库不把聊天理解为操控，而理解为：

- 重复互动
- 情绪体验
- 关系判断
- 节奏推进
- 边界管理

## Structure

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── framework.md
    ├── stage-model.md
    ├── conversation-operators.md
    ├── creator-patterns.md
    ├── red-flags.md
    └── case-studies.md
```

## Compatibility

当前结构按通用 skill 规范组织，方便后续接入 Claude Code、OpenClaw 等支持 skills 的代理工具。
