# 解构.Skill

“ 解构 ” 听起来很高深，但是换一种通俗的说法，其实就是“ 看透 ”的意思。

高位生物是无法共情虫子的。同样，当你站在高维视角，低维的烦恼自然烟消云散。

当情感占据上风，陷入负面情绪难以自拔时，这个skill可以帮你从无止境的自我怀疑/内耗中脱身，理性看待生活与社会中的现象、问题与困惑。

通过一套完整的流程，你将得到看待问题的“高维视角”，“看破问题”，进而“解决问题”。

### 「通过“解构”，获取对抗现实的力量吧——」


---

## 1.适合什么时候用🧐

- 遇到说不清、想不通的生活或社会事件
- 感到无力、卡住，或陷入意义危机
- 想「看透」「祛魅」，并找到下一步可以做什么

在对话里可以这样触发：

> 用 deconstruct skill 帮我看这件事：……

或直接描述困惑，Agent 会根据描述匹配本 skill。

## 2.输出结构


1. **此刻的状态** — 复述使用者当前面临的情境，可供确认
2. **动机分析** — 找出情境中的各个主体，划清各方动机、责任边界，明确不同主体的局限
3. **解构** — 运用解构技能，消解多余意义，帮助使用者理性看清面对的问题
4. **可改与不可改** — 分清什么是短期内难以改变的，什么是可以改变、且能迅速取得成效的
5. **可以试试的两件事** — 直接给出 1–2 条可实操建议

## 3.安装

### 个人 Skill（推荐）

把本仓库复制到 Cursor/Codex 个人 skills 目录：

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

### 更加便捷的版本（？）

复制本项目的地址[https://github.com/wwwwwxinchi/deconstruction-skill](https://github.com/wwwwwxinchi/deconstruction-skill.git)，发给AI，附加说明是用户级安装（所有项目可以）还是项目级安装（单个项目可用）



