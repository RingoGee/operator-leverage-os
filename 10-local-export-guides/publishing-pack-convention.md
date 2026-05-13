# Local Publishing-Pack Convention

## Purpose

Use this guide to keep Operator Leverage OS publishing assets organized after repo work is approved.

GitHub remains the source of truth for thinking, planning, prompts, and reviewable Markdown/CSV files. Local export folders are for final production assets that are too heavy, too visual, or too platform-specific for the repo.

This guide documents the convention only. It does not require creating any local folders until a publishing workflow is actually being run on a local computer.

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

### Mode B: Local publishing-pack workflow

Use this mode after a carousel or content asset is ready for design, export, scheduling, or publishing.

Local export folders should store:

- Final generated images
- Edited design files or Canva exports
- Platform-ready carousel images
- Final captions copied into publishing tools
- Thumbnail or cover variants
- Platform screenshots
- Publishing checklist copies
- Archive copies of what was actually posted

Local export folders are production shelves, not the doctrine source of truth.

## Recommended local folder structure

Use one top-level local folder for the operating system and keep the repo separate from exports.

```text
Operator-Leverage-OS/
  repo/
    operator-leverage-os/
  exports/
    publishing-packs/
      2026-05/
        2026-05-13_07_capital-concentration-proof-stack/
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

## Publishing-pack naming convention

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

If no publishing date is confirmed, use the pack creation date and update the published record later.

## File naming convention inside a publishing pack

Use the same topic number and slug across every file.

```text
07_capital-concentration-proof-stack_brief-source.md
07_capital-concentration-proof-stack_generation-prompt.md
07_capital-concentration-proof-stack_slide-01.png
07_capital-concentration-proof-stack_slide-02.png
07_capital-concentration-proof-stack_cover-option-a.png
07_capital-concentration-proof-stack_caption-final.txt
07_capital-concentration-proof-stack_published-record.md
```

Keep local file names boring and predictable. The goal is retrieval, not cleverness.

## What belongs in GitHub vs local exports

| Asset type | GitHub | Local export folder |
| --- | --- | --- |
| Brand doctrine | Yes | No, except occasional read-only reference copies |
| Research notes and source logs | Yes | Only if needed for a local production handoff |
| Topic bank | Yes | No |
| Carousel brief | Yes | Optional copied reference |
| Production draft | Yes | Optional copied reference |
| Design prompt | Yes | Optional copied reference |
| Visual execution pack | Yes | Optional copied reference |
| Visual generation prompt | Yes | Optional copied reference |
| Generated images | No, unless explicitly approved | Yes |
| Edited Canva/design files | No | Yes |
| Final platform-ready images | No | Yes |
| Final caption text | Optional if text-only and reviewable | Yes |
| Publishing screenshots | No | Yes |
| Published post archive | Optional summary only | Yes |
| Heavy exports and videos | No | Yes |

## Recommended publishing-pack subfolders

### `01-source-from-github/`

Use for copied reference files only when a local designer, founder, or operator needs everything in one place.

Suggested contents:

- Brief copy
- Production draft copy
- Design prompt copy
- Visual generation prompt copy

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

Before creating a local publishing pack, confirm:

- [ ] The carousel brief is approved or intentionally skipped.
- [ ] The production draft is approved or intentionally skipped.
- [ ] The design prompt is approved.
- [ ] The visual generation prompt is final for the current attempt.
- [ ] Evidence and caveats are source-backed.
- [ ] No fake statistics were introduced.
- [ ] The paid bridge is optional and implementation-led, if present.
- [ ] The local pack name matches the repo number and topic slug.

## Local publishing checklist

Before publishing, confirm:

- [ ] Final slide order is correct.
- [ ] Source/caveat text is legible where needed.
- [ ] No generated image added fake numbers, fake logos, or fake claims.
- [ ] The cover creates tension without over-answering.
- [ ] The final slide creates a behavior shift or profile-entry reason.
- [ ] Caption matches the final carousel argument.
- [ ] Published record is saved locally after posting.

## Guardrails

- Do not store heavy image, video, or design exports in GitHub by default.
- Do not let local folders become the only source of approved thinking.
- Do not create local publishing packs until an asset is ready for design/export/publishing.
- Do not overwrite GitHub source files from local copies without review.
- Do not mix multiple carousels inside one publishing pack.
- Do not use local exports to bypass evidence, design, or carousel quality checks.

## Summary rule

GitHub is the operating brain. Local publishing packs are the production shelf.

Keep the brain reviewable. Keep the shelf organized.
