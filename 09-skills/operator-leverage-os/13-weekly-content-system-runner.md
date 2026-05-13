# OLS Weekly Content System Runner

## Purpose
Coordinate a weekly Operator Leverage OS content cycle using research, content bank, analytics, and product bridge logic.

This orchestration skill helps choose the right weekly mix and then coordinates specialist skills only to the depth the user requests.

For final usable carousel outputs, the default handoff should be two folders only:

1. `07-exports/visual-generation-prompts/`
2. `07-exports/post-copy/`

## When to use
Use when the user asks to plan or run the weekly content system.

## Inputs required
- Week/date range
- Desired number of posts
- Focus pillars
- Available analytics
- Available research
- Product/bridge priorities, if any
- Desired output depth

## Source files to read
Read only the files needed for the requested weekly workflow:

- `04-content-bank/topic-bank.csv`
- `04-content-bank/first-30-posts.md`
- `08-research-bank/README.md`
- `08-research-bank/source-log.csv`
- `08-research-bank/claim-bank.csv`
- `08-research-bank/example-bank.csv`
- `08-research-bank/research-to-content-map.md`
- `06-analytics/analytics-review-template.md`
- `06-analytics/post-performance-tracker.csv`
- `05-products/product-ladder.md`
- `05-products/paid-product-ideas.md`
- `09-skills/operator-leverage-os/01-research-scan.md`
- `09-skills/operator-leverage-os/02-idea-generator.md`
- `09-skills/operator-leverage-os/03-carousel-brief-builder.md`
- `09-skills/operator-leverage-os/04-production-draft-builder.md`
- `09-skills/operator-leverage-os/05-design-prompt-builder.md`
- `09-skills/operator-leverage-os/06-visual-execution-pack-builder.md`
- `09-skills/operator-leverage-os/07-visual-generation-prompt-builder.md`
- `09-skills/operator-leverage-os/09-analytics-reviewer.md`
- `09-skills/operator-leverage-os/10-product-bridge-reviewer.md`

## Output files to create or update
Depends on the requested weekly output depth.

Planning outputs, if requested:

- Weekly planning summary
- Topic-bank updates only if explicitly requested:
  - `04-content-bank/topic-bank.csv`

Upstream carousel package outputs only if explicitly requested or needed:

- `07-exports/carousel-briefs/`
- `07-exports/carousel-production-drafts/`
- `07-exports/design-prompts/`
- `07-exports/visual-execution-packs/`

Final default handoff outputs for publishable carousel requests:

- `07-exports/visual-generation-prompts/##_topic-slug-master-prompt.md`
- `07-exports/post-copy/##_topic-slug-post-copy.md`
- `07-exports/post-copy/##_topic-slug-post-copy.csv`

## Step-by-step procedure
1. Review analytics if available and relevant.
2. Review research bank if relevant.
3. Review topic bank.
4. Recommend weekly content mix:
   - flagship visual memo
   - antithesis map
   - decision tool
   - field note
   - case lens
5. Select topics.
6. Define output depth requested.
7. Coordinate specialist skills to create required files.
8. If final usable carousel outputs are requested, stop with:
   - master prompts in `07-exports/visual-generation-prompts/`
   - post copy Markdown + CSV files in `07-exports/post-copy/`
9. Identify product bridge only where natural.
10. Create weekly summary.

## Guardrails
- Do not create dashboards.
- Do not create automatic schedules.
- Do not generate visuals.
- Do not create images, designed slides, Canva files, apps, APIs, scripts, charts, integrations, automations, products, or payment workflows.
- Do not overproduce files.
- Do not force paid product bridges.
- Do not pretend analytics are meaningful if sample size is too small.
- Do not treat all posts as flagship memos.
- Do not duplicate the same final master prompt across many folders.
- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not create local files unless explicitly requested.
- Do not edit product files, analytics files, or research-bank CSVs unless explicitly requested.
- Create full publishing packs only if explicitly requested.

## Done when
- Weekly content plan or requested files are created.
- Topic mix is balanced.
- If final handoff is requested, final outputs live in only:
  - `07-exports/visual-generation-prompts/`
  - `07-exports/post-copy/`
- Research/analytics/product logic is clearly summarized.

## Summary format
1. Week/date range
2. Inputs reviewed
3. Recommended content mix
4. Topics selected or recommended
5. Output depth completed
6. Final two-folder handoff status, if relevant
7. Product bridge notes, if any
8. Next action

## Weekly candidate readability and continuity gate
Weekly carousel candidates must pass narrative continuity and mobile readability standards before becoming full prompt packages.

Before advancing a weekly candidate, check:

- Does the candidate have one coherent argument?
- Is there a reader question chain?
- Does each planned slide connect to the previous slide?
- Does each planned slide create a reason to continue?
- Is there a visual continuity motif?
- Are transition risks identified?
- Are mobile readability risks identified?
- Is the smallest meaningful text risk identified?
- Can the concept use a four-level mobile text hierarchy?

## Weekly guardrails
- Do not advance candidates that depend on tiny essential text.
- Do not advance candidates that require dense unreadable diagrams.
- Do not advance candidates that are just disconnected good points.
- Do not advance candidates where evidence feels randomly inserted.
- Do not advance candidates where the framework appears without buildup.
- Do not advance candidates where the application slide feels bolted on.

## Weekly final tests
- Can the reader follow the carousel without feeling reset at every slide?
- Does each slide make the next slide feel necessary?
- Is every meaningful text element readable on Instagram mobile?
- Are small labels supportive rather than essential?
- Does the carousel feel like one guided argument?
