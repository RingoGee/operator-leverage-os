# Local Export and Publishing-Pack Convention

## Purpose
Use this guide to keep Operator Leverage OS final handoffs and optional local exports simple.

The repo default is not a local publishing pack. The repo default is two final handoff folders:

1. `07-exports/visual-generation-prompts/` — final copyable image generation prompts.
2. `07-exports/post-copy/` — final caption, hashtags, alt text, CTA, and posting notes.

Local export folders are optional convenience shelves. Do not create local files unless a local workflow is explicitly requested.

## Where to find final outputs in the repo

### Image generation prompt
Use:

```text
07-exports/visual-generation-prompts/
```

Purpose:

- Contains the final copyable master prompt for each carousel.
- This is the only visual prompt file the user should copy into ChatGPT Images or another image generation tool.

Naming convention:

```text
##_topic-slug-master-prompt.md
```

Each file should contain:

- Carousel title
- Carousel ID / number
- Intended image generation tool
- Full copyable master visual generation prompt
- Slide count and format
- Brand identity lock
- Slide-by-slide generation instructions
- Text accuracy instructions
- Final generation checklist

### Caption, hashtags, and posting text
Use:

```text
07-exports/post-copy/
```

Purpose:

- Contains the final posting text assets for each carousel.
- This is where the user should open captions, hashtags, alt text, CTA, and posting notes.

Naming conventions:

```text
##_topic-slug-post-copy.md
##_topic-slug-post-copy.csv
```

The Markdown file should contain:

- Carousel title
- Carousel ID / number
- Primary caption
- Short caption alternative
- Caption hook options
- CTA
- Hashtags
- Alt text / accessibility description
- Suggested first comment, if useful
- Posting notes
- Caveats / source note, if relevant

The CSV file should contain these columns:

```csv
carousel_id,title,caption,short_caption,caption_hook_options,cta,hashtags,alt_text,source_note,posting_notes
```

## Upstream files are not the final handoff

These folders may still exist for quality control and traceability:

- `07-exports/carousel-briefs/`
- `07-exports/carousel-production-drafts/`
- `07-exports/design-prompts/`
- `07-exports/visual-execution-packs/`

However:

- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not duplicate the same final master prompt across many folders.

## Optional local export: quick final handoff copy

Use this only when the user explicitly asks for local files.

Local structure may look like:

```text
exports/
  visual-prompts/
  post-copy/
```

Default local export scope:

- copy the final master prompt from `07-exports/visual-generation-prompts/`
- copy the final post copy Markdown and/or CSV from `07-exports/post-copy/`

Do not copy unnecessary source files locally by default.

## Sample local Codex prompt

Use this when working with local Codex or a local manual workflow:

> Copy the final handoff files for carousel 13 into my local export folder. Use only the matching file from `repo/07-exports/visual-generation-prompts/` and the matching files from `repo/07-exports/post-copy/`. Do not copy briefs, production drafts, design prompts, visual execution packs, research files, product files, analytics files, or create a full publishing pack.

## Optional local export: full publishing pack

Use a full publishing pack only when the user explicitly wants to organize final images, edited designs, platform-ready assets, publishing records, screenshots, or archives.

This workflow is optional and heavier than the default final handoff.

## Optional full publishing-pack folder structure

Use one top-level local folder for the operating system and keep the repo separate from exports.

```text
Operator-Leverage-OS/
  repo/
    operator-leverage-os/
  exports/
    visual-prompts/
      13_ai-productivity-is-a-work-design-problem-master-prompt.md
    post-copy/
      13_ai-productivity-is-a-work-design-problem-post-copy.md
      13_ai-productivity-is-a-work-design-problem-post-copy.csv
    publishing-packs/
      2026-05/
        2026-05-13_13_ai-productivity-is-a-work-design-problem/
          01-source-from-github/
          02-generated-visuals/
          03-edited-designs/
          04-final-platform-assets/
          05-caption-and-post-copy/
          06-published-record/
```

Do not mirror the entire GitHub repo inside every publishing pack. Each pack should only contain the local files needed to publish, verify, and archive one asset.

## What belongs in GitHub vs local exports

| Asset type | GitHub | Quick local final handoff copy | Optional full publishing pack |
| --- | --- | --- | --- |
| Brand doctrine | Yes | No | No, except occasional read-only reference copies |
| Research notes and source logs | Yes | No | Only if explicitly needed for a local production handoff |
| Topic bank | Yes | No | No |
| Carousel brief | Yes | No | Optional copied reference only if explicitly requested |
| Production draft | Yes | No | Optional copied reference only if explicitly requested |
| Design prompt | Yes | No | Optional copied reference only if explicitly requested |
| Visual execution pack | Yes | No | Optional copied reference only if explicitly requested |
| Final master visual generation prompt | Yes, in `07-exports/visual-generation-prompts/` | Yes | Optional copied reference |
| Final post copy | Yes, in `07-exports/post-copy/` | Yes | Yes |
| Generated images | No, unless explicitly approved | No | Yes |
| Edited Canva/design files | No | No | Yes |
| Final platform-ready images | No | No | Yes |
| Publishing screenshots | No | No | Yes |
| Published post archive | Optional summary only | No | Yes |
| Heavy exports and videos | No | No | Yes |

## Optional publishing-pack subfolders

### `01-source-from-github/`

Use for copied reference files only when a local designer, founder, or operator needs everything in one place.

Suggested contents:

- Final visual generation prompt copy
- Final post copy copy
- Brief copy, only if explicitly needed
- Production draft copy, only if explicitly needed
- Design prompt copy, only if explicitly needed

Do not treat copied files here as the source of truth. If the content changes, update GitHub first.

### `02-generated-visuals/`

Use for first-pass image outputs from external image/design tools.

Suggested contents:

- Raw generated slide images
- Failed attempts worth comparing
- Alternate cover attempts

### `03-edited-designs/`

Use for working design files and manual edits.

Suggested contents:

- Canva exports
- Design-tool working files
- Revised slide images
- Human-edited versions

### `04-final-platform-assets/`

Use only for the files intended to upload to a platform.

Suggested contents:

- Final slide images in order
- Final cover image
- Platform-specific versions if needed

### `05-caption-and-post-copy/`

Use for final publishing text copied from `07-exports/post-copy/` only when a full publishing pack is explicitly requested.

Suggested contents:

- Final caption
- Alt text, if used
- Hashtags, if used
- First comment, if used
- Platform notes

### `06-published-record/`

Use as the archive of what actually went live.

Suggested contents:

- Published URL
- Publishing date
- Final caption copy
- Screenshot of live post
- Notes on any deviation from the GitHub source files

## Repo final handoff checklist

Before calling a carousel ready for user handoff, confirm:

- [ ] The final master visual generation prompt is in `07-exports/visual-generation-prompts/`.
- [ ] The final master prompt uses `##_topic-slug-master-prompt.md`.
- [ ] The final master prompt is directly copyable into ChatGPT Images or another image generation tool.
- [ ] The matching post copy Markdown file is in `07-exports/post-copy/`.
- [ ] The matching post copy CSV file is in `07-exports/post-copy/`.
- [ ] The post copy files use `##_topic-slug-post-copy.md` and `##_topic-slug-post-copy.csv`.
- [ ] Source notes and caveats are present when evidence is used.
- [ ] No final handoff requires the user to open design prompts or visual execution packs.

## Local generation checklist

Before generating visuals from the final master prompt, confirm:

- [ ] The prompt source path matches the intended carousel.
- [ ] The full copyable prompt is present.
- [ ] The prompt says not to add fake numbers, fake logos, or fake claims.
- [ ] The prompt includes slide count and locked chrome instructions.
- [ ] The prompt includes post-generation review checks.

## Local publishing checklist

Before publishing from a full publishing pack, confirm:

- [ ] Final slide order is correct.
- [ ] Source/caveat text is legible where needed.
- [ ] No generated image added fake numbers, fake logos, or fake claims.
- [ ] The cover creates tension without over-answering.
- [ ] The final slide creates a behavior shift or profile-entry reason.
- [ ] Caption matches the final carousel argument.
- [ ] Published record is saved locally after posting.

## Guardrails

- Default to the two repo final handoff folders.
- Create local files only when explicitly requested.
- Create a full publishing pack only when explicitly requested.
- Do not copy unnecessary source files locally.
- Do not duplicate the same final master prompt across many folders.
- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not store heavy image, video, or design exports in GitHub by default.
- Do not let local folders become the only source of approved thinking.
- Do not overwrite GitHub source files from local copies without review.
- Do not mix multiple carousels inside one optional publishing pack.
- Do not use local exports to bypass evidence, design, or carousel quality checks.
- Do not generate images, designed slides, Canva files, apps, APIs, dashboards, scripts, automations, products, or payment workflows.

## Summary rule

GitHub is the operating brain. The final user handoff is two folders:

- `07-exports/visual-generation-prompts/` for image generation prompts
- `07-exports/post-copy/` for captions, tags, alt text, CTA, source notes, and posting notes

Local exports and full publishing packs are optional shelves. Use them only when explicitly requested.
