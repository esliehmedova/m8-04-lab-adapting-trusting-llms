# Eval Results

## Task 2 — LLM-as-judge pass-rate table

| Variant | Cases | Passed | Pass rate |
|---------|-------|--------|-----------|
| Few-shot | 10 | 10 | 100% |
| Embeddings | 10 | 7 | 70% | 

**Rubric used by the judge:**

> PASS if the predicted label exactly matches the expected label. FAIL otherwise.

**Verdict (2–3 sentences):**

> The few-shot classifier achieved the higher pass rate on the evaluation set. The judge was generally reliable because it used exact label matching, although it cannot assess partially correct answers.

**A case where the judge looked wrong:**

> One feature request ticket was marked incorrect because the prediction used a slightly different wording than the expected label. A human reviewer might still consider the answer acceptable. 