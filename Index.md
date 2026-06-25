---
name: Toto Tech Modern
colors:
  surface: '#f8f9ff'
  surface-dim: '#d8dae1'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3fb'
  surface-container: '#e5eeff'
  surface-container-high: '#e6e8ef'
  surface-container-highest: '#e0e2ea'
  on-surface: '#191c21'
  on-surface-variant: '#44474d'
  inverse-surface: '#2d3036'
  inverse-on-surface: '#eff0f8'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#095bbf'
  on-secondary: '#ffffff'
  secondary-container: '#5e97fe'
  on-secondary-container: '#002f6a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c20'
  on-tertiary-container: '#828489'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a41'
  on-secondary-fixed-variant: '#004494'
  tertiary-fixed: '#e1e2e8'
  tertiary-fixed-dim: '#c5c6cc'
  on-tertiary-fixed: '#191c20'
  on-tertiary-fixed-variant: '#44474c'
  background: '#f8f9ff'
  on-background: '#191c21'
  surface-variant: '#e0e2ea'
  whatsapp-green: '#25D366'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  lg: 40px
  xl: 64px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style

Toto Tech Modern is a professional, technology-focused design system that balances technical expertise with approachable service. The brand personality is "Expertly Transparent"—it uses high-contrast typography and structured layouts to convey reliability and precision.

The style is a hybrid of **Corporate Modern** and **High-Contrast Minimal**. It utilizes a predominantly light, airy background (Surface) punctuated by deep navy blocks (Primary) and vibrant cobalt accents (Secondary). Visual interest is maintained through crisp photography, subtle backdrop blurs (glassmorphism in the navigation), and a systematic bento-box approach to feature highlights. The emotional response is one of security and efficiency, tailored for users seeking high-quality repairs and premium tech accessories.

## Colors

The palette is rooted in a professional "Midnight Navy" (#0a192f) which serves as the primary anchor for text and dark-themed containers. The "Digital Cobalt" (#0058bc) is the active secondary color, used for links, icons, and interactive states to drive user focus.

The background system uses a cool-toned "Ice Blue" (#f8f9ff) rather than pure white to reduce eye strain and provide a more premium feel. Functional colors include a specific WhatsApp Green for direct communication and a range of muted blue-grays for borders and secondary text. Containers use hierarchical tints of the secondary color to create logical groupings without introducing new hues.

## Typography

The system relies exclusively on **Inter** to maintain a clean, utilitarian, and highly legible interface. The type scale is optimized for information density and clarity. 

- **Display & Headlines:** Use tight letter-spacing and bold/semi-bold weights to create a strong visual hierarchy. On mobile devices, the `display` style should scale down to the `headline-lg` size.
- **Body Text:** Standardizes on a 16px base for comfort. `body-lg` is reserved for introductory paragraphs or hero sub-headings.
- **Labels:** Utilized for buttons, tags, and small metadata. These use medium to semi-bold weights and occasionally increased letter-spacing for all-caps treatments to ensure they don't get lost in the layout.

## Layout & Spacing

The layout follows a **Fixed Grid** system for desktop (max-width 1280px) and a fluid layout for mobile. 

- **Grid:** A 12-column grid is used for desktop. Service cards typically span 3 columns each (4-up), while the hero and specialized sections use an 8/4 or 6/6 split. 
- **Bento Grid:** The accessories section utilizes a CSS Grid "Bento" approach where items span multiple rows and columns (e.g., a feature card spanning 8 columns and 2 rows) to create a modern, curated look.
- **Rhythm:** Vertical spacing between major sections is defined by the `xl` unit (64px). Internal card padding uses the `md` unit (24px).
- **Responsive:** Margins transition from 16px on mobile to 32px on desktop to allow the content room to breathe.

## Elevation & Depth

The system uses **Tonal Layers** combined with **Ambient Shadows** to establish depth.

- **Surfaces:** There are four primary surface levels:
    1. Base Background (Lowest)
    2. Surface-Container-Low (Secondary sections)
    3. Surface-Container-Lowest (Interactive cards/forms)
    4. Glass Layer (Navigation bar with 80% opacity and 12px blur)
- **Shadows:** A signature "Soft Tech" shadow is applied to cards: `0px 4px 20px rgba(10, 25, 47, 0.05)`. On hover, this elevates to `0px 8px 24px rgba(10, 25, 47, 0.1)`, providing a subtle "lift" effect that signals interactivity.
- **Borders:** Low-contrast outlines (#c5c6cd at 30-50% opacity) are used on white cards to define edges without adding visual weight.

## Shapes

The shape language is consistently **Rounded**, reflecting a modern and "friendly-tech" aesthetic.

- **Standard Containers:** Cards and large sections use a 0.75rem (xl) to 1.5rem (2xl) radius.
- **Buttons & Inputs:** Use a 0.5rem (lg) radius for a balanced, approachable look.
- **Badges/Tags:** Use "Full" roundedness (pill-shaped) to distinguish them from interactive buttons.
- **Icon Enclosures:** Small decorative containers (like those behind service icons) use a 0.5rem radius to mirror the button shapes.

## Components

- **Buttons:** 
    - *Primary:* Solid #0a192f background with white text. 
    - *Secondary:* Tinted background (#e5eeff) with cobalt text (#0058bc). 
    - *Special:* WhatsApp green button for high-conversion CTAs. 
    - All buttons feature a subtle scale-down effect (active:scale-95) for tactile feedback.
- **Input Fields:** Use a light surface background with a subtle border. On focus, they transition to a 1px cobalt ring. Labels are positioned above the field in a small, capitalized `label-sm` style.
- **Service Cards:** Feature a top-aligned icon in a tinted box, followed by a headline and body text. They include a "ghost" link at the bottom with a trailing arrow icon.
- **Navigation:** Fixed to the top with a backdrop-blur (glassmorphism). Active links are indicated by a 2px bottom border in the secondary color.
- **Bento Cards:** Feature full-bleed imagery with a dark-to-transparent gradient overlay at the bottom to ensure white text remains legible over photography.