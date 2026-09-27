# Independent AI Evaluation — Environmental Reasoning

A public, de-identified portfolio project evaluating how two general-purpose AI systems reason from incomplete, multi-layered environmental evidence.

## What this project tests

- factual accuracy and source discipline
- uncertainty calibration
- hallucination and overclaim detection
- local-vs-general evidence separation
- administrative and legal precision
- environmental nuance
- open-web citation auditing
- reproducible comparative scoring

## Evaluation design

The benchmark was fixed before scoring. Twelve prompts were used: ten closed-source tasks and two open-web stretch tasks. Responses were saved unedited, anonymised as X/Y, scored blind on a weighted 100-point rubric, and attributed only after scores were locked.

The evaluated configurations were Microsoft Copilot Auto and Google Gemini 3.1 Pro.

## Public results

Across all 12 prompts:

| Model | Score |
|---|---:|
| Microsoft Copilot Auto | 1,156 / 1,200 (96.3%) |
| Google Gemini 3.1 Pro | 945 / 1,200 (78.8%) |

Closed-source round only:

| Model | Score |
|---|---:|
| Microsoft Copilot Auto | 980 / 1,000 (98.0%) |
| Google Gemini 3.1 Pro | 897 / 1,000 (89.7%) |

The project is designed as an evaluation of reasoning discipline rather than a product recommendation.

## Repository contents

- `Independent_AI_Evaluation_Report.pdf` — 10-page public portfolio report
- `docs/METHODOLOGY.md` — evaluation design and rubric
- `docs/PROMPT_BANK.md` — de-identified prompt themes
- `docs/RESULTS.md` — score summary and key findings

## Privacy and source handling

This repository contains only the public, de-identified portfolio layer. Location, institutional and source identifiers have been generalised. Private correspondence, exact source records, raw audit material and identifying case files are retained separately and are not published here.

Prepared: 27 September 2026.
