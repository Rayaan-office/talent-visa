---
name: Global Mobility Framework
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#3e4850'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#6e7881'
  outline-variant: '#bec8d1'
  surface-tint: '#006590'
  primary: '#006590'
  on-primary: '#ffffff'
  primary-container: '#019cdc'
  on-primary-container: '#002f46'
  inverse-primary: '#87ceff'
  secondary: '#506070'
  on-secondary: '#ffffff'
  secondary-container: '#d3e4f7'
  on-secondary-container: '#566676'
  tertiary: '#bc004b'
  on-tertiary: '#ffffff'
  tertiary-container: '#ff537f'
  on-tertiary-container: '#5d0021'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c8e6ff'
  primary-fixed-dim: '#87ceff'
  on-primary-fixed: '#001e2e'
  on-primary-fixed-variant: '#004c6d'
  secondary-fixed: '#d3e4f7'
  secondary-fixed-dim: '#b7c8da'
  on-secondary-fixed: '#0c1d2a'
  on-secondary-fixed-variant: '#384857'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#ffb2be'
  on-tertiary-fixed: '#400014'
  on-tertiary-fixed-variant: '#900038'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  slate-deep: '#243442'
  action-blue: '#019CDC'
  accent-pink: '#E91E63'
  surface-gray: '#F8FAFB'
  border-subtle: '#E2E8F0'
typography:
  headline-lg:
    fontFamily: Nunito Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Nunito Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Nunito Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  headline-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  max-width: 1200px
---

## Brand & Style

The design system is engineered for a visa application platform where clarity, institutional trust, and efficiency are paramount. The brand personality is **Professional, Systematic, and Facilitative**, designed to guide users through complex legal processes with a sense of calm and progress.

The aesthetic follows a **Corporate / Modern** style, utilizing a "Clean Institutional" approach. It prioritizes high legibility and a structured information hierarchy to reduce the cognitive load associated with government forms and documentation. The interface relies on a generous use of white space, a disciplined color palette, and subtle elevation to create a workspace that feels authoritative yet accessible.

## Colors

The color strategy is anchored in **Action Blue** (#019CDC), used for primary interactions and to signify progress. **Slate Deep** (#243442) provides the foundational professional weight, used for headings and navigation to instill a sense of legal authority. 

**Accent Pink** (#E91E63) is reserved strictly for high-priority alerts, errors, or critical status indicators that require immediate user attention. The background should remain primarily white or very light gray (`#F8FAFB`) to ensure the platform feels like a clean, digital "desk" for document preparation.

## Typography

This design system utilizes **Nunito Sans** exclusively to maintain a modern, highly legible, and friendly professional tone. Its balanced x-height and slightly rounded terminals soften the bureaucratic nature of the content while remaining efficient for long-form data entry.

Headlines use a bold weight and tight letter spacing to create a strong visual anchor for different application sections. Body text maintains a standard 16px base for optimal readability. Labels for form fields are consistently styled to be distinct from input text, often using a heavier weight or uppercase styling to guide the eye through complex layouts.

## Layout & Spacing

The system employs a **Fixed Grid** layout for desktop environments to maintain a controlled reading width for forms, centered within the viewport. 

- **Desktop (1024px+):** 12-column grid with 24px gutters and a 1200px maximum container width. 
- **Tablet (768px - 1023px):** 8-column grid with 20px gutters and 32px side margins.
- **Mobile (<767px):** 4-column fluid grid with 16px gutters and 16px margins.

Vertical rhythm is based on an 8px base unit. Spacing between form fields should be consistently 24px, while related groups of information (sections within a card) should be separated by 32px.

## Elevation & Depth

Visual hierarchy is conveyed through **Tonal Layers** and **Ambient Shadows**. The primary background is neutral, while the "work area" (the form container) sits on a white surface elevated by a very soft, diffused shadow (0px 4px 20px rgba(36, 52, 66, 0.08)).

Secondary information, such as sidebars or tooltips, uses subtle borders (`#E2E8F0`) rather than depth to keep the interface feeling flat and efficient. Interactive elements like buttons use a slight upward lift on hover to provide tactile feedback without breaking the professional, utilitarian aesthetic.

## Shapes

The shape language uses a **Rounded** (Level 2) approach. Standard UI elements like input fields, buttons, and progress bars feature a 0.5rem (8px) corner radius. This strikes a balance between the precision of a professional tool and the approachability of a modern service.

Large container cards and application panels use `rounded-xl` (1.5rem / 24px) to frame content softly, while smaller decorative elements like status badges (chips) utilize a full pill-shape for maximum distinction from input fields.

## Components

### Buttons
Primary buttons use a solid **Action Blue** fill with white text. Secondary buttons should use a Slate Deep outline or ghost style. Buttons must maintain a minimum height of 48px to ensure accessibility.

### Input Fields
Inputs are white with a 1px border (`#E2E8F0`). On focus, the border transitions to Action Blue with a 2px outer glow. Labels are placed above the field in `label-md` style for clarity during data entry.

### Cards
Cards are the primary container for application steps. They should feature a white background, the standard soft shadow defined in Elevation, and a padding of 32px to provide breathing room for complex questions.

### Progress Steppers
A horizontal stepper at the top of the application view is essential. Active steps are highlighted in Action Blue, completed steps show a checkmark icon, and upcoming steps are rendered in a light slate gray.

### Status Chips
Used for visa status (e.g., "Pending," "Approved"). These use low-saturation background tints of the primary/tertiary colors with high-contrast text for immediate identification.