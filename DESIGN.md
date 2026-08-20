---
name: Clinical Capital Architecture
colors:
  surface: '#f7fafd'
  surface-dim: '#d7dadd'
  surface-bright: '#f7fafd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f7'
  surface-container: '#ebeef1'
  surface-container-high: '#e5e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#181c1e'
  on-surface-variant: '#42474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f4'
  outline: '#73777f'
  outline-variant: '#c2c7cf'
  surface-tint: '#3a6188'
  primary: '#002541'
  on-primary: '#ffffff'
  primary-container: '#0b3b60'
  on-primary-container: '#7fa6d0'
  inverse-primary: '#a3caf6'
  secondary: '#006782'
  on-secondary: '#ffffff'
  secondary-container: '#92dfff'
  on-secondary-container: '#00647e'
  tertiary: '#4b0900'
  on-tertiary: '#ffffff'
  tertiary-container: '#721300'
  on-tertiary-container: '#ff7b5d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e4ff'
  primary-fixed-dim: '#a3caf6'
  on-primary-fixed: '#001d35'
  on-primary-fixed-variant: '#1f496f'
  secondary-fixed: '#baeaff'
  secondary-fixed-dim: '#84d1f0'
  on-secondary-fixed: '#001f29'
  on-secondary-fixed-variant: '#004d62'
  tertiary-fixed: '#ffdad2'
  tertiary-fixed-dim: '#ffb4a3'
  on-tertiary-fixed: '#3d0600'
  on-tertiary-fixed-variant: '#8c1900'
  background: '#f7fafd'
  on-background: '#181c1e'
  surface-variant: '#e0e3e6'
  deep-charcoal: '#18232D'
  muted-gray: '#667085'
  white: '#FFFFFF'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap-lg: 120px
  section-gap-md: 80px
---

## Brand & Style

The design system is engineered for a premium B2B Medical Billing and Revenue Cycle Management (RCM) platform. The brand personality balances the sterile precision of modern healthcare with the sophisticated stability of high-finance enterprise software. 

The aesthetic follows a **Corporate / Modern** style influenced by **Minimalism**. It utilizes generous whitespace to reduce cognitive load—essential when dealing with complex financial data—and employs high-quality, editorial-style imagery of modern clinical environments and professional business interactions. The goal is to evoke a sense of "Reliable Innovation," positioning the product as a high-tier partner rather than a mere utility.

Avoid clichéd medical symbols (stethoscopes, crosses). Instead, focus on architectural layouts, clean lines, and a structured hierarchy that communicates organizational excellence.

## Colors

The palette is anchored by **Deep Healthcare Navy**, establishing immediate authority and professionalism. **Healthcare Teal** serves as the secondary brand color for interactive elements and data visualization, providing a calming yet modern bridge between the primary navy and the background.

**Premium Coral-Orange** is the strategic accent color. It must be used sparingly for high-intent Call-to-Actions (CTAs), critical alerts, or meaningful data highlights to ensure it retains its visual impact without overwhelming the sophisticated core palette. 

The background uses a **Soft Light Blue-Gray** (`#F5F8FB`) instead of pure white to reduce eye strain and provide a subtle canvas for white cards and containers to "pop" via elevation. Text uses **Deep Charcoal** for primary headings to maintain high legibility while appearing softer and more premium than pure black.

## Typography

This system utilizes a dual-font approach. **Plus Jakarta Sans** is used for headlines to provide a modern, welcoming, and slightly geometric personality. High-contrast sizing between headlines and body text is encouraged to create a strong editorial rhythm.

**Inter** is the workhorse typeface for body copy and UI labels. Its neutral, highly legible characteristics are perfect for the data-heavy environments of RCM and medical billing. Use `body-lg` for introductory paragraphs and `body-md` for standard content. Labels should utilize the semi-bold weight of Inter to ensure clear distinction from body text at smaller sizes.

## Layout & Spacing

The layout follows a **12-column Fluid Grid** system with a fixed maximum container width of 1280px to maintain readability on ultra-wide monitors. Spacing is based on an **8px linear scale**, ensuring consistent vertical rhythm across all components.

- **Desktop:** 12 columns, 24px gutters, 48px side margins.
- **Tablet:** 8 columns, 20px gutters, 32px side margins.
- **Mobile:** 4 columns, 16px gutters, 16px side margins.

Generous section gaps (`section-gap-lg`) should be used between major landing page modules to emphasize the premium, spacious feel. In dashboard views, density should increase, utilizing `base` (8px) and its multiples for internal component padding.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows**. The interface uses a tiered background system:
1. **App Background:** `#F5F8FB` (Base level).
2. **Surface Containers:** `#FFFFFF` (Elevated cards and sections).

Shadows are exceptionally soft, using the Primary Navy color as a base for the tint rather than pure black. This creates a "glow" that feels integrated into the UI. 
- **Low Elevation:** 0px 2px 4px rgba(11, 59, 96, 0.05). Used for static cards.
- **High Elevation:** 0px 12px 24px rgba(11, 59, 96, 0.1). Used for sticky headers, dropdowns, and hover states on cards.

Avoid heavy borders; use subtle `1px` strokes in a lightened version of the Primary Navy (`rgba(11, 59, 96, 0.1)`) only when necessary to define boundaries on white-on-white layouts.

## Shapes

The design system uses a **Rounded** shape language (`0.5rem` or `8px` base) to strike a balance between the clinical hardness of healthcare and the approachability of modern SaaS. 

- **Standard Elements:** 8px (Buttons, Input Fields, Small Cards).
- **Large Components:** 16px (Main content containers, Feature cards).
- **Interactive Pill:** 100px (Used exclusively for status badges/chips to differentiate them from buttons).

Buttons and interactive elements should maintain a consistent corner radius to reinforce the feeling of a unified, premium platform.

## Components

### Buttons
- **Primary:** Solid `#0B3B60` with white text. 8px radius.
- **Secondary:** Outlined `#0B3B60` with 1.5px stroke.
- **Accent:** Solid `#FF6B4A` with white text (Reserved for "Get Started" or "Critical Action").
- **Hover States:** Subtle lift (High Elevation shadow) and a 10% brightness increase.

### Cards
Cards are white with a subtle 1px border and Low Elevation. On hover, cards should transition smoothly to High Elevation with a `-4px` Y-axis translation to create a "lift" effect.

### Header & Navigation
A premium sticky header with a blur effect (`backdrop-filter: blur(10px)`). Mega menus should use 2 or 3 column layouts with clear category headers and descriptive sub-text for each link.

### Input Fields
Inputs use a white background, 8px radius, and a 1px border of `#667085` (30% opacity). On focus, the border shifts to Primary Navy with a subtle outer glow.

### Footer
A "massive" enterprise footer with 4-5 columns of links, a newsletter signup, and a dedicated section for compliance badges (HIPAA, SOC2). Background should be the `Deep Charcoal` or `Primary Navy` with light-toned text.

### Iconography
Use **Bootstrap Icons**. Icons should be thin-stroke (1px or 1.5px) to match the refined typography. Use Primary Navy for functional icons and Secondary Teal for decorative/feature icons.