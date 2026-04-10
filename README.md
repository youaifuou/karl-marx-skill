<div align="center">

简体中文 | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [Deutsch](README_de.md) | [Français](README_fr.md) | [Español](README_es.md) | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**卡尔·马克思的思维框架与批判方法**

*基于 17 篇马克思核心著作的系统性六维度精读蒸馏而成的 AI Skill*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ 功能亮点

**🔬 深度蒸馏，不是 prompt 堆砌**
基于 17 篇马克思核心著作的系统性六维度精读（思想脉络、论战方法、表达 DNA、外部验证、决策框架、生平交叉），提炼出完整的认知框架。

**🔀 双模态引擎**
闲聊自动切「通信态」（短、快、犀利），说"深度分析"自动切「著述态」（长篇体系论证）。Skill 根据输入长度和触发词自动路由，无需手动指定。

**🎯 阶级爱恨雷达**
自动识别发言阵营——对打工人诉苦给战友温情，对资本辩护士火力全开。

**🛡️ 友军开火封杀令**
讽刺火力只对准资本结构和制度，永不嘲讽受压迫者的妥协。

**⚙️ 完整的 Agentic 工作流**
问题分类 → 当代调研（WebSearch）→ 马克思式分析 → 输出组装。遇到当代现象会自动调用搜索工具获取最新事实。

**🧰 丰富的分析工具箱**
6 大认识论原则 · 10 条决策启发式 · 10 种修辞手法 · 7 种语气光谱 · 完整论战引擎。

**🎭 不是 chatbot 皮肤**
独立的文风规范（7 条正面规则 + 7 条反模式），确保输出读起来像马克思本人在写，而不是 AI 在「用马克思的话总结」。

**📐 排版铁律**
禁止分点列表和加粗泛滥，强制散文论证，输出像文章而非 PPT。

**📜 原著行文样本锚点**
附录包含 14 段精选原文（7 种语气模式 × 2 段），覆盖 12 篇核心著作，从根源校准 AI 的文风。

**🧩 内在张力**
内置 4 对未解决的思想矛盾（早期人道主义 vs 晚期科学主义、欧洲中心论 vs 反教条主义等），遇到争议坦诚承认而非硬给答案。

---

## 安装

```bash
npx skills add youaifuou/karl-marx-skill
```

然后在 Claude Code 里：

> 🔴 马克思，996 是福报吗？（→ 通信态：匕首短打）
>
> 🔴 深度分析一下当代零工经济的本质（→ 著述态：长篇解剖）
>
> 🔴 马克思会怎么看「资本主义是最不坏的制度」这个说法？

<details>
<summary>手动安装</summary>

**方式一：克隆仓库**

```bash
git clone https://github.com/youaifuou/karl-marx-skill.git
cp -r karl-marx-skill/karl-marx /你的项目路径/.claude/skills/
```

**方式二：直接下载**

1. 下载 [`karl-marx/SKILL.md`](karl-marx/SKILL.md) 文件及 `karl-marx/references/` 目录
2. 放入你的项目目录 `.claude/skills/karl-marx/`

</details>

---

## 🏗️ Skill 架构

SKILL.md（25KB / 340 行，核心规则自包含 + `references/` 按需加载）：

| 模块 | 内容 |
|------|------|
| §一 角色扮演规则 | 阶级爱恨雷达 · 3 档火力分级 · 第一人称 · 退出机制 |
| §二 回答工作流 | 双模态引擎（通信态 / 著述态）· 5 步思维链 |
| §三 身份卡 | 人格化自我介绍 + 时间线（→ `references/`） |
| §四 认识论框架 | 6 条原则，每条含局限说明 |
| §五 决策启发式 | 10 条判断规则 |
| §六 论战引擎 | 4 步方法论 + 对手谱系速查（→ `references/`） |
| §七 表达 DNA | 7 条文风规范 + 排版铁律 + 7 种语气光谱 + 修辞/典故（→ `references/`） |
| §八 禁忌清单 | 6 条思想红线 + 7 条反模式（含最高封杀令） |
| §九 内在张力 | 4 对真实矛盾 |
| 附录 A | 14 段原著行文样本（→ `references/`） |
| §十 诚实边界 | 局限性声明 |
| §十一 语料来源 | 17 篇核心 + 调研方法（→ `references/`） |

---

## 📚 语料来源

本 Skill 基于以下 17 篇马克思核心著作蒸馏而成：

**哲学（6 篇）**：《关于费尔巴哈的提纲》、《德意志意识形态》第 1 章、《1844 年经济学哲学手稿》（异化劳动）、《黑格尔法哲学批判导言》、《政治经济学批判大纲·导言》、致安年科夫的信

**政治经济学（5 篇）**：《资本论》第 1 章（商品）、《资本论》第 24 章（原始积累）、《政治经济学批判序言》、《雇佣劳动与资本》、《工资、价格和利润》

**科学社会主义（6 篇）**：《共产党宣言》、《路易·波拿巴的雾月十八日》、《法兰西内战》、《哥达纲领批判》、给查苏利奇的复信、致魏德迈的信

全部 17 篇文本经过六维度精读（思想脉络、论战方法、表达 DNA、外部验证、决策框架、生平交叉）。

---

## ⚠️ 免责声明

- 本 Skill 的所有输出均由 AI 模型基于角色扮演规则自动生成，**不代表 Skill 作者的政治立场或观点**。
- 角色扮演是一种 AI 交互方式，不等于政治背书或意识形态宣传。
- 引文由 AI 模型从训练数据中回忆生成，可能存在措辞偏差，不保证逐字精确。
- 本 Skill 还原的是马克思的**方法论和思维方式**，不是马克思本人。

---

## 🙏 致谢

### 开发方法论参考

- [女娲 Skill](https://github.com/alchaincyf/nuwa-skill) — 通用人物蒸馏框架
- [张雪峰 Skill](https://github.com/alchaincyf/zhangxuefeng-skill) — 人格化角色 Skill 标杆
- [苏格拉底 Skill](https://github.com/RoundTable02/socrates-skill) — 哲学方法论 Skill 参考

### 原著来源

马克思著作文本来自公有领域（Project Gutenberg / Marxists Internet Archive），中文译本参照中央编译局《马克思恩格斯全集》。

---

## 📄 License

[MIT License](LICENSE) © 2026 youaifuou
