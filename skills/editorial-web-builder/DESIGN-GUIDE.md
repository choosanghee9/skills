# Design guide

Use this guide to turn a mood into a coherent system. The goal is an authored reading experience with brand character, not a catalog of fashionable components.

## 1. Write a visual contract

Before drawing screens, complete this template:

| Decision | One accountable answer |
| --- | --- |
| Emotional tone | One sentence describing how the page should feel |
| Primary audience | The person whose decision matters most |
| Primary action | One action the page should make easy |
| Base | The neutral canvas and its material quality |
| Primary color | The color carrying identity and action |
| Accent | One optional contrast used sparingly |
| Display type | Role, weight, and maximum size |
| Body type | Role, weight, and language coverage |
| Expressive gesture | One intentional typographic or graphic interruption |
| Image rule | Subject, light, crop, grain, and color temperature |
| Repeated motif | A line, curve, frame, crop, or mark used throughout |
| Avoid | Three tempting choices that would break the direction |

Every section should be explainable by this contract. If a component needs a new visual language, revise or remove it.

## 2. Color direction

Start with a small system:

- one light or dark neutral base;
- one deep brand color;
- one softer tint derived from the brand color;
- one optional accent reserved for a real signal.

Let photography and paper-like material create warmth when possible. A restrained muted-blue interface can feel warm through cream, wood, skin, flash, grain, and humane copy without adding unrelated pink.

Avoid arbitrary pink-and-blue mixing. Use that relationship only when the identity or supplied references establish a clear reason and define which color leads. Check text and interactive contrast in the actual combinations, not in isolated swatches.

## 3. Typography

Build roles, not a font collection:

- display: primary message and section entry;
- body: facts, explanation, controls, and long Korean text;
- data: dates, labels, prices, or structured records;
- expressive moment: a single emotional inflection.

An optional proven editorial pairing is:

- **Manrope SemiBold 600** for English display, navigation, and compact data;
- **Instrument Serif Italic 400** for one intentional English word, line, or quotation;
- **Pretendard** for Korean copy and the Hangul fallback.

Manrope and Instrument Serif do not provide Korean glyphs. Define Pretendard explicitly rather than relying on an uncontrolled system fallback. The expressive serif should appear once per page or once in a major standalone screen, not as a recurring decoration.

Keep body copy comfortably readable. Avoid compressed tracking below `-0.04em`, fragile light weights, and oversized headings that force every screen to shout. Test the longest Korean line and the shortest English label.

## 4. Composition and rhythm

Design the page as a sequence of changes in scale and density:

1. establish identity;
2. orient the reader;
3. reveal the problem or context;
4. demonstrate the system or experience;
5. provide evidence and detail;
6. close with a clear next action.

Use full-bleed image bands, ruled information rows, offset columns, cropped type, or controlled asymmetry when they support that narrative. Repeat one motif across sections so the page feels connected.

Do not default to stacked rounded cards. First try flat sections, dividers, lists, editorial columns, and intentional whitespace. Use a card only when grouping or interaction genuinely requires a bounded surface.

Pills belong to filters, statuses, tags, and compact controls. They are not generic decoration. Keep button and surface radii moderate unless a soft geometry is a documented brand trait.

## 5. Imagery and art direction

Define imagery with five decisions: subject, point of view, light, crop, and finish.

For a warm documentary direction, consider direct flash, imperfect candid posture, restrained grain, warm highlights, and cool or neutral backgrounds. Do not apply “film” filters indiscriminately; preserve natural skin, fur, product color, and readable printed matter.

Use approved photography or approved generated imagery consistently. Do not generate an entire asset family before the image direction is approved. Do not leave placeholder AI portraits or impossible product mockups in a final build.

Write alt text for the purpose of the image, not every visible pixel. Decorative images should be ignored by assistive technology.

## 6. Copy direction

Warm copy is specific, not sugary. A useful pattern is:

1. what was observed;
2. what was done in response;
3. what the reader can do next.

Prefer “드라이 소리에 몸이 굳어 풍량을 낮추고 잠시 쉬었습니다” to “세심한 케어로 편안하게 진행했어요.” The first sentence shows care through action.

Do not invent details to make a page feel complete. Use supplied facts, ask for missing facts, or mark examples as illustrative. Avoid fake quotes, implausibly precise metrics, unverified medical advice, and generic claims such as “best,” “premium,” or “personalized” without evidence.

## 7. Interaction and accessibility

- Preserve a logical heading order and document landmarks.
- Keep touch targets usable and focus states visible.
- Do not encode meaning through color alone.
- Use native controls before custom imitations.
- Explain demo-only actions in plain language.
- Respect reduced motion and avoid essential information in animation.
- Ensure share, download, print, and copy actions have fallbacks.
- Test zoom and reflow rather than freezing text inside image exports.

## 8. Anti-AI review

Before approval, remove anything that feels auto-filled:

- repeated three-card grids with interchangeable copy;
- oversized slogans followed by tiny unreadable facts;
- unrelated gradients, blob shapes, sparkles, and glass effects;
- arbitrary pastel combinations;
- decorative pills and status badges with no job;
- the same serif flourish on every heading;
- impossible mockup lighting or malformed printed type;
- abstract promises unsupported by a concrete story;
- inconsistent radii, shadow recipes, and icon styles;
- sections that could be reordered without changing the story.

The finished page should become weaker if its sections are shuffled. That dependency is evidence of a real narrative.
