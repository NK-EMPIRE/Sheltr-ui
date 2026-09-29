---
name: Warm Frosted Glass
colors:
  surface: '#fbf8fe'
  surface-dim: '#dcd9de'
  surface-bright: '#fbf8fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f2f8'
  surface-container: '#f0edf2'
  surface-container-high: '#eae7ed'
  surface-container-highest: '#e4e1e7'
  on-surface: '#1b1b1f'
  on-surface-variant: '#57423e'
  inverse-surface: '#303034'
  inverse-on-surface: '#f3f0f5'
  outline: '#8a716d'
  outline-variant: '#dec0ba'
  surface-tint: '#a33d2b'
  primary: '#a33d2b'
  on-primary: '#ffffff'
  primary-container: '#f07660'
  on-primary-container: '#661005'
  inverse-primary: '#ffb4a6'
  secondary: '#276864'
  on-secondary: '#ffffff'
  secondary-container: '#acece6'
  on-secondary-container: '#2c6c68'
  tertiary: '#006c49'
  on-tertiary: '#ffffff'
  tertiary-container: '#00b07a'
  on-tertiary-container: '#003b26'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a6'
  on-primary-fixed: '#3f0300'
  on-primary-fixed-variant: '#832617'
  secondary-fixed: '#afeee9'
  secondary-fixed-dim: '#93d2cd'
  on-secondary-fixed: '#00201e'
  on-secondary-fixed-variant: '#01504c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#fbf8fe'
  on-background: '#1b1b1f'
  surface-variant: '#e4e1e7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system establishes an architectural, luminous rental marketplace experience tailored for urban tenants and independent property owners. Rooted in hyper-minimalist frosted glassmorphism, it evokes calm, transparency, and serene domesticity. The interface retreats into the background, prioritizing high-resolution interior photography while using translucent materials, warm porcelain canvases, and tactile micro-interactions to build trust.

### Visual Aesthetic & Philosophy
- **Porcelain Canvas:** Avoids sterile clinical whites and harsh dark interfaces; relies on soft, architectural warmth.
- **Atmospheric Transparency:** Structural panels, floating action docks, and sticky navigation headers float using optical frosted-glass layers, reflecting environmental imagery underneath.
- **Intentional Contrast:** Delicate crystalline glass elements are anchored by deep charcoal typography and saturated coral interactive anchors, ensuring zero degradation in outdoor daylight legibility.

## Colors
The palette balances warm organic undertones with high-precision accents to deliver visual clarity across rental listings and application workflows.

### Color Roles & Semantics
- **Canvas Base (`#FAF7F4`):** The foundational substrate across all screens. Warm off-white / porcelain that absorbs ambient reflections beneath glass overlays.
- **Primary Brand Coral (`#F07660`):** Used exclusively for high-intent primary actions (instant booking, application submission, active filter badges, primary CTAs).
- **Secondary Muted Teal (`#2E6E6A`):** Balances warm coral with grounded stability; applied to secondary actions, map pins, transit tags, and neighborhood insight chips.
- **Tertiary Emerald (`#10B981` / `#059669`):** Dedicated status color reserved strictly for trust and verification (verified landlords, screened tenants, instant background approvals).
- **Text & Neutral Hierarchy:**
  - **Charcoal Primary (`#1A1A1E`):** High-contrast headline and body text, exceeding WCAG AAA standards against both the canvas and frosted glass.
  - **Secondary Neutral (`#6B6966`):** Supporting metadata, property addresses, and structural icons.
  - **Tertiary Neutral (`#9E9B97`):** Input placeholders, subtle dividers, and unselected tab states.
- **Glass Specular Fills:**
  - **Surface Fill:** `rgba(255, 255, 255, 0.76)` for resting cards and modals; `rgba(255, 255, 255, 0.88)` for elevated active states.
  - **Hairline Perimeter Border:** `1.2px solid rgba(255, 255, 255, 0.85)` producing an illuminated top-edge refraction.

## Typography
Plus Jakarta Sans provides crisp geometric architecture tempered by subtle rounded terminals, complementing the glass-like interface while preserving legibility over dynamic, translucent layers.

### Typography Rules
- **Numerical Stems:** All pricing values must use tabular numerals (`tnum`) in `headline-md` or `headline-lg` with tight tracking (`-0.02em`).
- **Hierarchy Separation:** Pair `display-lg` and `headline-lg` strictly with `body-md` in secondary text `#6B6966` to maintain airiness without heavy graphic dividing lines.
- **All-Caps Restraint:** Capital letters are reserved only for `label-sm` status chips (e.g., "VERIFIED", "APPLICATION PENDING") with deliberate letter spacing (`0.04em`).

## Layout & Spacing
A fluid column system adapts to mobile and tablet screen widths with strict adherence to a 48dp minimum touch target bounding box across all interactive points.

### Layout Mechanics
- **Mobile Grid (under 600px):** Single-column layout with `1.25rem` (20px) outer edge margins and an inner gutter of `0.75rem` (12px).
- **Tablet Grid (600px - 1024px):** 6-column fluid structure with `1.5rem` (24px) outer margins and `1rem` (16px) gutters. Property listings adapt to a 2-up grid.
- **Safe Area Insets:** Fixed bottom glass utility bars must append native system home indicator offsets (`env(safe-area-inset-bottom)`) directly to `space-md` inner padding.
- **Rhythm & Breathing Room:** Vertical rhythm scales in steps of 8px. Maintain `space-lg` (24px) between distinct contextual cards, and `space-sm` (8px) within card internal element groupings.

## Elevation & Depth
Elevation is generated through material translucency, backdrop diffusion, and ambient tinted light scattering rather than standard opaque dropshadows.

### Material Layering Hierarchy
1. **Canvas Layer (Base 0):** Solid `#FAF7F4`.
2. **Glass Base Cards (Elevation 1):**
   - Background: `rgba(255, 255, 255, 0.76)`
   - Backdrop Filter: `blur(18px) saturate(160%)`
   - Perimeter Hairline: `1.2px solid rgba(255, 255, 255, 0.85)`
   - Ambient Drop Shadow: `0 8px 20px -4px rgba(0, 0, 0, 0.04)`
3. **Floating Floating Action Bars / Docks (Elevation 2):**
   - Background: `rgba(255, 255, 255, 0.86)`
   - Backdrop Filter: `blur(24px) saturate(180%)`
   - Perimeter Hairline: `1.2px solid rgba(255, 255, 255, 0.95)`
   - Coral Ambient Scattering: `0 10px 30px -5px rgba(240, 118, 96, 0.08), 0 8px 20px -4px rgba(0, 0, 0, 0.04)`
4. **Modals & Drawers (Elevation 3):**
   - Background: `rgba(255, 255, 255, 0.92)`
   - Backdrop Scrim: `rgba(26, 26, 30, 0.25)` with `blur(8px)`
   - Ambient Drop Shadow: `0 24px 48px -12px rgba(26, 26, 30, 0.12)`

## Shapes
The shape system uses refined architectural curvature, transitioning from structural radii down to pill-shaped interactive components.

### Curvature Tokens & Specs
- **Large Contextual Cards & Property Tiles:** Standardized to `20px` radius (scaling up to `24px` on expanded tablet views) with nested media clipped via `overflow: hidden`.
- **Modals, Sheets, and Drawer Headers:** Top-edge radii locked at `28px`.
- **Inputs & Text Fields:** Built with a uniform `14px` radius.
- **Buttons, Floating Pills, and Badges:** Fully rounded (`9999px` pill architecture) to visually contrast against the rectangular structural cards.

## Components

### Buttons
- **Primary Action (Brand Coral):** Background `#F07660`, solid pure white text (`#FFFFFF`), pill-shaped (`9999px`). Minimum height 48px (48dp safe target). Subtle inner highlight border: `1px solid rgba(255, 255, 255, 0.2)` along the top hemisphere. Active pressed state scales down to `0.98`.
- **Secondary Glass Action:** Translucent fill `rgba(255, 255, 255, 0.8)` with hairline `1.2px solid rgba(255, 255, 255, 0.9)`. Text color `#1A1A1E`.
- **Tertiary Accent (Muted Teal):** Transparent background with `#2E6E6A` label and focus ring for secondary flows.

### Input Fields
- **Container:** Height 52px, corner radius `14px`, surface fill `rgba(255, 255, 255, 0.65)` with backdrop-blur `12px`.
- **Border:** `1.2px solid rgba(255, 255, 255, 0.8)`. On focus, border transitions to `1.5px solid #F07660` with a subtle halo `0 0 0 3px rgba(240, 118, 96, 0.15)`.
- **Typography:** Value input in `#1A1A1E` (`body-md`), placeholder in `#9E9B97`.

### Cards & Property Tiles
- **Structure:** Frosted glass backing `rgba(255, 255, 255, 0.76)`, 18px backdrop-blur, corner radius `20px`, padded with `16px`.
- **Media Inset:** Featured property image fills top edge with a `16px` inner corner radius, maintaining a `16:10` aspect ratio.
- **Metadata Layout:** Flex column gap of `6px` separating listing price (bold, `#1A1A1E`), physical address (`#6B6966`), and amenity icons.

### Chips & Filter Tags
- **Default State:** Pill shape, height 36px, `rgba(255, 255, 255, 0.7)` fill, `1.2px` hairline border, `#1A1A1E` text.
- **Active State:** Background shifts to `#2E6E6A` with crisp white text, or `#F07660` when actively indicating applied pricing bounds.

### Verification Badges
- **Visuals:** Emerald `#10B981` background tint at `12%` opacity (`rgba(16, 185, 129, 0.12)`), solid `#059669` icon and text.
- **Specs:** Pill format, `24px` height, inline SVG check icon, padding `2px 8px`.

### Selection Controls (Checkboxes & Radios)
- **Checkboxes:** `20px x 20px`, `6px` corner radius. Unchecked: `1.5px solid #9E9B97` with `rgba(255, 255, 255, 0.5)` fill. Checked: solid `#F07660` with white vector check mark.
- **Radio Buttons:** `20px` circle with matching coral center bullet when active.
- **Hit Slop:** Extended transparent touch padding ensuring a full 48dp interactable boundary.