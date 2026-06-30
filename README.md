# CLIMB-80
Benchmarking cloud-based and locally deployed LLMs on university-level mathematical reasoning

**Can Local Models Match Cloud Models? A Benchmark Study of Open-Source Models on University-Level Mathematical Reasoning**
## Overview

CLIMB-80 is a benchmark dataset and evaluation framework for comparing cloud-based language models (ChatGPT, Claude) against locally deployed open-source models (Llama 3.1 8B, Mistral 7B, Qwen 2.5 7B) on university-level mathematical reasoning. The benchmark spans three core mathematical domains — Calculus, Linear Algebra, and Probability — across three difficulty levels: Easy, Medium, and Hard.

This research was motivated by growing concerns over data privacy in cloud-based AI deployment. The study evaluates whether locally deployed models can offer a privacy-preserving alternative without a significant trade-off in mathematical reasoning performance.

---

## Repository Structure
CLIMB-80/
├── README.md
├── CITATION.cff
├── LICENSE
├── data/
│   └── benchmark_questions.csv
├── rubric/
│   ├── scoring_rubric.md
│   ├── error_taxonomy.md
│   └── prompt_template.md
├── results/
│   └── summary_statistics.csv
└── paper/
└── manuscript.pdf

- **data/** — 80 university-level mathematics questions sourced from MIT OpenCourseWare, spanning Calculus (27), Linear Algebra (27), and Probability (26), stratified across Easy, Medium, and Hard difficulty levels
- **rubric/** — the full scoring rubric, six-category Error-Mode Taxonomy (E1–E6), and the standardised prompt template applied uniformly across all five models
- **results/** — summary performance statistics computed for each model
- **paper/** — the full manuscript

---

## Dataset

The benchmark questions are also available as a structured dataset on HuggingFace:
🔗 https://huggingface.co/datasets/[your-username]/CLIMB-80

---

## Models Evaluated

| Model | Type | Parameters | Developer | Deployment |
|---|---|---|---|---|
| Llama 3.1 8B | Local | 8B | Meta | Ollama |
| Mistral 7B | Local | 7B | Mistral AI | Ollama |
| Qwen 2.5 7B | Local | 7B | Alibaba Cloud | Ollama |
| ChatGPT | Cloud | Undisclosed | OpenAI | Web Interface |
| Claude | Cloud | Undisclosed | Anthropic | Web Interface |

---

## Evaluation Dimensions

Each model response was scored across five dimensions:

1. **Correctness** (Y/N) — whether the final answer matches the verified solution
2. **Reasoning Quality** (0–3) — logic and coherence of the step-by-step reasoning
3. **Programming Correctness** (0–3) — validity of the mathematical procedure
4. **Response Time** (seconds) — elapsed time from prompt submission to response
5. **Hallucination** (0/1) — whether unsupported assumptions or fabricated facts were introduced

---


## Error-Mode Taxonomy (E1–E6)

A six-category error taxonomy was developed to classify the underlying cause of incorrect responses:

| Code | Category | Description |
|---|---|---|
| E1 | Conceptual Error | Wrong concept, wrong theorem, logic error |
| E2 | Method Error | Wrong method, wrong substitution, wrong procedure |
| E3 | Calculation Error | Arithmetic mistake, wrong numerical values |
| E4 | Reasoning Error | Incorrect explanation, weak justification |
| E5 | Incomplete Solution | Unfinished proof, no final answer |
| E6 | Hallucination | Fabricated information, unsupported assumptions |

See `rubric/error_taxonomy.md` for the full classification rule and methodology.

---

## Methodology Highlights

- 80 questions × 5 models = 400 evaluated responses
- Standardised prompt template applied identically across all models
- Multi-dimensional human annotation by four independent evaluators
- Full cross-annotator inter-rater reliability (IRR) study conducted across all 80 questions
- Local models deployed via Ollama with temperature set to 0 for deterministic, reproducible outputs

---
