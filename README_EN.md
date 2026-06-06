# Chinese Medicine Chinese Medicine-PMPH-10edition
<div align="center">

> *「21st Century Medical Student Guide」*

[![License: MIT-0](https://img.shields.io/badge/License-MIT--0-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)
[![ClawHub](https://img.shields.io/badge/ClawHub-Skill-orange)](https://clawhub.ai)

<br>
> A clinical skills manual based on the 10th edition of *Chinese Medicine* (PMPH) — 172 Core TCM Clinical Skills
<br>
<br>
<img src="assets/Chinese-Medicine.png" width="260px">
<br>

No need to read through an entire textbook<br>
Just ask a question, and get the answer from the textbook instantly

<br>

**Languages:**

[中文](README.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## About

This project systematically organizes core Traditional Chinese Medicine (TCM) knowledge covering basic theories, pattern differentiation, formula applications, acupuncture & tuina, gynecology & pediatrics, warm disease & cold damage, oncology, constitutional identification, and integrated Chinese-Western medicine, encompassing **172 key clinical skills** across 20 categories.

**Target Audience**: TCM practitioners, integrated Chinese-Western medicine doctors, medical students, TCM researchers, health preservation specialists

**Reference Textbook**: *Chinese Medicine*, 10th Edition, People's Medical Publishing House (PMPH)

**⚠️ Risk ⚠️**: This skill covers TCM diagnosis, formulas, acupuncture, and tuina procedures that could be misused as standalone medical advice.

Mitigation: Use output solely as educational reference or material for clinician review. Verify recommendations against current official guidelines, local protocols, and qualified TCM specialists.

## Project Structure

```
Chinese-Medicine-PMPH-10edition/
├── SKILL.md                    # Core config — 172-skill registry
├── README.md                   # This document — project overview (multi-language)
│   ├── README_EN.md            # English version
│   ├── README_JP.md            # Japanese version
│   ├── README_FR.md            # French version
│   └── README_RU.md            # Russian version
├── <skill-name>/               # Individual skill definitions
│   └── SKILL.md                #   Skill details (when to use, steps, references)
├── index.md                    # Skill navigation index
├── scripts/                    # Executable tool scripts
├── config/                     # Configuration files
├── tests/                      # Validation and tests
└── assets/                     # Project assets
```

## Skill Categories

| Category | Skills | Description |
|----------|--------|-------------|
| 🧬 Basic TCM Theory | 18 | Yin-Yang, Five Elements, Zang-Fu, Qi-Blood, Constitution |
| 🔍 Pattern Differentiation Principles | 8 | Core differentiation principles, treatment rules |
| 🫀 Zang-Fu & Meridian Physiology | 13 | Organ functions, meridian pathology |
| 🔬 Diagnostic Methods | 6 | Tongue, pulse, inspection, pediatric fingerprint |
| 🌡️ Exogenous Disease Patterns | 10 | Six evils, warm disease, cold damage |
| 🩺 Internal Medicine Patterns | 14 | Constipation, hemorrhoids, insomnia, bi syndrome |
| 👩 Gynecology Patterns | 9 | Menstrual disorders, leukorrhea, postpartum |
| 🚽 Urinary & Lin Syndrome | 3 | Six-type lin differentiation, hematuria |
| 💧 Thirst & Edema | 2 | Three wasting-thirst, yang/yin edema |
| 🟡 Jaundice & Accumulations | 2 | Yang/yin jaundice, herpetic keratitis |
| 🩸 Blood Stasis & Hemorrhage | 3 | Blood stasis patterns, Xuefu Zhuyu |
| 💊 Formulas & Materia Medica | 26 | Classical formulas, herb配伍, toxicity |
| 📍 Acupuncture & Moxibustion | 8 | Needling, moxibustion, auricular, acupoints |
| ✋ Tuina Manipulations | 5 | Eight methods, pulling, patting, reinforcing-reducing |
| 🫳 External Therapies | 3 | Cupping, Jinhuang San, external application |
| 🤝 Integrated Chinese-Western Medicine | 7 | Synergistic therapy, pre-diabetes intervention |
| 📚 Classic Literature & History | 4 | Four classics, Xinxiu Bencao, Ge Hong |
| 🎗️ Oncology & Severe Diseases | 5 | Tumor differentiation, Fuzheng Quxie |
| 👶 Pediatrics | 1 | Precocious puberty |
| ⚙️ Treatment Methods | 4 | Purgation, exterior-releasing, interior-warming |

## Quick Start

### Installation

CLI:
```bash
openclaw skills install chinese-medicine-10edition
```

Prompt (Claude Code):
```bash
Install the skill "Chinese-Medicine-PMPH-10edition" (xllgreen/chinese-medicine-10edition) from ClawHub.
Keep the work scoped to this skill only.
```

### Usage

Each skill contains four sections:
1. **When to Use** — Trigger conditions for the skill
2. **Procedure** — Standardized operating steps
3. **Precautions** — Contraindications and warnings
4. **References** — Supplementary materials

### Query Examples

**Concept:**
```bash
What are the five physiological functions of the Liver governing free coursing?
```

**Clinical Case Analysis:**
```bash
Male, 45, recurrent hypochondriac distension and pain for 3 years, aggravated by emotional stress...
```

## Full Skill Index

See [index.md](index.md) for the complete list of all 172 skills.

## About the Author

**xllgreen** — [Homepage](https://xllgreen.github.io) · Medical Student at Jiujiang University · Tech Geek

## License

MIT-0 — This project is organized based on the 10th edition of *Chinese Medicine* (PMPH) for educational reference only.
