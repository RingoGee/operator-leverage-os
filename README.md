# Operator Leverage OS

This repository is the working base for the Operator Leverage OS content and product operating system.

Start here:

- [Main operating-system guide](00-start-here/README.md)
- [How to use this repo](00-start-here/how-to-use-this-repo.md)

This root README is only an entry point. The main guidance lives inside `00-start-here/`.

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
