# OLS Visual Generation Prompt Builder

## Purpose
Create the final master visual generation prompt file for a specific Operator Leverage OS carousel.

This is the final visual handoff file. It is the only visual prompt file the user should copy into ChatGPT Images or another image generation tool.

## When to use
Use when the carousel direction is ready for image generation and the user needs one clean copyable master prompt.

Upstream files such as briefs, production drafts, design prompts, and visual execution packs may exist for traceability and quality control, but they are not the final user handoff.

## Inputs required
- Approved carousel direction from the latest available upstream files
- Target image generation tool, if known
- Optional feedback from prior visual attempts
- Carousel number / ID and topic slug

## Source files to read
Read only what is needed to create the final master prompt:

- Relevant file in `07-exports/visual-execution-packs/`, if present
- Relevant design prompt, production draft, and brief, if needed for accuracy
- `02-editorial-system/visual-carousel-rules.md`
- `03-carousel-system/carousel-quality-checklist.md`

## Output files to create or update
Create exactly one final visual handoff file by default:

- `07-exports/visual-generation-prompts/##_topic-slug-master-prompt.md`

Do not create duplicate final master prompts in `design-prompts/`, `visual-execution-packs/`, local folders, or publishing-pack folders unless explicitly requested.

## Prompt file must include
- Carousel title
- Carousel ID / number
- Intended image generation tool
- Full copyable master visual generation prompt
- Slide count and format
- Brand identity lock
- Slide-by-slide generation instructions
- Text accuracy instructions
- Final generation checklist

## Step-by-step procedure
1. Read the latest approved upstream direction only as needed.
2. Preserve the carousel’s argument, slide order, evidence caveats, and Brand Identity Lock v1.
3. Build one full copyable master prompt.
4. Make the prompt tool-ready for ChatGPT Images or another image generation tool.
5. Include slide count, format, locked chrome, and slide-by-slide generation instructions.
6. Include strict text accuracy instructions so the image tool does not invent claims, numbers, logos, or extra copy.
7. Save the file under `07-exports/visual-generation-prompts/` using `##_topic-slug-master-prompt.md`.
8. Stop. Do not create images, designed slides, Canva files, local exports, or publishing packs.

## Guardrails
- Do not generate images.
- Do not create designed slides.
- Do not create Canva files.
- Do not create apps, APIs, dashboards, scripts, charts, integrations, automations, products, or payment workflows.
- Do not create a new carousel concept.
- Do not change the core argument.
- Do not create product CTA unless approved.
- Do not create more than one final master prompt file unless asked.
- Do not make `design-prompts/` the final handoff folder.
- Do not make `visual-execution-packs/` the final handoff folder.
- Do not require the user to open upstream planning files for publishing.
- Do not create local files unless explicitly requested.

## Done when
- One master prompt file exists in `07-exports/visual-generation-prompts/`.
- The file is directly copyable into ChatGPT Images or another image generation tool.
- The file follows `##_topic-slug-master-prompt.md` naming.
- The prompt includes title, ID, intended tool, full copyable prompt, slide count/format, brand lock, slide instructions, text accuracy instructions, and final checklist.
- No out-of-scope files or visual assets were created.

## Summary format
1. File created
2. Prompt structure
3. Key generation constraints
4. Whether ready for visual generation
5. Confirmation that the final visual handoff is only in `07-exports/visual-generation-prompts/`
6. Confirmation of no out-of-scope work

## Brand Identity Lock v1 requirements
Final master prompts must include a locked identity block.

The prompt must preserve:

- Warm Ivory / Soft Paper White background
- Deep Charcoal / Near Black text and linework
- Dark Forest Green main accent
- Slate Blue evidence/source cards
- Proof Orange / Controlled Amber for gates, bottlenecks, and key questions
- Muted Red / Rust only for risk, leakage, false paths, or friction
- Deep Green for proof, confidence, verification, or readiness
- Display serif for major conceptual headlines
- Clean modern sans-serif for labels, notes, diagrams, and body text
- Optional mono-style only for small source tags, memo codes, or field-manual markers
- Stable top-left series label, top-right slide number, bottom-left Operator Leverage OS mark, consistent safe margins, and quiet footer/source lines when needed
- Clean line diagrams, structured cards, purposeful arrows, evidence cards, decision gates, proof trails, ladders, maps, matrices, or teardown panels where useful

## Free Value Per Slide final prompt requirements
Every final prompt must preserve reader value slide by slide.

The master prompt must instruct the image tool to make each slide teach, diagnose, clarify, compare, filter, rewrite, or help the reader decide.

The final prompt must protect:

- simple but informative language
- one dominant takeaway per slide
- useful density without clutter
- source/caveat legibility where relevant
- visual logic over decoration
- mental-model-led content over tool-led content

## Mobile readability and narrative continuity instructions for final prompts
Every final visual generation prompt must explicitly instruct the image tool:

- “Keep all essential text readable on Instagram mobile.”
- “Do not use tiny text for essential meaning.”
- “Make every diagram label readable without zooming.”
- “Make each slide visually and narratively connect to the next.”
- “The deck should feel like one guided argument, not eight separate cards.”

Final prompts must also include a **Reader Question Chain** block that lists the reader question answered by each slide.

## Final prompt continuity requirements
Each final prompt must include:

- previous slide connection;
- reader question answered;
- reader question created;
- next slide handoff;
- one-carousel-one-argument rule;
- visual continuity motif;
- transition risk;
- mobile readability risk;
- smallest meaningful text risk;
- four-level mobile text hierarchy.

## Text accuracy and readability guardrails
- Essential text must never be microcopy.
- The smallest meaningful text must be comfortably readable on a phone.
- Level 1 and Level 2 text must be instantly readable.
- Level 3 labels must be readable without zoom.
- Level 4 source/caveat/chrome text must remain minimal and non-essential.
- Small labels must support the slide, not carry the argument.
- If a generated slide would need many tiny labels, simplify the slide into fewer larger blocks.

## Final prompt tests
- Can the reader follow the carousel without feeling reset at every slide?
- Does each slide make the next slide feel necessary?
- Is every meaningful text element readable on Instagram mobile?
- Are small labels supportive rather than essential?
- Does the carousel feel like one guided argument?
