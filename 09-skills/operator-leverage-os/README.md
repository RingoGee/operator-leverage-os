# Operator Leverage OS Skills

This folder contains the Operator Leverage OS-specific Codex skill chain for running the content supply system.

These are Markdown workflow instructions, not executable automations. Use them one step at a time so each stage remains reviewable and doctrine-compliant.

## Orchestration skills

- `00-master-orchestrator.md` — coordinates all skills and selects the right workflow.
- `11-batch-carousel-builder.md` — handles multiple selected carousel topics.
- `12-trend-to-carousel-pack-runner.md` — handles trend/theme-to-package workflows.
- `13-weekly-content-system-runner.md` — handles weekly content cycles.

## The 10 specialist skills

1. `01-research-scan.md` — Research scan
2. `02-idea-generator.md` — Idea generation
3. `03-carousel-brief-builder.md` — Carousel brief builder
4. `04-production-draft-builder.md` — Production draft builder
5. `05-design-prompt-builder.md` — Design prompt builder
6. `06-visual-execution-pack-builder.md` — Visual execution pack builder
7. `07-visual-generation-prompt-builder.md` — Visual generation prompt builder
8. `08-carousel-auditor.md` — Carousel auditor
9. `09-analytics-reviewer.md` — Analytics reviewer
10. `10-product-bridge-reviewer.md` — Product bridge reviewer

## Pipeline

Grounded research
→ topic candidates
→ topic bank
→ carousel brief
→ production draft
→ design prompt
→ visual execution pack
→ visual generation prompt
→ generated visual
→ audit
→ publishing decision
→ analytics review
→ product bridge decision

## Usage rules

- Use the skills one step at a time. Use orchestration skills only to coordinate sequence, decision gates, stopping points, and allowed outputs.
- Codex should not skip downstream steps unless explicitly asked.
- Research and evidence must remain honest.
- Examples must not be presented as research.
- Visual generation itself is not done inside Codex unless the user later uses an external image/design tool.
- Free content should remain intellectually complete.
- Paid product bridges should only appear when they are natural and explicitly relevant.

## Current skill-chain rules

Every skill in this chain must enforce:
- Brand Identity Lock v1: same brand identity, different slide structures and narrative devices.
- Free Value Per Slide and Unfair Free Advantage.
- Expert-reader clarity.
- Minimum Mobile Readability Rule and Mobile Text Hierarchy Rule.
- Slide-to-Slide Narrative Continuity Rule, Reader Question Chain Rule, One Carousel, One Argument Rule, Narrative Bridge Rule, and Connected Narrative Spine.
- Plain Language First, Plain-language shadow, Direct Slide Copy, and Explain Then Name.

Final handoff defaults are `07-exports/visual-generation-prompts/` for the master prompt and `07-exports/post-copy/` for captions, hooks, CTA, hashtags, alt text, source note, and posting notes.
