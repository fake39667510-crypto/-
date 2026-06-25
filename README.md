# ?智慧伴读 · 阅读伴侣系统 | Wisdom Reading Companion

&gt; **不是替人读书，而是伴人读懂。**
&gt; _Not just reading for you, but reading with you until you truly understand._

---

## ? 为什么需要分层阅读？ | Why Tiered Reading?

### 痛点 | The Problem

- ❌ **读完了但记不住** — 划了满页的重点，合上书就忘了
- ❌ **看懂了但用不上** — 道理都懂，但一到真实场景就懵
- ❌ **被作者牵着走** — 跟着作者的逻辑走，但从来没想过"他说的对吗？"
- ❌ **一本书读了半年** — 越读越焦虑，越读越读不完

- ❌ **Finished but can't remember** — Highlighted the whole book, forgot everything when closing it
- ❌ **Understood but can't apply** — Got the theory, but clueless when facing real scenarios
- ❌ **Followed the author blindly** — Never asked: "Is this actually true?"
- ❌ **Half a year on one book** — The longer you read, the more anxious you get

### 我们的解决方案 | Our Solution

**智慧伴读** 是一套基于**花叔《阅读的方法》改良版**构建的**分层阅读系统**，帮你从「读完一本书」升级到「真正读懂一本书」。

_Wisdom Reading Companion is a **tiered reading system** built on the improved version of Uncle Hua's "Methods of Reading", helping you upgrade from "finishing a book" to "truly understanding a book"._

---

## ? 核心能力 | Core Capabilities

### 三级深度模式 | Three Depth Tiers

| 模式 | 流程 | 适合场景 | 预计耗时 |
|------|------|---------|---------|
| ? **轻量** Light | 狩猎法 → 苏格拉底追问 | 快速找答案、定位书中内容 | 15-30 分钟 |
| ? **标准** Standard | 狩猎法 → 费曼法 | 搞懂一个概念、暴露模糊地带 | 30-60 分钟 |
| ⚔️ **深度** Deep | 狩猎法 → 费曼法 → 华山论剑 | 验证核心观点是否经得起推敲 | 60-120 分钟 |

### 输出物 | Outputs

- ? Markdown 结构化阅读笔记 — Structured reading notes
- ? HTML 可视化阅读卡片（交互式信息图）— Interactive HTML reading cards

---

## ? 系统架构 | System Architecture

```
智慧伴读/
├── SKILL.md                        ← Bundle 入口（安装入口）
├── reading-hunting/SKILL.md        ← Stage 1：狩猎法
├── reading-feynman/SKILL.md        ← Stage 2：费曼法
├── meta-huashan-debate/SKILL.md    ← Stage 3：华山论剑
├── meta-reading-companion/SKILL.md ← Stage 4：分层阅读伴侣
└── 通用指南/
    └── 智慧伴读-通用阅读指南.md     ← 跨平台方法论（任何 AI 可用）
```

### 5 Stage 流程 | 5-Stage Workflow

```mermaid
graph LR
    A[Stage 1: 狩猎法] --&gt; B[Stage 2: 费曼法]
    B --&gt; C[Stage 3: 华山论剑]
    C --&gt; D[Stage 4: 阅读伴侣编排]
    D --&gt; E[Stage 5: 可视化输出]
```

---

## ? 安装 | Installation

### OpenSquilla 用户 | OpenSquilla Users

```bash
# 从 ClawHub 安装
opensquilla skills install 智慧伴读

# 或从本地安装
git clone https://github.com/fake39667510-crypto/wisdom-reading-companion.git
opensquilla skills publish ./智慧伴读
```

### 其他 AI 用户 | Other AI Users (Claude Code / ChatGPT / Cursor)

阅读 [`通用指南/智慧伴读-通用阅读指南.md`](./通用指南/智慧伴读-通用阅读指南.md) —— 这是纯方法论，不依赖任何框架，可直接粘贴给任何 AI 助手使用。

_Check [`通用指南/智慧伴读-通用阅读指南.md`](./通用指南/智慧伴读-通用阅读指南.md) for framework-agnostic reading methodology that works with any AI assistant._

---

## ? 快速开始 | Quick Start

### 方式一：全自动（OpenSquilla）

```
用户：帮我分层阅读《有限与无限的游戏》，我的问题是"如何成为无限游戏玩家"
系统：自动运行 12 步 DAG → 输出笔记 + 卡片
```

### 方式二：手动（任何 AI） | Manual (Any AI)

参考 [`通用指南/智慧伴读-通用阅读指南.md`](./通用指南/智慧伴读-通用阅读指南.md) 中的提示词模板，复制给任何 AI 即可。

_Copy the prompt templates from the guide to any AI assistant._

---

## ? 方法论来源 | Methodology Sources

- **花叔《阅读的方法》** — 核心阅读框架 _Core reading framework_
- **James P. Carse《有限与无限的游戏》** — 辩论素材 _Debate material_
- **Richard Feynman** — 费曼学习法（6 岁解释测试）_Feynman Technique_
- **Charlie Munger** — 跨学科思维模型 _Multidisciplinary mental models_
- **Naval Ravikant** — 永恒游戏哲学 _Infinite game philosophy_

---

## ? 许可证 | License

MIT

---

## ? 系统信息 | System Info

- **系统名称**：智慧伴读（2026-06-24 命名）_Named: Wisdom Reading Companion_
- **版本**：v1.0.0 _Version_
- **平台**：OpenSquilla（核心）+ 通用（方法论）_Platform: OpenSquilla (core) + Universal (methodology)_
