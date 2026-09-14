---
name: Curiosity in Motion
colors:
  surface: '#10131c'
  surface-dim: '#10131c'
  surface-bright: '#363943'
  surface-container-lowest: '#0b0e16'
  surface-container-low: '#191b24'
  surface-container: '#1d1f28'
  surface-container-high: '#272a33'
  surface-container-highest: '#32343e'
  on-surface: '#e1e2ee'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#e1e2ee'
  inverse-on-surface: '#2e303a'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#ffc174'
  on-tertiary: '#472a00'
  tertiary-container: '#f59e0b'
  on-tertiary-container: '#613b00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#10131c'
  on-background: '#e1e2ee'
  surface-variant: '#32343e'
typography:
  display-xl:
    fontFamily: Sora
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Sora
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Sora
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Sora
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-xl:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.005em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 2rem
  margin: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system is engineered around the creative thesis **"Curiosity in Motion"**—a visual metaphor bridging the nascent curiosity of a first-year Computer Science & Engineering (AI & ML) scholar with the infinite frontier of intelligence systems. 

### Visual Philosophy & Movements
The visual identity fuses **Cinematic Sci-Fi Glassmorphism** with **Atmospheric Layered Depth**. Rather than cold or dystopian computing tropes, the aesthetic is luminous, deeply dimensional, and inherently inviting.
- **Deep Space Substrates**: Infinite, low-luminosity ink-blacks evoke deep computational space.
- **Neural Radiance**: Chromatic gradients of electric cyan, radiant violet, and soft starlight amber simulate synapses firing in an artificial neural substrate.
- **Refined Translucency**: Meticulously graded frosted glass layers establish physical presence without obscuring ambient celestial glows beneath.

### Emotional Demeanor
- **Intellectually Curious & Forward-Looking**: Confident, forward-thinking visual cadence emphasizing momentum, active exploration, and research agility.
- **Warm, Humble & Accessible**: Luminous gold/amber starlight accents soften the tech-heavy palette, ensuring the portfolio feels personal, grounded, and human.
- **Precision Engineering**: Razor-sharp layout boundaries, micro-borders, and high-legibility typographic scale reflect disciplined code craftsmanship.

## Colors

The system uses an intentional, high-contrast dark space model where dark values absorb visual weight, allowing vibrant spectral accents to direct cognitive focus.

### Core Canvas & Neutral Palette
- **Base Canvas (`#05070F`)**: Deepest void black with faint blue-violet undertones, eliminating absolute dead black `#000000` in favor of atmospheric depth.
- **Surface Layer 1 (`#080D1A`)**: Slightly elevated space slate for major structural groupings, sections, and backdrop fields.
- **Glass Panel Surface (`rgba(13, 20, 36, 0.55)`)**: The standard canvas for interactive cards and floating containers.
- **Border Subtle (`rgba(255, 255, 255, 0.08)`)**: Low-luminosity structural perimeter.
- **Border Luminous (`rgba(56, 189, 248, 0.25)`)**: Active or interactive card edges reacting to hover states.

### Primary Accents: Cognitive Blue & Cyan
- **Primary Bright (`#38BDF8`)**: Primary focal point for interactive components, cursor trails, key metrics, and emphasized headers.
- **Primary Deep (`#0066FF`)**: Base gradient weight and foundational electric backlight.
- **Cyan Signal (`#06B6D4`)**: Used for code accents, live status badges, and telemetry markers.

### Secondary Accents: Synthetic Violet
- **Electric Violet (`#8B5CF6`) & Radiant Magenta (`#A855F7`)**: Represent neural network logic, research explorations, and algorithmic workflows. Commonly layered underneath primary blue to produce radiant, dual-tone chromatic falloffs.

### Tertiary Accent: Starlight Gold
- **Amber Starlight (`#F59E0B`) & Soft Gold (`#FDE68A`)**: Human warmth indicators, signifying pivotal milestones, personal reflections, awards, and intellectual epiphanies.

### Typography & Content Contrast
- **Text Highest (`#FFFFFF`)**: Pure high-impact white for display headlines and active states.
- **Text Moderate (`#94A3B8`)**: Cool slate for long-form narrative body and secondary metadata.
- **Text Muted (`#475569`)**: Structural annotations, code linenumbers, and subtle timestamps.

## Typography

The typographic hierarchy balances expressive geometric modernism with developer-grade precision.

### Type Roles
- **Display & Headlines (`Sora`)**: Distinctive geometric apertures and wide structure impart an architectural, visionary presence to titles, student identity headers, and marquee claims.
- **Body (`Space Grotesk`)**: Provides an engineered, tech-informed reading cadence that maintains clarity and open counters without feeling mechanical.
- **Labels, Telemetry & Code (`JetBrains Mono`)**: Provides strict monospace precision for neural layer readouts, project metadata tags, statistics, and academic credentials.

### Typographic Discipline
- Restrict uppercase transformations solely to `label-sm` and `label-md` roles to preserve natural readability.
- Maintain high line-height ratios across `body-xl` and `body-lg` to create breathing room over dark, textured backdrops.
- Highlight key research terms or project titles using selective gradient text masks spanning `#38BDF8` through `#A855F7`.

## Layout & Spacing

Designed specifically as an ultra-immersive, cinematic **Desktop-Only experience**, the layout maximizes horizontal scale, cinematic aspect ratios, and architectural canvas positioning.

### Layout Philosophy
- **Immersive 12-Column Grid**: A fixed-width container capped at `1440px` centered within ultra-wide displays, flanked by generous `4rem` (`margin`) gutters.
- **Horizontal & Layered Narratives**: Content flows with generous vertical spacing, balancing high-density technical modules (e.g., skill nodes, model parameters) with wide editorial pauses.
- **Structural Rhythm**: Components rely on predictable 8px-derived steps. Dense technical widgets utilize `space-sm` and `space-md`, while major narrative card interiors utilize `space-xl`.
- **Z-Index Layering**:
  - `z-0`: Deep space background with moving constellation grid and nebulous blur nodes.
  - `z-10`: Structural glass containers and project showcase cards.
  - `z-20`: Floating telemetry nodes, interactive tooltips, and hovering glow indicators.
  - `z-50`: Fixed navigation HUD, live academic status bar, and modal overlays.

## Elevation & Depth

Elevation is achieved through optical luminescence and physical refraction rather than opaque shadow stacking.

### Depth Hierarchy
1. **The Deep Void (Base Layer)**: Solid `#05070F` punctuated by multi-layered radial blur gradients (`radial-gradient(circle at x y, rgba(56, 189, 248, 0.12), transparent 60%)`).
2. **Backdrop Glass (Low Elevation)**:
   - Background: `rgba(8, 13, 26, 0.65)`
   - Backdrop Filter: `blur(16px) saturate(160%)`
   - Border: `1px solid rgba(255, 255, 255, 0.06)`
   - Used for structural panels, large section frames, and timeline backplates.
3. **Interactive Prism (Mid Elevation / Active Cards)**:
   - Background: `rgba(13, 20, 36, 0.75)`
   - Backdrop Filter: `blur(24px) saturate(180%)`
   - Border: `1px solid rgba(56, 189, 248, 0.2)`
   - Shadow: `0 8px 32px 0 rgba(0, 0, 0, 0.37), 0 0 16px -2px rgba(56, 189, 248, 0.15)`
   - Used for featured AI/ML project cards and academic milestone cards.
4. **Neural Emissive (High Elevation / Interactive Hover)**:
   - Edge Glow: `0 0 24px 2px rgba(139, 92, 246, 0.35), inset 0 0 12px 0 rgba(56, 189, 248, 0.2)`
   - Applied dynamically to focused inputs, selected nodes, and active preview modules.

## Shapes

The geometric framework uses a **Rounded (Level 2)** posture, avoiding the severity of hard brutalist edges while maintaining architectural clarity that avoids overly casual pill or bubble forms.

### Geometric Conventions
- **Standard Cards & Modal Units**: `rounded-lg` (16px / `1rem`) creates a clean frame for glass surfaces without cutting into corner content.
- **Interactive Buttons, Chips & Metric Badges**: `rounded` (8px / `0.5rem`) reinforces structured, physical device inputs.
- **Neural Nodes & Star Indicators**: Strict circles (`rounded-full`) used strictly for dynamic data points, avatar vignettes, and pulse rings.
- **Hairline Precision**: Card perimeters and dividers are bound strictly to `1px` stroke widths to preserve a crisp technological feel.

## Components

### Buttons
- **Primary Kinetic Glow Button**:
  - Background: Linear gradient from `#0066FF` to `#38BDF8`.
  - Content: Sora 14px bold, text color `#FFFFFF`.
  - Border: None; wrapped in a soft outer glow `box-shadow: 0 0 20px rgba(56, 189, 248, 0.4)`.
  - Hover: Elevation expansion with a subtle shift toward `#8B5CF6`.
- **Secondary Ghost Glass Button**:
  - Background: `rgba(255, 255, 255, 0.04)`.
  - Border: `1px solid rgba(255, 255, 255, 0.15)`.
  - Content: `#FFFFFF` with hover color switching to `#38BDF8` and border illuminating to match.

### Chips & Neural Badges
- **Algorithm / Skill Badges**:
  - Typography: `label-sm` (`JetBrains Mono`).
  - Container: `rgba(56, 189, 248, 0.08)` fill, `1px solid rgba(56, 189, 248, 0.25)` stroke.
  - Prefix: Dynamic micro-dot (4px circle) glowing either Cyan (In Progress) or Violet (Mastered).

### Cards & Project Showcases
- **Glassmorphic Project Chassis**:
  - Layering: Multi-tiered composition with a frosted surface, hairline boundary, and a faint inner gradient sheen originating from the top edge.
  - Hover Dynamics: Cards subtly tilt along cursor coordinate vectors (perspective 3D) while intensifying the internal background nebula glow from 10% to 25% opacity.

### Neural Node Network (Specialty Component)
- Interactive constellation map presenting B.Tech coursework, AI/ML domains (e.g., Computer Vision, NLP, Deep Learning), and university achievements.
- Interconnected with fine `1px` lines at `rgba(255, 255, 255, 0.1)` that illuminate sequentially when node clusters are engaged.

### Input Fields & Terminal Contact Box
- **Interactive Console Inputs**:
  - Surface: `rgba(5, 7, 15, 0.8)`.
  - Border: `1px solid rgba(255, 255, 255, 0.12)`.
  - Typography: `body-md` in `Space Grotesk` with prompt indicator (`>`) styled in `JetBrains Mono` glowing `#38BDF8`.
  - Focus State: Border transitions to `#8B5CF6` with an inner radial shadow blooming across the field base.

### Status Indicator (Academic Presence)
- **Live Beacon**:
  - Monospace pill reading: `YEAR 01 // CSE (AI & ML) @ JECRC`.
  - Accompanied by a pulsing `#F59E0B` starlight beacon indicating active open collaboration.