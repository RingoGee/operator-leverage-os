# Operator Leverage OS

A repo-based operating system for building a faceless Instagram content brand around AI systems, operator thinking, and leverage.

## Working brand idea
AI systems for people operating above their pay grade.

## Core positioning
This is not a generic AI automation channel. It is a visual, mental-model-led content brand for ambitious operators, founders, solopreneurs, and corporate professionals globally who want to think, communicate, and operate above their formal role.

## Core belief
The future does not belong to people who know the most AI tools. It belongs to people who can turn messy work into clear systems.

## Repository principle
This repository should stay Markdown-first and CSV-first unless the founder explicitly asks for code or an app.

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
