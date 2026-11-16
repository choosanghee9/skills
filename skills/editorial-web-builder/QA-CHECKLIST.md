# QA checklist

Use this checklist after the approval comp and again on the hosted build. Record failures and retest only the affected area plus one adjacent path.

## Approval and content

- [ ] The current direction, logo/BI treatment, and major image direction were approved.
- [ ] Real content is separated from sample or fictional content.
- [ ] Names, dates, prices, durations, measurements, quotes, and claims trace to supplied facts.
- [ ] Missing information is omitted, requested, or clearly labelled; it is not silently invented.
- [ ] The public audience and access level have explicit approval.

## Visual system

- [ ] One color leads; accents have defined roles.
- [ ] There is no arbitrary pink-and-blue mixing.
- [ ] Type roles are consistent across the full page.
- [ ] Korean text resolves to the intended Pretendard fallback where relevant.
- [ ] Expressive serif appears in only one intentional moment.
- [ ] Cards, pills, shadows, and rounded corners exist for a reason.
- [ ] Image crop, light, temperature, and grain follow the approved rule.
- [ ] The repeated motif is recognizable without becoming decoration everywhere.

## Responsive layout

- [ ] Check representative widths around 320, 390, and 430 CSS pixels.
- [ ] Check a wide desktop viewport and any layout-specific breakpoint.
- [ ] No horizontal overflow, clipped focus ring, or inaccessible off-screen control.
- [ ] Long Korean text, long English words, and large accessibility text wrap safely.
- [ ] Images preserve useful focal points and do not contain essential live text.
- [ ] The reading order remains coherent without the desktop grid.
- [ ] Sticky elements do not cover content or controls.

## Accessibility and interaction

- [ ] Semantic landmarks and heading order are logical.
- [ ] Every control is keyboard reachable and has a visible focus state.
- [ ] Inputs have labels, instructions, useful errors, and sensible autocomplete.
- [ ] Text and interactive colors meet the intended contrast target.
- [ ] Meaning is not conveyed by color, position, or motion alone.
- [ ] Informative images have purposeful alt text; decorative images are ignored.
- [ ] Reduced-motion preferences are respected.
- [ ] Share, copy, download, print, dialog, and navigation actions work or provide a clear fallback.
- [ ] Demo-only actions disclose that they are demos rather than pretending to complete a real transaction.

## Technical delivery

- [ ] Fonts load on the hosted origin and use acceptable fallback metrics.
- [ ] No missing assets, broken links, console-blocking errors, or mixed-content failures.
- [ ] Core content remains useful with slow images or script failure where feasible.
- [ ] Page title, description, social preview, favicon, and language metadata are correct.
- [ ] Asset dimensions and compression are appropriate for mobile delivery.
- [ ] The final production URL returns the expected page without unintended authentication.
- [ ] The hosted page visually matches the approved build.

## Privacy and publication

- [ ] Public pages contain no unnecessary contact, location, health, or other sensitive personal data.
- [ ] Personalized records use opaque, non-guessable links where possible.
- [ ] Expiration, revocation, or access control exists when the content should not remain permanently public.
- [ ] Analytics, embeds, and third-party fonts match the disclosed privacy expectation.
- [ ] The owner knows how to unpublish or update the content.

## QR handoff

- [ ] Generate the QR only after the final production URL is approved.
- [ ] The encoded destination exactly matches the canonical production URL.
- [ ] Export a branded version plus a high-contrast black-and-white fallback.
- [ ] Preserve a quiet zone of at least four modules.
- [ ] Avoid artwork that obscures finder patterns or reduces decoding reliability.
- [ ] Test every export with more than one camera or decoder when practical.
- [ ] Test at the intended printed size, on the intended stock, from a realistic distance.
- [ ] Confirm the destination is reachable without the creator's private session.
- [ ] Include a human-readable short URL near printed QR codes when appropriate.

## Handoff package

- [ ] Production URL and preview URL are identified correctly.
- [ ] Editable source, exported assets, font notes, and licenses are included.
- [ ] Content-update instructions name the fields the owner is expected to change.
- [ ] Known limitations, privacy decisions, and demo-only behavior are documented.
- [ ] QR source and tested exports are included.
