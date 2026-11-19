---
name: Obsidian Engineering
colors:
  surface: '#0e1321'
  surface-dim: '#0e1321'
  surface-bright: '#343948'
  surface-container-lowest: '#090e1c'
  surface-container-low: '#161b2a'
  surface-container: '#1a1f2e'
  surface-container-high: '#252a39'
  surface-container-highest: '#303444'
  on-surface: '#dee2f6'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dee2f6'
  inverse-on-surface: '#2b303f'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00885d'
  on-tertiary-container: '#000703'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0e1321'
  on-background: '#dee2f6'
  surface-variant: '#303444'
typography:
  display:
    fontFamily: Geist
    fontSize: 3.75rem
    fontWeight: '600'
    lineHeight: 4.25rem
    letterSpacing: -0.04em
  display-mobile:
    fontFamily: Geist
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: 3rem
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Geist
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: 2rem
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Geist
    fontSize: 1.125rem
    fontWeight: '500'
    lineHeight: 1.625rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.875rem
    letterSpacing: 0em
  body-md:
    fontFamily: Geist
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: -0.01em
  code-block:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: -0.015em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.06em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-md: 3rem
  margin-lg: 6rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system targets high-caliber software engineering portfolios, technical case studies, and senior developer showcases. The personality is precise, deliberate, quiet, and hyper-focused—evoking the craftsmanship and technical rigor found in modern developer tools like Linear, Vercel, and Raycast.

### Aesthetic Direction
- **High-End Modern Dark Surface:** Rooted in deep cosmic slates rather than pure pitch black, creating depth and atmospheric focus.
- **Glassmorphic Precision:** Subtle semi-transparent surfaces layered with 1px hairline borders that capture edge highlights.
- **Controlled Luminescence:** Restrained electric indigo and cobalt accents that emit soft, diffused glows to guide interaction and focus attention without visual noise.
- **Restraint Over Decoration:** Zero skeuomorphic fluff, no nostalgic 8-bit or pixelated graphics. Everything serves technical clarity, content hierarchy, and fluid execution.

## Colors

The palette is engineered exclusively for an immersive, reduced-eye-strain dark environment.

- **Primary (`#6366f1` / Indigo 500):** Used for focal calls to action, active navigation states, and primary commit/build status highlights.
- **Secondary (`#3b82f6` / Blue 500):** Complements the primary indigo for telemetry, technical tags, links, and secondary interactive states.
- **Tertiary (`#10b981` / Emerald 500):** Functional status indicator denoting clean build pipelines, operational deployments, and live project demos.
- **Neutral Palette (`#0a0f1d` to `#f8fafc`):**
  - **Canvas Base:** `#0a0f1d` (Deep Slate Void)
  - **Surface Container (Base Card):** `rgba(17, 24, 39, 0.7)` with backdrop blur
  - **Surface Container High (Hover / Popovers):** `rgba(31, 41, 61, 0.75)`
  - **Borders & Dividers:** Subtle hairlines at `#1f293d` and `#374151`
  - **Text High-Contrast:** `#f8fafc` (Slate 50)
  - **Text Muted / Secondary:** `#94a3b8` (Slate 400)
  - **Text Low-Contrast / Meta:** `#64748b` (Slate 500)

## Typography

Typography establishes an uncompromising hierarchy of functional clarity and developer credibility:

- **Primary Interface Type (`Geist`):** Delivers clean geometry, exceptional legibility at small sizes, and modern mechanical precision. Tighter letter spacing on display and headline scales reinforces a compact, modern UI rhythm.
- **Monospace Companion (`JetBrains Mono`):** Used deliberately for all technical metadata, labels, commit SHAs, stack chips, and code snippets.
- **All-Caps Labels:** Rendered exclusively in JetBrains Mono with expanded letter spacing (`0.06em` to `0.08em`) to differentiate metadata and system tags from conversational body copy.

## Layout & Spacing

The layout is built upon a responsive 12-column fluid grid system bounded by a maximum content container width of `1200px`.

### Grid Structure
- **Desktop (≥ 1024px):** 12 columns, `2rem` (32px) gutters, and `6rem` (96px) canvas side margins.
- **Tablet (768px – 1023px):** 8 columns, `1.5rem` (24px) gutters, and `3rem` (48px) canvas margins.
- **Mobile (< 768px):** 4 columns, `1rem` (16px) gutters, and `1.5rem` (24px) side margins.

### Spacing Philosophy
Internal component padding relies strictly on an 8-point base scale with 4-point micro-adjustments. Content cards and interactive containers prioritize breathing room around key code blocks and project descriptions, eliminating visual crowding while maintaining structural alignment.

## Elevation & Depth

Visual depth is achieved through layered translucency, subtle structural borders, and luminous radial glows rather than heavy drop shadows:

- **Base Canvas:** Solid `#0a0f1d` with an optional subtle ambient background radial gradient (`radial-gradient(circle at 50% 0%, rgba(99, 102, 241, 0.08), transparent 70%)`).
- **Glassmorphic Panes:** Surfaces utilize backdrop blur filters (`backdrop-filter: blur(12px)`) combined with semi-opaque fill colors (`rgba(17, 24, 39, 0.7)`).
- **Hairline Accent Borders:** Elevation is defined primarily by 1px borders using `#1f293d` for passive surfaces and `#374151` for interactive containers.
- **Luminous Edge & Glow Effects:**
  - **Resting:** `box-shadow: 0 4px 20px -2px rgba(0, 0, 0, 0.5)`.
  - **Interactive Hover:** Elements transition to an elevated highlight with a dual shadow: `box-shadow: 0 10px 30px -5px rgba(0, 0, 0, 0.8), 0 0 20px 0 rgba(99, 102, 241, 0.15)`.

## Shapes

The design uses a refined rounded geometry (`roundedness: 2` = 0.5rem / 8px default):

- **Standard Containers & Cards:** `0.5rem` (8px) corner radius, providing crisp modern structure without the harshness of zero-radius brutality.
- **Large Panels & Modals (`rounded-lg`):** `1rem` (16px) corner radius to create softer boundary transitions for primary case study showcases.
- **Hero Banners & Preview Frames (`rounded-xl`):** `1.5rem` (24px) for expansive framing.
- **Badges, Status Indicators, and Pill Chips:** Fully circular pill shapes (`9999px`) to immediately distinguish small status tokens and tech stack tags from actionable rectilinear cards.

## Components

### Buttons
- **Primary:** Filled `#6366f1` with high-contrast text (`#ffffff`), `0.5rem` radius, with a subtle top edge highlight (`inset 0 1px 0 rgba(255, 255, 255, 0.2)`). Hover triggers a diffused indigo bloom (`0 0 16px rgba(99, 102, 241, 0.4)`).
- **Secondary / Glass:** Background `rgba(31, 41, 61, 0.4)`, border `1px solid #1f293d`, text `#f8fafc`. Hover shifts background to `rgba(55, 65, 81, 0.5)` and border to `#3b82f6`.
- **Ghost:** Borderless, text `#94a3b8`, transitions to `#f8fafc` text and `rgba(255, 255, 255, 0.05)` background on hover.

### Tech Stack Chips & Tags
- Height: `24px` to `28px`.
- Shape: Pill radius (`9999px`).
- Styling: `rgba(17, 24, 39, 0.8)` background, `1px solid #1f293d`, `JetBrains Mono` label font, uppercase with muted text color `#94a3b8`.
- Hover/Active: Subtle border glow tinted with secondary blue `#3b82f6` and text brightness up to `#f8fafc`.

### Project & Architecture Cards
- Built with a frosted glass container (`rgba(17, 24, 39, 0.65)`, `backdrop-filter: blur(16px)`).
- Enclosed with a 1px border (`#1f293d`).
- On cursor hover, the card smoothly transitions border color to `#374151` and casts a soft indigo-tinted ambient glow under the cursor coordinate.

### Code Snippets & Command Bars
- Monospace-first blocks with `#070a14` deep backing, top toolbar with language badge and copy action.
- Inline code tags use `rgba(99, 102, 241, 0.1)` background with `1px solid rgba(99, 102, 241, 0.2)` and `#e0e7ff` typography.

### Input Fields & Terminal Search
- Dark inset backgrounds (`#0a0f1d`) surrounded by `1px solid #1f293d`.
- Focus state replaces default outline with a sharp 1px border in `#6366f1` alongside an outer ambient ring `0 0 0 3px rgba(99, 102, 241, 0.2)`.

### Live Deployment Status Dots
- Pulse indicator: `8px` circle with a solid `#10b981` core and an animated pinging ring (`rgba(16, 185, 129, 0.35)`) denoting live system availability or deployment status.