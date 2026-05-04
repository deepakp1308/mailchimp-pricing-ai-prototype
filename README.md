# Mailchimp Pricing · Analytics AI Prototype

A single-page prototype that mirrors the public Mailchimp Marketing pricing page and layers in one Analytics AI experience. Built for stakeholder review.

## Single AI overlay

The page renders a single deterministic AI experience: the **Pricing Co-Pilot Rail**. The rail is a sticky right-side buddy with persona-driven prompts, an animated mini chart, an insight, and one cited customer outcome. Below the rail, a separate yellow "Get Standard with Analytics AI" CTA smooth-scrolls to the pricing table.

The deeper "Try Analytics AI" sandbox is reachable from the rail via "Open the full Analytics AI sandbox", which opens a focus-trapped modal of the same demo. The modal has no checkout flow inside it and closes back to the page with the passive "Get Standard" CTA still visible below the rail.

## Pricing comparison table

The pricing comparison table now mirrors the structure of the live mailchimp.com/pricing/marketing page:

- Top utility bar with "Customize your plan", a Contacts dropdown (default 0 to 500), and a yellow "Find my plan" ribbon.
- Three paid columns visible at the top: Premium, Standard (with "Best deal" yellow badge), Essentials. The leftmost meta column shows the Free plan blurb and a "Sign Up" button.
- Four row groups in this order: Key Plan Features, Admin, Services & Support, Email Marketing & Segmentation.
- "Compare all features" pill button below the table.
- Free plan is collapsed into a "Basic plans for smaller businesses" section below the table, not a fourth top-level column.

## Sections, in order

1. Top nav
2. Pricing hero
3. Pricing utility bar (Customize your plan + Contacts pill + yellow ribbon)
4. Pricing comparison table + Co-Pilot Rail
5. Awards / "Work with a trusted industry leader" (dark)
6. Two-column: Rates for nonprofits and charities + Prefer to pay as you go
7. Basic plans for smaller businesses (centered)
8. Real customer testimonials
9. FAQs (4 accordion items)
10. Footnotes (numbered)
11. Footer (related links, Watch.Mailchimp callout, columns, lockup)

## Real customer quotes

Verbatim, attribution intact. No fabricated quotes anywhere.

- Anuj Chaudhry, Chief Growth Officer, Faris Team. Outcome: -92% time on quarterly review.
- Suskia Strafella, Founder, I Am Wild Woman. Outcome: 2.3x campaign revenue, quarter over quarter.
- Damon Runnals, CEO, Minnesota Playlist. Outcome: +38% click-through rate.

## Brand tokens

- Cavendish Yellow `#FFE01B` for primary CTA and accents
- Peppercorn `#241C15` for text and dark surfaces
- Teal Dark `#007C89` for links and secondary accents
- Off-white `#F6F6EE` background, white card surfaces with Peppercorn-tinted borders
- Cooper-style serif (Cooper Light / Georgia) for display headlines, italics for hero subheads
- Helvetica / system sans for body
- 12-column grid, generous whitespace

## Accessibility

- Keyboard-first. Every CTA, persona button, prompt, FAQ accordion, and modal action is reachable via Tab.
- Modal traps focus and closes on Esc.
- `prefers-reduced-motion` is respected. Chart animations and the live indicator pulse are paused when set.
- Every visual has alt text or an aria-label.

## Asset map

See `assets/` for staged source. All illustrations are sourced from the Mailchimp brand asset library.

## Run locally

Open `index.html` in a browser. No build step.
