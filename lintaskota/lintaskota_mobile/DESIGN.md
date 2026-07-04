---
name: LintasKota Mobile
colors:
  surface: '#f8f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f6'
  surface-container: '#edeef0'
  surface-container-high: '#e7e8ea'
  surface-container-highest: '#e1e2e4'
  on-surface: '#191c1e'
  on-surface-variant: '#434654'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f3'
  outline: '#737685'
  outline-variant: '#c3c6d6'
  surface-tint: '#0c56d0'
  primary: '#003d9b'
  on-primary: '#ffffff'
  primary-container: '#0052cc'
  on-primary-container: '#c4d2ff'
  inverse-primary: '#b2c5ff'
  secondary: '#285ab9'
  on-secondary: '#ffffff'
  secondary-container: '#709bfe'
  on-secondary-container: '#003179'
  tertiary: '#00418a'
  on-tertiary: '#ffffff'
  tertiary-container: '#0058b6'
  on-tertiary-container: '#bfd3ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b2c5ff'
  on-primary-fixed: '#001848'
  on-primary-fixed-variant: '#0040a2'
  secondary-fixed: '#d9e2ff'
  secondary-fixed-dim: '#b1c6ff'
  on-secondary-fixed: '#001946'
  on-secondary-fixed-variant: '#00419d'
  tertiary-fixed: '#d7e2ff'
  tertiary-fixed-dim: '#abc7ff'
  on-tertiary-fixed: '#001b3f'
  on-tertiary-fixed-variant: '#004590'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e1e2e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.1px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.5px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 16px
  margin-mobile: 16px
  margin-tablet: 24px
---

## Brand & Style

The design system is engineered for **LintasKota**, an intercity travel platform where reliability and efficiency are paramount. The visual language follows a **Corporate / Modern** aesthetic, heavily influenced by **Material Design 3 (MD3)** principles but elevated with a premium, travel-focused finish.

The target audience consists of frequent travelers and commuters who require clarity under pressure. The UI evokes a sense of **trust, precision, and ease**. Key stylistic hallmarks include:
- **Clarity over Decoration:** Minimalist layouts that prioritize the booking funnel and itinerary details.
- **Intentional Depth:** Use of tonal surfaces and soft shadows to indicate interactable cards.
- **High-Affordance Elements:** Large touch targets and prominent primary actions designed specifically for one-handed mobile use.

## Colors

The palette is anchored by **Primary Blue (#0052CC)**, a color associated with professionalism and institutional trust. 

- **Primary & Secondary:** Used for high-emphasis UI like primary buttons, active navigation states, and progress indicators.
- **Surface & Background:** The background uses a cool-toned neutral (#F4F5F7) to reduce glare, while interactive cards utilize pure White (#FFFFFF) to create a clear "layering" effect.
- **Semantic Colors:** Green and Red are reserved strictly for success states (ticket confirmed) and error states (seat unavailable), ensuring immediate user recognition of system status.

## Typography

This design system utilizes **Inter** for its exceptional legibility on mobile screens and its systematic, neutral character.

- **Scale:** The hierarchy is strictly enforced to ensure travel times and prices (the most critical data) are easily scannable.
- **Weights:** Use `600` (Semi-bold) for headlines and `500` (Medium) for labels/buttons to ensure they stand out against body copy.
- **Optimizations:** Letter spacing is slightly tightened on larger headlines for a more premium "editorial" feel, while labels utilize increased tracking for readability at small sizes.

## Layout & Spacing

The layout follows a **Fluid Grid** model optimized for the Android handheld experience.

- **Grid System:** A 4-column grid for mobile handsets, expanding to 8 columns for tablets. 
- **Rhythm:** An 8pt spacing system is used to maintain vertical rhythm. 
- **Safe Zones:** Consistent 16px side margins are required for all content containers.
- **Vertical Packing:** Elements within a travel card (e.g., Departure City to Arrival City) use `sm` (8px) spacing, while separate cards use `md` (16px) spacing to distinguish between different travel options.

## Elevation & Depth

Hierarchy is established using **Tonal Layers** supplemented by **Ambient Shadows**, moving away from harsh outlines.

- **Level 0 (Background):** Surface/Background (#F4F5F7). No shadow.
- **Level 1 (Cards):** Pure White (#FFFFFF). Uses a soft, diffused shadow: `0px 2px 8px rgba(0, 0, 0, 0.05)`.
- **Level 2 (Active/Floating):** Used for Floating Action Buttons (FAB) or active search bars. Uses a more pronounced shadow: `0px 4px 12px rgba(0, 0, 0, 0.1)`.
- **Modals/Bottom Sheets:** Feature a backdrop scrim (40% opacity black) to focus user attention on the task at hand.

## Shapes

The design system adopts a **Rounded** shape language to appear approachable and modern.

- **Small Components (Buttons, Inputs):** 8px (0.5rem) corner radius.
- **Medium Components (Cards, Modals):** 16px (1rem) corner radius.
- **Large Components (Bottom Sheets, Full-width containers):** 24px (1.5rem) corner radius on top corners only.
- **Selection States:** Use pill-shapes (full rounding) for chips and toggle indicators to differentiate them from structural containers.

## Components

### Buttons
- **Primary:** High-emphasis, Primary Blue background, White text. Height: 56px for main actions (e.g., "Search Flights").
- **Secondary:** Outlined with Primary Blue or Ghost style for less critical actions (e.g., "Add Return").

### Cards
- Travel cards must use 16px internal padding. 
- Include a subtle 1px border (#E6E8ED) only if elevation shadows are disabled for performance.

### Input Fields
- MD3-inspired filled styles with a clear "Active" indicator (Primary Blue bottom border).
- Icons (Leading): Use for "From", "To", and "Date" to aid rapid scanning.

### Bottom Navigation
- Fixed 56px-80px height. 
- Icons use an active "pill" background indicator as per Material 3 specs.

### Search Bar
- Floating at the top of the home screen with a 24px corner radius to invite interaction.

### Chips
- Used for filtering: "Price: Low to High", "Morning Departure", etc.
- 32px height, 8px padding, with a 1px stroke.