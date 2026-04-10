<div align="center">

[简体中文](README.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [Deutsch](README_de.md) | Français | [Español](README_es.md) | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**Cadre de pensée et méthode critique de Karl Marx**

*Un Skill Claude distillé à partir de la lecture systématique en six dimensions de 17 textes fondamentaux de Marx*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ Points forts

**🔬 Distillation profonde, pas un empilement de prompts**
Construit à partir d'une lecture systématique en six dimensions de 17 textes fondamentaux de Marx (fils de pensée, méthodes polémiques, ADN expressif, validation externe, cadres décisionnels, croisements biographiques), produisant un cadre cognitif complet.

**⚙️ Workflow agentique complet**
Classification du problème → recherche contemporaine (WebSearch) → analyse marxienne → assemblage de la sortie. Invoque automatiquement les outils de recherche pour les phénomènes contemporains.

**🧰 Boîte à outils analytique riche**
6 principes épistémologiques · 10 heuristiques décisionnelles · 10 procédés rhétoriques · 5 spectres de ton · moteur polémique complet.

**🎭 Pas une simple apparence de chatbot**
Directives de style d'écriture indépendantes (9 règles positives + tableau anti-modèles) garantissant que la sortie se lit comme si Marx lui-même écrivait.

**📜 Ancres stylistiques des textes originaux**
L'annexe comprend 4 passages sélectionnés des œuvres originales de Marx pour le calibrage du style.

---

## Installation

```bash
npx skills add youaifuou/karl-marx-skill
```

Puis dans Claude Code :

> 🔴 Analyse l'économie des plateformes du point de vue de Marx
>
> 🔴 Que dirait Marx de « le capitalisme est le système le moins mauvais » ?
>
> 🔴 Passe en mode Marx et aide-moi à analyser les rapports de travail dans l'économie de plateforme

<details>
<summary>Installation manuelle</summary>

**Option 1 : Cloner le dépôt**

```bash
git clone https://github.com/youaifuou/karl-marx-skill.git
cp -r karl-marx-skill/karl-marx /chemin/vers/votre/projet/.claude/skills/
```

**Option 2 : Téléchargement direct**

1. Télécharger le fichier [`karl-marx/SKILL.md`](karl-marx/SKILL.md) et le répertoire `karl-marx/references/`
2. Les placer dans votre projet : `.claude/skills/karl-marx/`

</details>

---

## 🏗️ Architecture

SKILL.md (33 Ko / 481 lignes) contient les modules suivants :

| Module | Contenu | Lignes |
|--------|---------|--------|
| §1 Règles de jeu de rôle | Identité, règles linguistiques, mécanisme de sortie | ~25 |
| §2 Workflow de réponse | Protocole agentique en 4 étapes + modèles d'analyse | ~90 |
| §3 Carte d'identité | Contexte, préoccupations, méthode, chronologie | ~25 |
| §4 Cadre épistémologique | 6 principes épistémologiques | ~30 |
| §5 Heuristiques décisionnelles | 10 méthodes de décision | ~50 |
| §6 Moteur polémique | Méthodologie polémique + généalogie des adversaires | ~35 |
| §7 ADN expressif | Style + rhétorique + spectre tonal + allusions littéraires | ~100 |
| §8 Interdictions | Lignes rouges + tableau anti-modèles IA | ~25 |
| §9 Limites d'honnêteté | 5 déclarations de limitations | ~10 |
| §10 Corpus source | 17 textes fondamentaux + méthodologie | ~35 |

---

## 📚 Corpus source

Ce Skill est distillé à partir de 17 textes fondamentaux de Marx :

**Philosophie (6)** : Thèses sur Feuerbach · L'Idéologie allemande (ch. 1) · Manuscrits de 1844 (Travail aliéné) · Contribution à la critique de la philosophie du droit de Hegel. Introduction · Grundrisse : Introduction · Lettre à Annenkov

**Économie politique (5)** : Le Capital, t. I, ch. 1 (La Marchandise) · Le Capital, t. I, ch. 24 (L'accumulation primitive) · Préface de la Contribution à la critique de l'économie politique · Travail salarié et Capital · Salaire, prix et profit

**Socialisme scientifique (6)** : Le Manifeste du Parti communiste · Le 18 Brumaire de Louis Bonaparte · La Guerre civile en France · Critique du programme de Gotha · Lettre à Vera Zassoulitch · Lettre à Weydemeyer

Les 17 textes ont fait l'objet d'une lecture approfondie en six dimensions.

---

## ⚠️ Avertissement

- Toutes les sorties sont générées par un modèle d'IA selon des règles de jeu de rôle et **ne représentent pas les opinions politiques de l'auteur**.
- Le jeu de rôle est une méthode d'interaction avec l'IA, pas un soutien politique.
- Les citations sont rappelées des données d'entraînement et peuvent contenir de légères variations.
- Ce Skill reconstitue la **méthodologie et les modes de pensée** de Marx, pas Marx lui-même.

---

## 🙏 Remerciements

- [Nuwa Skill](https://github.com/alchaincyf/nuwa-skill) — Cadre universel de distillation de persona
- [Zhang Xuefeng Skill](https://github.com/alchaincyf/zhangxuefeng-skill) — Référence de Skill à personnalité
- [Socrate Skill](https://github.com/RoundTable02/socrates-skill) — Référence méthodologique philosophique

Textes de Marx issus du domaine public (Project Gutenberg / Marxists Internet Archive).

---

## 📄 Licence

[MIT License](LICENSE) © 2026 youaifuou
