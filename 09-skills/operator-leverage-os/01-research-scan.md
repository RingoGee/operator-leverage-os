# OLS Research Scan

## Purpose
Run a grounded research scan to identify credible content themes, source-backed claims, public examples, workplace patterns, and potential evidence slides for Operator Leverage OS.

This skill supports future creation of content ideas, topic-bank rows, evidence slides, mini-cases, public examples, research-backed claims, carousel themes, and product insight.

## When to use
Use when the user asks for new content themes, data-backed ideas, research-backed carousel topics, market/workplace trends, or credible examples.

## Inputs required
- Research theme or content pillar
- Optional target audience
- Optional content format
- Optional date/freshness requirement
- Optional geography or market
- Optional source preference

## Source files to read
- `01-brand-foundation/positioning.md`
- `01-brand-foundation/audience.md`
- `02-editorial-system/thought-leadership-doctrine.md`
- `02-editorial-system/mental-model-content-rules.md`
- `02-editorial-system/what-we-do-not-post.md`
- `04-content-bank/topic-bank.csv`
- `04-content-bank/pillar-wise-ideas.md`

## Output files to create or update
For now, this skill should usually create or update planning outputs only when explicitly asked.

Preferred research-bank storage locations when the user explicitly asks Codex to store grounded research:

- `08-research-bank/source-log.csv`
- `08-research-bank/claim-bank.csv`
- `08-research-bank/example-bank.csv`
- `08-research-bank/research-notes/`
- `08-research-bank/research-to-content-map.md`

Research-bank entries must not be fabricated. Use `source-log.csv` for source records, `claim-bank.csv` for extracted claims, and `example-bank.csv` for public examples, workplace patterns, and mini-case inputs.

## Step-by-step procedure
1. Define the research question.
2. Identify the relevant Operator Leverage OS pillar.
3. Search for credible sources.
4. Extract claims, examples, patterns, and caveats.
5. Classify evidence type:
   - statistic
   - research finding
   - public example
   - benchmark
   - mini-case
   - workplace observation
6. Map each source to potential content angles.
7. Mark whether the evidence is strong enough for visible slide use.
8. Identify possible carousel hooks and mental models.
9. Recommend whether the idea should become:
   - topic-bank idea
   - carousel brief
   - evidence slide
   - case lens
   - product insight
10. Summarize with source quality and caveats.

## Guardrails
- Do not invent statistics.
- Do not use vague “studies show” language.
- Do not treat examples as research.
- Do not cite weak sources as high-confidence.
- Do not create final posts.
- Do not generate captions.
- Do not generate visuals.
- Do not create product claims.
- Do not create paid product content.
- Do not use evidence unless it directly supports the argument.

## Done when
- Research question is answered.
- Sources are summarized.
- Claims and caveats are extracted.
- Potential content angles are identified.
- Evidence quality is assessed.

## Summary format
1. Research theme
2. Sources reviewed
3. Key claims
4. Useful examples
5. Caveats
6. Recommended content angles
7. Recommended next skill to run
