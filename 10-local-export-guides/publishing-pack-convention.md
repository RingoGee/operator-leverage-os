# Local Export and Publishing-Pack Convention

## Purpose

Use this guide to keep Operator Leverage OS local exports organized after repo work is approved.

The default local export is **not** a full publishing pack. The default is one final visual generation prompt file saved locally for quick copying into ChatGPT Images or another image/design tool.

GitHub remains the source of truth for thinking, planning, prompts, and reviewable Markdown/CSV files. Local export folders are convenience shelves for prompt copying, image generation, design production, publishing, or archiving.

This guide documents the convention only. It does not require creating any local folders until a local workflow is actually being run on a local computer.

## Default local export: quick visual prompt export

Use this when the user only needs the final visual prompt quickly.

This should be the default local export behavior.

### Local structure

```text
exports/
  visual-prompts/
```

### File naming

Use this pattern:

```text
YYYY-MM-DD_##_topic-slug_visual-prompt.md
```

Examples:

```text
2026-05-13_07_capital-concentration-proof-stack_visual-prompt.md
2026-05-13_08_investor-update-diligence-file_visual-prompt.md
2026-05-13_09_liquidity-pressure-narrative_visual-prompt.md
```

If no publishing date is confirmed, use the local export creation date.

### What the quick visual prompt file should contain

The one local Markdown file should contain:

- carousel title
- source repo file path
- full copyable visual generation prompt
- short usage notes
- generation checklist

### What the quick visual prompt file should not contain

Do not copy unnecessary source files locally by default.

The quick export should not include:

- carousel brief copy
- production draft copy
- design prompt copy
- visual execution pack copy
- research-bank copies
- generated images
- edited design files
- captions
- screenshots
- published records

Those stay in GitHub or belong in the optional full publishing pack only when explicitly requested.

## Sample local Codex prompt

Use this when working with local Codex or a local manual workflow:

> Create a quick local visual prompt export for carousel 09. Work only inside `exports/visual-prompts/`. Read the final visual generation prompt from `repo/07-exports/visual-generation-prompts/[file]`. Create one local Markdown file containing the full copyable prompt and usage notes. Do not modify repo files.

## Optional local export: full publishing pack

Use a full publishing pack only when the user explicitly wants to organize final images, edited designs, captions, publishing records, or archives.

This workflow is optional and heavier than the default quick visual prompt export.

Use it when the asset is moving beyond prompt copying into actual publishing production.

## Two working modes

### Mode A: GitHub-first source workflow

Use this mode while Codex is creating, editing, or reviewing source material.

GitHub should store:

- Brand and editorial doctrine
- Research-bank structure and research notes
- Topic banks and planning CSVs
- Carousel briefs
- Production drafts
- Design prompts
- Visual execution packs
- Visual generation prompt files
- Caption drafts or caption directions
- Analytics templates and lightweight trackers
- Product strategy notes and product bridge logic

GitHub should stay reviewable, text-first, and lightweight.

### Mode B: Optional full local publishing-pack workflow

Use this mode after a carousel or content asset is ready for image generation, editing, export, scheduling, publishing, or archiving.

Local publishing-pack folders may store:

- Final generated images
- Edited design files or Canva exports
- Platform-ready carousel images
- Final captions copied into publishing tools
- Thumbnail or cover variants
- Platform screenshots
- Publishing checklist copies
- Archive copies of what was actually posted

Local export folders are production shelves, not the doctrine source of truth.

## Optional full publishing-pack folder structure

Use one top-level local folder for the operating system and keep the repo separate from exports.

```text
Operator-Leverage-OS/
  repo/
    operator-leverage-os/
  exports/
    visual-prompts/
      2026-05-13_09_liquidity-pressure-narrative_visual-prompt.md
    publishing-packs/
      2026-05/
        2026-05-13_09_liquidity-pressure-narrative/
          01-source-from-github/
          02-generated-visuals/
          03-edited-designs/
          04-final-platform-assets/
          05-caption-and-post-copy/
          06-published-record/
    final-carousels/
    captions/
    research-exports/
    archives/
```

Do not mirror the entire GitHub repo inside every publishing pack. Each pack should only contain the local files needed to publish, verify, and archive one asset.

## Optional publishing-pack naming convention

Use this pattern:

```text
YYYY-MM-DD_##_short-topic-slug
```

Where:

- `YYYY-MM-DD` = intended publishing date or pack creation date.
- `##` = repo content number when available.
- `short-topic-slug` = lowercase topic name with hyphens.

Examples:

```text
2026-05-13_07_capital-concentration-proof-stack
2026-05-13_08_investor-update-diligence-file
2026-05-13_09_liquidity-pressure-narrative
```

## Optional file naming convention inside a publishing pack

Use the same topic number and slug across every file.

```text
09_liquidity-pressure-narrative_generation-prompt.md
09_liquidity-pressure-narrative_slide-01.png
09_liquidity-pressure-narrative_slide-02.png
09_liquidity-pressure-narrative_cover-option-a.png
09_liquidity-pressure-narrative_caption-final.txt
09_liquidity-pressure-narrative_published-record.md
```

Keep local file names boring and predictable. The goal is retrieval, not cleverness.

## What belongs in GitHub vs local exports

| Asset type | GitHub | Quick local visual prompt export | Optional full publishing pack |
| --- | --- | --- | --- |
| Brand doctrine | Yes | No | No, except occasional read-only reference copies |
| Research notes and source logs | Yes | No | Only if needed for a local production handoff |
| Topic bank | Yes | No | No |
| Carousel brief | Yes | No | Optional copied reference |
| Production draft | Yes | No | Optional copied reference |
| Design prompt | Yes | No | Optional copied reference |
| Visual execution pack | Yes | No | Optional copied reference |
| Visual generation prompt | Yes | Yes, final prompt only | Optional copied reference |
| Generated images | No, unless explicitly approved | No | Yes |
| Edited Canva/design files | No | No | Yes |
| Final platform-ready images | No | No | Yes |
| Final caption text | Optional if text-only and reviewable | No | Yes |
| Publishing screenshots | No | No | Yes |
| Published post archive | Optional summary only | No | Yes |
| Heavy exports and videos | No | No | Yes |

## Optional publishing-pack subfolders

### `01-source-from-github/`

Use for copied reference files only when a local designer, founder, or operator needs everything in one place.

Suggested contents:

- Final visual generation prompt copy
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

Use for final publishing text.

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

## GitHub source-to-local export handoff checklist

Before creating a quick local visual prompt export, confirm:

- [ ] The final visual generation prompt is the correct current file.
- [ ] The source repo file path is included in the local export.
- [ ] The local export contains the full copyable prompt.
- [ ] The local export includes short usage notes and a generation checklist.
- [ ] No unnecessary source files are copied locally.

Before creating a full local publishing pack, confirm:

- [ ] The user explicitly requested a full publishing pack.
- [ ] The carousel brief is approved or intentionally skipped.
- [ ] The production draft is approved or intentionally skipped.
- [ ] The design prompt is approved.
- [ ] The visual generation prompt is final for the current attempt.
- [ ] Evidence and caveats are source-backed.
- [ ] No fake statistics were introduced.
- [ ] The paid bridge is optional and implementation-led, if present.
- [ ] The local pack name matches the repo number and topic slug.

## Local generation checklist

Before generating visuals from the quick local prompt, confirm:

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

- Default to quick local visual prompt export.
- Create a full publishing pack only when explicitly requested.
- Do not copy unnecessary source files locally.
- Keep GitHub as the source of truth for briefs, drafts, design prompts, visual execution packs, and visual generation prompt files.
- Treat local quick exports as convenience copies only.
- Do not store heavy image, video, or design exports in GitHub by default.
- Do not let local folders become the only source of approved thinking.
- Do not overwrite GitHub source files from local copies without review.
- Do not mix multiple carousels inside one optional publishing pack.
- Do not use local exports to bypass evidence, design, or carousel quality checks.

## Summary rule

GitHub is the operating brain. Quick local visual prompt exports are convenience copies. Full local publishing packs are optional production shelves.

Keep the brain reviewable. Keep the quick export lightweight. Use the shelf only when publishing production needs it.

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
