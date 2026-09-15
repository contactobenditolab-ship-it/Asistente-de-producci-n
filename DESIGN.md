---
name: OpticCut Precision Interface
colors:
  surface: '#0e141c'
  surface-dim: '#0e141c'
  surface-bright: '#343a42'
  surface-container-lowest: '#090f16'
  surface-container-low: '#161c24'
  surface-container: '#1a2028'
  surface-container-high: '#242a33'
  surface-container-highest: '#2f353e'
  on-surface: '#dde3ee'
  on-surface-variant: '#bac9cc'
  inverse-surface: '#dde3ee'
  inverse-on-surface: '#2b3139'
  outline: '#849396'
  outline-variant: '#3b494c'
  surface-tint: '#00daf3'
  primary: '#c3f5ff'
  on-primary: '#00363d'
  primary-container: '#00e5ff'
  on-primary-container: '#00626e'
  inverse-primary: '#006875'
  secondary: '#ffb692'
  on-secondary: '#562000'
  secondary-container: '#fd6c00'
  on-secondary-container: '#562000'
  tertiary: '#b1ffbf'
  on-tertiary: '#003918'
  tertiary-container: '#22ef7e'
  on-tertiary-container: '#006731'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#9cf0ff'
  primary-fixed-dim: '#00daf3'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f58'
  secondary-fixed: '#ffdbcb'
  secondary-fixed-dim: '#ffb692'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#7a3000'
  tertiary-fixed: '#62ff96'
  tertiary-fixed-dim: '#00e475'
  on-tertiary-fixed: '#00210b'
  on-tertiary-fixed-variant: '#005226'
  background: '#0e141c'
  on-background: '#dde3ee'
  surface-variant: '#2f353e'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0em
  title-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  metric-xl:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.03em
  metric-md:
    fontFamily: JetBrains Mono
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
  code-param:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers a high-precision digital workshop environment for high-output diode laser manufacturing and engraving. The design movement marries **Precision Engineering Minimal** with **Instrumental Tactility**: deep carbon-black architectural depths paired with coherent, luminescent laser-spectrum signatures.

The visual style communicates surgical accuracy, hardware control, and machine safety. It avoids superficial cyberpunk tropes, leaning instead toward industrial laboratory grade instrumentation, high-end avionics, and high-frequency CNC telemetry consoles. Surfaces suggest matte anodized aluminum, anti-reflective optical glass, and technical CAD workspaces.

### Target Audience & Mindset
- **Users**: Digital fabrication artists, mechanical prototyping engineers, bespoke woodworkers, and makers operating 20W class-4 diode lasers.
- **Atmosphere**: Technical clarity, absolute control, active diagnostic feedback, and zero cognitive latency under real-time machine run states.
- **Emotional Response**: Confident, deliberate, laser-accurate, and structurally reliable.

## Colors

The system relies on a calibrated luminance model built specifically for low-light shop environments and optical protection goggles (OD4+ shielding screens).

### Primary System: Optical Beam Emissive
- **Primary (`#00E5FF` / Coherent Cyan)**: Signifies target acquisition, path vectors, primary interactive control states, active toolhead coordinates, and framing boundaries.
- **Secondary (`#FF6D00` / Thermal Hazard Amber)**: Designates laser firing status, thermal head load, perimeter safety thresholds, flammable workpiece warnings, and burn/cut power levels.
- **Tertiary (`#00E676` / Diagnostic Green)**: Reserved for completed passes, successful homing sequences, air-assist flow stability, and safe-to-open interlocks.
- **Critical Alert (`#FF1744` / Immediate Stop)**: Dedicated entirely to E-stop states, tilt warnings, and flame sensor triggers.

### Neutral Layer Architecture
- **Base Canvas (`#0B0F14`)**: Void carbon slate, grounding visual weight and preventing screen flare during machine operation.
- **Surface Elevation 1 (`#121820`)**: Structural card decks, toolbar trays, and coordinate panels.
- **Surface Elevation 2 (`#1A222D`)**: Interactive components, nested parameter blocks, and active cell groupings.
- **Surface Elevation 3 (`#242F3D`)**: Hover states, popovers, and elevated telemetry monitors.
- **Structural Lines & Grid (`#2A3646`)**: 1px structural registration lines and precision coordinate grids.
- **Text & Telemetry**:
  - `Text-Primary` (`#F0F4F8`): Maximum contrast reading for active values and primary labels.
  - `Text-Secondary` (`#94A3B8`): Contextual units, static dimensioning, and structural legends.
  - `Text-Muted` (`#526071`): Disabled axes, inactive vector paths, and micro-grid indicators.

## Typography

The typography strategy leverages dual visual engines:
1. **Geometric Functionalism (`Space Grotesk`)**: Anchors visual hierarchy in titles, primary device metrics, and high-level states. Its technological geometry evokes precision drafting.
2. **Neutral Systematic (`Inter`)**: Drives continuous documentation, instruction steps, contextual notices, and body-level feedback.
3. **Hardware Monospace (`JetBrains Mono`)**: Strict, non-proportional alignment for numerical telemetry: laser speed (`mm/min`), line interval (`mm`), power density (`%` / `mW`), coordinates (`X: 340.25 Y: 120.00`), and G-code parsing. All tabular numbers feature slashed zeroes to eliminate misreads during active fabrication runs.

## Layout & Spacing

The layout utilizes an engineered, space-efficient fluid grid designed to operate without horizontal drift or visual distraction during workshop machine cycles.

### Grid Rhythm & Responsive Rules
- **Mobile Handheld (360px - 599px)**:
  - Outer margin: `1rem` (`16px`), gutter: `0.75rem` (`12px`).
  - Single-column flow prioritized for thumb-driven manual axis jogging, live speed/power overrides, and machine emergency controls.
  - Sticky bottom telemetry drawer with instant E-stop access.
- **Tablet & Tool-Stand Workstations (600px - 1023px)**:
  - 6-column fluid structure. Margin: `1.25rem` (`20px`), gutter: `1rem` (`16px`).
  - Split interface: Left 55% dedicated to interactive canvas preview and vector boundary coordinates; Right 45% houses hardware configuration, laser power curves, and layer pass controllers.
- **Desktop / Workshop Hub (1024px+)**:
  - 12-column fixed/fluid hybrid grid maxing out at `1440px`. Margin: `1.5rem` (`24px`), gutter: `1rem` (`16px`).
  - Triple-dock architecture: Navigation & diagnostic rail (left), CAD/CAM interactive vector bed (center), parameter matrix and job queue (right).

## Elevation & Depth

To maximize legibility and minimize eye strain under harsh shop lights, depth is achieved primarily through **Tonal Stacking and Crisp Boundary Definition** rather than diffuse drop shadows.

### Elevation Hierarchy
- **Level 0 (Workspace Canvas)**: Deep slate `#0B0F14` featuring an integrated 10mm technical grid pattern rendered in `#1A222D` at 50% opacity.
- **Level 1 (Structural Containers)**: `#121820` with a 1px solid border in `#2A3646`. Used for laser bed staging cards, job queue items, and material preset panels.
- **Level 2 (Interactive Modules)**: `#1A222D` with an inner 1px border in `#2A3646`. Elevates active axis step selectors, focus adjusters, and numeric input blocks.
- **Level 3 (Diagnostic Flyouts & Overlays)**: `#242F3D` with a high-contrast edge highlight (`#38485C` 1px) and a precise directional drop-shadow: `0 8px 24px -4px rgba(0, 0, 0, 0.65)`.
- **Emissive State Indicators (Active Laser States)**: When the 20W diode is actively firing or in test-fire pulse mode, components cast a tight, high-intensity neon glow: `0 0 12px rgba(255, 109, 0, 0.45)`. Safe framing bounds project a cyan wash: `0 0 10px rgba(0, 229, 255, 0.3)`.

## Shapes

The design system employs **Soft Industrial Corner Radii (`roundedness: 1`)**. 

- Standard interactive controls, parameter fields, and data cells use `0.25rem` (`4px`) corner radii, preserving a tight, CNC-machined, metallic feel.
- Outer container frames, preview viewports, and modal boundary enclosures use `0.5rem` (`8px`).
- Badges, status chips, and toggle track hulls maintain a minimal `0.25rem` (`4px`) bevel or corner rounding rather than full pills, reinforcing the look of hardline equipment instrumentation.
- No organic, high-radius bubble forms are permitted; all geometries align to a consistent 4px structural baseline.

## Components

### Buttons
- **Primary Action (Vector Trace, Frame, Connect)**: Solid `#00E5FF` fill, high-contrast `#0B0F14` bold text, `0.25rem` radius. Hover triggers an emissive cyan border glow and slight brightness lift.
- **Hazard Action (Test Fire, Laser Run)**: Deep carbon background with a vibrant 2px `#FF6D00` border, `#FF6D00` text, and a striped diagonal safety indicator on hover.
- **Emergency Stop (E-Stop)**: Fixed, high-visibility solid `#FF1744` with `#FFFFFF` bold sans typography. Full width on mobile footer with tactile pressed depth (`inset 0 3px 0 rgba(0,0,0,0.4)`).
- **Secondary / Ghost**: Outline `#2A3646`, text `#F0F4F8`, background `#121820`. Active state illuminates border to `#00E5FF`.

### Input Fields & Numeric Steppers
- Matte background (`#121820`), 1px structural stroke (`#2A3646`).
- Integrated parameter units (`mm/min`, `mW`, `%`, `DPI`, `passes`) displayed in fixed JetBrains Mono text in `#94A3B8` on the trailing edge.
- Focus state switches the border to `#00E5FF` with zero diffuse spread to keep adjacent telemetry crisp.
- Dual-axis nudgers feature split touch targets with micro tactile chevrons (`+ / -`) for fine manual calibration under gloved usage.

### Segmented Controls & Machine Mode Selectors
- Low-profile enclosure (`#0B0F14`), housing inline switches: `Cut (Vector)` | `Engrave (Raster)` | `Score`.
- Active segment utilizes `#1A222D` with an illuminated 2px cyan bottom baseline and clean `#F0F4F8` typography.

### Tactile Parameter Meters & Power Gauges
- Horizontal segmented bars composed of 20 distinct blocks (representing 5% wattage increments each).
- Color transition logic:
  - 1% to 70% power: Coherent Cyan segments (`#00E5FF`).
  - 71% to 90% power: Laser Amber segments (`#FF6D00`).
  - 91% to 100% power: Overdrive Warning red-orange segments (`#FF3D00`) accompanied by focal lens life warning flags.

### Data Badges & Status Chips
- Height: `22px`, font: `JetBrains Mono 11px`, letter-spacing `0.06em`, uppercase.
- Structural border with 15% opacity background fills:
  - `CONNECTED`: Green border `#00E676`, green text, with a pulsing 6px radial dot.
  - `FRAMING`: Cyan border `#00E5FF`, cyan text.
  - `EMISSION ACTIVE`: Amber border `#FF6D00`, amber text, solid backplate `#FF6D00` at 20% alpha.

### Cards & Telemetry Containers
- Flat matte surface (`#121820`) encased in `#2A3646` single-pixel rules.
- Header bands feature micro-subtitles, machine coordinate readouts (`X/Y/Z`), and CAD registration crosshairs in top-right corners.