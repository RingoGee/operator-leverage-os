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

## Free Value Per Slide requirements
Every production draft slide must state what the reader gains.

For each slide, include:

- reader value delivered;
- practical takeaway;
- plain-language point;
- what the slide teaches or helps the reader do;
- how useful density is organized without clutter.

Reject thin, transitional, or merely decorative slides before moving to design prompting.

## Mobile readability and narrative continuity requirements
Every slide in a production draft must state:

- **Previous slide connection:** how this slide advances the prior slide.
- **Reader question answered:** what question this slide resolves.
- **Reader question created:** what question this slide opens next.
- **Next slide handoff:** the soft handoff into the next idea.
- **Narrative function:** why this slide belongs in the argument.
- **Visual continuity motif:** the repeated object, marker, path, color meaning, or diagram thread carried forward.
- **Transition risk:** how this slide could feel abrupt if produced poorly.
- **Mobile readability risk:** where the slide could become too dense or too small.
- **Smallest meaningful text risk:** the smallest essential label or text element that must stay readable.

## Production text hierarchy requirement
Production notes must define a clear mobile-first text hierarchy:

- **Level 1:** main idea / headline.
- **Level 2:** support line / core explanation.
- **Level 3:** framework labels / table rows / diagram labels.
- **Level 4:** optional source / caveat / chrome / memo code.

Rules:

- Level 1 and Level 2 must be instantly readable.
- Level 3 must be readable without zoom.
- Level 4 must remain minimal and non-essential.
- Do not use tiny labels for essential meaning.
- Do not let diagrams depend on unreadable labels.
- Dense slides should use fewer larger blocks, not many tiny fragments.

## Production guardrails for continuity
- Every slide must connect to the previous slide and lead to the next.
- Each slide should end with a soft handoff into the next idea.
- The framework slide must feel earned by Slides 1–5.
- The application slide must feel like the natural next step from the framework.
- The final slide must resolve the argument, not act as a generic checklist.

## Final production tests
- Can the reader follow the carousel without feeling reset at every slide?
- Does each slide make the next slide feel necessary?
- Is every meaningful text element readable on Instagram mobile?
- Are small labels supportive rather than essential?
- Does the carousel feel like one guided argument?
