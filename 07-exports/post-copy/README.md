# Post Copy Exports

## Purpose
This folder contains the final publishing copy for approved Operator Leverage OS carousels.

Use this folder only for final post-copy handoff files. The user should not need to open upstream working folders for publishing copy.

## Final handoff relationship
Final usable output folders are only:

1. `07-exports/visual-generation-prompts/`
   - One final copyable master image-generation prompt per carousel.
   - Required naming convention: `##_topic-slug-master-prompt.md`.

2. `07-exports/post-copy/`
   - Caption, short caption, caption hook options, CTA, hashtags, alt text, source note, and posting notes.
   - Required naming conventions:
     - `##_topic-slug-post-copy.md`
     - `##_topic-slug-post-copy.csv`

Upstream folders may remain for traceability, but they are not the final handoff location:
- `07-exports/carousel-briefs/`
- `07-exports/carousel-production-drafts/`
- `07-exports/design-prompts/`
- `07-exports/visual-execution-packs/`

## Required CSV columns
Every post-copy CSV must use exactly these columns:

```csv
carousel_id,title,caption,short_caption,caption_hook_options,cta,hashtags,alt_text,source_note,posting_notes
```

## Post-copy quality rules
Post-copy should preserve the same doctrine as the carousel:

- Plain Language First: write in simple, useful English.
- Free Value Per Slide: the caption should reinforce the useful takeaway, not merely describe the design.
- Unfair Free Advantage: free post copy should make the thinking feel valuable, not thin or sales-heavy.
- One Carousel, One Argument Rule: the caption, CTA, and posting notes should support the same core argument as the carousel.
- Plain-language shadow: any formal framework term used in the caption should be translated in plain English.
- Free/paid boundary: free content teaches the thinking; paid products, if mentioned, help implement the thinking.

## Guardrails
Do not create post-copy files unless explicitly asked for a specific approved carousel.

Do not use this folder for:
- carousel briefs;
- production drafts;
- design prompts;
- visual execution packs;
- final image files;
- dashboards;
- payment links;
- automations.
