# Daybreak Books — Kimi K2.6 Design

## Palette
- `#F3E8D4` (warm parchment, 70% surface)
- `#8B6F4B` (aged leather, 20% accent)
- `#1C1814` (inkwell brown, 10% primary)
- `#E4D4BC` (faded vellum, placeholder background)
- `#4A3A2C` (sepia pen, secondary text)

## Typography
- Display/headings: **Cormorant Garamond** (Google Fonts, weights 500/600/700) — a refined serif with literary elegance, as if set by a hand-fed letterpress.
- Body: **Crimson Pro** (Google Fonts, weight 400/400italic) — a warm, highly readable serif designed for long-form reading on screens, with an authentic book-page feel.

## Layout Direction
Single-column, centered, generous vertical rhythm. The page breathes like a quiet Tuesday morning in a Carroll Gardens shop. Max-width 840px on desktop, full-bleed on mobile. Sticky header anchors the top at 64px. Hero is exactly what you see when you push through the door: the shelves, the quiet, the light.

## Hero Placeholder Strategy
A CSS-only rectangle using a warm linear gradient (parchment to faded tan) with a nested CSS silhouette of stacked books: four horizontally-oriented `<div>` elements of decreasing width, alternating between the accent color and a muted brown, layered with box-shadow to create depth. Overlaid with a soft radial gradient glow from the top-center, evoking early morning light hitting a crooked stack of used paperbacks by the front window.

## Micro-Detail Accent
A fine 1px horizontal rule (`#D8C8B2`, low contrast, 40% of container width) sits above the caption. The caption itself is 11px uppercase with 0.15em letter-spacing in sepia semi-opaque text — like a hand-stamped note on the counter.

## Animation Strategy
Single animation: the H1 fades in with a translateY(16px→0) over 300ms via CSS `@keyframes fadeUp`. No other motion. The stillness is the point.

## Why This Is Not a SaaS Template
This page uses nothing but warm serif typefaces, a palette pulled from a leather-bound cover and a paper bag, and a literal CSS stack of used books as the hero visual. The layout is unhurried and narrow, the CTA is a mailto link (no booking widget, no signup flow), and the footer reads like a hand-stamped receipt. There are no cards, no avatars, no gradients that go blue-to-purple, no mock testimonials, no dashboard anywhere. It looks like a bookshop because it smells like paper and quiet, not like cloud infrastructure.
