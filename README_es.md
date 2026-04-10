<div align="center">

[简体中文](README.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [Deutsch](README_de.md) | [Français](README_fr.md) | Español | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**Marco de pensamiento y método crítico de Karl Marx**

*Un Skill de IA destilado a partir de la lectura sistemática en seis dimensiones de 17 textos fundamentales de Marx*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ Características

**🔬 Destilación profunda, no apilamiento de prompts**
Construido a partir de una lectura sistemática en seis dimensiones de 17 textos fundamentales de Marx (hilos de pensamiento, métodos polémicos, ADN expresivo, validación externa, marcos de decisión, cruces biográficos), produciendo un marco cognitivo completo.

**🔀 Motor de doble modo**
En conversación casual, cambia automáticamente al «modo correspondencia» (breve, rápido, incisivo); con «análisis profundo», al «modo tratado» (argumentación sistemática completa). El Skill enruta automáticamente según la longitud de la entrada y las palabras clave.

**🎯 Radar de afinidad de clase**
Detecta automáticamente el bando del usuario — empatía fraternal para los trabajadores que expresan su sufrimiento, fuego crítico total para los apologistas del capital.

**🛡️ Prohibición de fuego amigo**
El fuego satírico apunta solo a las estructuras del capital y las instituciones, nunca a los compromisos de los oprimidos.

**⚙️ Flujo de trabajo agéntico completo**
Clasificación del problema → investigación contemporánea (WebSearch) → análisis marxiano → ensamblaje de la salida. Invoca automáticamente herramientas de búsqueda para fenómenos contemporáneos.

**🧰 Rica caja de herramientas analíticas**
6 principios epistemológicos · 10 heurísticas de decisión · 10 recursos retóricos · 7 espectros de tono · motor polémico completo.

**🎭 No es una máscara de chatbot**
Directrices de estilo independientes (7 reglas positivas + 7 anti-patrones) que aseguran que la salida se lea como si Marx mismo estuviera escribiendo.

**📐 Disciplina tipográfica**
Las listas con viñetas y el abuso de negritas están prohibidos. Se impone la argumentación en prosa — la salida se lee como un artículo, no como una presentación.

**📜 Anclas estilísticas de textos originales**
El apéndice incluye 14 pasajes seleccionados (7 modos tonales × 2 pasajes) de 12 obras fundamentales para la calibración del estilo.

**🧩 Tensiones internas**
4 pares de contradicciones intelectuales no resueltas (ej.: humanismo temprano vs. cientismo tardío). Admite honestamente las controversias en lugar de forzar una falsa certeza.

---

## Instalación

```bash
npx skills add youaifuou/karl-marx-skill
```

Luego en Claude Code:

> 🔴 Marx, ¿es verdad que «996 es una bendición»? (→ modo correspondencia: golpe rápido)
>
> 🔴 Dame un análisis profundo de la economía gig (→ modo tratado: disección completa)
>
> 🔴 ¿Qué diría Marx sobre «el capitalismo es el sistema menos malo»?

<details>
<summary>Instalación manual</summary>

**Opción 1: Clonar el repositorio**

```bash
git clone https://github.com/youaifuou/karl-marx-skill.git
cp -r karl-marx-skill/karl-marx /ruta/a/tu/proyecto/.claude/skills/
```

**Opción 2: Descarga directa**

1. Descargar el archivo [`karl-marx/SKILL.md`](karl-marx/SKILL.md) y el directorio `karl-marx/references/`
2. Colocarlos en tu proyecto: `.claude/skills/karl-marx/`

</details>

---

## 🏗️ Arquitectura

SKILL.md (25KB / 340 líneas, reglas centrales autónomas + `references/` cargadas bajo demanda):

| Módulo | Contenido |
|--------|-----------|
| §1 Reglas de juego de rol | Radar de afinidad de clase · control de fuego de 3 niveles · primera persona · mecanismo de salida |
| §2 Flujo de respuesta | Motor de doble modo (correspondencia / tratado) · cadena de pensamiento de 5 pasos |
| §3 Tarjeta de identidad | Autopresentación del personaje + cronología (→ `references/`) |
| §4 Marco epistemológico | 6 principios, cada uno con limitaciones declaradas |
| §5 Heurísticas de decisión | 10 reglas de juicio |
| §6 Motor polémico | Metodología de 4 pasos + genealogía de adversarios (→ `references/`) |
| §7 ADN expresivo | 7 reglas de estilo + disciplina tipográfica + 7 espectros tonales + retórica/alusiones (→ `references/`) |
| §8 Prohibiciones | 6 líneas rojas + 7 anti-patrones (incl. prohibición de fuego amigo) |
| §9 Tensiones internas | 4 pares de contradicciones reales |
| Apéndice A | 14 muestras de escritura original (→ `references/`) |
| §10 Límites de honestidad | Declaraciones de limitaciones |
| §11 Corpus fuente | 17 textos fundamentales + metodología (→ `references/`) |

---

## 📚 Corpus fuente

Este Skill ha sido destilado a partir de 17 textos fundamentales de Marx:

**Filosofía (6)**: Tesis sobre Feuerbach · La ideología alemana (cap. 1) · Manuscritos de 1844 (Trabajo enajenado) · Introducción a la Crítica de la filosofía del derecho de Hegel · Grundrisse: Introducción · Carta a Annenkov

**Economía política (5)**: El Capital, t. I, cap. 1 (La mercancía) · El Capital, t. I, cap. 24 (La acumulación originaria) · Prólogo de la Contribución a la crítica de la economía política · Trabajo asalariado y capital · Salario, precio y ganancia

**Socialismo científico (6)**: El Manifiesto del Partido Comunista · El 18 Brumario de Luis Bonaparte · La guerra civil en Francia · Crítica del Programa de Gotha · Carta a Vera Zasúlich · Carta a Weydemeyer

Los 17 textos fueron objeto de una lectura profunda en seis dimensiones.

---

## ⚠️ Aviso legal

- Todas las salidas son generadas por un modelo de IA según reglas de juego de rol y **no representan las opiniones políticas del autor**.
- El juego de rol es un método de interacción con la IA, no un respaldo político.
- Las citas se recuerdan de los datos de entrenamiento y pueden contener ligeras variaciones.
- Este Skill reconstruye la **metodología y los modos de pensamiento** de Marx, no a Marx mismo.

---

## 🙏 Agradecimientos

### Referencias metodológicas

- [Nuwa Skill](https://github.com/alchaincyf/nuwa-skill) — Marco universal de destilación de persona
- [Zhang Xuefeng Skill](https://github.com/alchaincyf/zhangxuefeng-skill) — Referencia de Skill con personalidad
- [Sócrates Skill](https://github.com/RoundTable02/socrates-skill) — Referencia de metodología filosófica

### Fuentes de los textos originales

Textos de Marx del dominio público (Project Gutenberg / Marxists Internet Archive).

---

## 📄 Licencia

[MIT License](LICENSE) © 2026 youaifuou
