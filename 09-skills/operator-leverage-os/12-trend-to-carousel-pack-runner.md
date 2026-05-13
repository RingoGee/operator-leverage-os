# OLS Trend to Carousel Pack Runner

## Purpose
Turn a broad trend/theme request into grounded Operator Leverage OS carousel packages.

This orchestration skill coordinates research, idea generation, and carousel package creation while preserving evidence quality and caveats.

By default, final usable trend carousel handoff should stop with two outputs per carousel:

1. final master visual generation prompt
2. post copy file set

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
  - final handoff packages, default for publishable carousel requests

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
Depends on requested depth and explicit permission.

Research storage only if explicitly requested:

- `08-research-bank/source-log.csv`
- `08-research-bank/claim-bank.csv`
- `08-research-bank/example-bank.csv`
- `08-research-bank/research-notes/`

Upstream planning/package outputs only if requested or needed:

- `04-content-bank/topic-bank.csv`
- `07-exports/carousel-briefs/`
- `07-exports/carousel-production-drafts/`
- `07-exports/design-prompts/`
- `07-exports/visual-execution-packs/`

Final handoff outputs, by default for publishable carousel requests:

- `07-exports/visual-generation-prompts/##_topic-slug-master-prompt.md`
- `07-exports/post-copy/##_topic-slug-post-copy.md`
- `07-exports/post-copy/##_topic-slug-post-copy.csv`

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
8. If the user asks for final usable carousel outputs, create only the final two-folder handoff:
   - master prompt in `07-exports/visual-generation-prompts/`
   - post copy Markdown + CSV in `07-exports/post-copy/`
9. Ensure format variety.
10. Summarize sources, caveats, and outputs.

Decision gates:

- If current-trend research is required, do not proceed without credible sources.
- If research cannot be run, state that output is hypothesis-based and should not be labeled current.
- For 10 requested carousels, generate at least 15–25 candidates first, then shortlist.
- Recommend starting with 3 if the theme is untested.
- Create full publishing packs only if explicitly requested.

## Guardrails
- Do not invent trends.
- Do not fabricate sources.
- Do not generate fake statistics.
- Do not create final visuals.
- Do not create images, designed slides, Canva files, apps, APIs, dashboards, scripts, charts, integrations, automations, products, or payment workflows.
- Do not overproduce all requested carousels as heavy flagship memos.
- Do not skip evidence/caveat review.
- Do not duplicate the same final master prompt across many folders.
- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not create local files unless explicitly requested.
- Do not edit product files, analytics files, or research-bank CSVs unless explicitly requested.

## Done when
- Trend/theme is converted into grounded carousel packages to requested depth.
- If final handoff is requested, each carousel has:
  - one master prompt in `07-exports/visual-generation-prompts/`
  - one Markdown post copy file in `07-exports/post-copy/`
  - one CSV post copy file in `07-exports/post-copy/`
- Sources and caveats are summarized.
- Output batch is organized and reviewable.

## Summary format
1. Trend/theme
2. Research status and caveats
3. Candidate idea count and shortlist logic
4. Packages created or recommended
5. Output depth completed
6. Final two-folder handoff status
7. Format variety notes
8. Next decision gate

## Brand Identity Lock v1 trend-package requirements
Trend-based packages must apply Brand Identity Lock v1 while varying visual logic by theme.

For every trend package:

- Preserve the locked palette, typography, chrome, spacing, diagram language, and surface treatment.
- Choose the visual metaphor based on the trend's actual business logic.
- Keep finance/fundraising content expert-readable, plain-English, and decision-oriented when relevant.
- Avoid over-abstract visuals that look sophisticated but do not clarify the situation.
- Avoid visually overcomplicated trend packages.

Final QA:

- Does this feel like the same publication as other Operator Leverage OS posts, while still having a distinct argument?
- Would a reader recognize the brand without every carousel using the same template?

## Free Value Per Slide trend-package requirements
Trend-based content must turn research into useful reader advantage, not trend commentary.

Each trend package must teach action, diagnosis, or judgment.

Require:

- free value promise
- reader value delivered per slide
- simple but informative language
- plain-language shadows
- useful density without clutter
- framework necessity test
- first-principles framework innovation only where needed

Guardrail: reject “market update” posts that do not teach action, diagnosis, or judgment.

## Trend carousel continuity requirements
Trend-based carousels must connect research → implication → mechanism → framework → action smoothly.

Every trend-based package must include:

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

## Trend evidence guardrails
- Prevent market/evidence slides from feeling like random trend inserts.
- Evidence must answer the prior question and create the next question.
- Evidence must feed the contrast, mechanism, framework, or action.
- Do not create “market update” carousels that do not teach action, diagnosis, or judgment.
- Do not let source/caveat text carry the main argument.
- Do not use tiny evidence-card labels that require zooming.

## Trend final tests
- Can the reader follow the carousel without feeling reset at every slide?
- Does each slide make the next slide feel necessary?
- Is every meaningful text element readable on Instagram mobile?
- Are small labels supportive rather than essential?
- Does the carousel feel like one guided argument?
