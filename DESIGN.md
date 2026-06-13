---
name: Neon Developer Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c0cab1'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8a947d'
  outline-variant: '#404a36'
  surface-tint: '#83dd2b'
  primary: '#ffffff'
  on-primary: '#1a3700'
  primary-container: '#9efa49'
  on-primary-container: '#3c7100'
  inverse-primary: '#386a00'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#ffffff'
  on-tertiary: '#003354'
  tertiary-container: '#cfe5ff'
  on-tertiary-container: '#0e69a4'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#9efa49'
  primary-fixed-dim: '#83dd2b'
  on-primary-fixed: '#0d2000'
  on-primary-fixed-variant: '#295000'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#cfe5ff'
  tertiary-fixed-dim: '#98cbff'
  on-tertiary-fixed: '#001d33'
  on-tertiary-fixed-variant: '#004a77'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  neon-lime: '#A2FF4D'
  deep-charcoal: '#0F0F0F'
  subtle-gray: '#666666'
  surface-border: '#262626'
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
This design system is tailored for an elite IT & Programming specialist. It blends a **High-Contrast / Bold** aesthetic with a refined **Modern** layout. The visual narrative focuses on "Expertise in the Shadows"—using a deep, dark canvas to make technical achievements and programming prowess vibrate with energy.

The target audience includes tech recruiters, CTOs, and project managers looking for high-end PHP and systems development. The UI should evoke a sense of precision, technical mastery, and "always-on" availability. It utilizes the raw power of neon accents against charcoal backdrops to signify a cutting-edge developer environment.

## Colors
The palette is dominated by a true-dark background (`#0A0A0A`) to reduce eye strain and provide maximum contrast for code-heavy content. 

- **Primary (Neon Lime):** Reserved for the most important Calls to Action (CTAs), primary headings, and critical "active" states. It represents the "pulse" of the application.
- **Secondary (Deep Charcoal):** Used for card surfaces and container backgrounds to create subtle depth without breaking the dark immersion.
- **Tertiary (Workana Blue):** A legacy nod to the developer's professional roots, used sparingly for secondary links or technical tags.
- **Neutral:** A range of grays used for supporting text to maintain a clear visual hierarchy.

## Typography
The system uses **Plus Jakarta Sans** for its modern, approachable yet highly geometric structure, ensuring the "Rober Y." brand feels professional and contemporary. 

To emphasize the technical nature of IT and Programming, **JetBrains Mono** is introduced for labels, skill tags, and metadata. This creates a functional contrast between the "narrative" of the portfolio and the "technical data" of the skills. Headlines use aggressive negative letter-spacing and heavy weights to command attention.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop (12 columns, 1200px max-width) to ensure the portfolio feels like a curated gallery. 

- **Vertical Rhythm:** Large vertical gaps (`120px`) between sections are essential to give the dark design "room to breathe" and prevent it from feeling claustrophobic.
- **Mobile Adaptation:** On mobile, margins shrink to `20px`, and section gaps reduce to `64px`. Content reflows into a single-column vertical stack. 
- **Grouping:** Use the `stack-sm` unit for related metadata (e.g., Name + Hourly Rate) and `stack-md` for distinct content blocks (e.g., Headline + Body Text).

## Elevation & Depth
In this dark-themed system, depth is conveyed through **Tonal Layering** rather than heavy shadows. 

- **Base Level:** `#0A0A0A` (The background canvas).
- **Surface Level:** `#1A1A1A` (Cards, project containers).
- **Interaction Level:** `#262626` (Hover states on cards).

Shadows, when used, are extreme-low-opacity black glows that serve to slightly separate cards from the background. High-contrast **Neon Lime** outlines (1px) are used to indicate focus states and primary interactive boundaries, creating a "glowing wireframe" effect that feels technical and precise.

## Shapes
The shape language is **Rounded**, utilizing a `0.5rem` (8px) base radius for most containers and a full **Pill** shape for tags and skill chips. This softens the aggressive high-contrast color palette, making the professional profile feel more approachable. 

Cards and large sections should use the `rounded-xl` (24px) setting to create a modern, app-like feel.

## Components
- **Primary Buttons:** Solid **Neon Lime** (`#A2FF4D`) background with black text (`#000000`). No border. High-impact for "Hire Me" or "View Project."
- **Secondary Buttons:** Ghost style with a 1px border of `#666666` and white text. On hover, the border and text transition to the primary neon color.
- **Skill Chips:** Dark background (`#1A1A1A`) with subtle white or tertiary blue text. These should use the **JetBrains Mono** font.
- **Project Cards:** Deep charcoal backgrounds with a subtle transition to a 1px Neon Lime border on hover. 
- **Input Fields:** Bottom-border only or very subtle dark-gray backgrounds. Focus state must trigger a Neon Lime glow/border.
- **Experience Timeline:** A vertical 2px line in `#262626` with Neon Lime nodes for each career milestone (e.g., PHP Developer roles).