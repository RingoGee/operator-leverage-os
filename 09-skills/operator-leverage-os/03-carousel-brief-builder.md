# OLS Carousel Brief Builder

## Purpose
Create an Operator Leverage OS carousel brief from a selected topic, research note, operator problem, or idea-bank row.

## When to use
Use when the user has selected a content idea and wants a structured carousel brief before production drafting.

## Inputs required
- Topic title or topic-bank row
- Target audience segment
- Content format
- Optional evidence/source notes
- Optional product bridge
- Optional primary action objective

## Source files to read
- `01-brand-foundation/positioning.md`
- `01-brand-foundation/audience.md`
- `02-editorial-system/thought-leadership-doctrine.md`
- `02-editorial-system/mental-model-content-rules.md`
- `02-editorial-system/visual-carousel-rules.md`
- `02-editorial-system/free-vs-paid-logic.md`
- `02-editorial-system/what-we-do-not-post.md`
- `03-carousel-system/infographic-carousel-template.md`
- `03-carousel-system/carousel-quality-checklist.md`
- `03-carousel-system/visual-object-bank.md`
- `04-content-bank/topic-bank.csv`
- Relevant research notes if available

## Output files to create or update
- `07-exports/carousel-briefs/[number-topic-slug].md`

Brief must include:

- Working title
- Content format type
- Primary action objective
- Exact operator problem
- First-principles cause
- Evidence / data / example plan
- Common false solution
- Antithesis
- Hidden mechanism
- Framework / model
- Applied example
- Behavior shift
- Profile-entry reason
- Optional bio-click bridge
- Visual argument path
- Slide-by-slide argument sequence
- Structured text plan
- Visual moves by slide
- Composition archetype by slide
- Dominant element by slide
- Headline mode by slide
- Signature visual grammar by slide
- Optional paid asset bridge
- Quality checklist

## Step-by-step procedure
1. Read doctrine and template files.
2. Confirm the selected idea is strong enough.
3. Define the exact operator problem.
4. Diagnose the first-principles cause.
5. Add evidence/example plan.
6. Define antithesis.
7. Define hidden mechanism.
8. Decide if a named framework is deserved.
9. Choose content format intensity.
10. Create the 8-slide or suitable slide arc.
11. Assign archetype, dominant element, headline mode, and signature visual grammar per slide.
12. Add behavior shift and profile-entry reason.
13. Add optional paid bridge only if natural.
14. Save the brief under carousel-briefs.

## Guardrails
- Do not create production drafts unless asked.
- Do not create design prompts unless asked.
- Do not create visual execution packs unless asked.
- Do not generate images.
- Do not force a framework name if the idea does not deserve one.
- Do not include fake statistics.
- Do not create product CTA unless the content naturally supports it.
- Do not create generic AI-tool content.

## Done when
- One complete doctrine-compliant brief is created.
- The brief is ready for production drafting.
- All slide roles and visual logic are clear.

## Summary format
1. File created
2. Topic and pillar
3. Core argument
4. Framework or mental model
5. Slide arc
6. Evidence/example layer
7. Strategic choices needing human input
8. Confirmation of no out-of-scope work

## Brand Identity Lock v1 requirements
Every brief must apply `01-brand-foundation/visual-identity.md` Brand Identity Lock v1.

The brief must state:

- Brand identity lock applied: yes/no.
- Primary accent for the carousel and why it fits the argument.
- Supporting accents and what each one means, if used.
- Visual variation from house style, while staying inside the locked identity.
- Plain-language shadows for major framework terms.

Guardrail: visual variation must happen through slide archetype, visual metaphor, framework intensity, evidence treatment, or diagram type — not through a new palette, typography personality, chrome system, or surface style.

## Free Value Per Slide requirements
Every brief must define the free value promise of the carousel.

Briefs must include:

- the unfair free advantage: what useful thinking the reader receives for free;
- slide-level reader value notes;
- practical takeaway for each slide;
- plain-language shadows for abstract terms;
- the framework or tool used on each slide, if any;
- a slide usefulness test: if this slide were removed, what specific useful idea would the reader lose?

Reject brief directions that produce thin, transitional, or merely decorative slides.

## Plain-language and narrative refinement gate
Every carousel brief must enforce simple language before clever language.

Required additions to every brief:
- Simple narrative spine in this format: “This carousel starts with [tension], shows [cause/mechanism], then gives [tool/framework], so the reader can [action/behavior shift].”
- Plain-language shadows for every major term in the format `Formal term → Plain-language meaning`.
- A “Reader should think” line for every slide.
- Slide-level previous answer and next question.
- Bridge logic before moving to production draft.

Briefing rules:
- Say the simple thing first.
- Use formal terms only when they make the idea clearer.
- Explain the problem before naming the framework.
- Reject decorative frameworks that rename common sense or do not make the next action easier.
- Bridge lines should be used only when they reduce reader effort.
- If the narrative spine is unclear, do not create the carousel brief yet.

Final tests:
- Could a smart reader explain this slide without using our terminology?
- Does this slide read like a useful insight, not a strategy document?
- Does the next slide feel inevitable?
- Did we explain the problem before naming the framework?
- Would simpler wording make this more powerful?

## Current doctrine checks for this skill

This skill must enforce the latest Operator Leverage OS rules before handing work forward:
- Brand Identity Lock v1: same brand identity, different slide structures and narrative devices.
- Expert-reader clarity: exact situation, audience, consequence, one-sentence point, and behavior shift must be clear.
- Free Value Per Slide and Unfair Free Advantage: every slide must give a useful takeaway that feels worth saving.
- Useful density without clutter: detail is allowed only when it improves action, diagnosis, or judgment.
- Framework innovation: named frameworks must pass first-principles, practical, clarity, visual, originality, and necessity tests.
- Minimum Mobile Readability Rule: essential text must be readable on Instagram without zoom.
- Mobile Text Hierarchy Rule: use Level 1 headline, Level 2 support, Level 3 labels, and Level 4 non-essential chrome/source text.
- Slide-to-Slide Narrative Continuity Rule: each slide answers or advances the previous slide and creates a reason to continue.
- Reader Question Chain Rule: every slide has a reader question.
- One Carousel, One Argument Rule: the carousel is one guided argument, not disconnected good slides.
- Visual Continuity Rule: varied archetypes must still share motifs, chrome, palette, typography, and spacing.
- Plain Language First and Direct Slide Copy: use spoken, useful, plain English before formal terms.
- Plain-language shadow: every major framework term needs `Formal term → Plain-language meaning`.
- Narrative Bridge Rule and Connected Narrative Spine: every slide should feel like the next natural sentence in the story.
- Explain Then Name: show the problem, consequence, and repeated pattern before naming the framework.

Final handoff default: the user should only need `07-exports/visual-generation-prompts/` and `07-exports/post-copy/` for final image generation and publishing. Upstream folders are traceability files.
