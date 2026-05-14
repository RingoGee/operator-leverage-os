# How To Use This Repo

Use this repo as the operating base for the brand.

## Weekly workflow
1. Review the brand foundation.
2. Pick one primary content pillar for the week.
3. Select topics from the content bank.
4. Turn each topic into an infographic-led carousel brief.
5. Separate the free mental model from any paid implementation asset.
6. Track post and payment performance after publishing.

## Rule of thumb
If an idea sounds like a tool tutorial, convert it into a thinking framework first.

## Codex skills
Reusable Codex workflow instructions live in `09-skills/README.md`. Use them when you want Codex to run a specific repeatable workflow, such as research scanning, idea generation, carousel brief creation, visual output auditing, analytics review, or product bridge review.

## Research bank
Use `08-research-bank/` for source logs, claim banks, example banks, and research-to-content mapping before turning research into topic ideas or carousel briefs.

## Local exports
Use `10-local-export-guides/publishing-pack-convention.md` when moving approved repo work into local access. The default local export is only the final visual generation prompt in `exports/visual-prompts/`, so it can be copied into ChatGPT Images or another image/design tool. Full publishing packs for final images, captions, and post archives are optional and should be used only when explicitly needed. GitHub stays the source of truth for Markdown/CSV planning files.

## Final handoff folders

Final publishing and image-generation handoff defaults point only to:

1. `07-exports/visual-generation-prompts/`
   - Purpose: one final copyable master image-generation prompt per carousel.
   - Naming: `##_topic-slug-master-prompt.md`.

2. `07-exports/post-copy/`
   - Purpose: caption, short caption, caption hook options, CTA, hashtags, alt text, source note, and posting notes.
   - Naming: `##_topic-slug-post-copy.md` and `##_topic-slug-post-copy.csv`.
   - Required CSV columns: `carousel_id,title,caption,short_caption,caption_hook_options,cta,hashtags,alt_text,source_note,posting_notes`.

The user should not need to open `07-exports/carousel-briefs/`, `07-exports/carousel-production-drafts/`, `07-exports/design-prompts/`, or `07-exports/visual-execution-packs/` for final publishing or image generation. Those upstream folders may remain for traceability.
