# Codex Skills

This folder contains reusable Codex workflows for running repeatable work inside the Operator Leverage OS repository.

These skills are **not executable automations**. They are Markdown operating procedures that tell Codex which repo files to read, which outputs are allowed, which guardrails apply, and how to summarize the work for review.

## Where final carousel handoffs live

Future carousel generation tasks should default to two final handoff folders:

1. `07-exports/visual-generation-prompts/`
   - final copyable master prompt for ChatGPT Images or another image generation tool
   - naming convention: `##_topic-slug-master-prompt.md`

2. `07-exports/post-copy/`
   - final caption, CTA, hashtags, alt text, source note, and posting notes
   - naming conventions:
     - `##_topic-slug-post-copy.md`
     - `##_topic-slug-post-copy.csv`

Upstream folders can still exist for traceability, but skills should not make the user open briefs, production drafts, design prompts, or visual execution packs for final publishing handoff.

## Current skill families

- `operator-leverage-os/` — Operator Leverage OS-specific workflows for the content supply chain.
- `utility/` — supporting repo-operation and export workflows.

The generic reusable Instagram carousel design-system skill family is intentionally **not included yet**. This pass only creates skills for the Operator Leverage OS brand and operating system.

Some skills are specialist workflows for one production step. Others are orchestration workflows that coordinate multiple specialist skills without bypassing their guardrails.

## How to use these skills

Use a skill by pasting or referencing the relevant file in a Codex task, for example:

> Use `09-skills/operator-leverage-os/03-carousel-brief-builder.md` to create a carousel brief for this selected topic.

Each skill should be used one step at a time unless the user explicitly asks Codex to run multiple workflow steps together.

## Review model

All repo work should remain reviewable through GitHub pull requests. Skills may describe how to create or update Markdown/CSV planning files, but they should not imply automatic API usage, app building, dashboards, scripts, payment workflows, image generation, or automation workflows.

## Source-of-truth rule

Before using a skill, Codex should read the source files listed inside that skill. The source files keep the work aligned with the Operator Leverage OS doctrine-first, evidence-backed, visual-strategy-memo direction.

## Final handoff guardrails

- Do not duplicate the same final master prompt across many folders.
- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not create local files unless explicitly requested.
- Do not generate images, designed slides, Canva files, apps, APIs, dashboards, scripts, automations, products, or payment workflows.
