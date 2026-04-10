<div align="center">

[简体中文](README.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [Deutsch](README_de.md) | [Français](README_fr.md) | Español | [Русский](README_ru.md) | [日本語](README_ja.md)

# 🔨 Karl Marx Skill

**Marco de pensamiento y método crítico de Karl Marx**

*Un Skill de Claude destilado a partir de la lectura sistemática en seis dimensiones de 17 textos fundamentales de Marx*

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)

</div>

---

## ✨ Características

**🔬 Destilación profunda, no apilamiento de prompts**
Construido a partir de una lectura sistemática en seis dimensiones de 17 textos fundamentales de Marx (hilos de pensamiento, métodos polémicos, ADN expresivo, validación externa, marcos de decisión, cruces biográficos), produciendo un marco cognitivo completo.

**⚙️ Flujo de trabajo agéntico completo**
Clasificación del problema → investigación contemporánea (WebSearch) → análisis marxiano → ensamblaje de la salida. Invoca automáticamente herramientas de búsqueda para fenómenos contemporáneos.

**🧰 Rica caja de herramientas analíticas**
6 principios epistemológicos · 10 heurísticas de decisión · 10 recursos retóricos · 5 espectros de tono · motor polémico completo.

**🎭 No es una máscara de chatbot**
Directrices de estilo de escritura independientes (9 reglas positivas + tabla de anti-patrones) que aseguran que la salida se lea como si Marx mismo estuviera escribiendo.

**📜 Anclas estilísticas de textos originales**
El apéndice incluye 4 pasajes seleccionados de las obras originales de Marx para la calibración del estilo.

---

## Instalación

```bash
npx skills add youaifuou/karl-marx-skill
```

Luego en Claude Code:

> 🔴 Analiza la economía gig desde la perspectiva de Marx
>
> 🔴 ¿Qué diría Marx sobre «el capitalismo es el sistema menos malo»?
>
> 🔴 Cambia a Marx y ayúdame a analizar las relaciones laborales en la economía de plataformas

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

SKILL.md (33KB / 481 líneas) contiene los siguientes módulos:

| Módulo | Contenido | Líneas |
|--------|-----------|--------|
| §1 Reglas de juego de rol | Identidad, reglas lingüísticas, mecanismo de salida | ~25 |
| §2 Flujo de respuesta | Protocolo agéntico de 4 pasos + plantillas de análisis | ~90 |
| §3 Tarjeta de identidad | Contexto, preocupaciones, método, cronología | ~25 |
| §4 Marco epistemológico | 6 principios epistemológicos | ~30 |
| §5 Heurísticas de decisión | 10 métodos de decisión | ~50 |
| §6 Motor polémico | Metodología polémica + genealogía de adversarios | ~35 |
| §7 ADN expresivo | Estilo + retórica + espectro tonal + alusiones literarias | ~100 |
| §8 Prohibiciones | Líneas rojas + tabla de anti-patrones IA | ~25 |
| §9 Límites de honestidad | 5 declaraciones de limitaciones | ~10 |
| §10 Corpus fuente | 17 textos fundamentales + metodología | ~35 |

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

- [Nuwa Skill](https://github.com/alchaincyf/nuwa-skill) — Marco universal de destilación de persona
- [Zhang Xuefeng Skill](https://github.com/alchaincyf/zhangxuefeng-skill) — Referencia de Skill con personalidad
- [Sócrates Skill](https://github.com/RoundTable02/socrates-skill) — Referencia de metodología filosófica

Textos de Marx del dominio público (Project Gutenberg / Marxists Internet Archive).

---

## 📄 Licencia

[MIT License](LICENSE) © 2026 youaifuou
