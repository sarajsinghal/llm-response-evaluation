# LLM Response Evaluation

A multilingual response comparison project using 100 prompts in English, Hindi, and Hinglish. Two model outputs are captured side by side and assessed with a six-dimension rubric and pairwise preference labels.

## Current project status

- 100 prompt rows are present, and both response columns are populated for all 100.
- 80 pairs (LLM-001–060 and LLM-081–100) received an AI-assisted first-pass evaluation.
- LLM-061–080 remain unscored: the workbook contains reference passages, while both responses say the passage was missing. Confirm whether the passages were included in the models’ actual inputs; if not, rerun both models with the same prompt and context.
- Source model names, versions, and response dates were not provided. The workbook therefore keeps those fields blank.

The current evaluation is a preliminary AI-assisted review by Codex. It is not an independent human annotation or validated benchmark. Review and confirm scores before presenting them as personal human judgments.

## Preliminary descriptive results

For the 80 scored pairs only, the workbook records mean dimension scores of **4.85/5 for Model A** and **4.82/5 for Model B**. Pairwise preferences: **A 10**, **B 4**, **Tie 66**, **Neither 0**. These are descriptive results from this prompt set and one AI-assisted reviewer; they should not be interpreted as a general model ranking.

## Evaluation dimensions

Responses are rated from 1 (poor) to 5 (strong) for factual accuracy, relevance, instruction following, clarity, completeness, and safety. Each pair also receives an overall preference of A, B, Tie, or Neither, with a short rationale tied to observable differences. The workbook calculates each model’s row mean after all six scores are entered.

## Dataset

The authored prompt bank contains 100 prompts across five categories, with 20 prompts per category: Knowledge & Explanation, Reasoning, Instruction Following, Summarization, and Safety & Responsible Response. Languages: 35 English, 35 Hindi, and 30 Hinglish. The prompt set is an instructional portfolio sample, not a statistically representative benchmark.

## Files

- `Project 2 - LLM Response Evaluation Workbook.xlsx` — prompt bank, paired responses, rubric, row-level evaluation, and summary formulas.
- `METHODOLOGY.md` — scoring guidance, limitations, and input verification notes.

## Reproduction steps

1. Record the exact displayed model names, versions (if shown), collection dates, and relevant settings.
2. Submit identical prompt text and reference context to both models.
3. Preserve complete, unedited responses and keep prompt IDs aligned.
4. Rate each response independently against the rubric before making a pairwise preference choice.
5. Support the rationale with a specific strength, omission, error, or instruction-following difference.
6. Confirm LLM-061–080 were generated with their reference passages before scoring; otherwise regenerate them under matched conditions.

## Limitations

Model provenance is missing in the supplied workbook. The current scores are AI-assisted and need human confirmation. Twenty summarization pairs have an input-context ambiguity. The prompt set is small and authored; results can depend on the evaluator, language proficiency, prompt design, model version, and generation settings. Do not claim that a small average-score difference establishes a general winner.

