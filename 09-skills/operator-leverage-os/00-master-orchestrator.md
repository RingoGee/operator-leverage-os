# OLS Master Orchestrator

## Purpose
Decide which Operator Leverage OS skill or sequence of skills should be used for a user request.

This orchestration skill coordinates the existing specialist skills. It should not duplicate their full procedures or skip their decision gates.

## When to use
Use when the user request is broad, multi-step, ambiguous, or spans multiple stages of the content supply chain.

Examples:

- “Create a batch of 10 carousels.”
- “Find trends and turn them into posts.”
- “Build next week’s content system.”
- “Audit this carousel and update the prompt.”
- “Use analytics to decide what we should make next.”

Classify the request into one of these workflows:

- Research-only
- Research → ideas
- Ideas → briefs
- Brief → production draft
- Draft → design prompt
- Design prompt → visual execution pack
- Execution pack → visual generation prompt
- Generated visual → audit
- Analytics → next content decisions
- Content/product bridge review
- Full batch build
- Weekly content run

## Inputs required
- User request
- Desired output depth, if known
- Topic, trend, brief, draft, prompt, visual output, analytics, or product signal, if available
- Any explicit constraints on files, scope, or stage boundaries

## Source files to read
Read only the files needed for the identified workflow:

- `09-skills/operator-leverage-os/01-research-scan.md`
- `09-skills/operator-leverage-os/02-idea-generator.md`
- `09-skills/operator-leverage-os/03-carousel-brief-builder.md`
- `09-skills/operator-leverage-os/04-production-draft-builder.md`
- `09-skills/operator-leverage-os/05-design-prompt-builder.md`
- `09-skills/operator-leverage-os/06-visual-execution-pack-builder.md`
- `09-skills/operator-leverage-os/07-visual-generation-prompt-builder.md`
- `09-skills/operator-leverage-os/08-carousel-auditor.md`
- `09-skills/operator-leverage-os/09-analytics-reviewer.md`
- `09-skills/operator-leverage-os/10-product-bridge-reviewer.md`
- `09-skills/operator-leverage-os/11-batch-carousel-builder.md`
- `09-skills/operator-leverage-os/12-trend-to-carousel-pack-runner.md`
- `09-skills/operator-leverage-os/13-weekly-content-system-runner.md`
- `08-research-bank/README.md`
- `08-research-bank/source-log.csv`
- `08-research-bank/claim-bank.csv`
- `08-research-bank/example-bank.csv`
- `08-research-bank/research-to-content-map.md`
- `04-content-bank/topic-bank.csv`
- `06-analytics/analytics-review-template.md`

## Output files to create or update
Usually none. This skill primarily scopes work and selects the correct next skill.

If the user explicitly requests execution after orchestration, allowed output files are determined by the selected specialist or orchestration skill.

## Step-by-step procedure
1. Interpret the user request.
2. Identify the intended stage in the supply chain.
3. Identify the relevant skill or skill sequence.
4. Decide whether research is needed.
5. Decide whether user approval is needed before moving downstream.
6. Define allowed files to create/update.
7. Prevent out-of-scope work.
8. Summarize the planned workflow before execution when the task is broad.

Decision gates:

- Do not move from research to ideas unless requested.
- Do not move from ideas to briefs unless requested.
- Do not create production drafts unless briefs are approved or user asks for batch output.
- Do not create visual prompts until design direction exists.
- Do not create products/payment work unless explicitly asked.
- Do not invent current trends without research.

## Guardrails
- Do not run research unless the selected workflow requires it and the user asked for it.
- Do not create content outputs during orchestration unless explicitly asked to execute the selected workflow.
- Do not generate visuals.
- Do not create products, payment links, dashboards, scripts, charts, integrations, automations, apps, APIs, or executable code.
- Do not skip specialist skill guardrails.
- Do not create generic carousel-system-builder skills.

## Done when
- The correct skill sequence is identified.
- The allowed outputs are clear.
- The next Codex action is scoped.

## Summary format
1. Interpreted request
2. Recommended workflow classification
3. Skill or skill sequence to use
4. Decision gates / stopping points
5. Allowed files to create or update
6. Out-of-scope items blocked
7. Next recommended action
