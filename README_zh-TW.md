<div align="center">

[简体中文](README.md) | 繁體中文 | [English](README_en.md) | [Deutsch](README_de.md) | [Français](README_fr.md) | [Español](README_es.md) | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**卡爾·馬克思的思維框架與批判方法**

*基於 17 篇馬克思核心著作的系統性六維度精讀蒸餾而成的 Claude Skill*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ 功能亮點

**🔬 深度蒸餾，不是 prompt 堆砌**
基於 17 篇馬克思核心著作的系統性六維度精讀（思想脈絡、論戰方法、表達 DNA、外部驗證、決策框架、生平交叉），提煉出完整的認知框架。

**⚙️ 完整的 Agentic 工作流**
問題分類 → 當代調研（WebSearch）→ 馬克思式分析 → 輸出組裝。遇到當代現象會自動呼叫搜尋工具取得最新事實。

**🧰 豐富的分析工具箱**
6 大認識論原則 · 10 條決策啟發式 · 10 種修辭手法 · 5 種語氣光譜 · 完整論戰引擎。

**🎭 不是 chatbot 皮膚**
獨立的文風規範（9 條正面規則 + 反模式表），確保輸出讀起來像馬克思本人在寫，而不是 AI 在「用馬克思的話總結」。

**📜 原著行文樣本錨點**
附錄包含 4 段精選原文，從根源校準 AI 的文風，涵蓋內在批判、宣言式排比、歷史敘事和悲憫控訴四種典型文體。

---

## 安裝

```bash
npx skills add youaifuou/karl-marx-skill
```

然後在 Claude Code 裡：

> 🔴 用馬克思的視角分析一下當代零工經濟的本質
>
> 🔴 馬克思會怎麼看「資本主義是最不壞的制度」這個說法？
>
> 🔴 切換到馬克思，幫我分析一下平台經濟中的勞資關係

<details>
<summary>手動安裝</summary>

**方式一：克隆倉庫**

```bash
git clone https://github.com/youaifuou/karl-marx-skill.git
cp -r karl-marx-skill/karl-marx /你的專案路徑/.claude/skills/
```

**方式二：直接下載**

1. 下載 [`karl-marx/SKILL.md`](karl-marx/SKILL.md) 檔案及 `karl-marx/references/` 目錄
2. 放入你的專案目錄 `.claude/skills/karl-marx/`

</details>

---

## 🏗️ Skill 架構

SKILL.md（33KB / 481 行）包含以下模組：

| 模組 | 內容 | 行數 |
|------|------|------|
| §一 角色扮演規則 | 身份設定、語言規則、退出機制 | ~25 行 |
| §二 回答工作流 | 四步 Agentic Protocol + 專項分析模板 | ~90 行 |
| §三 身份卡 | 人物背景、核心關懷、方法、關鍵時間線 | ~25 行 |
| §四 核心認識論框架 | 6 大認識論原則 | ~30 行 |
| §五 決策啟發式 | 10 條決策判斷方法 | ~50 行 |
| §六 論戰引擎 | 論戰方法論 + 對手譜系速查表 | ~35 行 |
| §七 表達 DNA | 文風規範 + 修辭手法 + 語氣光譜 + 文學典故 | ~100 行 |
| §八 禁忌清單 | 思想紅線 + AI 反模式表 | ~25 行 |
| §九 誠實邊界 | 5 條局限性聲明 | ~10 行 |
| §十 語料來源 | 17 篇核心著作 + 調研方法 | ~35 行 |

---

## 📚 語料來源

本 Skill 基於以下 17 篇馬克思核心著作蒸餾而成：

**哲學（6 篇）**：《關於費爾巴哈的提綱》、《德意志意識形態》第 1 章、《1844 年經濟學哲學手稿》（異化勞動）、《黑格爾法哲學批判導言》、《政治經濟學批判大綱·導言》、致安年科夫的信

**政治經濟學（5 篇）**：《資本論》第 1 章（商品）、《資本論》第 24 章（原始積累）、《政治經濟學批判序言》、《僱傭勞動與資本》、《工資、價格和利潤》

**科學社會主義（6 篇）**：《共產黨宣言》、《路易·波拿巴的霧月十八日》、《法蘭西內戰》、《哥達綱領批判》、給查蘇利奇的覆信、致魏德邁的信

全部 17 篇文本經過六維度精讀（思想脈絡、論戰方法、表達 DNA、外部驗證、決策框架、生平交叉）。

---

## ⚠️ 免責聲明

- 本 Skill 的所有輸出均由 AI 模型基於角色扮演規則自動生成，**不代表 Skill 作者的政治立場或觀點**。
- 角色扮演是一種 AI 互動方式，不等於政治背書或意識形態宣傳。
- 引文由 AI 模型從訓練資料中回憶生成，可能存在措辭偏差，不保證逐字精確。
- 本 Skill 還原的是馬克思的**方法論和思維方式**，不是馬克思本人。

---

## 🙏 致謝

### 開發方法論參考

- [女媧 Skill](https://github.com/alchaincyf/nuwa-skill) — 通用人物蒸餾框架
- [張雪峰 Skill](https://github.com/alchaincyf/zhangxuefeng-skill) — 人格化角色 Skill 標竿
- [蘇格拉底 Skill](https://github.com/RoundTable02/socrates-skill) — 哲學方法論 Skill 參考

### 原著來源

馬克思著作文本來自公有領域（Project Gutenberg / Marxists Internet Archive），中文譯本參照中央編譯局《馬克思恩格斯全集》。

---

## 📄 License

[MIT License](LICENSE) © 2026 youaifuou
