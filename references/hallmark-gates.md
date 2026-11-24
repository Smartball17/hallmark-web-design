# Hallmark gates

Use this checklist after a browser render. Record deliberate exceptions.

## Floor

- [ ] All colours and fonts come from tokens.
- [ ] No `transition: all`; animate transform and opacity where possible.
- [ ] `:focus-visible` is present and visible on every interactive control.
- [ ] Reduced motion keeps content visible and removes non-essential movement.
- [ ] No invented facts, metrics, testimonials, logos, or counts.
- [ ] No decorative eyebrow, tracked all-caps label, middle-dot metadata, or universal arrows.
- [ ] No nested card pattern, generic gradient, or decorative graph.
- [ ] Desktop hero shows its purpose and primary action without avoidable scroll.
- [ ] Mobile layout is usable without hover and without horizontal scrolling.
- [ ] Headlines wrap safely; images do not collapse grid tracks.

## Distinctiveness

- [ ] The signature belongs to this product and comes from its subject matter.
- [ ] The composition is not a generic SaaS dashboard, magazine, or landing page.
- [ ] Structure communicates content relationships instead of decorating them.
- [ ] The page has one dominant idea, not several competing visual treatments.

## Content

- [ ] Copy uses sentence case and plain verbs.
- [ ] Buttons describe their actual outcome.
- [ ] Dates, sources, ownership, freshness, and language variants are accurate.
- [ ] Empty and error states explain the next useful action.

## Evidence after implementation

- [ ] Key routes, links, forms, headings, and handlers preserved.
- [ ] TypeScript/build checks pass.
- [ ] Tests pass.
- [ ] Desktop and mobile screenshots reviewed.
