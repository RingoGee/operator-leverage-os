# OLS Production Draft Builder

## Purpose
Convert an approved Operator Leverage OS carousel brief into a slide-by-slide production draft.

## When to use
Use after a carousel brief is approved and the user wants detailed production direction before design prompting.

## Inputs required
- Approved carousel brief file
- Optional user feedback
- Optional evidence/source notes
- Optional visual preference

## Source files to read
- Selected file in `07-exports/carousel-briefs/`
- `02-editorial-system/thought-leadership-doctrine.md`
- `02-editorial-system/visual-carousel-rules.md`
- `03-carousel-system/carousel-quality-checklist.md`
- `03-carousel-system/visual-object-bank.md`

## Output files to create or update
- `07-exports/carousel-production-drafts/[number-topic-slug-production-draft].md`

Production draft must include:

- Carousel objective
- Audience
- Core thesis
- Central mental model / framework
- Evidence/example layer
- Slide-by-slide production draft
- For each slide:
  - slide role
  - slide objective
  - structured slide text direction
  - visual move
  - composition archetype
  - dominant element
  - headline mode
  - signature visual grammar
  - layout guidance
  - what this slide adds
  - what to avoid
- Caption draft/direction, if requested
- Optional product bridge notes
- Quality checklist

## Step-by-step procedure
1. Read the brief and doctrine.
2. Preserve the brief’s core argument.
3. Expand each slide into production-ready direction.
4. Ensure every slide advances the argument.
5. Add structured text direction.
6. Add mobile readability guidance.
7. Add visual hierarchy guidance.
8. Ensure evidence is honest.
9. Preserve antithesis and mechanism.
10. Write production draft in Markdown.

## Guardrails
- Do not create design prompts unless asked.
- Do not generate images.
- Do not create final captions unless asked.
- Do not add fake statistics.
- Do not expand into unnecessary complexity.
- Do not make every slide headline-dominant.
- Do not create product CTA unless explicitly approved.

## Done when
- Production draft is complete.
- Slide-by-slide direction is ready for design prompt building.
- The draft preserves doctrine and brief logic.

## Summary format
1. File created
2. Key production choices
3. Slide-by-slide structure summary
4. Evidence/antithesis/framework notes
5. Readiness for design prompt generation
6. Confirmation of no out-of-scope work

## Brand Identity Lock v1 requirements
Production drafts must preserve Brand Identity Lock v1 from `01-brand-foundation/visual-identity.md`.

Slide-by-slide production notes must respect:

- locked palette family;
- locked typography direction;
- stable slide chrome;
- generous spacing and mobile-first hierarchy;
- clean diagram/icon language;
- restrained surface treatment.

Each abstract term in the draft must be translated into plain English before design. Framework terms should have plain-language shadows so the expert reader does not have to decode the model.

Final QA:

- Does this feel like the same publication as other Operator Leverage OS posts, while still having a distinct argument?
- Would a reader recognize the brand without every carousel using the same template?
