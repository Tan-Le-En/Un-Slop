# Typography

Contents: 1 decisions, 2 pairing, 3 scale and spacing, 4 details, 5 web and print specs.

## 1. Decisions
- Choose type by voice: what should the words sound like if spoken? Then check legibility at the real size and medium.
- Default sans (Inter, Roboto, Arial, system stack) is acceptable for dense UI, but as the automatic choice for a branded page it signals no decision. If kept, say why, and give headlines a distinct voice.
- Use one family with several weights, or two families with clear roles. A third needs a reason.
- Free, reliable sources: Google Fonts, Fontshare, Open Foundry. Check licence for commercial use. Always set a fallback stack.

## 2. Pairing
- Contrast in structure (serif with sans, or condensed display with neutral text), harmony in proportion (similar x-height).
- Do not pair two similar faces. Do not use two display faces.
- Headline face carries personality; text face carries endurance.
- Check the same pair at small, medium and large sizes.

## 3. Scale and spacing
- Pick a modular ratio (1.2 minor third for UI, 1.25 to 1.5 for editorial, larger for posters) and stick to 5-7 steps.
- Body: 16-20px on screen, line-height 1.4-1.6, line length 45-75 characters. Headings: line-height 1.0-1.25, tighter tracking at large sizes.
- Uppercase and small caps: add letter-spacing (about 0.05-0.12em). Do not letter-space lowercase body text.
- Paragraph spacing: either space between paragraphs or first-line indent, not both.
- Left-align body text. Justify only with hyphenation and wide measure.

## 4. Details
- Real typographic marks: curly quotes, proper apostrophes, en dash for ranges, minus sign, ellipsis character, non-breaking spaces before units.
- Numbers: tabular figures in tables, lining or oldstyle by context.
- Avoid widows, orphans and single-word last lines in headlines (text-wrap: balance, pretty).
- Hierarchy through size, weight, colour and space, usually not more than two at once.
- Avoid all-caps paragraphs, italic paragraphs, light grey light-weight text, gradient text, text over busy images without a scrim.

## 5. Specs
- Web: font-display: swap; limit to 2-3 files; use variable fonts where they replace several files.
- Print: body 9-11pt for reading, minimum 7pt for captions; posters readable from the stated distance (title about 1 inch of cap height per 10 feet is a common rule of thumb, adjust to context).
- Export: PDF with embedded fonts, 300 dpi raster at final size, vector for logos and charts, bleed 3mm if printing to edge, CMYK or a stated profile only when the printer asks.
