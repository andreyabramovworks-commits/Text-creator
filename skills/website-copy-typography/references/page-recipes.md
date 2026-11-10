# Page recipes

Choose a structure based on the visitor's decision, not a fixed landing-page formula. Remove blocks that do not change the decision.

## Selection matrix

| Situation | Leading block | Supporting sequence | Avoid |
|---|---|---|---|
| New category / unfamiliar product | What it does and for whom | Mechanism → use cases → evidence → risk → CTA | Vague aspirational headline before the category is clear |
| Known problem, comparison shopping | Differentiating result | Specific differences → proof → price/terms → FAQ → CTA | Generic feature grid with interchangeable claims |
| High-risk B2B purchase | Outcome with scope | Workflow → security/operations → case evidence → implementation → contact | Unsupported ROI and customer logos |
| Service / agency | Who it helps and deliverable | Process → sample work → team fit → scope → inquiry | Promising quantified results without a basis |
| Direct purchase | Product and key choice | Details → price/shipping/returns → reviews → purchase | Hiding material terms below the fold |

These are editorial starting hypotheses. Choose by the audience's stage and available proof. The [Marketing Skills copywriting](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copywriting) and [site architecture](https://github.com/coreyhaines31/marketingskills/tree/main/skills/site-architecture) skills offer additional prompts, but their examples cannot supply product facts.

## Product or service landing page

| Block | Job | Must be grounded in |
|---|---|---|
| Hero | State outcome, audience, and next action | Approved offer and audience |
| Context/problem | Help the right visitor recognize the situation | Observed pain or research |
| How it works | Make the mechanism credible | Actual workflow |
| Benefits | Connect features to relevant change | Product facts and audience needs |
| Proof | Reduce doubt | Verifiable results, sources, customers, or method |
| Objections/FAQ | Resolve decision blockers | Sales, support, research, policy |
| Final CTA | Repeat the appropriate next action | Real conversion path |

Use a hero pattern only when the evidence permits it:

```
Eyebrow: [audience or category, optional]
H1: [specific outcome] for [audience or use case]
Support: [mechanism, scope, or proof that makes it believable]
Primary CTA: [direct verb + outcome]
Secondary CTA: [lower-commitment path, if real]
```

## Pricing page

Lead with who each plan is for and the decision difference between plans. Put prices, billing period, included limits, exclusions, taxes, and cancellation terms near the choice. Never conceal a required sales call behind a self-serve CTA.

Choose the comparison structure: **one offer** → a single price and inclusion list; **few clearly different plans** → cards with audience and decisive limits; **many dimensions** → a comparison table that still works on mobile. State annual/monthly arithmetic honestly. Treat “most popular” as a factual claim. If price is custom, explain what drives the quote and what happens after contact. See the [Marketing Skills pricing skill](https://github.com/coreyhaines31/marketingskills/tree/main/skills/pricing) for idea generation; confirm every commercial term from the owner.

## Form or transactional flow

The page title states the task. Labels name the requested data; helper text explains only non-obvious input. An error identifies the field/problem and recovery. A confirmation says what completed and what happens next, including timing when known.

Use persistent labels. Separate required from optional fields. The error must reuse the label's vocabulary, identify the correction, and preserve entered values. On a multi-field page, put a linked summary above the form and a message by each affected field. A service failure needs a separate recovery path; it is not a user-input error. These patterns come from [GOV.UK error message](https://design-system.service.gov.uk/components/error-message/) and [error summary](https://design-system.service.gov.uk/components/error-summary/).

| State | Russian model | English model |
|---|---|---|
| Label | «Рабочая почта» | “Work email” |
| Hint, only if needed | «Отправим на неё расчёт» | “We’ll send the estimate here.” |
| Missing input | «Укажите рабочую почту» | “Enter your work email.” |
| Format issue | «Укажите адрес в формате name@example.com» | “Enter an email address, such as name@example.com.” |
| Submission success | «Запрос отправлен. Ответим на указанную почту [срок подтвердить].» | “Request sent. We’ll reply to your email [confirm timeframe].” |

The strings are original models, not verified copy for any business. Adapt terminology and action to the actual flow.

## FAQ

Use real questions from sales, support, research, or a declared hypothesis. Each answer should be self-contained, concise, and linked to policy or documentation for consequential terms. Do not use FAQ to bury caveats that belong next to a price or CTA.

Sort questions by the visitor's decision: eligibility/fit → practical use → costs/terms → risk and support. Use an accordion only when the page remains scannable and answers remain discoverable; [GOV.UK accordion](https://design-system.service.gov.uk/components/accordion/) gives an implementation reference. Questions about cancellation, data handling, eligibility, and refund terms require current policy evidence. “What if…” answers should state the actual condition and action, not reassurance alone.

## Trust blocks

Use a testimonial only with permission and an attributable source. For logos, certifications, reviews, statistics, or case studies, capture source URL, date, scope, and approval status in the evidence ledger. If proof is missing, use a process explanation rather than fabricated social proof.

Proof hierarchy: **demonstrable product behavior** → **verifiable case with context** → **attributed testimonial** → **third-party certification/review with current status** → **process explanation**. Match proof to the exact claim beside it. State sample size, timeframe and comparability for metrics. Disclose material relationships where applicable. The [FTC endorsement guidance](https://www.ftc.gov/news-events/topics/truth-advertising/advertisement-endorsements) is US-specific; apply local law for the target market.

## CTA and card copy

The CTA label should complete “I want to…” and match the destination. Use one primary action per decision area; a secondary action offers a genuinely different commitment level. Cards should have a unique heading, one concrete point and, if needed, a specific link. If three cards repeat the same promise, consolidate them. For links, [GOV.UK link guidance](https://guidance.publishing.service.gov.uk/writing-to-gov-uk-standards/writing-guidelines/add-links/) favors destination-aware wording over “learn more” in isolation.
