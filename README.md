# UNSLOP

A set of instructions that helps an AI make websites, writing, posters, slides and charts that look and read like careful human work, instead of generic AI output.

UNSLOP is not about minimalism. Playful, colourful and loud work can pass. Unchosen defaults and invented facts fail.

## What is inside

- `SKILL.md`: the main rules and the five modes (Create, Audit, Refactor, Art Direction, Final QC)
- `references/`: framework, writing, web, poster, slides, typography, psychology, scoring rubric, sources
- `workflows/`: step-by-step process for each mode
- `examples/`: before and after samples and stress tests
- `UNSLOP-lite.md`: one short file for tools that cannot load folders

## Install

### Claude (claude.ai or app)
1. Go to the Releases page of this repo and download `unslop.skill`.
2. In Claude, open Settings and find Skills (menu names vary). Upload the file, or press Save skill if a card appears.
3. Make sure Code execution and file creation is on.

### Claude Code
```
git clone https://github.com/Tan-Le-En/unslop ~/.claude/skills/unslop
```

### ChatGPT, Gemini and other AI tools
1. Open `UNSLOP-lite.md`, copy everything.
2. Paste it at the start of a chat, or into custom instructions, a Custom GPT, a Gem, or a project.
3. For longer jobs, also upload the relevant file from `references/` (for example `poster-design.md` for posters).

## Use it

- "Use UNSLOP to create a landing page for my science project."
- "UNSLOP audit this poster and score it."
- "UNSLOP refactor my slides. Keep my content."
- "Run UNSLOP final quality control before I submit."

Give it your real content, photos, data and competition rules. It will not invent facts and will use labelled placeholders for anything missing.

## Honest limits

- Built from a small research pass. Items marked "canonical" in `references/research-foundations.md` were cited from background knowledge and should be checked.
- Scores are structured judgments, not measurements.
- The stress tests use invented sample inputs and were not visually rendered.
- Other AIs may follow the rules less reliably. Always check for made-up facts.

## License

MIT. See `LICENSE`.
