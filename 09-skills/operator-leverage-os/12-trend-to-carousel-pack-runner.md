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
  - `07-exports/post-copy/`

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

## Brand Identity Lock v1 trend-package requirements
Trend-based packages must apply Brand Identity Lock v1 while varying visual logic by theme.

For every trend package:

- Preserve the locked palette, typography, chrome, spacing, diagram language, and surface treatment.
- Choose the visual metaphor based on the trend's actual business logic.
- Keep finance/fundraising content expert-readable, plain-English, and decision-oriented.
- Avoid over-abstract finance/fundraising visuals that look sophisticated but do not clarify the situation.
- Avoid visually overcomplicated trend packages.

Final QA:

- Does this feel like the same publication as other Operator Leverage OS posts, while still having a distinct argument?
- Would a reader recognize the brand without every carousel using the same template?

## Free Value Per Slide trend-package requirements
Trend-based content must turn research into useful reader advantage, not trend commentary.

Each trend package must teach action, diagnosis, or judgment.

Require:

- free value promise;
- reader value delivered per slide;
- simple but informative language;
- plain-language shadows;
- useful density without clutter;
- framework necessity test;
- first-principles framework innovation only where needed.

Guardrail: reject “market update” posts that do not teach action, diagnosis, or judgment.

## Trend-to-carousel plain-language translation gate
Trend-based carousels must translate market language into simple operator implications.

Rules:
- Do not let trend commentary become abstract, overformal, or finance-jargon-heavy.
- Explain what the trend means for a founder, operator, investor, or team in plain English.
- Put formal market language in notes unless it makes the slide clearer.
- Give every market or framework term a plain-language shadow.
- Build one narrative spine before creating packages.
- Make evidence slides create the next practical question.
- Explain the problem and repeated pattern before naming any framework.

Trend package tests:
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
