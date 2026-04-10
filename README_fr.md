<div align="center">

[简体中文](README.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [Deutsch](README_de.md) | Français | [Español](README_es.md) | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**Cadre de pensée et méthode critique de Karl Marx**

*Un Skill IA distillé à partir de la lecture systématique en six dimensions de 17 textes fondamentaux de Marx*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ Points forts

**🔬 Distillation profonde, pas un empilement de prompts**
Construit à partir d'une lecture systématique en six dimensions de 17 textes fondamentaux de Marx (fils de pensée, méthodes polémiques, ADN expressif, validation externe, cadres décisionnels, croisements biographiques), produisant un cadre cognitif complet.

**🔀 Moteur bimodal**
En conversation courante, bascule automatiquement en « mode correspondance » (bref, incisif, percutant) ; au mot-clé « analyse approfondie », bascule en « mode traité » (argumentation systématique). Le routage est automatique selon la longueur de l'entrée et les mots déclencheurs.

**🎯 Radar d'affinité de classe**
Détecte automatiquement le camp de l'utilisateur — empathie fraternelle pour les travailleurs en souffrance, feu critique total pour les apologistes du capital.

**🛡️ Interdiction du tir ami**
Le feu satirique ne cible que les structures du capital et les institutions, jamais les compromis des opprimés.

**⚙️ Workflow agentique complet**
Classification du problème → recherche contemporaine (WebSearch) → analyse marxienne → assemblage de la sortie. Invoque automatiquement les outils de recherche pour les phénomènes contemporains.

**🧰 Boîte à outils analytique riche**
6 principes épistémologiques · 10 heuristiques décisionnelles · 10 procédés rhétoriques · 7 spectres de ton · moteur polémique complet.

**🎭 Pas une simple apparence de chatbot**
Directives de style indépendantes (7 règles positives + 7 anti-modèles) garantissant que la sortie se lit comme si Marx lui-même écrivait.

**📐 Discipline typographique**
Les listes à puces et l'abus de gras sont interdits. L'argumentation en prose est imposée — la sortie se lit comme un article, pas comme un diaporama.

**📜 Ancres stylistiques des textes originaux**
L'annexe comprend 14 passages sélectionnés (7 modes tonaux × 2 passages) de 12 œuvres fondamentales pour le calibrage du style.

**🧩 Tensions internes**
4 paires de contradictions intellectuelles non résolues (ex. : humanisme précoce vs. scientisme tardif). Admet honnêtement les controverses plutôt que de forcer une fausse certitude.

---

## Installation

```bash
npx skills add youaifuou/karl-marx-skill
```

Puis dans Claude Code :

> 🔴 Marx, « 996 est une bénédiction » ? (→ mode correspondance : frappe rapide)
>
> 🔴 Analyse en profondeur l'économie de plateforme (→ mode traité : dissection complète)
>
> 🔴 Que dirait Marx de « le capitalisme est le système le moins mauvais » ?

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

SKILL.md (25 Ko / 340 lignes, règles cœur autonomes + `references/` chargées à la demande) :

| Module | Contenu |
|--------|---------|
| §1 Règles de jeu de rôle | Radar d'affinité de classe · contrôle de feu à 3 niveaux · première personne · mécanisme de sortie |
| §2 Workflow de réponse | Moteur bimodal (correspondance / traité) · chaîne de pensée en 5 étapes |
| §3 Carte d'identité | Auto-présentation du personnage + chronologie (→ `references/`) |
| §4 Cadre épistémologique | 6 principes, chacun avec limites déclarées |
| §5 Heuristiques décisionnelles | 10 règles de jugement |
| §6 Moteur polémique | Méthodologie en 4 étapes + généalogie des adversaires (→ `references/`) |
| §7 ADN expressif | 7 règles de style + discipline typographique + 7 spectres tonaux + rhétorique/allusions (→ `references/`) |
| §8 Interdictions | 6 lignes rouges + 7 anti-modèles (incl. interdiction du tir ami) |
| §9 Tensions internes | 4 paires de contradictions réelles |
| Annexe A | 14 échantillons de style original (→ `references/`) |
| §10 Limites d'honnêteté | Déclarations de limitations |
| §11 Corpus source | 17 textes fondamentaux + méthodologie (→ `references/`) |

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

### Références méthodologiques

- [Nuwa Skill](https://github.com/alchaincyf/nuwa-skill) — Cadre universel de distillation de persona
- [Zhang Xuefeng Skill](https://github.com/alchaincyf/zhangxuefeng-skill) — Référence de Skill à personnalité
- [Socrate Skill](https://github.com/RoundTable02/socrates-skill) — Référence méthodologique philosophique

### Sources des textes originaux

Textes de Marx issus du domaine public (Project Gutenberg / Marxists Internet Archive).

---

## 📄 Licence

[MIT License](LICENSE) © 2026 youaifuou
