# Mailchimp Pricing · Analytics AI Prototype

A single-page prototype that mirrors the public Mailchimp Marketing pricing page and layers in three switchable Analytics AI experiences. Built for stakeholder review.

## Variants

The variant switcher tabs (below the top nav) toggle the AI overlay only. The pricing comparison table grid stays identical across all three variants.

- `?v=p1` Pricing Co-Pilot Rail (default). Sticky right-rail buddy with three suggested questions and a rotating customer-quote ticker.
- `?v=p2` Inline Plan Lens. A compact "Try Analytics AI" block inside the Standard plan card hero. Equal-height spacers preserve grid parity. Above-table ribbon scrolls three real customer outcomes.
- `?v=p3` Floating Demo Console. Bottom-right pill that expands into a 30-second scripted Analytics AI demo with chart fill and a Damon Runnals citation.

All three variants open the same shared "Try Analytics AI" modal: scoped chat on the left, chart and insight + cited customer quote on the right, sticky checkout footer pre-selecting Standard with `analytics_ai=on`.

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

- Keyboard-first. The variant switcher, every CTA, and the modal are reachable via Tab.
- Modal traps focus, closes on Esc.
- `prefers-reduced-motion` is respected. The Variant 3 console autoplay is replaced by a static still + CTA. The Variant 2 ribbon and pulse animations are paused.
- Every visual has alt text or an aria-label.

## Asset map

See `assets/` for staged source. All illustrations are sourced from the Mailchimp brand asset library.

## Run locally

Open `index.html` in a browser. No build step.
