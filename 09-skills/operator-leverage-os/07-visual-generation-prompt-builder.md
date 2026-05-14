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

## Free Value Per Slide final prompt requirements
Final visual prompts must include a “reader value per slide” control.

Each slide prompt must state:

- what the slide teaches;
- what practical takeaway it gives;
- what useful question, filter, rewrite, or lens the reader can use;
- how the slide avoids looking premium but feeling thin.

Add final tests:

- Would the reader feel they received a useful operating lens for free?
- If this slide were removed from the carousel, would the reader lose a specific useful idea?

## Required plain-language and narrative blocks for final visual prompts
Every final visual prompt must include a narrative spine block and a slide-level reader-thought block.

Required narrative spine block:

> This carousel starts with [tension], shows [cause/mechanism], then gives [tool/framework], so the reader can [action/behavior shift].

Required global language instructions:
- Use simple, direct, classy language.
- Do not use jargon unless translated in plain English.
- Each slide should feel like the next natural step in one argument.
- Use bridge lines only when they reduce reader effort.
- Explain the problem before naming the framework.

Required slide-level block:
- Slide point in plain English:
- Previous slide answer:
- Question this slide creates:
- Bridge into next slide:
- Formal terms used:
- Plain-language shadows:
- Reader should think:

Final prompt tests:
- Could a smart reader explain this slide without using our terminology?
- Does this slide read like a useful insight, not a strategy document?
- Does the next slide feel inevitable?
- Did we explain the problem before naming the framework?
- Would simpler wording make this more powerful?
