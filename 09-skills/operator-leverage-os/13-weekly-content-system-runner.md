# OLS Weekly Content System Runner

## Purpose
Coordinate a weekly Operator Leverage OS content cycle using research, content bank, analytics, and product bridge logic.

This orchestration skill helps choose the right weekly mix and then coordinates specialist skills only to the depth the user requests.

## When to use
Use when the user asks to plan or run the weekly content system.

## Inputs required
- Week/date range
- Desired number of posts
- Focus pillars
- Available analytics
- Available research
- Product/bridge priorities, if any

## Source files to read
- `04-content-bank/topic-bank.csv`
- `04-content-bank/first-30-posts.md`
- `08-research-bank/README.md`
- `08-research-bank/research-to-content-map.md`
- `06-analytics/analytics-review-template.md`
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
Depends on the requested weekly output depth:

- Weekly planning summary, if requested
- Topic-bank updates only if explicitly requested:
  - `04-content-bank/topic-bank.csv`
- Carousel package outputs only if explicitly requested:
  - `07-exports/carousel-briefs/`
  - `07-exports/carousel-production-drafts/`
  - `07-exports/design-prompts/`
  - `07-exports/visual-execution-packs/`
  - `07-exports/visual-generation-prompts/`

## Step-by-step procedure
1. Review analytics if available.
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
8. Identify product bridge only where natural.
9. Create weekly summary.

## Guardrails
- Do not create dashboards.
- Do not create automatic schedules.
- Do not generate visuals.
- Do not overproduce files.
- Do not force paid product bridges.
- Do not pretend analytics are meaningful if sample size is too small.
- Do not treat all posts as flagship memos.
- Do not create products, payment workflows, scripts, charts, integrations, automations, apps, APIs, or executable code.

## Done when
- Weekly content plan or requested files are created.
- Topic mix is balanced.
- Research/analytics/product logic is clearly summarized.

## Summary format
1. Week/date range
2. Inputs reviewed
3. Recommended content mix
4. Topics selected or recommended
5. Output depth completed
6. Product bridge notes, if any
7. Next action
