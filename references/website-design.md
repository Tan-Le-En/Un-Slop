# Website and UI design

Contents: 1 the default look, 2 process, 3 layout, 4 colour, 5 components, 6 motion, 7 engineering and accessibility, 8 exceptions.

## 1. The default look and why it appears
Prompted without constraints, models return the average of their training data: Inter or system font, indigo-to-purple gradient, centred hero with two buttons, a small pill badge above the headline, three rounded cards with line icons, soft shadows, glass panels, emoji as icons, invented testimonials, a pricing grid with a lifted "Most Popular" card. None is wrong alone. The problem is that nobody chose them. Banning them often yields a second-wave default (cream and terracotta, near-black with acid accent), so always derive choices from the brief.

## 2. Process
1. Brief: audience, goal, primary action, content inventory, tone, constraints. If content is missing, use honest placeholders.
2. Concept: one sentence, plus a metaphor or reference from the subject (a ship's log, a field guide, a ticket stub, a lab notebook).
3. Information architecture: pages and sections justified by user tasks.
4. Type and colour decisions (typography.md). Write tokens first.
5. Layout on a grid with a spacing scale.
6. Build with semantic HTML and modern CSS.
7. QC: squint test, mobile width, keyboard, contrast, content realism.

## 3. Layout
- Choose structure from content: editorial column, index list, split screen, timeline, catalogue grid, dashboard. Not every page is hero plus cards.
- Vary section rhythm and density; repeat a module only where content repeats.
- Whitespace is for grouping and emphasis. Use proximity: related things close, unrelated things clearly apart. Inconsistent gaps look sloppy; a limited spacing scale (e.g. 4, 8, 16, 24, 40, 64) fixes it.
- Navigation: plain labels, visible current state, predictable location. Do not hide primary navigation behind novelty.
- Keep line length 45-75 characters for reading text.
- Cards are a tool for independent, comparable objects. If the content is a list or a narrative, use a list or prose.

## 4. Colour
- Roles: background, text, one dominant, one support, one accent for action, plus semantic states. Most pages need fewer colours than first instinct.
- Take palette cues from subject matter, materials, photographs or brand assets.
- Gradients only when they model something (light, depth, data); never as a generic backdrop.
- Check contrast (4.5:1 body, 3:1 large text and UI). Never rely on colour alone.

## 5. Components
- Buttons: verbs for labels; one primary per view; clear hover, focus, active, disabled.
- Forms: visible labels, helpful errors, sensible defaults.
- Icons: one set, one stroke weight, only where they aid recognition.
- Images: real, relevant, consistent treatment. Avoid generic stock people and abstract 3D blobs.
- Social proof and numbers: only real. Otherwise omit or mark as placeholder.
- Radii and shadows: pick a small system (e.g. 0, 4, 12) and obey it. Shadows signal elevation, not decoration.

## 6. Motion
Purpose: show cause and effect, orient, give feedback. Use transform and opacity, 120-300 ms for UI feedback, ease-out for entering. Respect prefers-reduced-motion. No scroll-jacking, parallax for its own sake, or looping ambient animation behind text.

## 7. Engineering and accessibility
- Semantic landmarks (header, nav, main, footer), one h1, logical heading order.
- Responsive from 320px up; no horizontal scroll; fluid type with clamp() where appropriate.
- Design tokens as CSS custom properties; avoid magic numbers.
- Visible :focus-visible, 44px targets, alt text, labelled controls, 200% zoom survives.
- Performance: few font files, subset or system fallbacks, optimised images, no layout shift.
- Test with keyboard only.

## 8. Exceptions
Brutalist, maximalist, playful, retro and kitsch sites can be excellent when the system is consistent and the hierarchy holds. Conventions (checkout, forms, settings) should stay conventional. A dashboard may legitimately use cards.
