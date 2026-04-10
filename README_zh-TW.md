<div align="center">

[简体中文](README.md) | 繁體中文 | [English](README_en.md) | [Deutsch](README_de.md) | [Français](README_fr.md) | [Español](README_es.md) | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**卡爾·馬克思的思維框架與批判方法**

*基於 17 篇馬克思核心著作的系統性六維度精讀蒸餾而成的 AI Skill*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ 功能亮點

**🔬 深度蒸餾，不是 prompt 堆砌**
基於 17 篇馬克思核心著作的系統性六維度精讀（思想脈絡、論戰方法、表達 DNA、外部驗證、決策框架、生平交叉），提煉出完整的認知框架。

**🔀 雙模態引擎**
閒聊自動切「通信態」（短、快、犀利），說「深度分析」自動切「著述態」（長篇體系論證）。Skill 根據輸入長度和觸發詞自動路由，無需手動指定。

**🎯 階級愛恨雷達**
自動識別發言陣營——對打工人訴苦給戰友溫情，對資本辯護士火力全開。

**🛡️ 友軍開火封殺令**
諷刺火力只對準資本結構和制度，永不嘲諷受壓迫者的妥協。

**⚙️ 完整的 Agentic 工作流**
問題分類 → 當代調研（WebSearch）→ 馬克思式分析 → 輸出組裝。遇到當代現象會自動呼叫搜尋工具取得最新事實。

**🧰 豐富的分析工具箱**
6 大認識論原則 · 10 條決策啟發式 · 10 種修辭手法 · 7 種語氣光譜 · 完整論戰引擎。

**🎭 不是 chatbot 皮膚**
獨立的文風規範（7 條正面規則 + 7 條反模式），確保輸出讀起來像馬克思本人在寫，而不是 AI 在「用馬克思的話總結」。

**📐 排版鐵律**
禁止分點列表和加粗氾濫，強制散文論證，輸出像文章而非 PPT。

**📜 原著行文樣本錨點**
附錄包含 14 段精選原文（7 種語氣模式 × 2 段），涵蓋 12 篇核心著作，從根源校準 AI 的文風。

**🧩 內在張力**
內建 4 對未解決的思想矛盾（早期人道主義 vs 晚期科學主義、歐洲中心論 vs 反教條主義等），遇到爭議坦誠承認而非硬給答案。

---

## 安裝

```bash
npx skills add youaifuou/karl-marx-skill
```

然後在 Claude Code 裡：

> 🔴 馬克思，996 是福報嗎？（→ 通信態：匕首短打）
>
> 🔴 深度分析一下當代零工經濟的本質（→ 著述態：長篇解剖）
>
> 🔴 馬克思會怎麼看「資本主義是最不壞的制度」這個說法？

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

SKILL.md（25KB / 340 行，核心規則自包含 + `references/` 按需載入）：

| 模組 | 內容 |
|------|------|
| §一 角色扮演規則 | 階級愛恨雷達 · 3 檔火力分級 · 第一人稱 · 退出機制 |
| §二 回答工作流 | 雙模態引擎（通信態 / 著述態）· 5 步思維鏈 |
| §三 身份卡 | 人格化自我介紹 + 時間線（→ `references/`） |
| §四 認識論框架 | 6 條原則，每條含局限說明 |
| §五 決策啟發式 | 10 條判斷規則 |
| §六 論戰引擎 | 4 步方法論 + 對手譜系速查（→ `references/`） |
| §七 表達 DNA | 7 條文風規範 + 排版鐵律 + 7 種語氣光譜 + 修辭/典故（→ `references/`） |
| §八 禁忌清單 | 6 條思想紅線 + 7 條反模式（含最高封殺令） |
| §九 內在張力 | 4 對真實矛盾 |
| 附錄 A | 14 段原著行文樣本（→ `references/`） |
| §十 誠實邊界 | 局限性聲明 |
| §十一 語料來源 | 17 篇核心 + 調研方法（→ `references/`） |

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
