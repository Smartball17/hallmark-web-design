---
name: hallmark-web-design
description: Distinctive, evidence-led web design and redesign that avoids generic AI-generated UI. Use when designing, auditing, or substantially reshaping a website, landing page, app surface, or responsive interface where visual identity, hierarchy, content fit, and production quality matter.
---

# Hallmark Web Design for Manus

Use this skill to make interfaces feel deliberately designed rather than assembled from familiar AI patterns. Adapt the method to the product; do not copy a Hallmark theme or impose a generic aesthetic.

## Core rule

Design from the user's real job, real content, and the subject's own visual language. Make one opinionated choice memorable per screen, keep the rest quiet, and remove decoration that does not improve understanding or action.

## When redesigning an existing product

1. Read the existing app, routes, design tokens, fonts, content model, and tests before proposing changes.
2. Record what must remain: routes, links, forms, handlers, language support, brand assets, authentication, and factual content.
3. Decide whether the request is a full redesign, a restyle, or a polish pass. Do not silently remove wiring or deep content.
4. Capture the current key screens at desktop and mobile before changing them.
5. Define the new system and page anatomy before editing code.
6. Implement one representative screen first, review it visually, then extend the system.

## Plan before code

Write a compact design brief with:

- **Job:** the one decision or action this screen should enable.
- **Audience:** who arrives and what they already know.
- **Material:** real content, imagery, data, and brand assets available.
- **Tone:** choose a specific direction, not “clean and modern”.
- **Signature:** one visual idea that belongs to this product.
- **Tokens:** 4–6 colours, typography roles, spacing, surfaces, borders, focus, and motion.
- **Anatomy:** a short wireframe showing what appears first, second, and last.
- **Content rules:** what is factual, current, sourced, user-generated, or absent.

Challenge the plan once: if it could describe any SaaS, magazine, or dashboard, revise it until it is specific to the product.

## Anti-pattern floor

Never ship these as defaults:

- an eyebrow above every heading;
- tracked all-caps labels or small caps used as decoration;
- one coloured or italic word inside a headline without a real semantic reason;
- middle-dot metadata strings;
- arrows appended to every link or button;
- identical card grids repeated down the page;
- cards nested inside cards;
- invented metrics, testimonials, customer counts, logos, or proof;
- generic purple-blue gradients, decorative blobs, circuit lines, or node maps with no real relationship;
- a dark dashboard with one acid accent unless the product genuinely requires that material;
- a warm cream background plus oversized serif plus terracotta accent unless the brief specifically demands it;
- a sidebar, chart, progress bar, or numbered steps when the content is not actually sequential or operational;
- text that explains the system rather than helping the user use it.

A rule may be broken only when the content requires it. Record the reason in the design brief.

## Content and language

Use sentence case and plain verbs. Name things the way users understand them, not the way the database or architecture is named. A button must state what happens: “Save changes”, “Open source”, “Start lesson”. Keep the same action name through the whole flow.

Do not invent freshness, numbers, ownership, quotes, outcomes, or source confidence. When evidence is missing, show the absence plainly or omit the claim.

For bilingual products, define the layout with the longer language in mind. Never solve translation overflow by shrinking text below a readable size.

## Interaction and motion

Make interaction reveal a real state change or relationship. Prefer short transitions on transform and opacity. Use motion for opening, filtering, connecting, or confirming—not for constant ambient decoration. Add visible keyboard focus, useful empty states, and a reduced-motion fallback. Keep content understandable without scripting where practical.

## Responsive and accessibility floor

Check at least one desktop and one narrow mobile viewport. Keep headlines breakable, image grid tracks flexible, horizontal overflow clipped safely, and primary content usable without hover. Every interactive control needs a visible `:focus-visible` state. Check contrast, target size, reading order, alt text, and reduced motion.

## Review loop

1. Render the representative screen in a real browser.
2. Review the screenshot cold: hierarchy, density, distinctiveness, mobile behavior, and whether the signature is functional rather than decorative.
3. Check every preserved route, link, form, heading, and handler after a redesign.
4. Run project type checks and tests.
5. Fix all accessibility and layout failures. Resolve or explicitly record any deliberate exception to the anti-pattern floor.
6. Stop after one focused refinement pass unless a concrete defect remains.

Read `references/hallmark-gates.md` for the compact gate checklist and `references/smartball-adaptation.md` when this skill is used on SMARTBALL AI or another knowledge product.

## Upstream attribution

This Manus adaptation is inspired by and compatible with the open-source Hallmark project by Nutlope/Together AI, licensed under MIT: https://github.com/nutlope/hallmark. It is a workflow adaptation, not a copy of Hallmark's theme library or implementation.
