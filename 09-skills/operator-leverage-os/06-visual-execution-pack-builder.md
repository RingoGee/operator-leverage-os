# OLS Visual Execution Pack Builder

## Purpose
Create a visual execution pack that converts design prompt directions into copyable image/design-tool prompt instructions.

## When to use
Use after a design prompt file is approved and the user wants a practical prompt pack for image/design tools.

## Inputs required
- Approved design prompt file
- Optional user notes on format or tool
- Optional previous visual output critique

## Source files to read
- Selected file in `07-exports/design-prompts/`
- Relevant production draft and brief
- `02-editorial-system/visual-carousel-rules.md`
- `03-carousel-system/carousel-quality-checklist.md`
- `03-carousel-system/visual-object-bank.md`

## Output files to create or update
- `07-exports/visual-execution-packs/[number-topic-slug-visual-execution-pack].md`

Execution pack must include:

- Final design direction
- Format decision
- Locked slide chrome
- Visual identity direction
- Slide-by-slide visual production instructions
- Master prompt draft
- Individual slide prompts
- Quality guardrails
- Pre-generation checklist
- Post-generation review checklist

## Step-by-step procedure
1. Read design prompt and source files.
2. Create a practical execution pack.
3. Preserve locked chrome and visual hierarchy.
4. Add slide-by-slide prompt blocks.
5. Add master prompt for full-deck generation.
6. Add fallback instruction for one-slide-at-a-time generation.
7. Add quality checklist.
8. Save under visual-execution-packs.

## Guardrails
- Do not generate images.
- Do not create designed slides.
- Do not create Canva files.
- Do not edit carousel content unless required for clarity.
- Do not mention paid products unless approved.
- Do not create generic prompt language that loses brand specificity.

## Done when
- Visual execution pack is ready for image/design-tool use.
- It supports both full-deck and slide-by-slide generation.
- It preserves Operator Leverage OS standards.

## Summary format
1. File created
2. Execution pack structure
3. Key generation constraints
4. Visual choices needing human input
5. Confirmation of no out-of-scope work

## Brand Identity Lock v1 requirements
Visual execution packs must carry Brand Identity Lock v1 into every slide prompt.

Each execution pack must preserve:

- locked palette family;
- locked typography direction;
- stable slide chrome;
- spacing discipline;
- clean diagram/icon language;
- restrained surface treatment;
- mobile readability.

Guardrails:

- Do not allow random palette changes slide to slide.
- Do not allow type personality changes.
- Do not move chrome positions.
- Do not create a new visual identity for a single carousel.
- Vary slide composition, visual object, and argument structure instead.

## Free Value Per Slide execution requirements
Prompt packs must preserve the free-value-per-slide doctrine.

Every slide prompt should include what the slide teaches, diagnoses, clarifies, or helps the reader do.

Guardrail: do not create empty premium-looking slides. A polished slide with no useful takeaway fails.

## Plain-language and narrative execution guardrails
Visual execution packs must preserve simple language and bridge logic from the brief and production draft.

Rules:
- Keep the plain-English slide point visible in the execution plan.
- Preserve the narrative spine and slide handoffs.
- Include formal term → plain-language shadow notes where any jargon appears.
- Guard against prompts that create visually strong but disconnected slides.
- Use bridge lines only when they reduce reader effort.
- Ensure each slide’s visual decision supports the “Reader should think” line.
- Do not let visual polish hide overformal or unclear copy.

Execution QA:
- Could a smart reader explain this slide without using our terminology?
- Does this slide read like a useful insight, not a strategy document?
- Does the next slide feel inevitable?
- Did we explain the problem before naming the framework?
