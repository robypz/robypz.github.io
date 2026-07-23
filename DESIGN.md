---
name: Warm CV-Inspired Portfolio
colors:
  surface: '#FFFFFF'
  surface-dim: '#FFFCF8'
  surface-bright: '#FFFFFF'
  surface-container-lowest: '#F7EEE2'
  surface-container-low: '#FBF5EC'
  surface-container: '#FBF5EC'
  surface-container-high: '#F3E6D3'
  surface-container-highest: '#EEDDC4'
  on-surface: '#241C13'
  on-surface-variant: '#5C5347'
  inverse-surface: '#241C13'
  inverse-on-surface: '#FFFCF8'
  outline: '#C9BBA3'
  outline-variant: '#E9DCC7'
  surface-tint: '#FFBD47'
  primary: '#211A14'
  on-primary: '#FFFFFF'
  primary-container: '#FF8427'
  on-primary-container: '#3D1A00'
  inverse-primary: '#FFBD47'
  secondary: '#5C5347'
  on-secondary: '#FFFFFF'
  secondary-container: '#F3E6D3'
  on-secondary-container: '#3D3226'
  tertiary: '#B22600'
  on-tertiary: '#FFFFFF'
  tertiary-container: '#FBD9CB'
  on-tertiary-container: '#5C1200'
  error: '#B3261E'
  on-error: '#FFFFFF'
  error-container: '#F9DEDC'
  on-error-container: '#410E0B'
  primary-fixed: '#FFBD47'
  primary-fixed-dim: '#FFBD47'
  on-primary-fixed: '#3D1A00'
  on-primary-fixed-variant: '#7A3B00'
  secondary-fixed: '#241C13'
  secondary-fixed-dim: '#5C5347'
  on-secondary-fixed: '#FFFCF8'
  on-secondary-fixed-variant: '#3D3226'
  tertiary-fixed: '#FBD9CB'
  tertiary-fixed-dim: '#F2B49A'
  on-tertiary-fixed: '#3D0F00'
  on-tertiary-fixed-variant: '#7A2400'
  background: '#FFFCF8'
  on-background: '#241C13'
  surface-variant: '#F3E6D3'
  neon-lime: '#FFBD47'
  deep-charcoal: '#1A130B'
  subtle-gray: '#726249'
  surface-border: '#E9DCC7'
  accent-red: '#B22600'
  accent-orange: '#FF8427'
  accent-red-orange: '#E84C22'
  accent-terracotta: '#B64926'
  accent-mustard: '#CC9900'
  accent-warm-gray: '#5C5347'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 32px
---

## Brand & Style
This design system mirrors the visual identity of Robert's résumé: a warm, paper-like canvas with a friendly illustrated portrait and bold color-coded section markers. It trades the earlier "dark mode developer" narrative for an approachable, human, **editorial** feel — closer to a printed CV than a terminal.

The target audience remains tech recruiters, CTOs, and project managers, but the tone shifts from "expertise in the shadows" to "expertise you can sit down and read comfortably." Warm neutrals and a confident red/amber accent pair replace neon-on-charcoal.

## Colors
The palette is dominated by a soft off-white canvas (`#FFFCF8`) — never stark white — to echo the paper tone of the résumé.

- **Accent Red (`#B22600`):** The signature color lifted directly from the CV's section headers. Used for eyebrow labels ("Specialties", "Projects", "About"), hover states on links/icons, and any small text or border sitting on the light canvas.
- **Warm Amber (`#FFBD47`):** Used exclusively as a solid fill — primary CTA buttons, the language-toggle active pill, and the decorative circles around the portrait. Never used as text or a thin border on the light background (fails contrast).
- **Supporting warm circle palette:** Orange (`#FF8427`), red-orange (`#E84C22`), terracotta (`#B64926`), mustard (`#CC9900`) and a warm gray (`#5C5347`) — used for the decorative circles behind the hero portrait and the per-section icon badges, echoing the CV header illustration.
- **Deep charcoal (`#1A130B`):** Reserved for dark scrims over photographs (project thumbnail hover overlays, modal gallery controls) — never used as a page background anymore.
- **Neutral text:** `on-surface` (#241C13) for body copy, `secondary`/`subtle-gray` warm grays for de-emphasized text — all tuned to pass WCAG AA (4.5:1+) against the cream canvas.

## Typography
Unchanged: **Plus Jakarta Sans** for headings and body copy, **JetBrains Mono** for skill tags/metadata labels. The pairing still reads as professional and technical, now on a warmer canvas.

## Layout & Spacing
Layout structure is unchanged (12-column desktop grid, 1200px max-width, `120px` section gaps, `20px` mobile margins). The hero section was restructured into two columns: copy + CTAs on one side, the illustrated portrait ringed by decorative color circles on the other (mirroring the CV header layout).

## Elevation & Depth
Depth now comes from soft warm-cream tonal layers instead of dark tonal layers:

- **Base Level:** `#FFFCF8` (page canvas).
- **Surface Level:** `#FBF5EC` (cards, chips, mobile nav).
- **Footer Level:** `#F7EEE2` (slightly deeper cream to ground the page).

Borders are thin, warm, and light (`#E9DCC7`) rather than dark hairlines. Hover "glow" effects on cards/buttons use a soft accent-red halo instead of a neon-amber one, since amber doesn't read against the light canvas.

## Shapes
Unchanged: **Rounded** language, `0.5rem` base radius, full pill shape for tags and skill chips, `rounded-xl` for larger cards. Section eyebrows now carry a small circular icon badge (filled with an accent color, white icon glyph) directly lifted from the CV's icon+heading pattern.

## Components
- **Primary Buttons:** Solid **Warm Amber** (`#FFBD47`) background with dark text (`#1A130B`). Hover shifts fill to **Orange** (`#FF8427`).
- **Secondary Buttons:** Ghost style with a light warm border; hover transitions border/text to **Accent Red**.
- **Section Eyebrows:** Small circular icon badge (amber/terracotta/red fill + white icon) followed by bold uppercase **Accent Red** label — mirrors the CV's icon-plus-heading rows.
- **Skill Chips:** Cream background (`#FBF5EC`) with warm border and warm-gray text; border highlights red on hover.
- **Project Cards:** Light cream surfaces; image thumbnails keep a dark scrim overlay on hover (for legibility over photos) with an amber "View gallery" label; card title turns accent red on hover.
- **Hero Portrait:** Circular illustrated portrait framed by 7 decorative circles in the CV's warm palette, replacing the old dark network-graph banner.
