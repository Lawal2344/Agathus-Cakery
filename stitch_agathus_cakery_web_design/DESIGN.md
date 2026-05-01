---
name: Artisanal Elegance
colors:
  surface: '#fcf9f5'
  surface-dim: '#dcdad6'
  surface-bright: '#fcf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ef'
  surface-container: '#f0ede9'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e5e2de'
  on-surface: '#1c1c1a'
  on-surface-variant: '#58413f'
  inverse-surface: '#31302e'
  inverse-on-surface: '#f3f0ec'
  outline: '#8c716e'
  outline-variant: '#dfbfbc'
  surface-tint: '#ab3331'
  primary: '#590007'
  on-primary: '#ffffff'
  primary-container: '#7d1015'
  on-primary-container: '#ff857e'
  inverse-primary: '#ffb3ad'
  secondary: '#605e5a'
  on-secondary: '#ffffff'
  secondary-container: '#e6e2dc'
  on-secondary-container: '#666460'
  tertiary: '#2a2822'
  on-tertiary: '#ffffff'
  tertiary-container: '#413e38'
  on-tertiary-container: '#ada9a0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#8a1b1d'
  secondary-fixed: '#e6e2dc'
  secondary-fixed-dim: '#c9c6c1'
  on-secondary-fixed: '#1c1c18'
  on-secondary-fixed-variant: '#484743'
  tertiary-fixed: '#e8e2d9'
  tertiary-fixed-dim: '#cbc6bd'
  on-tertiary-fixed: '#1d1b16'
  on-tertiary-fixed-variant: '#494640'
  background: '#fcf9f5'
  on-background: '#1c1c1a'
  surface-variant: '#e5e2de'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 32px
---

## Brand & Style
This design system centers on the intersection of premium craftsmanship and local warmth. The brand personality is sophisticated yet deeply approachable, mirroring the experience of a high-end neighborhood bakery. The UI should evoke an emotional response of comfort, indulgence, and trust.

The chosen style is **Modern Minimalism with Tactile warmth**. We utilize heavy whitespace and a refined color palette to establish a premium "gallery-like" feel for the products, while employing soft shadows and organic curves to ensure the interface remains inviting rather than cold. Visuals should prioritize high-quality, appetizing photography of textures (flour, golden crusts, rich creams) contrasted against clean, structured layouts.

## Colors
The palette is rooted in the "Deep Red" primary color, a rich, wine-inspired hue that suggests heritage and premium quality. This is balanced by a "Warm Cream" background to prevent the clinical feel of pure white, providing a cozy, parchment-like canvas.

- **Primary (#7D1015):** Used for key actions, brand marks, and high-emphasis headings.
- **Secondary/Neutral (#FDF9F3):** The primary surface color for the entire application.
- **Tertiary (#E8E2D9):** Used for subtle section containers and input backgrounds.
- **Text/Neutral (#706F6C):** A soft gray used for body text to maintain a gentle contrast that is easy on the eyes.

## Typography
The typographic hierarchy uses a "Serif for Headlines, Sans-Serif for Utility" approach. **Noto Serif** provides an authoritative, literary elegance that communicates the brand's premium positioning. It should be used for storytelling elements and product names.

**Plus Jakarta Sans** is used for all functional text. Its soft, rounded terminals complement the "approachable" brand pillar while maintaining excellent readability across digital devices. Headlines should use tighter tracking to feel more "editorial," while labels use slightly increased tracking for clarity at small sizes.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop (12-column, 1140px max-width) and a fluid model for mobile. The spacing rhythm is based on an 8px baseline to ensure consistent vertical alignment.

Intentional "air" is a core principle; we use generous margins (`xl`) to separate major sections, allowing the product photography to breathe. Content cards and smaller elements should use the `md` spacing unit for internal padding to maintain a feeling of luxury and openness. Avoid crowding elements; the design should feel as carefully plated as a pastry.

## Elevation & Depth
Visual hierarchy is achieved through **Ambient Shadows** and tonal layering. Rather than harsh black shadows, this design system employs soft, extra-diffused shadows with a very low opacity, slightly tinted with the primary red color (`rgba(125, 16, 21, 0.08)`) to maintain warmth.

- **Level 1 (Base):** Warm Cream background.
- **Level 2 (Cards):** Slightly raised with a large blur radius (20px-30px) shadow to suggest they are sitting softly on a surface.
- **Level 3 (Interactions):** Buttons and active states use a slightly deeper shadow to invite touch.
- **Tonal Layers:** Tertiary beige surfaces are used for "sunken" elements like search bars or footer areas to provide contrast without adding shadow complexity.

## Shapes
The shape language is defined by **Roundedness Level 2**. This level of corner radius (0.5rem for standard elements) removes the "sharpness" of digital interfaces, making the UI feel more organic and hand-crafted. 

Large-scale components like hero image containers and product cards should utilize `rounded-xl` (1.5rem) to emphasize the soft, appetizing nature of the brand. Buttons should remain consistently rounded but not fully pill-shaped, maintaining a sense of structure.

## Components
- **Buttons:** Primary buttons feature a solid Deep Red background with Warm Cream text. Secondary buttons use a Deep Red outline with a subtle cream fill on hover. All buttons use the `label-md` type spec for a clean, uppercase appearance.
- **Cards:** Product cards are the centerpiece. They must feature a `rounded-lg` top corner for images and a clean white or tertiary-beige footer. Shadows should be subtle and ambient.
- **Input Fields:** Fields use the Tertiary Beige for backgrounds rather than white, creating a "soft" landing for text. Borders are only used on focus, using the Deep Red primary color.
- **Chips:** Used for categories (e.g., "Gluten-Free," "Seasonal"). These should have a very light Primary tint background and Deep Red text, with fully rounded corners.
- **Lists:** Clean, separated by subtle `0.5px` soft gray lines. Use `body-md` for list items with generous vertical padding.
- **Additional Suggestion:** **"The Artisanal Badge"** — A floating or anchored circular component used for awards, local sourcing labels, or "Fresh Today" callouts, utilizing Noto Serif and the Primary Red.