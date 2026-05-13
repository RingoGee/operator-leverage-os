# Local Export Workflow

## Purpose
Document how to move from Codex/GitHub repo work to local computer files.

Default local export is now the final visual generation prompt only. This is the file the user usually needs to copy into ChatGPT Images or another image/design tool.

## When to use
Use when the user wants local access to a repo output or wants to understand how Codex web repo work connects to local folders.

Use the quick local prompt export by default when the user only needs the final visual prompt quickly.

Use the full local publishing pack only when the user explicitly asks to organize final images, edited designs, captions, publishing records, or archives.

## Inputs required
- Repo location
- Desired local export folder
- Selected carousel number or final visual generation prompt file
- Whether the user wants:
  - quick local visual prompt export, default
  - full local publishing pack, optional/heavy

## Source files to read
- `00-start-here/how-to-use-this-repo.md`
- `09-skills/README.md`
- Relevant final prompt in `07-exports/visual-generation-prompts/`
- `10-local-export-guides/publishing-pack-convention.md`, only if the user asks for a full publishing pack

## Output files to create or update
Usually none inside the repo unless explicitly asked.

When working locally, the default output should be one local Markdown file under:

- `exports/visual-prompts/`

Do not create full local publishing-pack folders unless explicitly requested.

May update repo documentation only when explicitly requested:

- `10-local-export-guides/`
- `00-start-here/how-to-use-this-repo.md`

## Step-by-step procedure
1. Identify whether the user needs quick prompt access or a full publishing archive.
2. Default to Mode A — Quick local visual prompt export:
   - Read the final visual generation prompt from `repo/07-exports/visual-generation-prompts/`.
   - Create one local Markdown file in `exports/visual-prompts/`.
   - Include only the final copyable prompt and essential usage context.
   - Do not copy briefs, production drafts, design prompts, or visual execution packs unless explicitly requested.
   - Treat the local file as convenience copy, not the source of truth.
3. Use Mode B — Full local publishing pack only if explicitly requested:
   - Use when the user wants to organize final images, edited design files, captions, platform-ready assets, screenshots, and published records.
   - Follow `10-local-export-guides/publishing-pack-convention.md`.
   - Keep the full folder structure optional and heavy.
4. Explain Mode C — GitHub-first source workflow:
   - Codex web creates PRs.
   - User reviews and merges.
   - User pulls latest repo locally.
   - Repo stores source files:
     - briefs
     - drafts
     - design prompts
     - visual execution packs
     - visual generation prompt files
     - captions or caption directions
     - research notes
     - analytics trackers
     - metadata
5. Clarify what belongs in GitHub and what belongs locally.
6. Ask open setup questions only if needed.

## Quick local visual prompt export convention
Use this local folder:

```text
exports/
  visual-prompts/
```

Use this file naming pattern:

```text
YYYY-MM-DD_##_topic-slug_visual-prompt.md
```

Example:

```text
2026-05-13_09_liquidity-pressure-narrative_visual-prompt.md
```

The local Markdown file should contain:

- carousel title
- source repo file path
- full copyable visual generation prompt
- short usage notes
- generation checklist

## Sample local Codex prompt
Use this when working with local Codex or a local manual workflow:

> Create a quick local visual prompt export for carousel 09. Work only inside `exports/visual-prompts/`. Read the final visual generation prompt from `repo/07-exports/visual-generation-prompts/[file]`. Create one local Markdown file containing the full copyable prompt and usage notes. Do not modify repo files.

## What belongs in GitHub
GitHub remains the source of truth for reviewable Markdown/CSV work:

- Brand doctrine
- Research notes and source logs
- Topic banks
- Carousel briefs
- Production drafts
- Design prompts
- Visual execution packs
- Visual generation prompt files
- Caption drafts or directions
- Analytics templates
- Product strategy notes

## What belongs locally by default
The default local export should contain only:

- final visual prompt copy
- usage notes
- generation checklist

This exists so the user can quickly copy the prompt into ChatGPT Images or another image/design tool.

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
- Default to quick local visual prompt export.
- Create a full publishing pack only when explicitly requested.
- Do not copy unnecessary source files locally.
- Keep the repo as source of truth for briefs, drafts, design prompts, visual execution packs, and visual generation prompt files.
- Treat the local quick export as convenience only.
- Do not assume Codex CLI is installed.
- Do not create files outside the user-requested local export folder.
- Do not include complex executable commands.
- Do not store heavy image/video exports in the repo unless explicitly intended.
- Do not generate images or designed slides.

## Done when
- The default quick local visual prompt export is clearly explained.
- The optional full publishing-pack workflow is clearly separated.
- The user knows what belongs in GitHub vs local folders.
- No actual local files are created unless the user is running a local workflow and explicitly asks for them.

## Summary format
1. Workflow documented
2. Default quick local visual prompt export
3. Optional full publishing-pack workflow
4. What belongs in repo
5. What belongs locally
6. Open setup questions
