# Operator Leverage OS Skills

This folder contains the Operator Leverage OS-specific Codex skill chain for running the content supply system.

These are Markdown workflow instructions, not executable automations. Use them one step at a time so each stage remains reviewable and doctrine-compliant.

## Where to find final outputs

Future carousel generation tasks should stop with two final handoff outputs by default:

1. **Final image generation prompt:** `07-exports/visual-generation-prompts/`
   - One master prompt per carousel.
   - This is the only visual prompt file the user should copy into ChatGPT Images or another image generation tool.
   - Naming convention: `##_topic-slug-master-prompt.md`.

2. **Final caption/tags/posting text:** `07-exports/post-copy/`
   - One Markdown file and one CSV file per carousel.
   - Naming conventions:
     - `##_topic-slug-post-copy.md`
     - `##_topic-slug-post-copy.csv`

Do not make the user hunt through carousel briefs, production drafts, design prompts, or visual execution packs for final copy-paste outputs. Those upstream files may still exist for traceability and quality control, but the default user handoff points only to the two folders above.

## Orchestration skills

- `00-master-orchestrator.md` — coordinates all skills and selects the right workflow.
- `11-batch-carousel-builder.md` — handles multiple selected carousel topics.
- `12-trend-to-carousel-pack-runner.md` — handles trend/theme-to-package workflows.
- `13-weekly-content-system-runner.md` — handles weekly content cycles.

## The 10 specialist skills

1. `01-research-scan.md` — Research scan
2. `02-idea-generator.md` — Idea generation
3. `03-carousel-brief-builder.md` — Carousel brief builder
4. `04-production-draft-builder.md` — Production draft builder
5. `05-design-prompt-builder.md` — Design prompt builder
6. `06-visual-execution-pack-builder.md` — Visual execution pack builder
7. `07-visual-generation-prompt-builder.md` — Final master visual generation prompt builder
8. `08-carousel-auditor.md` — Carousel auditor
9. `09-analytics-reviewer.md` — Analytics reviewer
10. `10-product-bridge-reviewer.md` — Product bridge reviewer

## Pipeline

Grounded research
→ topic candidates
→ topic bank
→ carousel brief
→ production draft
→ design prompt
→ visual execution pack
→ **final master visual generation prompt**
→ **post copy file set**
→ optional external image generation
→ optional audit
→ publishing decision
→ analytics review
→ product bridge decision

## Usage rules

- Use the skills one step at a time. Use orchestration skills only to coordinate sequence, decision gates, stopping points, and allowed outputs.
- Codex should not skip downstream steps unless explicitly asked.
- Research and evidence must remain honest.
- Examples must not be presented as research.
- Visual generation itself is not done inside Codex unless the user later uses an external image/design tool.
- Free content should remain intellectually complete.
- Paid product bridges should only appear when they are natural and explicitly relevant.
- Full publishing packs remain optional and should only be created if explicitly requested.

## Final handoff guardrails

- Do not duplicate the same final master prompt across many folders.
- Do not make `07-exports/design-prompts/` the final handoff folder.
- Do not make `07-exports/visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not create local files unless explicitly requested.
- Do not create images, designed slides, Canva files, apps, APIs, dashboards, scripts, automations, products, or payment workflows.

## Global readability and continuity gate
Before any future carousel becomes a final prompt package, the relevant skill must enforce:

- minimum mobile readability;
- no essential microcopy;
- four-level text hierarchy;
- reader question chain;
- previous slide connection;
- reader question answered;
- reader question created;
- next slide handoff;
- one-carousel-one-argument rule;
- visual continuity motif;
- transition risk;
- mobile readability risk;
- smallest meaningful text risk.

Final gate questions:

- Can the reader follow the carousel without feeling reset at every slide?
- Does each slide make the next slide feel necessary?
- Is every meaningful text element readable on Instagram mobile?
- Are small labels supportive rather than essential?
- Does the carousel feel like one guided argument?
