# Operator Leverage OS Skills

This folder contains the Operator Leverage OS-specific Codex skill chain for running the content supply system.

These are Markdown workflow instructions, not executable automations. Use them one step at a time so each stage remains reviewable and doctrine-compliant.

## The 10-skill production chain

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

- Use the skills one step at a time.
- Codex should not skip downstream steps unless explicitly asked.
- Research and evidence must remain honest.
- Examples must not be presented as research.
- Visual generation itself is not done inside Codex unless the user later uses an external image/design tool.
- Free content should remain intellectually complete.
- Paid product bridges should only appear when they are natural and explicitly relevant.
