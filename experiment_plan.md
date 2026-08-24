# Long-Document Summarization Experiment Plan

## Objective

Evaluate how well Qwen/Qwen3-1.7B summarizes real Arabic and English documents as document length and complexity increase.

The experiment will measure whether longer documents cause degradation in:

- Faithfulness
- Coverage
- Relevance
- Conciseness
- Instruction Following
- Language Quality
- Structure
- Hallucination

Critical checks will also include:

- Numbers preservation
- Dates preservation
- Decision-status preservation
- Critical information omission
- Wrong output language
- Excessive copying

## Initial Document Matrix

| Document | Length | Language | Type |
|---|---|---|---|
| L01 | 1–2 pages | English | Business |
| L02 | 2–3 pages | Arabic | Business / Procedural |
| L03 | 3–4 pages | English | Technical |
| L04 | 4–5 pages | Arabic | Technical / Procedural |
| L05 | 6+ pages | Arabic or English | Complex |

## Experiment Stages

1. Extract text from the document.
2. Verify extraction quality.
3. Generate a baseline summary.
4. Evaluate the summary using the established rubric.
5. Audit numbers, dates, and decision status.
6. Record PASS / FAIL and observed failure modes.
7. Test improvement methods such as better prompting and chunking.
8. Compare results.
9. Decide whether persistent gaps justify fine-tuning.
