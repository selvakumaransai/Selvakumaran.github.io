---
name: Geospatial & Autonomous Aerial Systems Portfolio
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
  on-surface-variant: '#bcc9cd'
  inverse-surface: '#dee2f6'
  inverse-on-surface: '#2b303f'
  outline: '#869397'
  outline-variant: '#3d494c'
  surface-tint: '#4cd7f6'
  primary: '#4cd7f6'
  on-primary: '#003640'
  primary-container: '#06b6d4'
  on-primary-container: '#00424f'
  inverse-primary: '#00687a'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#adc6ff'
  on-tertiary: '#002e6a'
  tertiary-container: '#78a5ff'
  on-tertiary-container: '#00397f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acedff'
  primary-fixed-dim: '#4cd7f6'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#0e1321'
  on-background: '#dee2f6'
  surface-variant: '#303444'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  telemetry-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.04em
  telemetry-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 3rem
  margin-mobile: 1rem
  margin-tablet: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an elite, technical, and mission-critical visual presence for a senior Geospatial Engineer and UAV Intelligence specialist. Rooted in tactical avionics, high-precision remote sensing, and GIS cartography, the interface delivers operational clarity, precision, and restrained futurism.

The aesthetic fuses **Precision Technical Glassmorphism** with **Cartographic Data Grid Architecture**. Visual cues are borrowed from LiDAR point clouds, multispectral telemetry displays, and vector coordinate systems. Every visual element conveys engineered intentionality, avoiding gratuitous sci-fi tropes in favor of an authentic defense-grade, aerospace-grade instrumentation feel. Surfaces stay grounded in abyssal slates and deep obsidians, punctured by calibrated laser pulses of cyan and emerald telemetry indicators.

## Colors

The palette is engineered around dark-mode operational environments, calibrated to minimize eye strain while maintaining hyper-focused contrast for critical geospatial metrics.

- **Primary Accent (`#06B6D4` / Electric Cyan):** Represents sensor scans, active radar/sonar sweeps, vector telemetry, and primary call-to-actions.
- **Secondary Accent (`#10B981` / Emerald Beacon):** Signals verified coordinates, operational health, nominal flight status, and vegetation/NDVI classification overlays.
- **Tertiary Accent (`#3B82F6` / Avionics Azure):** Designates secondary navigation tracks, spatial boundaries, and analytical metadata.
- **Base Surfaces & Neutral (`#0A0F1D` / Void Obsidian):** The foundational substrate. Elevated tiers transition through `#111827` (Charcoal Slate) to `#1E293B` (Field Slate) for raised instrument panels and telemetry containers.
- **Supportive Alert Spectrum:** `#F59E0B` for pre-flight warnings and satellite acquisition holds; `#EF4444` for restricted airspace boundaries and critical diagnostic anomalies.
- **Grid & Contour Stroke (`rgba(148, 163, 184, 0.08)`):** Subtle topographic and graticule reference guides across the deep canvas.

## Typography

The typographic hierarchy distinguishes narrative presentation from structural data readouts.

- **Plus Jakarta Sans (Headlines):** High-clarity geometric letterforms provide human warmth without sacrificing technical sharpness. Negative tracking is applied to large sizes for a calibrated editorial presence.
- **Inter (Body):** Exceptional legibility in micro-textures, documentation notes, and narrative project breakdowns across high-density viewports.
- **JetBrains Mono (Telemetry, Coordinates, & Spec Sheets):** Dedicated strictly to UTM/WGS84 lat-long coordinates, flight altitudes, Ground Sampling Distance (GSD) ratios, sensor configurations, and status indicators. All uppercase data labels leverage wide letter spacing (`letterSpacing: 0.12em`) to mirror aerospace heads-up displays (HUD).

## Layout & Spacing

The layout is grounded in a **12-column rigid fluid grid system**, flanked by cartographic margin indices (e.g., crosshairs and coordinate indicators at outer boundaries).

- **Grid Architecture:** 12 columns on desktop (max width 1440px), 8 columns on tablet (breakpoint 768px - 1024px), and 4 columns on mobile (< 768px).
- **Cartographic Margin Layering:** Section containers feature structural hairline perimeter bounds with coordinate tick marks at intersections.
- **Rhythm & Gaps:** Spacing values use a strict 4px/8px incremental cadence. Micro panels (telemetry chips, coordinate badges) utilize `space-xs` and `space-sm`, while analytical card layouts employ `space-lg` to prevent visual collision between dense geospatial layers.

## Elevation & Depth

Visual hierarchy does not rely on heavy drop shadows; it is constructed through **luminous surface layering, low-contrast ghost borders, and selective photonic luminescence**.

- **Level 0 (Base Canvas):** Solid `#0A0F1D`. May feature a faint SVG vector topographic contour grid pattern or orthomosaic graticule at 4% opacity.
- **Level 1 (Structural Cards & Panels):** `#111827` blended with 70% opacity and `backdrop-filter: blur(12px)`. Enclosed by a hairline 1px border of `rgba(255, 255, 255, 0.08)`.
- **Level 2 (Active Telemetry & Floating Controls):** `#1E293B` blended at 85% opacity with `backdrop-filter: blur(16px)`. Border is accented with `rgba(6, 182, 212, 0.25)`.
- **Photonic Glows (Emissive States):** Critical telemetry nodes, hover triggers, and active flight path indicators emit soft, diffused colored glows: `box-shadow: 0 0 20px -4px rgba(6, 182, 212, 0.35)` or `0 0 16px -2px rgba(16, 185, 129, 0.4)`. Shadows stay constrained to accent colors, never muddy blacks.

## Shapes

The interface embraces a **disciplined, semi-angular industrial geometry** (`roundedness: 1`).

- **Base Radius (0.25rem / 4px):** Applied to telemetry badges, buttons, data inputs, and code/spec chips to retain a military-avionics instrument panel aesthetic.
- **Large Radius (`rounded-lg`, 0.5rem / 8px):** Applied to primary project showcase cards, viewport containers, and modal dialogs.
- **Chamfered / Technical Accent Motif:** Specialized UI highlights (like mission-status pills or map tool overlays) can employ micro 45-degree corner clips (using `clip-path` or border-corner accents) to evoke tactical optics and HUD targeting brackets.

## Components

### Buttons & Interactive Triggers
- **Primary Telemetry Button:** Solid Electric Cyan fill (`#06B6D4`) with `#0A0F1D` text (JetBrains Mono, bold), 4px border radius. On hover: shifts background to `#10B981` with a localized cyan glow (`box-shadow: 0 0 24px rgba(6, 182, 212, 0.45)`).
- **Secondary Ghost Action:** Transparent background with a 1px border of `rgba(6, 182, 212, 0.4)`, text in `#E2E8F0`. Hover state triggers background fill of `rgba(6, 182, 212, 0.08)` and border shifts to solid cyan.
- **HUD Reticle Action:** Square or 1:1 icon buttons bound by crosshair ticks on hover.

### Status Badges & Telemetry Chips
- Compact, monospaced pill elements using `label-caps`.
- Composed of a translucent background (`rgba(16, 185, 129, 0.1)` for nominal/online; `rgba(6, 182, 212, 0.1)` for tracking), matched with an animated pulsing LED dot (4px circle with a subtle CSS ping/ripple animation).

### Cards (Project, Mission, & Sensor Architecture)
- Frosted glass substrate with 1px border of `rgba(255, 255, 255, 0.07)`.
- Top header row reserves space for a monospaced mission/project index code (e.g., `MISSION // 04-LIDAR`) and coordinate metadata.
- Interactive states raise the border opacity to `rgba(6, 182, 212, 0.5)` with an ambient edge wash.

### Form Inputs & Coordinate Queries
- Background `#0A0F1D` inset with a 1px border of `#1E293B`.
- Typography is strictly `JetBrains Mono` (`telemetry-lg`).
- Focus state creates an electric cyan border with zero outer ring, paired with a small upper-right targeting corner mark.

### Domain-Specific Components
- **Orthomosaic Before/After Slider:** Dual-layered split viewport with high-precision drag bar capped by crosshair needles.
- **LiDAR Point Cloud Density Metric:** Segmented multi-step gauge bars featuring glowing neon green and cyan increments.
- **Flight Path Waypoint Log:** Vertical list linked via a continuous 1px dashed cyan track line with numbered node vertices.