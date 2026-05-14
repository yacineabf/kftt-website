---
name: KFTT Industrial Logistics
colors:
  surface: '#f7f9ff'
  surface-dim: '#d7dadf'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f9'
  surface-container: '#ebeef3'
  surface-container-high: '#e5e8ee'
  surface-container-highest: '#e0e3e8'
  on-surface: '#181c20'
  on-surface-variant: '#43474e'
  inverse-surface: '#2d3135'
  inverse-on-surface: '#eef1f6'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#455f88'
  primary: '#002045'
  on-primary: '#ffffff'
  primary-container: '#1a365d'
  on-primary-container: '#86a0cd'
  inverse-primary: '#adc7f7'
  secondary: '#4a6800'
  on-secondary: '#ffffff'
  secondary-container: '#c2f363'
  on-secondary-container: '#4e6e00'
  tertiary: '#6d5e00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c5aa00'
  on-tertiary-container: '#4a3f00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#adc7f7'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#c2f363'
  secondary-fixed-dim: '#a7d64a'
  on-secondary-fixed: '#141f00'
  on-secondary-fixed-variant: '#364e00'
  tertiary-fixed: '#ffe251'
  tertiary-fixed-dim: '#e4c600'
  on-tertiary-fixed: '#211b00'
  on-tertiary-fixed-variant: '#524600'
  background: '#f7f9ff'
  on-background: '#181c20'
  surface-variant: '#e0e3e8'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is built upon the pillars of reliability, structural integrity, and kinetic momentum. It serves a dual purpose: establishing high-authority trust for B2B stakeholders while providing high-performance utility for logistics operations. 

The visual language follows a **Corporate Modern** aesthetic with an **Industrial** edge. It prioritizes clarity and high-compliance standards, utilizing generous whitespace to prevent information density from becoming overwhelming. Imagery should focus on the "Macro" of global transit—shipping containers, long-haul freight, and global connectivity—using the globe motif from the brand identity as a recurring structural element.

## Colors

The palette is engineered for authority and action. 

- **Primary (Deep Navy Blue):** Used for headers, primary navigation, and core branding elements to signify institutional trust.
- **Secondary (Vibrant Green):** Representing movement and "all-clear" status, this is used for primary calls to action, tracking progress, and success states.
- **Accents (Warning Yellow & Error Red):** Derived from industrial safety standards, these colors are reserved for alerts, critical transit delays, and high-priority notifications.
- **Neutrals:** A range of greys provides structural separation without the harshness of pure black, maintaining a professional, "blueprint-like" cleanliness.

## Typography

The design system employs a highly legible, dual-sans-serif hierarchy. 

**Inter** is the typeface for headlines and interface labels. Its technical precision and geometric clarity mirror industrial engineering. Large headlines use tight letter-spacing and bold weights to command attention in a systematic way.

**Open Sans** is utilized for body text and long-form data. Its humanist characteristics improve readability in high-density environments like shipping manifests and transit logs, ensuring that complex information is easily digestible.

## Layout & Spacing

The layout is governed by a **12-column fixed grid** for marketing surfaces and a **fluid grid** for operational dashboards. A rigorous 8px baseline grid ensures every element is aligned with mathematical precision, reinforcing the "standardized" industrial theme.

- **Desktop:** 12 columns with 24px gutters. Wide 64px margins create a professional, spacious frame that prevents the content from feeling cramped.
- **Tablet:** 8 columns with 24px gutters.
- **Mobile:** 4 columns with 16px margins. Headlines scale down for better legibility on small screens.

Generous vertical spacing (48px+) is used between major sections to emphasize the premium nature of the logistics services.

## Elevation & Depth

To maintain a "high-compliance" and professional feel, the design system avoids heavy shadows. Instead, it utilizes **tonal layers** and **low-contrast outlines**.

1.  **Level 0 (Surface):** The main background uses the Neutral Light Grey (#F8F9FA) to reduce eye strain.
2.  **Level 1 (Card):** White surfaces with a subtle 1px border (#E2E8F0) and no shadow. This creates a "blueprint" feel.
3.  **Level 2 (Interaction):** Very soft, diffused ambient shadows (4% opacity Navy) are used only for floating elements like dropdowns or active modal windows.
4.  **Indicators:** Active states are indicated by 2px solid Navy or Green borders rather than elevation changes, keeping the interface feeling grounded and sturdy.

## Shapes

The design system uses a "Soft" corner radius of 4px (`rounded-sm`). This provides a subtle nod to modern digital interfaces while retaining the rigid, structural look of shipping containers and heavy machinery. 

Buttons, input fields, and status chips all share this consistent radius. Circular shapes are reserved strictly for icons and the globe-motif logo elements to create a distinctive visual contrast against the otherwise rectangular, modular environment.

## Components

### Buttons
- **Primary:** Solid Navy (#1A365D) with white text. High-weight sans-serif labels.
- **Action:** Solid Green (#84B026) for "Start Tracking," "Accept Transit," or "Confirm."
- **Ghost:** Transparent background with 1px Navy border for secondary actions.

### Input Fields
Inputs are structured with 1px borders and clear label text above. Errors are marked with a 2px left-border accent in Red (#DC3545), ensuring accessibility and industrial compliance.

### Status Chips
Used for tracking (e.g., "In Transit," "Delivered," "Delayed"). These use low-opacity backgrounds of the status color with high-contrast text of the same hue to ensure readability without being distracting.

### Logistics Cards
Cards are the primary container for shipment data. They feature a structured header with the Primary color and a clear 1px separator, organizing information into a readable grid of data points (e.g., ETA, Destination, Weight).

### Tracking Bar
A custom component featuring a horizontal timeline using the Secondary Green for progress and the Globe motif as a "current location" marker.