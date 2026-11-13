# LLM Response Evaluation

A multilingual comparison of Gemini 3.8 Flash and Claude Haiku 5.5 Medium using 100 prompts in English, Hindi, and Hinglish. Responses are assessed side by side with a six-dimension rubric and a pairwise preference judgment.

## Dataset

The authored prompt bank contains 100 prompts across five categories, with 20 prompts per category: Knowledge & Explanation, Reasoning, Instruction Following, Summarization, and Safety & Responsible Response. Languages: 35 English, 35 Hindi, and 30 Hinglish. Summarization prompts include reference passages. This is an instructional portfolio sample, not a statistically representative benchmark.

## Preliminary results

All 100 prompt pairs have responses and an AI-assisted first-pass evaluation. Across the six 1–5 dimensions, mean scores are **4.92/5 for Gemini 3.8 Flash** and **4.95/5 for Claude Haiku 5.5 Medium**. Overall preferences: Gemini **4**, Claude **15**, **Tie 81**, **Neither 0**.

These results describe this prompt set and a single AI-assisted reviewer. They are not independent human labels, a validated benchmark, or evidence of a general model ranking. Human review is recommended before presenting these as personal evaluation results.

## Evaluation dimensions

Each response is scored from 1 (poor) to 5 (strong) on factual accuracy, relevance, instruction following, clarity, completeness, and safety. Each pair also receives a preference of A, B, Tie, or Neither, with a concise rationale tied to response evidence.

## Files

- `LLM Response Evaluation Workbook.xlsx` — prompt bank, model responses, row-level scores and rationales, rubric, and summary formulas.
- `METHODOLOGY.md` — scoring guidance, interpretation, and limitations.

## Reproduction steps

1. Record the exact model names, versions, collection dates, and relevant settings.
2. Submit identical prompt text and reference context to both models.
3. Preserve complete responses and keep prompt IDs aligned.
4. Rate the two responses independently against the rubric before making an overall preference choice.
5. Support each rationale with an observable strength, omission, error, or instruction-following difference.

## Limitations

The scores are AI-assisted and should be verified by a human reviewer. The prompt set is small and authored; results can depend on the evaluator, language proficiency, prompt design, model version, and generation settings. Small differences in average scores do not establish a general winner.

