# OLS Visual Generation Prompt Builder

## Purpose
Create a final master visual generation prompt file for a specific Operator Leverage OS carousel.

## When to use
Use after the visual execution pack is approved and the user wants one clean copyable prompt file for a visual generation attempt.

## Inputs required
- Approved visual execution pack
- Target attempt number
- Optional feedback from prior visual attempts

## Source files to read
- Selected file in `07-exports/visual-execution-packs/`
- Relevant design prompt, production draft, and brief
- `02-editorial-system/visual-carousel-rules.md`
- `03-carousel-system/carousel-quality-checklist.md`

## Output files to create or update
- `07-exports/visual-generation-prompts/[number-topic-slug-attempt-master-prompt].md`

Prompt file must include:

- Purpose of file
- Usage notes
- Full copyable master prompt
- Locked slide chrome
- Slide sequence
- Slide-level archetypes
- Dominant elements
- Headline modes
- Signature visual grammar
- Global avoid rules
- Final quality guardrails
- Post-generation review checklist

## Step-by-step procedure
1. Read execution pack and source files.
2. Identify whether this is first attempt, second attempt, final attempt, etc.
3. Build a full copyable prompt.
4. Make it tool-ready.
5. Include all slide-specific instructions.
6. Include strict guardrails from previous visual failures.
7. Save under visual-generation-prompts.

## Guardrails
- Do not generate images.
- Do not create designed slides.
- Do not create a new carousel concept.
- Do not change the core argument.
- Do not create product CTA unless approved.
- Do not create more than one prompt file unless asked.

## Done when
- One master prompt file is created.
- It is copyable into an image/design tool.
- It reflects the latest approved direction.

## Summary format
1. File created
2. Prompt structure
3. Key generation constraints
4. Whether ready for visual generation
5. Confirmation of no out-of-scope work

## Brand Identity Lock v1 requirements
Final master prompts must include a locked identity block.

The prompt must explicitly preserve brand identity across all slides:

- Same palette family.
- Same typography direction.
- Same slide chrome positions.
- Same spacing discipline.
- Same diagram/icon language.
- Same restrained surface treatment.

The prompt must say: vary composition, not identity.

Final QA language to include:

- Does this feel like the same publication as other Operator Leverage OS posts, while still having a distinct argument?
- Would a reader recognize the brand without every carousel using the same template?
