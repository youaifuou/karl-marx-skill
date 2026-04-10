<div align="center">

[简体中文](README.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | Deutsch | [Français](README_fr.md) | [Español](README_es.md) | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**Karl Marx' Denkrahmen und kritische Methode**

*Ein Claude Skill, destilliert aus der systematischen sechsdimensionalen Lektüre von 17 Kerntexten von Marx*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ Highlights

**🔬 Tiefendestillation, kein Prompt-Stacking**
Aufgebaut auf einer systematischen sechsdimensionalen Lektüre von 17 Marx-Kerntexten (Gedankenstränge, Polemik-Methoden, Ausdrucks-DNA, externe Validierung, Entscheidungsrahmen, biographische Schnittstellen) — ein vollständiges kognitives Framework.

**⚙️ Vollständiger agentischer Workflow**
Problemklassifikation → Gegenwartsrecherche (WebSearch) → Marx'sche Analyse → Ausgabemontage. Bei zeitgenössischen Phänomenen werden automatisch Recherchetools aufgerufen.

**🧰 Reichhaltiger Analyse-Werkzeugkasten**
6 erkenntnistheoretische Prinzipien · 10 Entscheidungsheuristiken · 10 rhetorische Mittel · 5 Tonlagen · vollständige Polemik-Engine.

**🎭 Keine Chatbot-Hülle**
Eigenständige Stilrichtlinien (9 positive Regeln + Anti-Muster-Tabelle) stellen sicher, dass die Ausgabe sich liest, als würde Marx selbst schreiben — nicht als „KI, die in Marx' Worten zusammenfasst."

**📜 Originaltext-Stilanker**
Der Anhang enthält 4 ausgewählte Passagen aus Marx' Originaltexten zur Stilkalibrierung: immanente Kritik, Manifest-Rhetorik, historische Erzählung und mitfühlende Anklage.

---

## Installation

```bash
npx skills add youaifuou/karl-marx-skill
```

Dann in Claude Code:

> 🔴 Analysiere die Gig Economy aus Marx' Perspektive
>
> 🔴 Was würde Marx zu „Kapitalismus ist das am wenigsten schlechte System" sagen?
>
> 🔴 Wechsle zu Marx und hilf mir, die Arbeitsverhältnisse in der Plattformökonomie zu analysieren

<details>
<summary>Manuelle Installation</summary>

**Option 1: Repository klonen**

```bash
git clone https://github.com/youaifuou/karl-marx-skill.git
cp -r karl-marx-skill/karl-marx /pfad/zu/deinem/projekt/.claude/skills/
```

**Option 2: Direkter Download**

1. Die Datei [`karl-marx/SKILL.md`](karl-marx/SKILL.md) und das Verzeichnis `karl-marx/references/` herunterladen
2. In dein Projektverzeichnis legen: `.claude/skills/karl-marx/`

</details>

---

## 🏗️ Architektur

SKILL.md (33KB / 481 Zeilen) enthält folgende Module:

| Modul | Inhalt | Zeilen |
|-------|--------|--------|
| §1 Rollenspiel-Regeln | Identität, Sprachregeln, Ausstiegsmechanismus | ~25 |
| §2 Antwort-Workflow | 4-Schritte Agentic Protocol + spezialisierte Analysevorlagen | ~90 |
| §3 Identitätskarte | Hintergrund, Kernanliegen, Methode, Zeitleiste | ~25 |
| §4 Erkenntnistheoretisches Framework | 6 erkenntnistheoretische Prinzipien | ~30 |
| §5 Entscheidungsheuristiken | 10 Entscheidungsmethoden | ~50 |
| §6 Polemik-Engine | Polemik-Methodik + Gegner-Genealogie | ~35 |
| §7 Ausdrucks-DNA | Stil + Rhetorik + Tonlagen + literarische Anspielungen | ~100 |
| §8 Verbotsliste | Rote Linien + KI-Anti-Muster | ~25 |
| §9 Ehrlichkeitsgrenzen | 5 Einschränkungen | ~10 |
| §10 Quellenkorpus | 17 Kerntexte + Forschungsmethodik | ~35 |

---

## 📚 Quellenkorpus

Dieser Skill wurde aus 17 Marx-Kerntexten destilliert:

**Philosophie (6)**: Thesen über Feuerbach · Die deutsche Ideologie (Kap. 1) · Ökonomisch-philosophische Manuskripte aus dem Jahre 1844 (Entfremdete Arbeit) · Zur Kritik der Hegelschen Rechtsphilosophie. Einleitung · Grundrisse: Einleitung · Brief an Annenkow

**Politische Ökonomie (5)**: Das Kapital Bd. I, Kap. 1 (Die Ware) · Das Kapital Bd. I, Kap. 24 (Die sogenannte ursprüngliche Akkumulation) · Vorwort zur Kritik der politischen Ökonomie · Lohnarbeit und Kapital · Lohn, Preis und Profit

**Wissenschaftlicher Sozialismus (6)**: Manifest der Kommunistischen Partei · Der achtzehnte Brumaire des Louis Bonaparte · Der Bürgerkrieg in Frankreich · Kritik des Gothaer Programms · Brief an Vera Sassulitsch · Brief an Weydemeyer

Alle 17 Texte wurden einer sechsdimensionalen Tiefenlektüre unterzogen.

---

## ⚠️ Haftungsausschluss

- Alle Ausgaben werden von einem KI-Modell auf Basis von Rollenspielregeln generiert und **repräsentieren nicht die politischen Ansichten oder Positionen des Autors**.
- Rollenspiel ist eine KI-Interaktionsmethode, keine politische Unterstützung oder ideologische Propaganda.
- Zitate werden aus den Trainingsdaten des KI-Modells erinnert und können leichte Abweichungen enthalten.
- Dieser Skill rekonstruiert Marx' **Methodologie und Denkweise**, nicht Marx selbst.

---

## 🙏 Danksagung

### Methodische Referenzen

- [Nuwa Skill](https://github.com/alchaincyf/nuwa-skill) — Universelles Persona-Destillations-Framework
- [Zhang Xuefeng Skill](https://github.com/alchaincyf/zhangxuefeng-skill) — Persona-basierter Skill-Benchmark
- [Sokrates Skill](https://github.com/RoundTable02/socrates-skill) — Philosophischer Methodik-Skill

### Originaltextquellen

Marx' Werke aus dem öffentlichen Bereich (Project Gutenberg / Marxists Internet Archive).

---

## 📄 Lizenz

[MIT License](LICENSE) © 2026 youaifuou
