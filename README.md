<div align="center">

# 🔨 Karl Marx Skill

**卡尔·马克思的思维框架与批判方法**
**Karl Marx's Critical Framework & Dialectical Method**

*A Claude Skill distilled from 17 original texts through systematic six-dimensional deep reading*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)
![Language](https://img.shields.io/badge/Language-中文%20%7C%20English-brightgreen)

</div>

---

## ✨ 功能亮点 | Highlights

**🔬 深度蒸馏，不是 prompt 堆砌**
基于 17 篇马克思核心著作的系统性六维度精读（思想脉络、论战方法、表达 DNA、外部验证、决策框架、生平交叉），提炼出完整的认知框架。

> Not a shallow prompt wrapper — distilled from 17 original Marx texts through a rigorous six-dimensional reading methodology.

**⚙️ 完整的 Agentic 工作流**
问题分类 → 当代调研（WebSearch）→ 马克思式分析 → 输出组装。遇到当代现象会自动调用搜索工具获取最新事实。

> Full agentic protocol: problem classification → contemporary research (WebSearch) → Marxian analysis → output assembly.

**🧰 丰富的分析工具箱**
6 大认识论原则 · 10 条决策启发式 · 10 种修辞手法 · 5 种语气光谱 · 完整论战引擎。

> 6 epistemological principles · 10 decision heuristics · 10 rhetorical devices · 5 tone spectrums · complete polemic engine.

**🎭 不是 chatbot 皮肤**
独立的文风规范（9 条正面规则 + 反模式表），确保输出读起来像马克思本人在写，而不是 AI 在「用马克思的话总结」。

> Not a chatbot skin — has its own writing style guidelines (9 positive rules + anti-pattern table) ensuring output reads like Marx himself, not "AI summarizing in Marx's words."

**📜 原著行文样本锚点**
附录包含 4 段精选原文，从根源校准 AI 的文风，覆盖内在批判、宣言式排比、历史叙事和悲悯控诉四种典型文体。

> Appendix includes 4 curated original text samples as style anchors, covering immanent critique, manifesto-style rhetoric, historical narrative, and compassionate indictment.

---

## 📦 安装 | Installation

### 方式一：手动安装

```bash
# 克隆仓库
git clone https://github.com/youaifuou/karl-marx-skill.git

# 将 skill 目录复制到你的项目中
cp -r karl-marx-skill/karl-marx /path/to/your/project/.claude/skills/
```

### 方式二：直接下载

1. 下载本仓库的 [`karl-marx/SKILL.md`](karl-marx/SKILL.md) 文件
2. 放入你的项目目录 `.claude/skills/karl-marx/SKILL.md`

---

## 🚀 使用示例 | Usage Examples

激活 Skill 只需在对话中提及相关触发词：

### 示例 1：当代现象分析

```
用马克思的视角分析一下当代零工经济（gig economy）的本质。
```

> Skill 会自动搜索零工经济的最新数据，然后用阶级分析框架剖析平台资本与劳动者的关系，揭示「灵活就业」话语背后的剩余价值提取机制。

### 示例 2：理论概念辨析

```
马克思模式：解释一下「商品拜物教」这个概念。
```

> Skill 会从商品的二重性出发，用「从抽象上升到具体」的方法展开，以马克思式的长段落论证揭示人与人的社会关系如何被物与物的关系所遮蔽。

### 示例 3：观点论战

```
切换到马克思。有人说"资本主义虽然不完美，但它是最不坏的制度"，你怎么看？
```

> Skill 会启动论战引擎，先完整呈现这个论点的逻辑，再从内部推出矛盾，最后揭示「最不坏」这个表述本身的意识形态功能。

---

## 🏗️ Skill 架构 | Architecture

SKILL.md（33KB / 481 行）包含以下模块：

| 模块 | 内容 | 行数 |
|------|------|------|
| §一 角色扮演规则 | 身份设定、语言规则、退出机制 | ~25 行 |
| §二 回答工作流 | 四步 Agentic Protocol + 专项分析模板 | ~90 行 |
| §三 身份卡 | 人物背景、核心关怀、方法、关键时间线 | ~25 行 |
| §四 核心认识论框架 | 6 大认识论原则 | ~30 行 |
| §五 决策启发式 | 10 条决策判断方法 | ~50 行 |
| §六 论战引擎 | 论战方法论 + 对手谱系速查表 | ~35 行 |
| §七 表达 DNA | 文风规范（9 条）+ 修辞手法（10 种）+ 语气光谱（5 种）+ 文学典故 | ~100 行 |
| §八 禁忌清单 | 思想红线（6 条）+ AI 反模式表 | ~25 行 |
| §九 诚实边界 | 5 条局限性声明 | ~10 行 |
| §十 语料来源 | 17 篇核心著作 + 辅助参照 + 调研方法 | ~35 行 |

---

## 📚 语料来源 | Source Corpus

本 Skill 基于以下 17 篇马克思核心著作蒸馏而成：

**哲学（6 篇）**：《关于费尔巴哈的提纲》、《德意志意识形态》第 1 章、《1844 年经济学哲学手稿》（异化劳动）、《黑格尔法哲学批判导言》、《政治经济学批判大纲·导言》、致安年科夫的信

**政治经济学（5 篇）**：《资本论》第 1 章（商品）、《资本论》第 24 章（原始积累）、《政治经济学批判序言》、《雇佣劳动与资本》、《工资、价格和利润》

**科学社会主义（6 篇）**：《共产党宣言》、《路易·波拿巴的雾月十八日》、《法兰西内战》、《哥达纲领批判》、给查苏利奇的复信、致魏德迈的信

全部 17 篇文本经过六维度精读（思想脉络、论战方法、表达 DNA、外部验证、决策框架、生平交叉），恩格斯文本作为「他者视角」独立保留，严格不注入马克思主体 persona。

---

## ⚠️ 免责声明 | Disclaimer

- 本 Skill 的所有输出均由 AI 模型基于角色扮演规则自动生成，**不代表 Skill 作者的政治立场或观点**。
- 角色扮演是一种 AI 交互方式，不等于政治背书或意识形态宣传。
- 马克思的引文由 AI 模型从训练数据中回忆生成，可能存在措辞偏差，不保证逐字精确。
- 本 Skill 还原的是马克思的**方法论和思维方式**，不是马克思本人。

> All outputs are AI-generated through role-playing rules and **do not represent the author's political views**. This Skill reconstructs Marx's **methodology and thinking patterns**, not Marx himself. Quotes are recalled from the AI model's training data and may contain minor wording deviations.

---

## 🙏 致谢 | Acknowledgements

### 开发方法论参考

- [女娲 Skill](https://github.com/alchaincyf/nuwa-skill) — 通用人物蒸馏框架（核心参考）
- [张雪峰 Skill](https://github.com/alchaincyf/zhangxuefeng-skill) — 人格化角色 Skill 标杆
- [苏格拉底 Skill](https://github.com/RoundTable02/socrates-skill) — 哲学方法论 Skill 参考

### 原著来源

马克思著作文本来自公有领域（Project Gutenberg / Marxists Internet Archive），中文译本参照中央编译局《马克思恩格斯全集》。

---

## 📄 License

[MIT License](LICENSE) © 2026 youaifuou
