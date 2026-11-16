---
name: editorial-web-builder
description: Designs and ships distinctive, brand-led, editorial, mobile-first web experiences from approved visual direction through accessible implementation, deployment, and QR handoff. Use when creating or refining a portfolio, branded service page, digital care card, campaign microsite, or responsive website where typography, imagery, content voice, and visual craft must work as one system.
---

# Editorial Web Builder

Build the page as one authored narrative, not a collection of isolated components. Protect brand coherence, factual integrity, accessibility, and publishing consent from the first comp through the QR handoff.

## Required references

- Read [DESIGN-GUIDE.md](DESIGN-GUIDE.md) before defining color, typography, imagery, composition, or copy direction.
- Use [QA-CHECKLIST.md](QA-CHECKLIST.md) before presenting a build as complete, publishing it, or generating a QR code.
- Consult [EXAMPLE.md](EXAMPLE.md) when the brief is vague or a concrete end-to-end pattern would help. Treat its content as fictional, never as reusable claims.

## Establish the brief

Confirm or infer only low-risk details. Ask for a decision when a missing answer would materially change the result.

Collect:

- audience, primary action, and success condition;
- supplied facts, evidence, and content ownership;
- existing logo, type, color, photography, illustrations, and references;
- target surfaces, breakpoints, hosting, domain, and QR use;
- accessibility, privacy, and public-access constraints;
- what the user likes in each reference, rather than copying the reference wholesale.

Separate three kinds of input:

1. **Truth** — facts and assets that may be published.
2. **Direction** — mood, visual principles, and references.
3. **Illustration** — clearly labelled sample data used only to demonstrate layout.

Never turn illustrative content into an implied real claim.

## Approval gates

Pause for explicit approval at these gates unless the user has already approved that exact scope:

1. **Direction gate** — present the visual contract and a representative comp before implementation when approval was requested.
2. **Identity and image gate** — approve logo/BI changes, illustration direction, and major generated or commissioned imagery before producing a full set or embedding it throughout the site.
3. **Publishing gate** — approve the final audience and access level before any public deployment, public URL, or live QR handoff.

Approval of a comp is not approval to publish. Approval of one asset is not approval of an entire generated series.

## Workflow

### 1. Audit the source material

- Inventory real assets and copy before designing.
- Identify missing facts, contradictory styles, and risky personal data.
- Note the strongest existing brand behavior worth preserving.
- Convert reference feedback into principles such as “quiet density,” “warm flash photography,” or “thin ruled information rows.”

### 2. Write one visual contract

Define the page in a short, testable contract:

- one emotional sentence;
- a restrained color system;
- type roles and hierarchy;
- one image treatment;
- spacing and density rules;
- repeated graphic behavior;
- explicit anti-patterns.

Do not begin implementation until the contract can explain every major section. Use the deeper rules in [DESIGN-GUIDE.md](DESIGN-GUIDE.md).

### 3. Make approval comps

- Show the most representative mobile screen first, plus a desktop crop if composition changes materially.
- Use real or clearly labelled sample content.
- Keep alternatives meaningfully different; do not make three near-identical color swaps.
- When testing a revision, change the disputed variable first so feedback remains interpretable.
- Annotate type roles, palette, image treatment, and intended interaction.

Wait at the direction gate when approval was requested.

### 4. Write human copy

- Prefer observed behavior, concrete action, and useful next step over abstract reassurance.
- Use warm, concise Korean or English appropriate to the brand; do not force translated marketing idioms.
- Preserve uncertainty. “약 40분” is only valid when the source supports it.
- Never invent customer quotes, awards, research findings, prices, durations, medical guidance, or performance claims.
- Label demo data as “sample,” “example,” or “fictional” outside the customer-facing surface when necessary.

### 5. Implement mobile first

- Start with semantic HTML and a single reading order that remains coherent without CSS.
- Build one responsive composition, not separate unrelated mobile and desktop pages.
- Use CSS custom properties for color, type, spacing, radius, and motion.
- Make every visible control work; remove decorative controls that suggest unavailable behavior.
- Provide keyboard focus, descriptive labels, useful alt text, sufficient contrast, and reduced-motion support.
- Prefer fast static delivery unless genuine application state requires more.

### 6. Refine as an editorial system

- Review the whole page at once for rhythm, repetition, and transitions.
- Let one visual motif travel across hero, information, proof, and handoff surfaces.
- Reduce component chrome before adding decoration.
- Keep warmth in copy, imagery, and material texture rather than scattering unrelated colors.
- Use the optional Manrope 600 + Instrument Serif Italic 400 pairing only when it fits the approved direction; use Pretendard for Korean and as the Hangul fallback. Restrict the expressive serif to one intentional moment.

### 7. Verify proportionately

Run the bounded checks in [QA-CHECKLIST.md](QA-CHECKLIST.md). At minimum verify:

- a compact mobile width and a wide desktop width;
- horizontal overflow and text wrapping;
- font loading and Korean fallback;
- keyboard, focus, contrast, and reduced motion;
- links, forms, share/download behavior, and any demo-state disclosure;
- deployment response and the final production URL.

Fix material issues before calling the work complete.

### 8. Deploy and hand off QR

- Deploy to a preview URL first.
- Verify content and access controls on the hosted version, not only locally.
- Ask for explicit approval before changing visibility to public.
- Generate the QR code only from the approved final production URL.
- Deliver a branded version and a high-contrast black-and-white fallback with a proper quiet zone.
- Decode-test every exported QR at intended print size and confirm the exact destination.
- Include the editable source, production URL, image exports, font notes, and a short content-update guide.

For records or personalized pages, do not expose unnecessary names, contact details, health information, or predictable identifiers. Prefer opaque links, expiration, revocation, and the least public audience that meets the use case.

## Anti-slop constraints

- No generic card stack as the default page structure.
- No arbitrary pink-and-blue mixing; every color relationship needs a brand or content reason.
- No decorative pills, badges, or floating chips without a functional or semantic role.
- No invented claims, metrics, testimonials, service details, or faux research.
- No oversized type merely to manufacture hierarchy.
- No repeated expressive serif in every section.
- No disconnected mockups pasted into a page without a narrative transition.
- No “AI-looking” filler imagery, pseudo-handwriting, or excessive gradients used to hide weak composition.

## Definition of done

The result is done only when:

- the approved visual contract is visible across the entire page;
- copy is factual, warm, and specific;
- the page is usable and coherent on mobile and desktop;
- core accessibility checks pass;
- the hosted build matches the reviewed build;
- publication scope is approved;
- every delivered QR resolves to the exact final URL;
- the handoff explains assets, fonts, content updates, and privacy limits.
