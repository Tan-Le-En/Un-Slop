---
name: unslop
description: Makes AI-generated work look and read like it was made by a skilled human professional. Use whenever the user asks to create, review, audit, critique, improve, redesign, or polish a website, landing page, UI, poster, infographic, chart, slide deck, brand identity, or piece of writing, and especially when they mention "AI slop", "generic", "looks AI-made", "make it better", "unsloppify", "more professional", "art direction", or "design review". Also use it proactively before delivering any visual or written deliverable, even if the user never says the word slop.
---

# UNSLOP

Goal: work that is intentional, specific, clear, and well made. Not "less AI". Not minimalism. A playful, loud, maximalist or colourful piece can pass; a clean grey one can fail.

Core diagnosis: slop is the statistical average of everything a model has seen. It comes from decisions nobody made. Defaults (a font, a gradient, a sentence shape) fill the gap where a choice should be. Every rule below is a way to force a real choice.

## Pick a mode

| User wants | Mode | Read |
|---|---|---|
| Make something new | CREATE | workflows/creation.md |
| Find what is wrong | AUDIT | workflows/auditing.md |
| Improve existing work, keep its purpose | REFACTOR | workflows/refactoring.md |
| Decide a direction, identity, look | ART DIRECTION | workflows/art-direction.md |
| Check before saying "done" | FINAL QC | workflows/final-quality-control.md |

Modes combine. CREATE always ends with FINAL QC. If unclear, ask one short question, otherwise choose and state the assumption.

## Operating rules

1. **Decide before you draw or write.** Settle audience, purpose, medium, one-sentence concept, and what the reader should notice first. No concept, no output.
2. **Every element earns its place.** If you cannot say what a gradient, card, shadow, icon, adjective, or paragraph does for the reader, remove it.
3. **Specific beats generic.** Real nouns, real numbers the user supplied, real constraints. Never invent facts, statistics, quotes, testimonials, sources, awards or achievements. Use clearly marked placeholders instead.
4. **Defaults are suspects.** When a first instinct arrives (Inter, purple-blue gradient, three icon cards, "delve", "It's not just X, it's Y", a rule-of-three list), stop and decide whether it is a real choice for this brief. Keep it only if it is.
5. **Beware the second wave.** Banning the obvious tell tends to produce the next most probable look (cream and terracotta, near-black with one acid accent, serif-italic headline). Pick from the brief, not from "what looks non-AI".
6. **Hierarchy first.** One clear focal point. Squint test: the top two or three things must survive blur.
7. **Craft is the signal.** Consistent spacing scale, shared alignment axes, a small type scale, matched margins, real contrast. Most perceived quality comes from here.
8. **Function over appearance.** Working links, readable text, responsive layout, accessible contrast (WCAG 2.2 AA: 4.5:1 body, 3:1 large text and UI). Beauty never offsets broken function or false content.
9. **Preserve intent.** Keep the user's message, essential facts, identity and constraints. Refactor, do not reinvent, unless asked.
10. **Separate taste from defects.** Label each finding OBJECTIVE (contrast fails, misaligned, unreadable, false claim) or JUDGMENT (a style call). Do not present taste as fact.
11. **Push back when the instruction weakens the result.** Say why in one or two sentences, offer a better alternative, then follow the user's decision.
12. **Context decides style.** Museum, kids' science fair, bank, indie game and funeral home want different work. Never impose one aesthetic.

## Reference map (load only what the task needs)

- Any task, first time: references/framework-pillars.md (the 8 pillars and sub-frameworks A to F)
- Text: references/writing-excellence.md
- Web or app UI: references/website-design.md, references/typography.md
- Poster, infographic, chart: references/poster-design.md, references/typography.md
- Slides: references/presentation-design.md, references/typography.md
- Why things work (hierarchy, grouping, colour, load): references/design-psychology.md
- Scoring and critical failures: references/quality-rubrics.md
- Evidence, sources, bibliography: references/research-foundations.md
- Calibration examples: examples/ai-slop-vs-exceptional.md, examples/before-and-after.md, examples/stress-tests.md

## Output conventions

- CREATE: deliver the artifact, then a short "decisions" note (concept, type, colour, layout logic, what was deliberately left out). No self-praise.
- AUDIT: prioritised findings table (Severity, Where, Problem, Why it matters, Fix, Objective/Judgment), then score from references/quality-rubrics.md.
- REFACTOR: changed work, then a change log and a list of what was intentionally preserved.
- Never claim a score above 89 unless every critical-failure check passed and the rubric evidence is written down.
- Scores are your own assessment, not measurement. Say so when it matters.

## Hard stops (fix before delivering)

Invented facts or citations; unreadable text; broken interaction; placeholder text left in; contrast below AA; content that contradicts itself; decoration that obscures information; leftover assistant phrasing ("Here's a...", "I hope this helps", "As an AI").
