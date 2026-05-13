# Codex Skills

This folder contains reusable Codex workflows for running repeatable work inside the Operator Leverage OS repository.

These skills are **not executable automations**. They are Markdown operating procedures that tell Codex which repo files to read, which outputs are allowed, which guardrails apply, and how to summarize the work for review.

## Current skill families

- `operator-leverage-os/` — Operator Leverage OS-specific workflows for the content supply chain.
- `utility/` — supporting repo-operation and export workflows.

The generic reusable Instagram carousel design-system skill family is intentionally **not included yet**. This pass only creates skills for the Operator Leverage OS brand and operating system.

## How to use these skills

Use a skill by pasting or referencing the relevant file in a Codex task, for example:

> Use `09-skills/operator-leverage-os/03-carousel-brief-builder.md` to create a carousel brief for this selected topic.

Each skill should be used one step at a time unless the user explicitly asks Codex to run multiple workflow steps together.

## Review model

All repo work should remain reviewable through GitHub pull requests. Skills may describe how to create or update Markdown/CSV planning files, but they should not imply automatic API usage, app building, dashboards, scripts, payment workflows, image generation, or automation workflows.

## Source-of-truth rule

Before using a skill, Codex should read the source files listed inside that skill. The source files keep the work aligned with the Operator Leverage OS doctrine-first, evidence-backed, visual-strategy-memo direction.
