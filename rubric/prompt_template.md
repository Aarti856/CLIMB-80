# Prompt Template

The following prompt was applied identically to all five models across all 80 benchmark questions, ensuring fairness and consistency.

```
You are given a university-level mathematics problem. Solve the problem. Present your response in the following format exactly:

Reasoning: [Your solution process]
Final Answer: [Your final answer]

Problem: {QUESTION}
```

## Design Rationale

The prompt requires a reasoning section before the final answer, enabling independent evaluation of Reasoning Quality and Programming Correctness regardless of final answer correctness. The fixed two-part structure ensures consistent response formatting across all models, reducing annotation ambiguity.


