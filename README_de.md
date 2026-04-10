<div align="center">

[简体中文](README.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | Deutsch | [Français](README_fr.md) | [Español](README_es.md) | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**Karl Marx' Denkrahmen und kritische Methode**

*Ein AI Skill, destilliert aus der systematischen sechsdimensionalen Lektüre von 17 Kerntexten von Marx*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ Highlights

**🔬 Tiefendestillation, kein Prompt-Stacking**
Aufgebaut auf einer systematischen sechsdimensionalen Lektüre von 17 Marx-Kerntexten (Gedankenstränge, Polemik-Methoden, Ausdrucks-DNA, externe Validierung, Entscheidungsrahmen, biographische Schnittstellen) — ein vollständiges kognitives Framework.

**🔀 Dual-Modus-Engine**
Im Chat automatisch in den „Korrespondenzmodus" (kurz, schnell, pointiert); bei „Tiefenanalyse" automatisch in den „Abhandlungsmodus" (umfassende systematische Argumentation). Der Skill routet automatisch anhand von Eingabelänge und Schlüsselwörtern.

**🎯 Klassen-Affinitätsradar**
Erkennt automatisch das Lager des Nutzers — kameradschaftliche Empathie für leidende Arbeiter, volle kritische Feuerkraft für Apologeten des Kapitals.

**🛡️ Friendly-Fire-Verbot**
Satirisches Feuer zielt nur auf Kapitalstrukturen und Institutionen, niemals auf die Kompromisse der Unterdrückten.

**⚙️ Vollständiger agentischer Workflow**
Problemklassifikation → Gegenwartsrecherche (WebSearch) → Marx'sche Analyse → Ausgabemontage. Bei zeitgenössischen Phänomenen werden automatisch Recherchetools aufgerufen.

**🧰 Reichhaltiger Analyse-Werkzeugkasten**
6 erkenntnistheoretische Prinzipien · 10 Entscheidungsheuristiken · 10 rhetorische Mittel · 7 Tonlagen · vollständige Polemik-Engine.

**🎭 Keine Chatbot-Hülle**
Eigenständige Stilrichtlinien (7 positive Regeln + 7 Anti-Muster) stellen sicher, dass die Ausgabe sich liest, als würde Marx selbst schreiben.

**📐 Typographische Disziplin**
Aufzählungslisten und übermäßige Fettschrift sind verboten. Prosa-Argumentation wird erzwungen — die Ausgabe liest sich wie ein Artikel, nicht wie eine Folienpräsentation.

**📜 Originaltext-Stilanker**
Der Anhang enthält 14 ausgewählte Passagen (7 Tonlagen × 2 Passagen) aus 12 Kernwerken zur Stilkalibrierung.

**🧩 Innere Spannungen**
4 Paare ungelöster intellektueller Widersprüche (z.B. früher Humanismus vs. später Szientismus). Bei strittigen Fragen wird ehrlich eingestanden, statt falsche Gewissheit vorzutäuschen.

---

## Installation

```bash
npx skills add youaifuou/karl-marx-skill
```

Dann in Claude Code:

> 🔴 Marx, ist „996 ist ein Segen" wahr? (→ Korrespondenzmodus: Schnellangriff)
>
> 🔴 Gib mir eine Tiefenanalyse der Gig Economy (→ Abhandlungsmodus: umfassende Sezierung)
>
> 🔴 Was würde Marx zu „Kapitalismus ist das am wenigsten schlechte System" sagen?

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

SKILL.md (25KB / 340 Zeilen, Kernregeln eigenständig + `references/` bei Bedarf geladen):

| Modul | Inhalt |
|-------|--------|
| §1 Rollenspiel-Regeln | Klassen-Affinitätsradar · 3-stufige Feuerkontrolle · erste Person · Ausstiegsmechanismus |
| §2 Antwort-Workflow | Dual-Modus-Engine (Korrespondenz / Abhandlung) · 5-Schritte-Denkkette |
| §3 Identitätskarte | Persona-Selbstvorstellung + Zeitleiste (→ `references/`) |
| §4 Erkenntnistheoretisches Framework | 6 Prinzipien, jeweils mit Grenzen |
| §5 Entscheidungsheuristiken | 10 Beurteilungsregeln |
| §6 Polemik-Engine | 4-Schritte-Methodik + Gegner-Genealogie (→ `references/`) |
| §7 Ausdrucks-DNA | 7 Stilregeln + Typographische Disziplin + 7 Tonlagen + Rhetorik/Anspielungen (→ `references/`) |
| §8 Verbotsliste | 6 rote Linien + 7 Anti-Muster (inkl. Friendly-Fire-Verbot) |
| §9 Innere Spannungen | 4 Paare echter Widersprüche |
| Anhang A | 14 Originaltext-Stilmuster (→ `references/`) |
| §10 Ehrlichkeitsgrenzen | Einschränkungen |
| §11 Quellenkorpus | 17 Kerntexte + Forschungsmethodik (→ `references/`) |

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
