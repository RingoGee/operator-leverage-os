# Utility Skills

Utility workflows support export and handoff. They are not executable automations.

## Where to find final carousel outputs

The final default carousel handoff lives in two repo folders:

1. `07-exports/visual-generation-prompts/`
   - final copyable master prompt for ChatGPT Images or another image generation tool
   - naming convention: `##_topic-slug-master-prompt.md`

2. `07-exports/post-copy/`
   - final caption, CTA, hashtags, alt text, source notes, and posting notes
   - naming conventions:
     - `##_topic-slug-post-copy.md`
     - `##_topic-slug-post-copy.csv`

## Local export rule

Local exports are optional and should only happen when explicitly requested.

If the user asks for a local export, copy only the final visual prompt and/or post copy by default. Do not copy upstream planning folders unless explicitly requested.

## Available utility workflow

- `01-local-export-workflow.md` — explains optional local copying of final handoff files and optional full publishing packs.

## Guardrails

- Do not duplicate the same final master prompt across many folders.
- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not create local files unless explicitly requested.
- Do not generate images, designed slides, Canva files, apps, APIs, dashboards, scripts, automations, products, or payment workflows.
