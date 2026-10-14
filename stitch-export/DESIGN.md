---
name: Sapphire Minimal Portfolio
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#0051b1'
  on-tertiary: '#ffffff'
  tertiary-container: '#0f69dc'
  on-tertiary-container: '#edf0ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.025em
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a high-precision, polished, and contemporary aesthetic tailored for senior creative technologists, engineers, and digital designers. The style is anchored in modern minimalism with an architectural sensibility: crisp structural boundaries, generous negative space, purposeful optical hierarchy, and delicate depth.

The interface projects authority, deliberate restraint, and digital mastery. It balances clinical clarity with human warmth through subtle cobalt transitions, balanced border radiuses, and crisp hairline framing.

## Colors

The palette is engineered around pure whites, deep mineral slate, and electric sapphire blue:

- **Primary (`#2563EB`)**: Anchor for primary calls to action, focus rings, interactive states, and hero emphasis.
- **Secondary / Headings (`#0F172A`)**: Deep slate for high-contrast titles, primary text blocks, and structured visual weight.
- **Tertiary (`#3B82F6`)**: Bright sapphire for interactive hover states, active pill chips, and directional icons.
- **Neutral (`#64748B`)**: Slate gray for body copy, meta timestamps, and secondary captions.
- **Backgrounds**: Pure canvas white (`#FFFFFF`) layered over subtle cool-slate backing (`#F8FAFC`). Soft blue highlights (`#EFF6FF`) provide tinting for active card highlights, badges, and inline callouts.
- **Borders & Dividers**: Crisp hairlines (`#E2E8F0`) provide layout structure without visual clutter.

## Typography

The type scale relies entirely on Inter for its neo-grotesque clarity, optical legibility, and tight tracking characteristics at large weights. 

- Large titles feature optical negative letter spacing (`-0.02em` to `-0.03em`) to deliver modern, compact editorial punch.
- Body text remains grounded with neutral kerning and open line heights (1.5x–1.6x) for effortless long-form reading across career histories and case studies.
- Badges and technical metadata utilize medium-to-semibold weights with slight positive tracking to ensure legibility when rendered in all-caps or small pill badges.

## Layout & Spacing

This design system uses a responsive fluid grid paired with constrained maximum reading widths:

- **Desktop (≥ 1024px)**: 12-column grid system capped at a maximum width of `1200px` for general sections, and `760px` for single-column long-form editorial views. Outer margins are `3rem` (`48px`) with `1.5rem` (`24px`) gutters.
- **Tablet (768px – 1023px)**: 8-column layout with `2rem` margins and `1.25rem` gutters.
- **Mobile (< 768px)**: 4-column layout with `1.25rem` (`20px`) margins and `1rem` (`16px`) gutters.

Component internals adhere strictly to an 8px rhythmic baseline (`0.25rem` through `2.5rem`), ensuring uniform vertical pacing across bio headers, timeline blocks, and project showcases.

## Elevation & Depth

Depth is established primarily through low-contrast hairline outlines and diffused ambient lighting, avoiding dense or muddy drop shadows:

- **Flat / Base Layer**: `#FFFFFF` cards resting on `#F8FAFC` backgrounds framed by 1px solid `#E2E8F0` outlines.
- **Hover / Active Cards**: Subtle multi-stage elevation using slate-tinted shadow (`0 10px 25px -5px rgba(15, 23, 42, 0.05), 0 8px 10px -6px rgba(15, 23, 42, 0.02)`) accompanied by a subtle outline shift to `#CBD5E1`.
- **Floating Overlays (Navbars / Tooltips / Modals)**: Subtle translucent glass surfaces using `backdrop-filter: blur(12px)` on `rgba(255, 255, 255, 0.85)` bordered with `rgba(226, 232, 240, 0.8)`.

## Shapes

The geometric framework is categorized as **Level 2 (Rounded)**:

- Standard controls, inputs, and interactive badges utilize `0.5rem` (`8px`) border radii.
- Project cards, section modules, and modal containers use `1rem` (`16px`) corner radiuses (`rounded-lg`).
- Feature cards and portrait containers step up to `1.5rem` (`24px`) (`rounded-xl`).
- Micro status indicators and tag badges may leverage fully round pill contours (`9999px`) to distinguish categorical metadata from structural content cards.

## Components

### Buttons
- **Primary**: Solid `#2563EB` fill, white `#FFFFFF` text, `0.5rem` radius, `0.625rem 1.25rem` padding. Subtle brightness increase and transition upward (`translate-y: -1px`) on hover.
- **Secondary / Outline**: `#FFFFFF` background, `#0F172A` text, 1px border in `#E2E8F0`. On hover, background shifts to `#F8FAFC` and border transitions to `#CBD5E1`.
- **Ghost**: Transparent background, `#64748B` text, shifting to `#EFF6FF` background with `#2563EB` text on hover.

### Tag Badges & Chips
- **Tech Stack Badges**: Height `26px`, `0.375rem` or full pill radius. Background `#EFF6FF`, border 1px solid `#DBEAFE`, text `#1D4ED8`, weight `500`, font size `12px`.
- **Neutral Tags**: Background `#F1F5F9`, border 1px solid `#E2E8F0`, text `#475569`.

### Cards & Case Studies
- Structural container with `#FFFFFF` background, 1px `#E2E8F0` border, `1rem` (`16px`) radius, and `1.5rem` inner padding.
- Interactive states shift border to `#93C5FD` with soft ambient slate shadow and smooth 200ms ease transitions.

### Experience Timeline Lists
- Unordered list connected by a continuous 1px `#E2E8F0` hairline vertical rule.
- List nodes use a solid `#2563EB` 8px circle with a 4px `#EFF6FF` concentric outer ring.
- Metadata and dates are set in `label-sm` (`#64748B`).

### Form Inputs
- Background `#FFFFFF`, 1px solid `#CBD5E1`, `0.5rem` radius, `0.625rem 0.875rem` padding.
- Focus state: Outline eliminated, border color shifted to `#2563EB`, paired with a 3px outer ring in `rgba(37, 99, 235, 0.15)`.

### Project Metrics / Key Stat Blocks
- Monospace or high-impact numeral treatment (`headline-lg` in `#0F172A`), sub-captioned by `label-sm` in `#64748B`.
- Integrated directly inside a subtle tinted container (`#F8FAFC`) with hairline dividers.