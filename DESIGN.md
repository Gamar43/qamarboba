---
name: Al-Qamar Boba
colors:
  surface: '#fff8f3'
  surface-dim: '#f4d6a5'
  surface-bright: '#fff8f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff2e1'
  surface-container: '#ffebcf'
  surface-container-high: '#ffe5bc'
  surface-container-highest: '#fddead'
  on-surface: '#271900'
  on-surface-variant: '#544340'
  inverse-surface: '#3f2d0b'
  inverse-on-surface: '#ffeed8'
  outline: '#867370'
  outline-variant: '#d9c1be'
  surface-tint: '#924940'
  primary: '#280000'
  on-primary: '#ffffff'
  primary-container: '#47100b'
  on-primary-container: '#c77469'
  inverse-primary: '#ffb4a9'
  secondary: '#7a5551'
  on-secondary: '#ffffff'
  secondary-container: '#ffcfc9'
  on-secondary-container: '#7a5652'
  tertiary: '#000e22'
  on-tertiary: '#ffffff'
  tertiary-container: '#002447'
  on-tertiary-container: '#718cb5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4a9'
  on-primary-fixed: '#3c0805'
  on-primary-fixed-variant: '#75322a'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#eabbb6'
  on-secondary-fixed: '#2e1412'
  on-secondary-fixed-variant: '#5f3e3b'
  tertiary-fixed: '#d4e3ff'
  tertiary-fixed-dim: '#acc8f4'
  on-tertiary-fixed: '#001c39'
  on-tertiary-fixed-variant: '#2c486d'
  background: '#fff8f3'
  on-background: '#271900'
  surface-variant: '#fddead'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.03em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 128px
  section-gap-mobile: 64px
  container-max-width: 1200px
  gutter: 32px
  margin-mobile: 20px
---

## Brand & Style

The design system is anchored in **Modern Minimalist Luxury**, blending clinical precision with the warmth of a high-end editorial publication. It targets a discerning demographic that values transparency, efficacy, and aesthetic tranquility. The UI must evoke a sense of **"Earthy Sophistication"**—using vast whitespace and warm, organic tones to allow the product photography and sophisticated typography to breathe.

The visual direction leans heavily into **Minimalism** with an **Editorial** edge. This is achieved through generous negative space, a restricted and intentional color palette, and a focus on rhythmic verticality that guides the user through a narrative-driven shopping experience.

## Colors

This design system utilizes a high-sophistication palette that balances deep earth tones and warm neutrals to create depth without visual noise.

- **Primary (Deep Maroon):** Used exclusively for high-priority typography, iconography, and primary call-to-action backgrounds. It provides the grounding weight for the interface.
- **Secondary (Dusty Rose):** An accent color for section blocks. It softens the palette, adding a premium, tactile quality.
- **Neutral (Warm Beige):** Reserved for product cards and containers to emphasize cleanliness while maintaining an organic, welcoming feel.

## Typography

The typography strategy is a classic serif-on-sans pairing. **Playfair Display** provides the editorial authority for headlines, while **Inter** ensures high readability for technical skincare data and ingredient lists.

Use **Display LG** for hero sections only. All **Label** styles should be used for metadata, product categories, or small caps navigation items to maintain a structured, organized feel. Ensure that large headlines are never centered unless the surrounding whitespace is symmetrical and intentional.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop, centered within the viewport to maintain an editorial "lookbook" feel. 

- **Grid:** A 12-column grid is used for the desktop experience. Product listings are strictly capped at a 3-column configuration to maximize image size and premium impact.
- **Rhythm:** Vertical spacing between sections is aggressive (128px) to reinforce the minimalist luxury aesthetic. 
- **Reflow:** On mobile, the 3-column grid collapses into a 1-column stack or a 2-column "staggered" layout for visual interest. Margins are reduced to 20px to allow photography to remain as large as possible.

## Elevation & Depth

This design system avoids heavy drop shadows. Depth is primarily communicated through **Tonal Layers**—placing warm beige containers (#FBDCAB) on dusty rose backgrounds (#D3A6A1). 

For product cards and interactive elements, use **Ambient Shadows**:
- A very soft, highly diffused shadow (Blur: 32px, Opacity: 4%) with a hint of deep maroon tinting. 
- **Dividers:** Use 1px solid lines in a muted maroon (10% opacity) for horizontal separation in accordions and navigation. No heavy borders or bevels are permitted.

## Shapes

The shape language is defined by **Pill-shaped (3)** aesthetics for interactive elements, contrasted against sharp, rectangular product imagery. This juxtaposition reflects the "Boba" aspect of the brand (soft, circular) against the "Modern Luxury" aspect (precise, geometric).

- **Primary Buttons:** Always fully rounded (pill).
- **Secondary Containers:** Can use a softer `rounded-lg` (2rem) for a gentler appearance in FAQs or informational cards.
- **Images:** Strictly sharp-edged (0px) to maintain the high-fashion editorial look.

## Components

### Buttons
Primary buttons are pill-shaped, using the Deep Maroon background with warm beige typography. They should have a minimum width to ensure the "pill" shape is elongated and elegant. Hover states involve a subtle scale-up (1.02x) rather than a color shift.

### Product Cards
3-column product grids use warm beige backgrounds with a subtle ambient shadow. The product name (Playfair) and price (Inter) should be separated by generous padding from the image.

### Accordions (FAQs)
Clean, horizontal lines separate accordion items. The "Open" state should use a Deep Maroon accent for the icon (a simple '+' or thin arrow) to guide the eye.

### Input Fields
Inputs are underlined (border-bottom only) to mirror the horizontal divider style, moving away from standard boxed inputs to maintain the minimalist feel. Use Inter for input text.

### Chips
Small, pill-shaped tags used for "New" or "Best Seller" labels. Use a Dusty Rose background with a low opacity and Deep Maroon text for a soft, integrated look.