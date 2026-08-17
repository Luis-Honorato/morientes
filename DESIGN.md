---
name: Obsidian Titanium
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
  on-surface-variant: '#c4c7c8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c7'
  primary: '#ffffff'
  on-primary: '#2f3131'
  primary-container: '#e2e2e2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#c7c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#484949'
  on-secondary-container: '#b8b8b8'
  tertiary: '#ffffff'
  on-tertiary: '#002c71'
  tertiary-container: '#dae2ff'
  on-tertiary-container: '#005cdb'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#dae2ff'
  tertiary-fixed-dim: '#b1c5ff'
  on-tertiary-fixed: '#001947'
  on-tertiary-fixed-variant: '#00419f'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  obsidian-deep: '#050505'
  titanium-brushed: '#D1D1D1'
  light-leak-blue: rgba(25, 110, 250, 0.15)
  border-subtle: rgba(255, 255, 255, 0.08)
typography:
  display-2xl:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  technical-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is a high-end, immersive framework tailored for a creative production powerhouse. It balances the raw intensity of a dark, obsidian-inspired environment with the surgical precision of technical hardware. 

The visual direction is **Modern-Corporate with a Tech-Luxury edge**, leaning into a cinematic aesthetic. It utilizes a deep "Obsidian" base to provide maximum contrast for high-fidelity video content and portfolio imagery. Design elements are inspired by precision engineering: thin strokes, metallic textures, and "light leaks" that simulate a high-end lens flare or studio lighting. 

Key attributes:
- **Sophisticated:** Refined through generous negative space and a disciplined color palette.
- **Cutting-Edge:** Communicated via monospaced technical accents and high-density information layouts.
- **Tactile:** Subtle use of brushed titanium gradients and glowing borders to create a sense of physical premium hardware.

## Colors

The palette is anchored in **#0A0A0A (Obsidian)**, ensuring a true black-level depth that allows media content to stand out. 

- **Primary & Secondary:** We use high-key grays (#F5F5F5 and #A1A1A1) for text and structural lines to mimic the look of etched metal. 
- **Accent:** A single high-tech blue (#196EFA) is used sparingly for interactive highlights, active states, and "recording" indicators.
- **Light Leaks:** Use soft, blurred radial gradients in the background using `light-leak-blue` to break the monotony of the dark background and provide a sense of atmospheric depth.
- **Surface Treatment:** Higher-level containers should use a subtle vertical linear gradient from #141414 to #0A0A0A to simulate a brushed metal sheen.

## Typography

This design system employs a dual-typeface strategy to represent the intersection of "Creative" and "Production."

- **Inter** handles all narrative and display content. Headlines should use tight tracking (letter spacing) and heavy weights to feel impactful and grounded.
- **JetBrains Mono** is the "production" voice. It is used for metadata, technical specifications, timestamps, and navigation labels. It should always feel precise and deliberate.
- **Micro-type:** Don't be afraid of small sizes for labels (10px-12px) if the contrast is maintained. This contributes to the high-density "tech" aesthetic.

## Layout & Spacing

The layout philosophy is based on an **Asymmetric Fluid Grid**. While content generally adheres to a 12-column structure on desktop, elements (especially video containers and imagery) should intentionally break the grid or be offset to create a dynamic, editorial feel.

- **Asymmetry:** Use a 7:5 or 8:4 column split for main content vs. metadata to create visual tension.
- **Vertical Rhythm:** Sections should be separated by large "breathable" gaps (120px+) to maintain a luxury, gallery-like feel.
- **Margins:** Desktop layouts use wide 64px gutters to frame the content, making the screen feel like a cinematic viewport.
- **Responsive:** On mobile, collapse into a single-column stack but maintain the monospaced technical labels pinned to the top-right of containers.

## Elevation & Depth

Depth is not communicated through shadows, but through **Tonal Layering** and **Luminance**.

- **Stacked Tiers:** The background is #0A0A0A. Surfaces (cards/modals) use #141414 with a 1px border of `rgba(255, 255, 255, 0.08)`.
- **Glassmorphism:** Use backdrop-blur (20px+) on navigation bars and overlays to simulate premium glass optics.
- **Inner Glows:** For primary buttons or active states, use a very subtle inner shadow (white at 10% opacity) to give the appearance of a beveled, physical edge.
- **The "Light Leak":** Background depth is created by placing soft, large, low-opacity blue or white radial gradients behind content blocks, simulating light hitting a dark stage.

## Shapes

The shape language is **Strict and Geometric**. We avoid "friendly" rounded corners in favor of sharp, professional edges or very slight softening.

- **Standard Radius:** 4px (Soft) for buttons and inputs, just enough to prevent a "sharp" digital feel while maintaining a technical look.
- **Hard Edges:** Main video containers and section dividers should remain 0px (Sharp) to emphasize the grid and architectural strength.
- **Circular Elements:** Reserved strictly for play buttons and status indicators to provide a functional contrast to the rectangular grid.

## Components

- **Buttons:** Primary buttons feature a "Titanium" gradient background with Inter Semibold text. Secondary buttons are "Ghost" style with a 1px `border-subtle` and a hover state that increases border opacity.
- **Video Containers:** Always 16:9 or 21:9 aspect ratios. On hover, show technical metadata (resolution, frame rate, project code) in `technical-sm` typography using JetBrains Mono.
- **Minimalist Navigation:** A fixed top bar with a heavy backdrop-blur. Navigation links use `label-caps` typography. The active link is indicated by a 2px horizontal line in `tertiary_color_hex`.
- **Input Fields:** Bottom-border only, or a very dark #141414 fill. Labels should be monospaced and positioned above the field. Focus state triggers a subtle glow on the bottom border.
- **Micro-interactions:** Transitions should be "Mechanical"—fast, precise, and linear. Use 200ms durations. Avoid "bouncy" or organic easings.
- **Project Cards:** Use asymmetric sizing. Metadata (Client, Year) should be aligned to a vertical "spine" or placed in the corners of the image to keep the center of the visual clean.