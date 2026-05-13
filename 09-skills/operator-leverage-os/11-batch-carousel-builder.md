# OLS Batch Carousel Builder

## Purpose
Create multiple Operator Leverage OS carousel packages from selected topic ideas.

This orchestration skill coordinates specialist skills 03–07. By default, the final user handoff should stop with two final outputs per carousel:

1. final master visual generation prompt
2. post copy file set

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
  - full final handoff package, default for publishable carousel requests
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
Allowed output folders depend on requested depth.

Upstream planning outputs, if needed:

- `07-exports/carousel-briefs/`
- `07-exports/carousel-production-drafts/`
- `07-exports/design-prompts/`
- `07-exports/visual-execution-packs/`

Final handoff outputs, by default for publishable carousel requests:

- `07-exports/visual-generation-prompts/##_topic-slug-master-prompt.md`
- `07-exports/post-copy/##_topic-slug-post-copy.md`
- `07-exports/post-copy/##_topic-slug-post-copy.csv`

Do not create outputs beyond the requested depth. Do not make the user open upstream planning files for final copy-paste outputs.

## Step-by-step procedure
1. Confirm selected topics.
2. Check topic strength and avoid duplicates.
3. Decide output depth.
4. For each topic, run only the needed specialist sequence:
   - brief builder, if a brief is needed
   - production draft builder, if a draft is needed
   - design prompt builder, if design direction is needed
   - visual execution pack builder, if an execution pack is needed
   - visual generation prompt builder for final image prompt handoff
   - post copy creation for caption, hashtags, alt text, CTA, and posting notes
5. Maintain consistent naming and numbering.
6. Ensure final handoff files point only to:
   - `07-exports/visual-generation-prompts/`
   - `07-exports/post-copy/`
7. Create batch summary.
8. Stop at requested depth.

## Guardrails
- Do not run research unless asked.
- Do not invent new topic themes if topics are provided.
- Do not generate visuals.
- Do not create images, designed slides, Canva files, apps, APIs, dashboards, scripts, charts, integrations, automations, products, or payment workflows.
- Do not create more files than requested.
- Do not make all carousels the same format.
- Do not force flagship visual memo format on every idea.
- Do not create product bridges unless natural or requested.
- Do not duplicate the same final master prompt across many folders.
- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not create local files unless explicitly requested.
- Create full publishing packs only if explicitly requested.

## Done when
- Requested batch files are created.
- If the request is for final usable carousel outputs, each carousel has:
  - one master prompt in `07-exports/visual-generation-prompts/`
  - one Markdown post copy file in `07-exports/post-copy/`
  - one CSV post copy file in `07-exports/post-copy/`
- Batch summary is clear.

## Summary format
1. Topics processed
2. Output depth completed
3. Files created or updated
4. Specialist skills coordinated
5. Final two-folder handoff status
6. Format variety notes
7. Stopping point reached
8. Out-of-scope work avoided

## Brand Identity Lock v1 batch requirements
Batch outputs must share one Brand Identity Lock v1 while varying slide archetypes, visual objects, and argument structures.

Across a batch:

- Keep palette family, typography direction, slide chrome, spacing discipline, diagram style, and premium editorial feel consistent.
- Vary visual metaphor, framework intensity, evidence treatment, diagram type, and narrative structure.
- Avoid creating carousels that look unrelated.
- Avoid creating carousels that look like the same template with new words.

Final batch QA:

- Does the batch feel like one publication system?
- Does each carousel still have a distinct argument?
- Would a reader recognize the brand without every carousel using the same template?

## Free Value Per Slide batch requirements
Batch outputs must vary frameworks and visual objects while preserving Brand Identity Lock v1.

Before generating final prompt packages, check value density:

- Does each carousel have a clear free value promise?
- Does every slide deliver a takeaway, tool, question, diagnostic, rewrite, or practical lens?
- Are frameworks useful and necessary rather than decorative?
- Is the batch avoiding many shallow carousels produced quickly?

Guardrail: do not produce a batch that looks polished but feels thin.

## Batch mobile readability and continuity requirements
Batch outputs must include reader question chains and mobile readability checks for every carousel.

For each carousel in a batch, require:

- reader question chain;
- previous slide connection;
- reader question answered;
- reader question created;
- next slide handoff;
- one-carousel-one-argument check;
- visual continuity motif;
- transition risk;
- mobile readability risk;
- smallest meaningful text risk;
- four-level mobile text hierarchy.

## Batch guardrails for quality under speed
- Prevent fast batch generation from producing disconnected decks.
- Do not accept slides that are individually good but do not connect.
- Do not let evidence slides feel like random trend inserts.
- Do not let frameworks appear without buildup.
- Do not let application slides feel bolted on.
- Do not allow tiny essential text or unreadable diagram labels.
- Ensure every deck can pass: “Can the reader follow the carousel without feeling reset at every slide?”

## Batch final tests
- Can the reader follow each carousel without feeling reset at every slide?
- Does each slide make the next slide feel necessary?
- Is every meaningful text element readable on Instagram mobile?
- Are small labels supportive rather than essential?
- Does each carousel feel like one guided argument?

Additional exact batch gate lines:

- Can the reader follow the carousel without feeling reset at every slide?
- Does the carousel feel like one guided argument?
