# Mango Design Language

This document captures the current Mango visual system as observed from `https://getmangoapp.com/` and is intended to keep future web, social, and product work visually consistent.

## Brand Character

Mango presents as:
- dark, focused, and modern
- minimal with strong spacing
- high-contrast and highly legible
- bright-lime accented rather than gradient-heavy
- product-first, with restrained use of color for emphasis

The overall feel is closer to a premium dark SaaS UI than a playful consumer brand.

## Typography

The site currently references two primary typefaces:

- **Display:** `Space Grotesk`
- **Body/UI:** `Outfit`

### Recommended Usage

- Use **Space Grotesk** for:
  - hero headlines
  - section headings
  - standout callouts
  - short announcement graphics

- Use **Outfit** for:
  - body copy
  - supporting text
  - UI labels
  - buttons
  - captions
  - longer marketing sections

### Font Fallbacks

If the primary fonts are unavailable, use:

- Display fallback: `ui-sans-serif, system-ui, sans-serif`
- Body fallback: `ui-sans-serif, system-ui, sans-serif`
- Mono fallback: `ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace`

## Core Color Palette

The site strongly centers on a near-black canvas with white text and a bright lime accent.

### Primary Brand Colors

- **Mango Lime:** `#CCFF00`
- **Primary Background:** `#0D0D11`
- **Dark Surface:** `#141418`
- **Primary Text:** `#FFFFFF`
- **Secondary Text:** `#E5E5E5`

### Supporting Dark Neutrals

Use these for cards, dividers, depth, and layered dark UI states:

- `#1A1A24`
- `#1C1C1C`
- `#2C2C2C`
- `#112328`

### Supporting Utility / Accent Colors Seen on Site

These appear as secondary accents or utility colors and should be used sparingly:

- Blue: `#3080FF`
- Green: `#00C758`
- Purple: `#AC4BFF`
- Red: `#FB2C36`
- Orange: `#F99C00`

## Color Usage Guidance

### Use Mango Lime (`#CCFF00`) for
- primary highlights
- active states
- key badges
- CTA emphasis
- small accent rules or strokes
- selected chips or navigation emphasis

### Avoid Using Mango Lime for
- large body text blocks
- full-screen fills
- dense paragraph backgrounds
- heavy gradients that reduce legibility

### Use Dark Backgrounds for
- the main page canvas
- social announcement creative
- cards and UI framing
- premium/product-forward presentations

### Text Contrast Rules

- Prefer `#FFFFFF` on dark backgrounds for primary copy.
- Use `#E5E5E5` for secondary/supporting text.
- Keep lime accents short and deliberate so they retain impact.
- Maintain high contrast; the brand relies on sharp readability.

## Layout and Composition

Mango’s current design language favors:
- generous whitespace
- centered or strongly aligned compositions
- minimal on-image copy
- clean panels and rounded surfaces
- subtle glow or accent treatment instead of noisy decoration

### Visual Principles

- One strong focal point per section
- Minimal copy on graphics
- Dark surfaces layered with subtle contrast
- Accent color used as punctuation, not wallpaper
- Product clarity before decorative flourish

## Social Creative Guidance

For social or announcement images:

- Start with a dark background (`#0D0D11`)
- Use white logo and white headline text
- Add a restrained lime accent line, glow, or small UI detail
- Keep text to one short headline or two short lines max
- Prefer elegant spacing over filling the canvas

### Good Example Pattern

- white Mango logo
- dark panel or field
- one short announcement line
- small lime accent bar or glow
- muted secondary label only if necessary

## UI Styling Guidance

### Buttons

- Primary button: lime background with dark text when high emphasis is needed
- Secondary button: dark surface with white text and subtle border
- Hover states should feel crisp, not overly animated

### Panels and Cards

- Rounded corners
- Dark layered surfaces
- Thin borders or subtle contrast separation
- Avoid heavy shadows; prefer soft elevation and controlled glow

### Iconography and Illustration

- Keep iconography simple and geometric
- Avoid cartoonish shapes or oversaturated palettes
- Use accent colors only when they convey meaning or hierarchy

## Tone Translation Into Design

The visual language should communicate:
- confidence
- clarity
- technical polish
- premium simplicity

It should not feel:
- noisy
- overly playful
- cluttered
- generic startup-gradient heavy

## Implementation Notes

When building new assets, pages, or creative for Mango:

1. use **Space Grotesk** for headlines
2. use **Outfit** for body and UI text
3. anchor the composition in `#0D0D11` and `#141418`
4. reserve `#CCFF00` for important emphasis
5. keep everything minimal, legible, and spacious

## Source

Derived from the current Mango public site:
- `https://getmangoapp.com/`

This should be updated if the site’s fonts, palette, or component styling changes.