# Scoring Rubric

Each model response was evaluated by human annotators across four dimensions using a standardised four-point rubric.

## Programming Correctness / Mathematical Procedure Correctness

| Score | Description |
|---|---|
| 0 | Completely invalid solution procedure/ Completely incorrect |
| 1 | Significant errors in the mathematical procedure/Partially correct 

 |
| 2 | Generally valid procedure with minor issues/Mostly correct  |
| 3 | Fully valid and mathematically sound solution procedure/ Fully correct 

 |

## Reasoning Quality

| Score | Description |
|---|---|
| 0 | No meaningful reasoning |
| 1 | Weak reasoning |
| 2 | Adequate reasoning |
| 3 | Strong reasoning |

## Correctness

Binary scale:
- **Y** — final answer fully matches the verified solution
- **N** — final answer does not match the verified solution

## Hallucination

Binary scale:
- **0** — no unsupported assumptions, formulas, or fabricated facts introduced
- **1** — model introduced mathematical assumptions, entities, formulas, or statements unsupported by the problem statement

## Partial Credit Principle

Responses are not evaluated solely on the final answer. A response with an incorrect final answer but a valid reasoning process and correct mathematical procedure may still receive high Reasoning Quality and Programming Correctness scores. This allows the framework to distinguish between conceptual failures and procedural slips.
