# Stress tests

Scope and honesty: these five scenarios use realistic but invented sample inputs, written as text or specification, not rendered and visually inspected in this run. Scores are my structured judgment under references/quality-rubrics.md, not measurements. Re-test with real artifacts before trusting the numbers.

## Test 1: Generic SaaS website ("Flowbase", task manager)
Original: indigo-purple gradient hero, Inter, pill badge "Now with AI", headline "Supercharge your productivity", two buttons, three rounded cards ("Fast", "Secure", "Collaborative"), invented testimonial, three-tier pricing with lifted "Most Popular".
Problems: unchosen defaults, vague copy, fabricated social proof (critical failure), no product visible, tier card emphasis without reason.
Applying UNSLOP: concept: "a task list that looks like a printed day-planner". Show the real product UI in the hero. Type: a serif display with a plain text sans. Colour: warm paper ground, ink, one accent for actions. Layout: editorial single column with one wide screenshot, a dated example task list, pricing as a plain table. Testimonials removed until real ones exist. Headline states the job ("Plan your day on one page").
Score: original 48 (capped 69 by invented testimonial; uncapped judgment 48). Improved 84 (concept clear; remaining weakness: no real screenshots or user quotes supplied, accent contrast to verify, motion untested).

## Test 2: Mediocre science competition poster (rainwater monitor)
Original: title in a gradient banner, six rounded boxes each with an icon and a paragraph, clip art droplets, drop shadows, 700 words in 14pt.
Problems: no focal point, text overload, mixed styles, unreadable at distance.
Applying UNSLOP: read the rubric first. Focal point: annotated photo or diagram of the prototype. Headline states the result (the user must supply). Panels: problem, build, test data, finding, next step with 40-60 words each. One accent colour. Grid with equal margins. Chart: sorted bars with direct labels.
Score: original 41. Improved 82. Remaining weakness: depends on real data and photos from the team; no print test performed; contrast not measured.

## Test 3: AI-written academic paragraph
Original: see examples/before-and-after.md item 1.
Applying UNSLOP: cut puffery and balance filler, state the claim, mark missing evidence.
Score (writing rubric): original 38, improved 80 as a skeleton. Remaining weakness: cannot reach 90 without the author's real finding, citation and methods.

## Test 4: Generic corporate presentation (quarterly update)
Original: "Overview", "Key Highlights", six bullets per slide, stock handshake, different font sizes per slide.
Applying UNSLOP: claim headlines, one chart per slide, single master, 28pt minimum body, numbers only from the user's data.
Score: original 45, improved 83. Remaining weakness: no real numbers supplied, so claim headlines are placeholders; speaker notes not written.

## Test 5: Cluttered infographic ("Benefits of recycling")
Original: 3D pie chart with 9 slices, rainbow colours, icons everywhere, text in curved paths, no source.
Applying UNSLOP: one message, one chart type (sorted horizontal bars), grey context with one highlighted bar, direct labels, source and units, remove icons that do not label something.
Score: original 35, improved 79. Remaining weakness: data not supplied, so values are placeholders; accessibility of colour pair not checked.

## Lessons folded back into the skill
- Invented testimonials and numbers appear in almost every generic original; hard stop added and placeholders encouraged.
- Improvements stall near 80-85 without real content; the rubric now requires evidence for 90+.
- Banning obvious tells risks second-wave defaults; rule 5 added to SKILL.md.
- Paragraph rewrites tempt invention of findings; writing guidance now flags gaps instead of filling them.
