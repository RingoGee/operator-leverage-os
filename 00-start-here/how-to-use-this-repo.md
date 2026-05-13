# How To Use This Repo

Use this repo as the operating base for the Operator Leverage OS brand.

## Where to find final outputs

You should only need to open two folders for final usable carousel handoff files:

1. **Image generation prompt:** `07-exports/visual-generation-prompts/`
   - This folder contains one final copyable master visual generation prompt per carousel.
   - Copy this prompt into ChatGPT Images or another image generation tool.
   - Naming convention: `##_topic-slug-master-prompt.md`.

2. **Caption, tags, and posting text:** `07-exports/post-copy/`
   - This folder contains the final posting text assets for each carousel.
   - Open this folder for captions, short captions, CTA, hashtags, alt text, source notes, and posting notes.
   - Naming conventions:
     - `##_topic-slug-post-copy.md`
     - `##_topic-slug-post-copy.csv`

Do not use `07-exports/design-prompts/` or `07-exports/visual-execution-packs/` as the final user handoff. Those folders can still exist as upstream planning files, but they are not where the user should copy final outputs from.

## Weekly workflow
1. Review the brand foundation.
2. Pick one primary content pillar for the week.
3. Select topics from the content bank.
4. Turn each topic into an infographic-led carousel brief.
5. Build upstream planning files only when useful for quality.
6. Finish with the two final handoff outputs:
   - master visual generation prompt in `07-exports/visual-generation-prompts/`
   - post copy Markdown + CSV in `07-exports/post-copy/`
7. Separate the free mental model from any paid implementation asset.
8. Track performance only after publishing.

## Rule of thumb
If an idea sounds like a tool tutorial, convert it into a thinking framework first.

## Codex skills
Reusable Codex workflow instructions live in `09-skills/README.md`. Use them when you want Codex to run a specific repeatable workflow, such as research scanning, idea generation, carousel brief creation, final master prompt creation, post copy creation, visual output auditing, analytics review, or product bridge review.

## Research bank
Use `08-research-bank/` for source logs, claim banks, example banks, and research-to-content mapping before turning research into topic ideas or carousel briefs.

Do not edit research-bank CSVs unless the task explicitly asks for research storage or research-bank maintenance.

## Local exports
Use `10-local-export-guides/publishing-pack-convention.md` only when moving approved repo work into local access.

Local exports are optional. Do not create local files unless explicitly requested.

When a local export is requested, copy only the final visual prompt and/or post copy by default:

- final prompt from `07-exports/visual-generation-prompts/`
- post copy from `07-exports/post-copy/`

Full publishing packs remain optional and should be created only when explicitly requested. GitHub stays the source of truth for Markdown/CSV planning files.

## Global carousel quality standards
Every future carousel must now pass two repo-wide quality gates before final handoff:

1. **Instagram mobile readability:** every meaningful text element must be readable on a phone; small labels may support but cannot carry the argument.
2. **Slide-to-slide continuity:** every slide must answer or advance the previous slide and create a reason to continue.

Use the global doctrine and checklist files for these gates:

- `01-brand-foundation/visual-identity.md`
- `02-editorial-system/thought-leadership-doctrine.md`
- `02-editorial-system/visual-carousel-rules.md`
- `03-carousel-system/infographic-carousel-template.md`
- `03-carousel-system/carousel-quality-checklist.md`
