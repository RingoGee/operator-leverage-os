# OLS Batch Carousel Builder

## Purpose
Create multiple Operator Leverage OS carousel production packages from selected topic ideas.

This orchestration skill coordinates specialist skills 03–07. It should stop at the output depth requested by the user.

## When to use
Use when the user wants a batch of carousels from an existing set of selected ideas or topic-bank rows.

Important: this skill assumes topics are already selected or available. If the user asks for “latest trends,” use `12-trend-to-carousel-pack-runner.md` instead.

## Inputs required
- Number of carousels
- Selected topics or topic-bank IDs
- Desired output depth:
  - briefs only
  - briefs + production drafts
  - briefs + production drafts + design prompts
  - full prompt packages
- Optional pillar/audience/product bridge constraints

## Source files to read
- `04-content-bank/topic-bank.csv`
- `02-editorial-system/thought-leadership-doctrine.md`
- `03-carousel-system/carousel-quality-checklist.md`
- `09-skills/operator-leverage-os/03-carousel-brief-builder.md`
- `09-skills/operator-leverage-os/04-production-draft-builder.md`
- `09-skills/operator-leverage-os/05-design-prompt-builder.md`
- `09-skills/operator-leverage-os/06-visual-execution-pack-builder.md`
- `09-skills/operator-leverage-os/07-visual-generation-prompt-builder.md`

## Output files to create or update
Allowed output folders depend on requested depth:

- `07-exports/carousel-briefs/`
- `07-exports/carousel-production-drafts/`
- `07-exports/design-prompts/`
- `07-exports/visual-execution-packs/`
- `07-exports/visual-generation-prompts/`

Do not create outputs beyond the requested depth.

## Step-by-step procedure
1. Confirm selected topics.
2. Check topic strength and avoid duplicates.
3. Decide output depth.
4. For each topic, run the relevant specialist skill sequence:
   - brief builder
   - production draft builder
   - design prompt builder
   - visual execution pack builder
   - visual generation prompt builder
5. Maintain consistent naming and numbering.
6. Create batch summary.
7. Stop at requested depth.

## Guardrails
- Do not run research unless asked.
- Do not invent new topic themes if topics are provided.
- Do not generate visuals.
- Do not create more files than requested.
- Do not make all carousels the same format.
- Do not force flagship visual memo format on every idea.
- Do not create product bridges unless natural or requested.
- Do not create products, payment workflows, dashboards, scripts, APIs, apps, or integrations.

## Done when
- Requested batch files are created.
- Each carousel package is complete to the requested depth.
- Batch summary is clear.

## Summary format
1. Topics processed
2. Output depth completed
3. Files created or updated
4. Specialist skills coordinated
5. Format variety notes
6. Stopping point reached
7. Out-of-scope work avoided

## Brand Identity Lock v1 batch requirements
Batch outputs must share one Brand Identity Lock v1 while varying slide archetypes, visual objects, and argument structures.

Across a batch:

- Keep palette family, typography direction, slide chrome, spacing discipline, diagram style, and premium editorial feel consistent.
- Vary visual metaphor, framework intensity, evidence treatment, diagram type, and narrative structure.
- Avoid creating 10 carousels that look unrelated.
- Avoid creating 10 carousels that look like the same template with new words.

Final batch QA:

- Does the batch feel like one publication system?
- Does each carousel still have a distinct argument?
- Would a reader recognize the brand without every carousel using the same template?

## Free Value Per Slide batch requirements
Batch outputs must vary frameworks and visual objects while preserving Brand Identity Lock v1.

Before generating full prompt packages, check value density:

- Does each carousel have a clear free value promise?
- Does every slide deliver a takeaway, tool, question, diagnostic, rewrite, or practical lens?
- Are frameworks useful and necessary rather than decorative?
- Is the batch avoiding many shallow carousels produced quickly?

Guardrail: do not produce a batch that looks polished but feels thin.
