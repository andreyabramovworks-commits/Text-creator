# Copy QA

Run this against the rendered page and the source brief. Record each finding as `block → issue → evidence → proposed change → owner` so factual decisions can be approved separately from editorial corrections.

## Review order

1. **Truth:** map claims and commercial terms to sources. Stop unsupported claims from reaching final copy.
2. **Decision path:** scan only H1, H2s, CTAs, prices and proof. Can the visitor understand what to do and why?
3. **Flow:** read each block in order; remove repetition and resolve objections at the point of decision.
4. **Interface states:** submit forms, trigger errors, open FAQ, follow CTAs and inspect confirmation states.
5. **Rendering:** inspect real strings in both languages at desktop, 320px-equivalent width, zoom, and text-spacing overrides.

Score each dimension `pass / revise / blocked by missing evidence`. A missing source is `blocked`, not a writing defect to hide with smoother prose.

## Evidence and claims

- [ ] Every factual claim maps to a source, owner, or explicit assumption.
- [ ] Metrics include scope, time period, denominator, and source where relevant.
- [ ] Testimonials, logos, certifications, and comparison claims are approved and attributable.
- [ ] Pricing, availability, integrations, guarantees, and legal conditions reflect the current product.

## Information hierarchy

- [ ] One H1 describes the page task or value; subsequent headings describe their sections.
- [ ] The first screen tells the intended visitor what it is, why it matters, and the next action.
- [ ] CTAs describe their result and match the actual path.
- [ ] Each card has a distinct job; repeated card copy has been consolidated.
- [ ] FAQ questions come from evidence or are marked as hypotheses.

## Interface language

- [ ] Terms, capitalization, and voice are consistent.
- [ ] Labels, errors, empty states, confirmations, and loading states explain outcome and recovery.
- [ ] Links make sense out of context; icon controls have accessible names.
- [ ] Copy does not depend on color, geometry, or screen position to be understood.
- [ ] English and Russian strings remain complete sentences where translation may reorder words.
- [ ] Error summary and field errors use matching language, link to the affected field, and preserve entered values.
- [ ] Service failure, eligibility and user-input errors have distinct messages and next actions.

## Typesetting in the built page

- [ ] Body text has a controlled measure; headings and CTAs do not become ambiguous when wrapping.
- [ ] Font files support every used script and glyph.
- [ ] 320px-equivalent width and 200%/400% zoom preserve reading and interaction.
- [ ] WCAG text-spacing override does not crop, overlap, or hide text or controls.
- [ ] Long names, currency, dates, plural forms, and Russian/English mixed strings have been inspected.

## Adversarial probes

- Remove the logo and ask: could a competitor use this hero unchanged? If yes, add a specific audience, mechanism, limitation or proof.
- Read only CTA labels: do they predict the destination? If not, rewrite them.
- Replace every metric with its source note: if the claim becomes unsupported, hold it.
- Read the page as a skeptical buyer: are price, time, setup, cancellation, support and data handling clear where relevant?
- Test the longest likely translation and 200% zoom: if a button or card clips, fix layout before abbreviating meaning.

Guidance anchors: [GOV.UK UI writing](https://www.gov.uk/service-manual/design/writing-for-user-interfaces), [GOV.UK error messages](https://design-system.service.gov.uk/components/error-message/), [W3C text spacing](https://www.w3.org/WAI/WCAG22/Understanding/text-spacing.html) and [reflow](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html). The probes and score states above are original workflow synthesis.
