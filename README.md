# 解构 Skill

Cursor Agent Skill：帮你理性看待生活与社会中的现象、问题与困惑。

先看清本质，再松开过度附着的意义，最后给出可执行的小步——不灌鸡汤，不替你做决定。

## 适合什么时候用

- 遇到说不清、想不通的生活或社会事件
- 感到无力、卡住，或陷入意义危机
- 想「看透」「祛魅」，并找到下一步可以做什么

在对话里可以这样触发：

> 用 deconstruct skill 帮我看这件事：……

或直接描述困惑，Agent 会根据描述匹配本 skill。

## 输出结构

一次说完，按固定顺序：

1. **此刻的状态** — 温柔、专业地描述你可能的情境与反应，并请你确认
2. **动机分析** — 划清各方动机、责任边界与局限（冷静、不带情绪）
3. **解构** — 用白话讲清机制；专有名词最多一个
4. **可改与不可改** — 分清短期难改的，和你可以动的
5. **可以试试的两件事** — 直接给出 1–2 条可操作建议，不问「要不要」

## 安装

### 个人 Skill（推荐）

把本仓库复制到 Cursor 个人 skills 目录：

```powershell
New-Item -ItemType Directory -Force -Path "$HOME\.cursor\skills\deconstruct"
Copy-Item ".\SKILL.md",".\examples.md" "$HOME\.cursor\skills\deconstruct\" -Force
```

路径示例：

```text
C:\Users\<你的用户名>\.cursor\skills\deconstruct\
├── SKILL.md
└── examples.md
```

### 项目 Skill

复制到任意项目的：

```text
.cursor/skills/deconstruct/
```

安装后**新开一个 Agent 对话**再测。

## 文件说明

| 文件 | 作用 |
|------|------|
| `SKILL.md` | 主流程、语气与输出模板 |
| `examples.md` | 职场内卷、亲密关系、社会新闻三类完整示例 |
| `README.md` | 本说明 |

## 边界

本 skill 只做陪伴性梳理，**不替代**心理咨询或医疗。若出现自伤意念、急性创伤仍处危险环境、或严重功能受损，请优先寻求专业帮助。

## License

可按个人或项目需要自由使用与修改。
