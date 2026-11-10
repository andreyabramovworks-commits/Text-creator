# Typography and responsive composition

Typography supports the reading task before it signals style. Select families that cover the scripts, weights, numerals, punctuation, and licensing needs of the page. For Russian + English, confirm Cyrillic support in the exact font files and test mixed-language headings, dates, prices, and uppercase labels.

## Typeface shortlist and roles

Use these as candidates, then inspect the exact family and license in [Google Fonts](https://fonts.google.com/). Do not assume a subset from a family name.

| Visual direction | Body candidate | Display candidate | Why / check |
|---|---|---|---|
| Neutral product UI | Inter | Inter | One family gives stable controls and dense UI; check Cyrillic font files and numeric alignment |
| Editorial service | Source Sans 3 | Source Serif 4 | Contrast between interface and story; confirm the chosen weights and Cyrillic glyphs |
| Calm humanist | IBM Plex Sans | IBM Plex Serif | Shared construction with visible contrast; inspect language subsets |
| Technical / data | IBM Plex Sans | IBM Plex Mono, sparingly | Mono for labels or data only; long prose remains sans |

These are candidate pairs, not universal brand prescriptions. Compare a real hero, paragraph, CTA, form, and FAQ in both Russian and English before selecting. Source: each family's page and license in [Google Fonts](https://fonts.google.com/); pairing is our editorial judgement.

## Pairing method

1. Establish a body face first: dependable screen rendering, adequate Cyrillic/Latin coverage, and regular/italic/bold needed by content.
2. Add a display face only when it adds a useful contrast in voice or texture. Keep the body face for controls, dense data, forms, and long reading.
3. Contrast one or two dimensions—serif/sans, width, or tone—while preserving a shared rhythm. If the pair competes, use one family with a weight/optical-size system.
4. Check font licenses and redistribution obligations before embedding or bundling. Google Fonts families commonly use SIL Open Font License, Apache 2.0, or Ubuntu Font Licence, but verify the family itself.

## Starting tokens (validate against the actual font)

```css
:root {
  --font-body: "Source Sans 3", Arial, sans-serif;
  --font-display: "Source Serif 4", Georgia, serif;
  --text-body: clamp(1rem, 0.2vw + 0.95rem, 1.125rem);
  --leading-body: 1.5;
  --text-h1: clamp(2.1rem, 5vw, 4.8rem);
  --leading-display: 1.03;
  --measure-reading: 65ch;
}
```

These are starting points, not a compliance formula. Adjust by font x-height, use case, density, and language. Keep uninterrupted prose near a readable measure; GOV.UK's public guidance uses a typical ceiling of 75 characters for desktop lines. Limit very tight tracking to short display text and avoid all-caps for long content.

## Hierarchy and placement

- Make hierarchy through size, weight, space, and placement before color or ornament.
- Reserve strongest contrast for the page decision: H1 and primary CTA should be immediately findable.
- Do not force line breaks in headings merely to create a desktop composition; let headings reflow or use a responsive, content-aware constraint.
- Keep captions, labels, helper text, and legal text readable; a smaller size does not justify low contrast or cramped leading.
- At narrow widths, prioritize one readable column, preserve source order, and keep the CTA near the claim it acts on.

Use an explicit specimen: H1 at 320, 768 and 1440 CSS pixels; body paragraph at ordinary and 200% zoom; card with longest real title; form with an error; Russian/English price. Log actual line breaks and clipping. Avoid fixed-height text containers. For optical rhythm, adjust heading line height and tracking only after viewing actual glyphs. Treat `65ch` as a starting measure, then inspect the resulting Cyrillic line length visually.

## Accessibility checks

The WCAG 2.2 text-spacing success criterion requires no loss of content or functionality when readers override line height to 1.5× font size, paragraph spacing to 2×, letter spacing to 0.12×, and word spacing to 0.16×. This is an override-resilience test, not a mandate to author all copy at those values. Reflow should preserve information and function at a 320 CSS-pixel-equivalent viewport; 400% zoom is a practical check.

Also verify [WCAG contrast minimum](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html) on actual foreground/background combinations. Large display type has a different threshold from ordinary text; do not infer pass/fail from font size alone. The [GOV.UK layout guidance](https://design-system.service.gov.uk/styles/layout/) explains its usual 75-character desktop ceiling; this is a reference, not a blanket requirement for every language and page.
