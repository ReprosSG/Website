---
name: Aequitas Global
colors:
  surface: '#0d1322'
  surface-dim: '#0d1322'
  surface-bright: '#33394a'
  surface-container-lowest: '#080e1d'
  surface-container-low: '#151b2b'
  surface-container: '#191f2f'
  surface-container-high: '#242a3a'
  surface-container-highest: '#2f3445'
  on-surface: '#dde2f8'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#dde2f8'
  inverse-on-surface: '#2a3040'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#bfcdff'
  on-tertiary: '#082b72'
  tertiary-container: '#97b0ff'
  on-tertiary-container: '#254188'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#27438a'
  background: '#0d1322'
  on-background: '#dde2f8'
  surface-variant: '#2f3445'
typography:
  display-xl:
    fontFamily: Newsreader
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '300'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
  stat-number:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  section-gap: 96px
  container-padding: 32px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
  gutter: 32px
---

## Brand & Style
Aequitas Global is an institutional yet emotionally resonant design system tailored for international NGOs and data-driven advocacy platforms. The brand personality is **Authoritative, Transparent, and Hopeful**. It balances the gravity of global issues with the clarity of modern data visualization.

The visual style is a sophisticated blend of **Modern Corporate** and **Glassmorphism**. It utilizes deep navy foundations to establish trust, punctuated by "Justice Gold" to highlight calls to action and critical data. The interface feels premium and expansive, using high-quality serif typography for narrative storytelling and clean sans-serif for functional data display. Soft backdrop blurs and glowing ambient effects prevent the dark theme from feeling heavy, creating a sense of "light within the darkness."

## Colors
The palette is rooted in a "Midnight Advocacy" theme. 

- **Primary (Justice Gold):** Used exclusively for high-impact elements: brand identity, primary buttons, and critical data trends. It symbolizes value and the "light" of justice.
- **Surface Strategy:** The background uses a deep navy (`#0B1120`). Component surfaces use a slightly lighter "Card Dark" (`#162032`) with low-opacity borders to create structural definition without high-contrast harshness.
- **Semantic Colors:** Standardized traffic-light colors (Red, Orange, Green) are used for the Corruption Perceptions Index and map markers to provide instant cognitive recognition of data health.
- **Accents:** A secondary blue is used sparingly for decorative glows and secondary interactive states to provide visual depth.

## Typography
The system employs a dual-font strategy to balance editorial authority with functional clarity.

- **Editorial Serif (Newsreader):** Used for large-scale displays, section headers, and narrative titles. It evokes the feeling of high-end journalism and historical record.
- **Functional Sans (Inter):** Used for all body copy, navigation, labels, and data visualizations. The tight apertures and tall x-height ensure maximum legibility at small sizes on digital screens.
- **Hierarchy Rule:** Headlines should utilize a tracking-tight setting (`-0.02em`) to feel cohesive, while uppercase labels should use expanded tracking (`0.1em`) for a modern, architectural feel.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop (max-width 1280px) and a **Fluid Stack** for mobile devices. 

- **Sectioning:** Sections are heavily padded vertically (96px) to allow for "breathable" transitions between complex data sets.
- **Data Grids:** Statistics and pillars are organized into a 3-column grid on desktop, collapsing to 1-column on mobile.
- **Rhythm:** A 4px baseline grid governs all internal component spacing. Cards use 32px of internal padding to maintain an airy, premium feel.
- **Margins:** Horizontal container margins are set to a minimum of 24px on mobile and scale to 80px on large displays.

## Elevation & Depth
Depth is communicated through **Tonal Layering** and **Atmospheric Glows** rather than traditional drop shadows.

- **Basal Layer:** Deep Navy (`#0B1120`).
- **Elevated Surfaces:** Components use "Card Dark" (`#162032`) with a subtle 1px border (`#1F2937`). 
- **Active States:** Hovering over interactive cards produces a "Justice Gold" outer glow (`shadow-primary/20`) and a slight vertical translation (-8px) to simulate physical lift.
- **Background Interest:** Large, low-opacity radial gradients (Primary and Secondary colors) are placed behind main content areas to create a sense of vast, 3D space.
- **Glass Effects:** Navigation bars and sticky elements use a 70% opacity fill with a heavy `backdrop-blur` (12px) to maintain context while scrolling.

## Shapes
The shape language is **Substantial and Modern**.

- **Standard Radius:** 0.5rem (8px) for buttons and small inputs.
- **Card Radius:** 1rem (16px) for major content containers and data blocks.
- **Pill Radius:** Full rounding is reserved exclusively for the "Action" buttons (e.g., "Get Involved", "Pledge") to distinguish them from structural elements.
- **Iconography:** Use "Material Symbols Outlined" with a consistent 24px optical size and 400 weight. Icons should be encased in a rounded-xl box with a 10% primary color tint for emphasis.

## Components
- **Primary Buttons:** Pill-shaped, gold background, bold white or dark-navy text. Include a soft glow shadow (`shadow-lg shadow-primary/30`).
- **Secondary Buttons:** Rounded (8px), transparent background with a 1px border of the primary color or neutral gray.
- **Cards:** 16px border-radius, background `#162032`, 1px border `#1F2937`. On hover, the border transitions to Primary Gold.
- **Data Markers:** Circular markers for maps. Use a 2px white "stroke" around the color-coded circle to ensure it pops against the map background.
- **Interactive Map:** Housed in a 16px rounded container with a high-contrast shadow (`shadow-2xl`). Use a "Light All" or "Positron" tile style to keep the data markers legible.
- **Pledge Counter:** Stylized stat component using the `stat-number` typography, punctuated by the Primary color to highlight the human impact.