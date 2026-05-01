# 🕌 ZIYARAT TERRA CORPUS

[![Layer](https://img.shields.io/badge/Layer-Human%20Research%20Branch-b45309)](https://github.com/Secret-Uzbek/ziyarat-terra-corpus)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--6394--4912-green)](https://orcid.org/0009-0000-6394-4912)
[![Release](https://img.shields.io/github/v/release/Secret-Uzbek/ziyarat-terra-corpus?display_name=tag)](https://github.com/Secret-Uzbek/ziyarat-terra-corpus/releases)
[![Last Commit](https://img.shields.io/github/last-commit/Secret-Uzbek/ziyarat-terra-corpus)](https://github.com/Secret-Uzbek/ziyarat-terra-corpus/commits/main)
[![Release Pipeline](https://github.com/Secret-Uzbek/ziyarat-terra-corpus/actions/workflows/release-and-publish.yml/badge.svg)](https://github.com/Secret-Uzbek/ziyarat-terra-corpus/actions/workflows/release-and-publish.yml)
[![Zenodo Sync](https://github.com/Secret-Uzbek/ziyarat-terra-corpus/actions/workflows/zenodo-release.yml/badge.svg)](https://github.com/Secret-Uzbek/ziyarat-terra-corpus/actions/workflows/zenodo-release.yml)
[![Terra Audit](https://github.com/Secret-Uzbek/ziyarat-terra-corpus/actions/workflows/terra-audit.yml/badge.svg)](https://github.com/Secret-Uzbek/ziyarat-terra-corpus/actions/workflows/terra-audit.yml)
[![Terra Legal](https://img.shields.io/badge/legal-terra--legal-7c6aff)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![FMP](https://img.shields.io/badge/Framework-FMP%20%7C%20PLT%20%7C%20NULLO-blue)](https://fractal-metascience.org)
[![Languages](https://img.shields.io/badge/Languages-17-orange)](./glossary/)

> **First open corpus of Uzbek ziyarat tourism discourse.**  
> Terminological lexicon · 17 languages · PLT-annotated · FMP-grounded · State-document-sourced.

---

## Layer role

**Ziyarat-Terra Corpus** — первый открытый тематический корпус лексики зиёрат-туризма узбекского языка, созданный в рамках Fractal Metascience Paradigm (FMP) как часть экосистемы корпусных исследований:

```
navoiy-terra-corpus     → Навоий «Лисонут-тайр» (XV в.)
babur-terra-codex       → Бабурнома (XVI в.)  
women-made-ca-corpus    → Женщины ЦА (III тыс. до н.э. – 2026)
ziyarat-terra-corpus    → Зиёрат дискурс (2019–2026)  ← ВЫ ЗДЕСЬ
```

Корпус обеспечивает **терминологическую базу** для диссертации Тиллябаевой Г.Б. (НУУ, 070004 Диншунослик) и цикла академических публикаций по корпусной лексикографии зиёрат-туризма.

This repository is a human-facing corpus branch.

It should hold:

- corpus and lexicon materials;
- branch-specific publications and field evidence;
- readable comparative and methodological explanations;
- release, citation, and audit surfaces for this branch.

It should not become:

- a fake DOI placeholder shell;
- a donor governance repository;
- a machine-first surface;
- an undifferentiated mix of archive residue and branch work.

---

## Авторы / Authors

| Роль | Имя | Аффилиация |
|---|---|---|
| Ведущий исследователь, FMP теория, DE/EN | **Абдукаримов Абдурашид** | Независимый исследователь, Ташкент · ORCID: 0009-0000-6394-4912 |
| Полевой исследователь, исламоведение, UZ | **Тиллябаева Гулсум Баҳодировна** | Магистрант НУУ, Диншунослик |

---

## Структура корпуса / Corpus Structure

```
ziyarat-terra-corpus/
│
├── glossary/
│   ├── ziyarat_semantic_lexicon_v1.0.json   ← 10 terms × 17 languages (PLT-annotated)
│   ├── ziyarat_terms_17lang.csv             ← machine-readable flat table
│   └── README.md                            ← glossary documentation
│
├── corpus/
│   ├── state_documents/     ← ПҚ–4095 (2019), ПФ-6165 (2021), ПҚ-223 (2023), Umra Plus (2026)
│   ├── field_observations/  ← Tillyabayeva G.B. — 480 respondents, 24 deep interviews (2023–2025)
│   └── academic_sources/    ← Muminov, Abashin, Babajanov, Choriyev — structured excerpts
│
├── religion-symbolism/
│   ├── seed-list.md         ← pre-Islamic, Buddhist, Islamic, hybrid, material culture nodes
│   ├── ziyarat-islam.md     ← Islamic layer: mazar practice, avliyo hagiography, tariqat
│   ├── pre-islamic-layer.md ← continuity from pre-Islamic sacred topography
│   └── hybrid-continuity.md ← syncretic practice documentation
│
├── oral-tradition/
│   ├── seed-list.md         ← lullabies, wedding songs, family legends, sacred orality
│   ├── otin-oyi-corpus.md   ← otin-oyi speech acts, zikr formulas, blessing texts
│   └── ritual-speech.md     ← ziyarat ritual utterances (PLT verbal components)
│
├── analysis/
│   ├── uzbekcorpora_frequency.md   ← search results from uzbekcorpora.uz
│   ├── plt_trace_mapping.md        ← PLT analysis of ziyarat lexicon
│   └── terminological_gaps.md     ← lacunae in national corpus
│
├── Core/                    ← FMP theoretical grounding
├── Theory/                  ← PLT / TraceLog application to ziyarat
├── Agents/                  ← research agents and methodology
├── Publications/            ← Article 1 (2026), Article 2 (forthcoming)
├── metadata/
│
├── README.md
├── CITATION.cff
├── LANGUAGE-STRATEGY.md
├── CONTRIBUTING.md
└── LICENSE                  ← CC BY-NC-SA 4.0
```

---

## Семантический лексикон / Semantic Lexicon

**`glossary/ziyarat_semantic_lexicon_v1.0.json`** — основной файл корпуса.

Формат совместим с `navoiy-terra-corpus/semantic_lexicon_v1.1_expanded.json`.

### 10 терминов в версии 1.0:

| # | Термин | Семантическое поле | FMP-слой |
|---|---|---|---|
| 001 | зиёрат | pilgrimage_core | UCOMM |
| 002 | мазор | sacred_topography | TraceLog |
| 003 | авлиё | islamic_hagiography | TraceLog |
| 004 | отин-ойи | religious_practice_women | **NULLO** |
| 005 | барака | islamic_theology_practice | UCOMM |
| 006 | чилла | sufi_practice | **NULLO** |
| 007 | хонақоҳ | sufi_institution | EUO |
| 008 | вақф | islamic_law_economics | TraceLog |
| 009 | зиёрат туризми | tourism_policy | EUO |
| 010 | PLT | fmp_theory | **PLT** |

### 17 языков:

`UZ · RU · EN · DE · TJ · KY · KK · TK · TR · ZH · KO · HI · FA · AR · FR · ES · PS`

Основание для выбора — статистика туристического потока (Агентство статистики РУз, 2023) + официальные языки ООН.

---

## Методология / Methodology

### PLT (Post-Lingua Trace)

Зиёрат-лексика передаётся не только через текст. Значение атамы «мазор» — это не только определение в словаре Чориева (1999). Это:
- тактильный ритуал (прикосновение к ткани гробницы)
- пространственный маршрут (направление приближения)  
- жест (снятие обуви на пороге)
- молчание (40 дней чиллы)

Всё это — **PLT-носители**. Корпус аннотирует каждый термин по его PLT-статусу:

| PLT-статус | Значение |
|---|---|
| `oral_written_dual` | передаётся через устную и письменную традицию |
| `material_ritual` | основной носитель — материальный объект / ритуал |
| `embodied_oral` | тело как канал передачи (отин-ойи) |
| `tactile_spatial` | пространство и прикосновение |
| `institutional_oral` | внутри институции без фиксации |

### NULLO (Zero-Point Ontology)

Отин-ойи и её роль в сохранении зиёрат-традиции в советский период — документированный пример NULLO: сохранение без бюджета, без разрешения, без институции.

### FMP-слои в аннотации

Каждый термин аннотирован по доминирующему FMP-слою:

```
NULLO    → выживание при нулевых ресурсах (отин-ойи, чилла)
PLT      → трансмиссия за пределами языка
UCOMM    → коммуникация живых и сакрального прошлого (зиёрат, барака)
EUO      → самоорганизация без центра (хонақоҳ, тариқат)
TraceLog → материальный узел цивилизационной памяти (мазор, вақф, мақбара)
```

---

## Источники / Sources

### Первичные / Primary
- Агентство статистики Республики Узбекистан. Туризм 2023. stat.uz
- ПҚ–4095-сон «Зиёрат туризмини ривожлантириш», 05.01.2019. lex.uz
- ПФ-6165-сон, 09.02.2021. lex.uz
- ВМ қарори «Умра плюс», 09.01.2026. lex.uz
- Тиллябаева Г.Б. Жойида тадқиқот маълумотлари (2023–2025). 480 respondents.

### Лексикографические / Lexicographic
- Раҳматуллаев Ш. Ўзбек тилининг изоҳли фразеологик луғати. Тошкент: Ўқитувчи, 1978.
- Чориев З. Тарих атамаларининг қисқача изоҳли луғати. Тошкент: Шарқ, 1999.
- Карзаев С. ва бошқ. Географиядан изоҳли луғат. Тошкент: Ўқитувчи, 1979.
- Аминов М. ва бошқ. Давлат тилида иш юритиш. Тошкент: ЎзР ФА, 2020.
- Дыбо А.В. Этимологический словарь базисной лексики тюркских языков. 2013.

### Академические / Academic
- Абашин С. Мазар Бобои-об. МАЭ РАН, 2010.
- Бабажанов Б. Ислам в Узбекистане. Тошкент: Фан, 2010.
- Муминов А. Святые места Мавераннахра. Тошкент, 2005.
- Lauer C. Otin-Oyi in Soviet Uzbekistan // Central Asian Survey. 2008. Vol. 27(3).
- Khalid A. Islam after Communism. University of California Press, 2007.

### FMP теория / FMP Theory
- Abdukarimov A. Fractal Metascience Paradigm. SSRN, 2025.
- Abdukarimov A. Invisible Shadow: Towards a Universal Ontology of Trace, Continuity, and Care. Zenodo, 2025.

---

## Связанные публикации / Related Publications

1. **Тиллябаева Г.Б., Абдукаримов А.А.** «Ўзбек тилида зиёрат туризми терминологиясини унификациялаш муаммолари». 2026. → `Publications/article_1_terminologiya.docx`
2. **Абдукаримов А.А., Тиллябаева Г.Б.** «Зиёрат туризми лексикасининг корпус лингвистикаси усулида тадқиқи». 2026. → `Publications/article_2_corpus.md` *(forthcoming)*
3. **Abdukarimov A., Tillyabayeva G.** «Ziyarat-Tourismus in Usbekistan: terminologische Grundlagen für die internationale Forschung». 2026 → *Zentralasien-Analysen (forthcoming)*

---

## Связанные репозитории / Related Repositories

| Репозиторий | Связь |
|---|---|
| [navoiy-terra-corpus](https://github.com/Secret-Uzbek/navoiy-terra-corpus) | Формат semantic_lexicon — прямая совместимость |
| [babur-terra-codex](https://github.com/Secret-Uzbek/babur-terra-codex) | 9-language PLT methodology — extended to 17 languages here |
| [women-made-central-asia-corpus](https://github.com/Secret-Uzbek/women-made-central-asia-corpus) | `religion-symbolism/` и `oral-tradition/` — прямой донор контента |
| [Nullo-PLT-UCOMM-FMP](https://github.com/Secret-Uzbek/Nullo-PLT-UCOMM-FMP-Academic-Research) | Теоретическая база |
| [FMP-CENTRAL-REPO](https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO) | Центральный хаб экосистемы |

---

## Цитирование / Citation

```bibtex
@dataset{tillyabayeva_abdukarimov_2026_ziyarat,
  title     = {Ziyarat-Terra Corpus: Multilingual Lexicon of Uzbek Ziyarat Tourism Discourse},
  author    = {Tillyabayeva, Gulsum B. and Abdukarimov, Abdurashid A.},
  year      = {2026},
  publisher = {GitHub / Zenodo},
  url       = {https://github.com/Secret-Uzbek/ziyarat-terra-corpus},
  doi       = {10.5281/zenodo.TODO},
  note      = {ORCID: 0009-0000-6394-4912. Part of FMP Corpus Ecosystem.}
}
```

---

## Лицензия / License

**CC BY-NC-SA 4.0** — Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International

© 2026 Тиллябаева Г.Б., Абдукаримов А.А.
