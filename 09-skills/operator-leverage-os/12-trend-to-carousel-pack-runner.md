# OLS Trend to Carousel Pack Runner

## Purpose
Turn a broad trend/theme request into grounded Operator Leverage OS carousel prompt packages.

This orchestration skill coordinates research, idea generation, and carousel package creation while preserving evidence quality and caveats.

## When to use
Use when the user asks for content based on current or emerging trends, such as:

- Latest investment trends
- Fundraising tactics
- Workplace AI adoption
- Founder productivity patterns
- Operator career leverage
- Corporate appraisal season
- Investor communication trends

## Inputs required
- Trend/theme
- Number of carousel packages requested
- Geography/market, if relevant
- Freshness requirement
- Desired output depth:
  - research summary only
  - research + ideas
  - briefs
  - full prompt packages

## Source files to read
- `08-research-bank/README.md`
- `08-research-bank/source-log.csv`
- `08-research-bank/claim-bank.csv`
- `08-research-bank/example-bank.csv`
- `08-research-bank/research-to-content-map.md`
- `09-skills/operator-leverage-os/01-research-scan.md`
- `09-skills/operator-leverage-os/02-idea-generator.md`
- `09-skills/operator-leverage-os/03-carousel-brief-builder.md`
- `09-skills/operator-leverage-os/04-production-draft-builder.md`
- `09-skills/operator-leverage-os/05-design-prompt-builder.md`
- `09-skills/operator-leverage-os/06-visual-execution-pack-builder.md`
- `09-skills/operator-leverage-os/07-visual-generation-prompt-builder.md`

## Output files to create or update
Depends on requested depth and explicit permission:

- Research storage only if explicitly requested:
  - `08-research-bank/source-log.csv`
  - `08-research-bank/claim-bank.csv`
  - `08-research-bank/example-bank.csv`
  - `08-research-bank/research-notes/`
- Content planning/package outputs only if requested:
  - `04-content-bank/topic-bank.csv`
  - `07-exports/carousel-briefs/`
  - `07-exports/carousel-production-drafts/`
  - `07-exports/design-prompts/`
  - `07-exports/visual-execution-packs/`
  - `07-exports/visual-generation-prompts/`

## Step-by-step procedure
1. Define trend research question.
2. Run or request grounded research.
3. Store research only if explicitly requested.
4. Extract claims, examples, patterns, and caveats.
5. Generate more candidate ideas than needed.
6. Shortlist ideas using:
   - audience relevance
   - evidence strength
   - originality
   - visual potential
   - product/brand fit
7. Create requested number of carousel packages to requested depth.
8. Ensure format variety.
9. Summarize sources, caveats, and outputs.

Decision gates:

- If current-trend research is required, do not proceed without credible sources.
- If research cannot be run, state that output is hypothesis-based and should not be labeled current.
- For 10 requested carousels, generate at least 15–25 candidates first, then shortlist.
- Recommend starting with 3 if the theme is untested.

## Guardrails
- Do not invent trends.
- Do not fabricate sources.
- Do not generate fake statistics.
- Do not create final visuals.
- Do not create products/payment workflows.
- Do not overproduce all 10 as heavy flagship memos.
- Do not skip evidence/caveat review.
- Do not create dashboards, scripts, charts, integrations, automations, apps, APIs, or executable code.

## Done when
- Trend/theme is converted into grounded carousel packages to requested depth.
- Sources and caveats are summarized.
- Output batch is organized and reviewable.

## Summary format
1. Trend/theme
2. Research status and caveats
3. Candidate idea count and shortlist logic
4. Packages created or recommended
5. Output depth completed
6. Format variety notes
7. Next decision gate
