# Rewrite an existing site in its actual layout

Use this mode when a site already has sections, copy and images. Preserve its useful facts and intent. Start with the rendered desktop and mobile page, its source text, supplied client materials and original images. Do not infer an event, date, participant, result, age requirement, location or price from a photo alone.

## Inventory before editing

Create one row per visible text element: page/section/element, current copy, purpose, audience, factual source, photo or UI neighbor, space available, and disposition (`keep`, `tighten`, `rewrite`, `move`, `remove`, `needs evidence`). Include navigation, hero, cards, news, buttons, forms, FAQ, footer, title/meta description and image alternatives where relevant. If the section order harms the path to signup, propose a revised order tied to the visitor's questions.

## News and photo matching

For each photo, record only observable details: people, activity, equipment, setting, and any legible signage. Separately record the client's caption, event description, date, names and permissions. Then choose the honest content type:

| Evidence available | Appropriate treatment |
|---|---|
| Verified event, date and outcome | News item: what happened, why it matters, and relevant next step |
| Verified activity, no event details | Evergreen story or club-life card; avoid a dated news claim |
| Photo only | Descriptive gallery caption; request facts before writing news |
| Text conflicts with photo | Hold the claim, clarify the match, or use another image |

Headline, lead, body and image must tell one story. The headline should add information beyond “Новости клуба”. The lead answers the main question in one or two sentences. Body copy can explain the experience, context, or result; end with a signup CTA only when the story naturally supports it. Keep news distinct from promotional copy. Alt text describes the image's informational content, not a sales slogan.

## Conversion path for a class-based club

Check whether the page answers, using verified information: who can join, what happens in a lesson, what a beginner needs, where and when classes happen, who teaches, safety/supervision where relevant, cost or how to learn it, and what happens after a signup request. Place the most relevant answer near the decision point. A CTA such as «Записаться на занятие» is suitable only if its destination actually starts that process; if it merely requests a callback, label it accordingly.

For a youth activity, distinguish the child from the parent or guardian as decision makers when the materials support that audience. Do not invent ages, achievements, instructor credentials, equipment availability, trial lessons or safety promises.

## Typesetting on the real page

Choose a unified body/display system after seeing the site's visual style and checking Cyrillic support and font licenses. Define tokens for H1, H2, card title, lead, body, caption, CTA and form labels. State font family, size range, weight, line height, max width, spacing and responsive behavior for each role. Use relative units or `clamp()` where useful, but verify actual line breaks; do not force identical word counts across sections. Give news leads enough size and measure to read comfortably. Keep text clear of busy image regions, use a reliable contrast treatment, and preserve reading order on mobile.

Review at desktop, tablet, narrow mobile and 200%/400% zoom. Check Russian word wrapping, dates, long headlines, image crops, CTA visibility and text-spacing overrides. Correct layout before shortening meaningful copy merely to fit.

## Output and acceptance

Deliver the inventory, revised section order if needed, before/after copy, image-to-story mapping, type tokens, implemented changes when authorized, and a short list of unresolved client facts. A pass means the visitor can understand the club and next step; each news item matches its image and evidence; typography is consistent and readable; and the rendered page has been inspected at target widths.
