---
name: Sonic Vanguard
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
  on-surface-variant: '#c0c7d6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8a919f'
  outline-variant: '#404754'
  surface-tint: '#a6c8ff'
  primary: '#a6c8ff'
  on-primary: '#00315f'
  primary-container: '#2992ff'
  on-primary-container: '#002a53'
  inverse-primary: '#005fb0'
  secondary: '#ffb2b8'
  on-secondary: '#67001c'
  secondary-container: '#be003b'
  on-secondary-container: '#ffcccf'
  tertiary: '#ffb77f'
  on-tertiary: '#4e2600'
  tertiary-container: '#dc7600'
  on-tertiary-container: '#442000'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a6c8ff'
  on-primary-fixed: '#001c3b'
  on-primary-fixed-variant: '#004786'
  secondary-fixed: '#ffdadb'
  secondary-fixed-dim: '#ffb2b8'
  on-secondary-fixed: '#40000e'
  on-secondary-fixed-variant: '#91002b'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb77f'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6f3900'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  surface-deep: '#000000'
  surface-elevated: '#1A1A1A'
  vibrant-blue: '#2499FF'
  electric-orange: '#FF6B00'
  power-pink: '#EC3258'
typography:
  display-hero:
    fontFamily: Hanken Grotesk
    fontSize: 72px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  cta-label:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '800'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap-lg: 120px
  section-gap-md: 80px
  stack-gap: 16px
---

## Brand & Style

This design system is engineered for the modern independent creator. It balances the grit of the music industry with the precision of a high-tier fintech platform. The personality is **empowering, high-energy, and professional**, designed to make artists feel like they are entering a partnership rather than just using a utility.

The aesthetic leans into **Modern Minimalist with High-Contrast Bold** influences. We utilize deep obsidian backgrounds to allow artist photography and vibrant accents to pop with maximum intensity. Large-scale typography and spacious layouts communicate transparency and scale, ensuring that complex distribution data feels accessible and heroic.

## Colors

The palette is built on a "Midnight Studio" foundation. A pure black (`#000000`) base ensures that vibrant accents achieve maximum "glow" through high-contrast ratios.

- **Primary (Vibrant Blue):** Reserved for core actions, distribution status, and "Revenue" indicators. It represents trust and the digital ecosystem.
- **Secondary (Power Pink/Orange):** Used for "Hot" features, promotional callouts, and the "Sign Up" funnel to create urgent visual interest.
- **Tonal Logic:** In this dark-first system, surfaces are defined by subtle shifts in luminosity rather than borders. Active states should use the primary blue, while secondary highlights use the orange-to-pink spectrum.

## Typography

The typography system is aggressive and modern. **Hanken Grotesk** provides a sharp, geometric edge for headlines, utilizing tight letter-spacing at large sizes to mimic editorial music magazines. 

**Inter** is the workhorse for body copy, ensuring maximum legibility on dark backgrounds where "haloing" can be an issue. **JetBrains Mono** is introduced for technical labels (e.g., ISRC codes, pricing units, and metadata) to provide a "behind-the-scenes" industrial feel that resonates with the technical nature of music distribution.

## Layout & Spacing

The layout follows a **Fluid Grid** model with high-density vertical rhythm. 

- **Desktop:** 12-column grid with generous 120px gaps between major narrative sections to emphasize "Premium" positioning.
- **Mobile:** 4-column grid with reduced vertical gaps (64px) to maintain momentum.
- **The "Hero" Offset:** Content should often be centered or staggered against high-quality artist photography. Use whitespace as a structural element to prevent the dark theme from feeling claustrophobic.

## Elevation & Depth

Depth is achieved through **Tonal Layering** and **Vibrant Glows** rather than traditional shadows.

- **Level 0 (Base):** `#000000` for the main canvas.
- **Level 1 (Cards/Containers):** `#0F0F0F` or `#1A1A1A`. These should feel like they are part of the floor, not floating.
- **Interactive Depth:** Buttons and active cards use a subtle "Outer Glow" (0px blur, primary color at 20% opacity) to simulate neon lighting in a dark studio.
- **Glassmorphism:** Use 20px backdrop blurs on navigation bars and floating music players to maintain context of the underlying artist imagery.

## Shapes

The shape language is **Soft (0.25rem)**. We avoid overly rounded or "bubbly" elements to maintain a professional, sharp-edged industry feel. 

- **Primary Buttons:** Subtle rounding (4px) to keep them feeling architectural.
- **Artist Image Containers:** Hard 0px corners are permitted for large hero shots to maximize the "Editorial" look.
- **Pricing Tables:** Use sharp vertical lines and subtle rounded corners on the overall container only.

## Components

### Buttons
- **Primary:** Gradient background (Vibrant Blue to Cyan), bold Hanken Grotesk caps, 4px radius. High-energy hover state with an increased glow.
- **Secondary:** Transparent with a 2px solid border, white text.

### Pricing Tables
- Use a "Vertical Pillar" layout. The "Unlimited" plan should be visually anchored with a primary color border or a subtle gradient top-bar. Pricing figures should be in `headline-lg` to ensure they are the first thing seen.

### Testimonial Cards
- Dark-on-dark styling. Quote text in `body-lg` (Italic), with the artist's name in `label-caps`. Include a high-res, desaturated avatar to keep the focus on the quote.

### Music Distribution Status
- Use "Step Progress" indicators. Completed steps in Vibrant Blue; active steps pulsing; upcoming steps in low-opacity grey.

### Input Fields
- Underline-only or subtle `#1A1A1A` fills. Focus state should trigger a primary blue bottom-border and a "glow" effect. No heavy boxes.