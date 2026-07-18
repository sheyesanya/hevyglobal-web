---
name: Institutional Noir
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#c5c6ce'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#8f9098'
  outline-variant: '#44474d'
  surface-tint: '#b6c7eb'
  primary: '#b6c7eb'
  on-primary: '#1f304d'
  primary-container: '#0b1e3a'
  on-primary-container: '#7586a8'
  inverse-primary: '#4e5f7e'
  secondary: '#ffb2b7'
  on-secondary: '#5d1521'
  secondary-container: '#7e2e38'
  on-secondary-container: '#ff9da4'
  tertiary: '#a2d1bb'
  on-tertiary: '#073829'
  tertiary-container: '#002419'
  on-tertiary-container: '#638f7c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b6c7eb'
  on-primary-fixed: '#081b37'
  on-primary-fixed-variant: '#364765'
  secondary-fixed: '#ffdadb'
  secondary-fixed-dim: '#ffb2b7'
  on-secondary-fixed: '#40000e'
  on-secondary-fixed-variant: '#7b2c36'
  tertiary-fixed: '#beedd7'
  tertiary-fixed-dim: '#a2d1bb'
  on-tertiary-fixed: '#002116'
  on-tertiary-fixed-variant: '#234f3f'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display-lg:
    fontFamily: IBM Plex Sans
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: IBM Plex Sans
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: 0em
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0em
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  label-md:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 40px
---

## Brand & Style

The design system is built on the philosophy of "Institutional Noir"—a visual language that communicates absolute stability, global authority, and high-stakes professionalism. The target audience includes executive leadership, institutional investors, and global stakeholders who value discretion and clarity over ornamentation.

The aesthetic merges **Minimalism** with **Corporate Modernism**. It utilizes a dark-mode-first approach to evoke a sense of a high-end, private boardroom. Layouts are strictly organized, emphasizing whitespace as a tool for focus. Visual interest is derived from precision, rigid grid alignment, and the deliberate use of deep, saturated accent colors against a near-black foundation.

## Colors

The palette is anchored in a monochromatic dark range, using "Deep Navy" and "Near-Black" to create a sense of infinite depth. 

- **Base Layers:** The primary background is the near-black `#0A0A0C`. Surface layers use the deep navy `#0B1E3A` at various opacities to create structural hierarchy.
- **Accents:** Use deep wine, forest green, and steel blue sparingly. These are reserved for status indicators, category markers, or high-level financial data visualization. 
- **Typography:** Contrast is kept maximum. All text must be solid white or off-white. Gradients are strictly prohibited to maintain the "Institutional Noir" aesthetic.

## Typography

This design system utilizes **IBM Plex Sans** for its systematic, engineered feel. The typeface reflects the industrial and corporate heritage of a global holding company.

- **Hierarchy:** Use dramatic size differences between display headers and body text to establish a clear information architecture.
- **Weight:** Headlines should primarily use SemiBold (600) or Medium (500). Regular (400) is reserved for body copy to ensure legibility against dark backgrounds.
- **Labels:** Use uppercase labels with slight letter spacing for metadata and small headers to provide a "technical report" feel.

## Layout & Spacing

The system follows a **Fixed Grid** model for desktop to maintain an architectural, controlled appearance. 

- **Grid:** A 12-column grid with a maximum container width of 1440px. 
- **Margins:** Generous 40px external margins on desktop, scaling down to 16px on mobile. 
- **Rhythm:** All spacing is based on a 4px baseline. Use `lg` (48px) and `xl` (80px) vertical spacers between major sections to emphasize the "Noir" minimalist scale.
- **Responsive:** On tablet (768px - 1024px), transition to an 8-column grid. On mobile, use a 4-column fluid grid.

## Elevation & Depth

Depth is signaled through **Tonal Layering** and **Low-Contrast Outlines** rather than traditional shadows.

- **Surface Tiers:** Background is always the darkest layer (`#0A0A0C`). Components like cards use a semi-transparent Deep Navy tint (`#0B1E3A` at 15-20% opacity).
- **Outlines:** Use 1px solid white borders at 10-15% opacity to define the edges of containers. This creates a "blueprint" or "glass" effect without using blurs.
- **Shadows:** Avoid drop shadows for structural elements. Small, sharp, low-opacity shadows (Black, 40% opacity, 4px blur) may be used only for floating menus or dropdowns to ensure they clear the content below.

## Shapes

The shape language is disciplined and geometric. 

- **Containers:** Standard cards and content modules use a 12px or 16px corner radius (`rounded-lg` or `rounded-xl`).
- **Small Elements:** Buttons and input fields use a tighter 8px radius to maintain a professional, sharp profile.
- **Strictness:** Do not use fully circular "pill" shapes for buttons; keep them rectangular with subtle rounding to preserve the institutional aesthetic.

## Components

### Buttons
- **Primary:** Solid White background with Deep Navy (#0B1E3A) text. High contrast for immediate action.
- **Secondary:** Deep Navy background with a 1px White border (20% opacity) and White text.
- **Interaction:** On hover, primary buttons should "lift" by 2-4px via a transform, with no color change.

### Cards
- **Structure:** Solid panels of Deep Navy (#0B1E3A) at 18% opacity. 
- **Border:** Constant 1px solid White at 12% opacity.
- **Content:** Headlines within cards are always White (#FFFFFF).

### Input Fields
- **Style:** Underlined or fully enclosed with a 1px border at 15% opacity. Background should be slightly darker than the card surface to create an "inset" feel.
- **Focus State:** Border opacity increases to 60% white.

### Lists & Tables
- **Dividers:** 1px solid White at 10% opacity.
- **Data:** Use monospaced numerals (available in IBM Plex Sans) for financial figures to ensure alignment in tables.

### Imagery
- **Treatment:** All photography must be professional (Architectural/Studio). Apply a 20% Deep Navy overlay to all background images to ensure white text remains legible and the "Noir" mood is consistent.