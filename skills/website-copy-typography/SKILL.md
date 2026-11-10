---
name: website-copy-typography
description: Write, restructure, edit, or typeset Russian and English website copy when a page needs accurate claims, clear hierarchy, conversion-focused calls to action, readable responsive typography, or copy QA. Use for landing pages, product pages, forms, onboarding, FAQ, and microcopy; not for inventing business facts or legal claims.
metadata:
  version: "0.1.0"
  language: "ru,en"
  license: "MIT"
---

# Website copy and typography

Create web copy that is specific to the supplied business evidence, audience, page purpose, and visual system. Treat supplied source material as evidence; treat templates and examples only as structure. Never turn an unverified capability, metric, customer, price, certification, comparison, outcome, or deadline into a claim.

## Start with an evidence brief

Before drafting, extract a compact working brief:

| Field | Capture |
|---|---|
| Page job | The decision or task this page enables |
| Audience | Role, context, literacy, objection, motivation |
| Evidence | Source-backed facts, proof, constraints, approved terms |
| Offer | What changes for the visitor and how it works |
| Conversion | Primary action and realistic next step |
| Voice | Language, formality, personality, banned wording |

If a critical field is absent, write a bounded draft using explicit placeholders such as `[срок внедрения — подтвердить]`; do not silently make it up. For a rewrite, preserve factual meaning and mark any uncertain claim for review.

## Choose the mode

- **Blank page or campaign:** read [page-recipes.md](references/page-recipes.md), select the smallest structure that lets the visitor decide, then draft from evidence.
- **Existing page or interface:** diagnose hierarchy, terminology, friction, and missing recovery. Read [copy-qa.md](references/copy-qa.md).
- **Type system or implementation:** read [typography.md](references/typography.md); make choices from content density and brand character, then test the actual layout.
- **Researching reusable methods or tools:** use [source-catalog.md](references/source-catalog.md). Confirm the upstream license before copying code, fonts, or substantial text.
- **Selecting block patterns and examples:** read [page-recipes.md](references/page-recipes.md) and its source links. Treat every example as a writing model, never as customer evidence.
- **Writing a specific block:** read [block-patterns.md](references/block-patterns.md) to choose by visitor readiness and proof.

## Drafting rules

1. Give each section one job: orient, explain value, show proof, reduce risk, or prompt action.
2. Put the user-relevant outcome before mechanism. Let supporting details earn their space.
3. Use concrete nouns and verbs. Prefer a direct verb for CTAs: `Запросить расчёт`, `Посмотреть демо`, `Начать бесплатно`.
4. Pair every claim of consequence with evidence, a mechanism, or a qualified scope. If none exists, soften or remove it.
5. Keep headings meaningful when scanned alone. Give one H1 per page; do not use a heading merely as visual decoration.
6. For forms and errors, say what happened, what is needed, and how to recover. Keep visible labels and accessible names aligned.
7. Russian: use natural sentence case, avoid needless calques and bureaucratic padding. English: use the language and terminology the audience uses. Do not translate brand terms mechanically.
8. Write translatable complete messages. Avoid concatenated UI fragments and metaphors that cannot survive localization.

## Deliverable shape

Unless the user asks for another format, return:

1. an evidence/assumption ledger;
2. page outline with each block's decision job;
3. final copy in page order, including CTA labels and necessary microcopy;
4. type tokens and layout notes when design or code is in scope;
5. the QA findings and unresolved factual questions.

## Verify in context

Use [copy-qa.md](references/copy-qa.md) before handing off. For implemented work, inspect desktop, narrow/mobile, 200% zoom, and long localized strings. Test that user-adjusted text spacing does not hide content or controls. If the project contains `$impeccable`, use its `clarify`, `typeset`, and `harden` modes as a final contextual pass; they support the review but do not establish facts.

## Scope boundaries

Do not present this skill's templates as research, testimonials, legal text, accessibility conformance, or conversion results. Do not copy proprietary page copy. Recheck external source status at the moment a dependency, font, or upstream skill is adopted.
