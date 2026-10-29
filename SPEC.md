# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: BRAND-001 exploration and proposals prepared; storefront and style guide remain neutral.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Scope recorded in issue #1; branch `feature/brand-001-first-branded-storefront` exists. No BRAND-001 pull request exists yet.
- Next small decisions: Review the logo proposal, confirm or revise the visual direction with the learner's reason, and discuss the visitor benefit of one approved persuasion proposal before applying the branded slice.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales. The comfort/simplicity promise is learner-supplied; comfort has not been independently verified as a product fact.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                                                                           | Secondary audience                                                                  |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Person in a concrete situation        | Everyday dressers; earlier hypothesis: a casual-day wearer who prefers understated designs                 | Person wanting individuality and visual expression; wearing situation not specified |
| Goal or meaning they seek             | Everyday wear, comfort, and simplicity (learner-stated promise; comfort is not verified as a product fact) | Individuality and visual expression (learner-stated need)                           |
| Concern before choosing               | Earlier learner-stated concern: standing out too much in public                                            | Not chosen yet                                                                      |
| What the page should help them decide | Not chosen yet                                                                                             | Not chosen yet                                                                      |
| Evidence or assumption                | Learner-provided hypothesis; earlier AI rationale adopted after a hint; both remain unvalidated            | Learner-provided contrast; not validated                                            |

## Early brand brief

| Decision                                 | Agreement                                        |
| ---------------------------------------- | ------------------------------------------------ |
| Brand name                               | Everyday                                         |
| One-sentence promise                     | Comfortable, simple T-shirts for everyday wear.  |
| Brand expression                         | Minimalist — clean, simple, and straightforward. |
| Primary archetype: the brand's character | Explorer                                         |
| Three voice traits                       | Clear, Calm, Confident                           |
| One example line in this voice           | Not chosen yet                                   |
| Learner's predicted audience effect      | Not yet evidenced                                |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                                                                                                                    |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | Preview copy, not yet approved: “Everyday, made simple.” / learner's promise / “View the white T-shirt.” Identical in A and B.                                                                                                                           |
| Modernist preview, reference, and annotations     | [Preview A](public/explorations/everyday-modernist.html): V&A's Christian Dell, _Dell-Lampe Type K_ (1929); grid, alignment, restrained palette. Intended to aid quick scanning; risk of a generic feel.                                                 |
| Postmodernist preview, reference, and annotations | [Preview B](public/explorations/everyday-postmodernist.html): V&A's Martine Bedin, _Super lamp prototype_ (1981); layering, offset blocks, serif/sans contrast. Intended to support expression; risk of competing with the product or feeling less calm. |
| Chosen direction and reason                       | Learner initially preferred A; reason not yet evidenced after an AI example. Keep as a preference, not a final direction.                                                                                                                                |
| Original SVG logo                                 | Learner selected the Daily Fold concept; AI-created SVG proposal at [logo review](public/explorations/everyday-logo-review.html), learner review pending                                                                                                 |
| Monochrome and small-size variants                | Same SVG proposed in one ink color; review page shows 175 × 32 px and 260 × 48 px presentations. AI browser inspection confirmed both images loaded; learner review pending.                                                                             |
| Logo review at actual use size                    | Proposal displayed at 175 × 32 px, matching the starter header image width; learner review pending                                                                                                                                                       |
| Shared palette, typography, spacing, and assets   | No branded system approved or applied. Storefront and style guide currently share the neutral starter `styles.css` and neutral wordmark; comparison styles remain isolated.                                                                              |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle                  | Approved proposal / planned page element                                                                                                                                                                 | Visitor benefit / factual support                                                                                                                                                                                               |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Reciprocity                | Free, ungated “A simple styling idea”: “Start with the plain white tee and pieces you already enjoy wearing.”                                                                                            | Offers a practical idea before asking for a size choice. The existing product image depicts a plain white T-shirt; the outfit wording is advice, not a product claim.                                                           |
| Commitment and consistency | Optional choice: “Keep it understated” or “Add a little expression”; show a brief styling suggestion that follows the visitor's choice. Do not store the choice or change the size selector or demo bag. | Lets the primary audience explore an understated idea and the contrasting audience an expressive idea. The page reflects only the visitor's selection and the visible plain-white shirt; no preferences or claims are inferred. |

Both proposals were approved by the learner on 2026-10-29. They remain proposed interface content and are not implemented. When asked how an element could help the intended visitor, the learner replied “unsure,” including after an AI example; the learner's own explanation remains not yet evidenced.

## Current storefront and style-guide implementation

- `public/index.html` is still the neutral starter storefront. It displays the plain white T-shirt and retains the size selector and temporary demo bag; it does not use the Everyday identity or Daily Fold SVG.
- `public/styleguide.html` is still the neutral starter board. It shares `public/styles.css` and the neutral starter wordmark, and its direction/logo content remains placeholder guidance rather than the approved brand identity.
- The Everyday preview pages and Daily Fold logo review page are isolated explorations. Neither is wired into the storefront or style guide.
- No learner revision to the previews, logo, or storefront is recorded. The previews and SVG proposal were drafted by AI; no learner revision reason is available.

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                                                                                                                                                                                                                                                 | Issue / PR                                                                                                                              | Actual checks and observations                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | [Preview A](public/explorations/everyday-modernist.html), [Preview B](public/explorations/everyday-postmodernist.html), [preview.css](public/explorations/preview.css), [Daily Fold SVG](public/assets/everyday-daily-fold.svg), [logo review](public/explorations/everyday-logo-review.html), [logo-review.css](public/explorations/logo-review.css) | [#1](https://github.com/JeshanFAhmad/is117-my-brand-studio/issues/1); branch `feature/brand-001-first-branded-storefront`; no PR exists | Latest `npm.cmd run check`: Prettier passed; `eslint .` completed; HTML Validate stopped with `No files matching patterns [ "'public/**/*.html'" ]`; Stylelint, `npm test`, and `npm run test:e2e` were not reached. Targeted Prettier, HTML Validate, and Stylelint for the logo-review files passed. Separately, `npm.cmd exec playwright -- test tests/browser/studio.spec.js --grep "negative: choosing no size"` passed (1 test): without a selected size, the size error is visible/nonempty and bag count remains 0. The learner inspected its test code and output; their explanation of the bug it would catch is not yet evidenced. Earlier AI browser inspection of hero previews at 1440 × 1000 and 375 × 812 checked matching copy/action/shirt image, intended fonts, action target, and horizontal overflow; axe reported zero violations for its selected WCAG tags. These are automated preview checks, not a learner observation or proof of brand fit. |

### Learner observations

- **Browser:** The available learner report says the neutral page and white shirt appeared; sizes were selectable; the learner selected XL, added it to the demo bag, saw the white shirt with XL there, and noticed no unexpected behavior. This is a report about the neutral baseline, not the branded storefront.
- **Keyboard:** No learner keyboard observation is recorded.
- **Narrow/mobile:** No learner narrow/mobile observation is recorded. Earlier AI browser checks of the preview pages at 375 × 812 are automated evidence only.
- **Revisions:** No learner-made revision or reason is recorded.
- **Merged BRAND-001 PR:** None exists; GitHub's pull-request list for this repository was empty when checked. Add a link only after a PR is created and merged.

**Logo proposal (learner review pending):** [Daily Fold SVG](public/assets/everyday-daily-fold.svg), shown in the [isolated review page](public/explorations/everyday-logo-review.html). Targeted Prettier, HTML Validate, and Stylelint passed; browser inspection confirmed both presentations load the same SVG at 175 × 32 px and 260 × 48 px. It has not been applied to the storefront or style guide.

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.
