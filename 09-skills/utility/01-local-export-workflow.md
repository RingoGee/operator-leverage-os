# Local Export Workflow

## Purpose
Document how to move from Codex/GitHub repo work to local computer files.

The repo now has a simple final carousel handoff:

1. final image generation prompt in `07-exports/visual-generation-prompts/`
2. final post copy in `07-exports/post-copy/`

Local exports are optional. Do not create local files unless the user explicitly asks for them.

## When to use
Use when the user wants local access to a repo output or wants to understand how Codex web repo work connects to local folders.

Use quick local export only when the user explicitly asks to copy final prompt and/or post copy out of the repo.

Use a full local publishing pack only when the user explicitly asks to organize final images, edited designs, captions, publishing records, or archives.

## Inputs required
- Repo location
- Desired local export folder
- Selected carousel number or final file name
- Whether the user wants:
  - final visual prompt export
  - final post copy export
  - both final handoff files
  - full local publishing pack, optional/heavy

## Source files to read
- `00-start-here/how-to-use-this-repo.md`
- `09-skills/README.md`
- Relevant final prompt in `07-exports/visual-generation-prompts/`
- Relevant final post copy in `07-exports/post-copy/`
- `10-local-export-guides/publishing-pack-convention.md`, only if the user asks for a full publishing pack

## Output files to create or update
Usually none inside the repo unless explicitly asked.

When working locally and explicitly requested, copy only the selected final handoff files by default:

- visual prompt from `07-exports/visual-generation-prompts/`
- post copy from `07-exports/post-copy/`

Do not create full local publishing-pack folders unless explicitly requested.

May update repo documentation only when explicitly requested:

- `10-local-export-guides/`
- `00-start-here/how-to-use-this-repo.md`

## Step-by-step procedure
1. Identify whether the user needs repo final handoff files, quick local copies, or a full publishing archive.
2. If the user only needs final outputs in the repo, point them to:
   - image generation prompt: `07-exports/visual-generation-prompts/`
   - caption/tags/posting text: `07-exports/post-copy/`
3. If quick local export is explicitly requested:
   - Copy only the relevant final master prompt and/or post copy files.
   - Do not copy briefs, production drafts, design prompts, visual execution packs, research-bank files, product files, or analytics files.
   - Treat local copies as convenience copies, not the source of truth.
4. Use full local publishing pack only if explicitly requested:
   - Use when the user wants to organize generated images, edited design files, captions, platform-ready assets, screenshots, and published records.
   - Follow `10-local-export-guides/publishing-pack-convention.md`.
   - Keep the full folder structure optional and heavy.
5. Clarify what belongs in GitHub and what belongs locally.
6. Ask setup questions only if needed.

## Final repo handoff convention
The final repo handoff folders are:

```text
07-exports/
  visual-generation-prompts/
    ##_topic-slug-master-prompt.md
  post-copy/
    ##_topic-slug-post-copy.md
    ##_topic-slug-post-copy.csv
```

## Sample local Codex prompt
Use this when working with local Codex or a local manual workflow:

> Copy the final handoff files for carousel 13 into my local export folder. Use only `repo/07-exports/visual-generation-prompts/13_topic-slug-master-prompt.md` and `repo/07-exports/post-copy/13_topic-slug-post-copy.*`. Do not copy briefs, production drafts, design prompts, visual execution packs, research files, product files, analytics files, or create a full publishing pack.

## What belongs in GitHub
GitHub remains the source of truth for reviewable Markdown/CSV work:

- Brand doctrine
- Research notes and source logs
- Topic banks
- Carousel briefs
- Production drafts
- Design prompts
- Visual execution packs
- Final master visual generation prompts
- Final post copy Markdown and CSV files
- Analytics templates
- Product strategy notes

## What belongs in the final user handoff by default
The final user handoff should contain only:

- final copyable master visual generation prompt
- caption, short caption, hook options, CTA, hashtags, alt text, source note, and posting notes

This exists so the user can quickly copy the visual prompt into ChatGPT Images or another image generation tool, then copy the caption/tags from the matching post-copy file.

## What belongs locally only when a full publishing pack is requested
Use full local publishing packs for:

- final generated images
- edited design files or Canva exports
- platform-ready carousel images
- final captions copied into publishing tools
- thumbnail or cover variants
- platform screenshots
- published-record archives

## Guardrails
- Default to the two repo final handoff folders.
- Create local files only when explicitly requested.
- Create a full publishing pack only when explicitly requested.
- Do not copy unnecessary source files locally.
- Do not duplicate the same final master prompt across many folders.
- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not store heavy image/video exports in the repo unless explicitly intended.
- Do not generate images or designed slides.
- Do not create apps, APIs, dashboards, scripts, charts, integrations, automations, products, or payment workflows.

## Done when
- The final two-folder repo handoff is clearly explained.
- Optional local export is clearly separated.
- Optional full publishing-pack workflow is clearly separated.
- The user knows what belongs in GitHub vs local folders.
- No actual local files are created unless the user is running a local workflow and explicitly asks for them.

## Summary format
1. Workflow documented
2. Final repo handoff folders
3. Optional quick local export scope
4. Optional full publishing-pack scope
5. Out-of-scope work avoided
