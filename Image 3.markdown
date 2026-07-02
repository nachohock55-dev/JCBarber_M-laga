---
name: Monochrome Architectural
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4c4546'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1c1c'
  on-tertiary-container: '#838484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 72px
    fontWeight: '900'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
This design system embodies a rigorous minimalist philosophy, prioritizing structural clarity and high-contrast visuals. The brand personality is sophisticated, authoritative, and unapologetically modern, drawing heavy inspiration from contemporary architectural journals and high-end editorial design.

The aesthetic is characterized by:
- **Absolute Contrast:** A strict black-and-white palette that removes the distraction of color to focus on form and function.
- **Architectural Layout:** Precision-engineered alignment and generous whitespace that creates a sense of luxury through "breathing room."
- **Typography as Hero:** Large, bold typographic statements that serve as both content and primary visual ornament.
- **Sharp Precision:** A preference for clean lines and rhythmic repetition over soft or organic shapes.

## Colors
The palette is restricted to a binary high-contrast range. By eliminating hue, we force the user's focus onto hierarchy and content.

- **Primary (#000000):** Used for all primary text, heavy borders, and high-emphasis action buttons.
- **Secondary (#FFFFFF):** The primary canvas color. It must be pure white to ensure maximum contrast.
- **Tertiary (#F5F5F5):** A very light gray used exclusively for subtle section backgrounds or "ghost" containers to prevent visual fatigue.
- **Neutral (#1A1A1A):** A slightly off-black used for secondary text or hover states on dark elements to maintain depth.

No gradients, transparency, or metallic accents are permitted. Functional colors (Success/Error) should be used sparingly and only as small indicators, never as primary surface colors.

## Typography
Montserrat is utilized here in its most geometric and bold expressions. The type scale is dramatic to create a clear informational hierarchy.

- **Display & Headlines:** Use heavy weights (700-900) with tight letter spacing for a high-impact, "ink-heavy" look.
- **Body Text:** Use 400 weight with generous line heights (1.6) to ensure legibility against the high-contrast background.
- **Labels:** Always use uppercase with increased letter spacing (tracking) for a technical, architectural feel.
- **Anti-Aliasing:** Ensure font-smoothing is enabled to keep the sharp edges of the geometric sans-serif crisp.

## Layout & Spacing
The system utilizes a **fixed-column grid** for desktop and a **fluid grid** for mobile. The layout is influenced by "Swiss Style" design—highly structured and predictable.

- **Desktop Layout:** 12-column grid with a maximum content width of 1280px. Gutters are fixed at 24px to maintain a rhythmic vertical "seam."
- **Mobile Layout:** 4-column fluid grid with 20px side margins. 
- **Spacing Rhythm:** All spacing must be multiples of 4px. Use aggressive whitespace (48px+) between major sections to emphasize the "minimalist" aspect.
- **Alignment:** Strict left-alignment for all text blocks. Centered text should be reserved only for display headers or hero callouts.

## Elevation & Depth
In this design system, depth is communicated through **layering and outlines** rather than shadows. 

- **Tonal Layers:** Use the Tertiary Gray (#F5F5F5) to pull elements forward against the White (#FFFFFF) background. 
- **Bold Borders:** Use 1px or 2px solid black borders to define containers. This creates a "blueprint" or "wireframe" aesthetic that is clean and intentional.
- **No Shadows:** Soft ambient shadows are strictly prohibited. If an element must float (e.g., a modal), use a thick 4px black offset border (hard shadow) to mimic a physical layer.
- **Interactions:** Elevation change on hover is signaled by inverted colors (Black background with White text) rather than a lifting shadow.

## Shapes
This design system utilizes a **Sharp (0)** roundedness level. All corners are 0px radius.

The use of 90-degree angles reinforces the architectural, structural nature of the brand. This applies to buttons, input fields, cards, and images. Circles are only permitted for icon backgrounds or status indicators where a square would be confusing.

## Components
Consistent styling across components ensures the high-contrast aesthetic remains functional and accessible.

- **Buttons:**
  - *Primary:* Solid black background, white text, 0px radius, uppercase label.
  - *Secondary:* Transparent background, 2px black border, black text.
  - *Hover:* Full inversion of colors.
- **Input Fields:** 1px black bottom-border only (minimalist style) or a full 1px black box. Labels are always small, uppercase, and positioned above the field.
- **Cards:** Defined by a 1px solid black border or a subtle light gray (#F5F5F5) background fill. No shadows.
- **Chips/Tags:** Small, sharp-cornered boxes with a 1px border. 
- **Lists:** Separated by 1px horizontal dividers that span the full width of the container. Use large "Index Numbers" (e.g., 01, 02, 03) in bold Montserrat to emphasize list items.
- **Checkboxes/Radios:** Square boxes with 0px radius. When active, they are filled solid black with a white "X" or checkmark.