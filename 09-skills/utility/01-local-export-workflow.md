# Local Export Workflow

## Purpose
Document how to move from Codex/GitHub repo work to local computer files.

## When to use
Use when the user wants outputs saved or organized on their computer, or wants to understand how Codex web repo work connects to local folders.

## Inputs required
- Repo location
- Desired local export folder
- Type of asset
- Whether the asset should stay in repo or local archive

## Source files to read
- `00-start-here/how-to-use-this-repo.md`
- `09-skills/README.md`
- Relevant `07-exports` files

## Output files to create or update
Usually none unless explicitly asked.

May update:

- `10-local-export-guides/` if created later
- `00-start-here/how-to-use-this-repo.md` if explicitly requested

## Step-by-step procedure
1. Identify whether the user needs repo source files, local final assets, or both.
2. Explain Mode A — GitHub-first workflow:
   - Codex web creates PRs.
   - User reviews and merges.
   - User pulls latest repo locally.
   - Repo stores source files:
     - briefs
     - drafts
     - prompts
     - captions
     - research notes
     - analytics trackers
     - metadata
3. Explain Mode B — Local export workflow:
   - User uses local terminal, local Codex, or a local manual workflow to save generated outputs to local folders.
   - Local folders store heavy/final assets:
     - final images
     - Canva exports
     - video exports
     - publishing packs
     - archives
4. Recommend this local folder structure:

   ```text
   Operator-Leverage-OS/
     repo/
     exports/
       final-carousels/
       captions/
       publishing-packs/
       research/
       archives/
   ```

5. Clarify what belongs in GitHub and what belongs locally.
6. Ask any open setup questions only if needed.

## Guardrails
- Do not assume Codex CLI is installed.
- Do not create files outside the repo.
- Do not include complex executable commands.
- Do not store heavy image/video exports in the repo unless explicitly intended.
- Keep GitHub as source of truth for Markdown/CSV planning files.

## Done when
- Local vs repo storage is clearly explained.
- The user knows what belongs in GitHub vs local folders.
- No actual local files are created.

## Summary format
1. Workflow documented
2. GitHub-first mode
3. Local export mode
4. What belongs in repo
5. What belongs locally
6. Open setup questions
