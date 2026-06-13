---
name: Heritage Estate Design System
colors:
  surface: '#141400'
  surface-dim: '#141400'
  surface-bright: '#3b3b1c'
  surface-container-lowest: '#0f0f00'
  surface-container-low: '#1d1d03'
  surface-container: '#212105'
  surface-container-high: '#2b2b0e'
  surface-container-highest: '#363618'
  on-surface: '#e6e5b9'
  on-surface-variant: '#c1c8c2'
  inverse-surface: '#e6e5b9'
  inverse-on-surface: '#323214'
  outline: '#8b938c'
  outline-variant: '#414943'
  surface-tint: '#a2d1b7'
  primary: '#a2d1b7'
  on-primary: '#083825'
  primary-container: '#013220'
  on-primary-container: '#6f9c84'
  inverse-primary: '#3b6751'
  secondary: '#66dd8b'
  on-secondary: '#003919'
  secondary-container: '#25a55a'
  on-secondary-container: '#003115'
  tertiary: '#e9c349'
  on-tertiary: '#3c2f00'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#bdedd2'
  primary-fixed-dim: '#a2d1b7'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#234f3b'
  secondary-fixed: '#83fba5'
  secondary-fixed-dim: '#66dd8b'
  on-secondary-fixed: '#00210c'
  on-secondary-fixed-variant: '#005227'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#141400'
  on-background: '#e6e5b9'
  surface-variant: '#363618'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is anchored in an "Evergreen Luxury" narrative, blending the lush, natural beauty of Pakistani farmhouses with a sophisticated, high-end hospitality aesthetic. The personality is authoritative yet welcoming, emphasizing privacy, nature, and family values.

The visual style is a hybrid of **Minimalism** and **High-Contrast Luxury**. It utilizes heavy whitespace to create a sense of breathing room and exclusivity, while employing metallic gold accents and deep forest tones to ground the experience in a premium feel. The interface avoids all forbidden imagery, focusing instead on architectural details, botanical textures, and the serene geometry of estate landscapes.

## Colors
This design system utilizes a "Deep Forest" palette to evoke a sense of shaded luxury and natural coolness.

*   **Primary (Dark Forest Green):** Used for the primary backgrounds and structural containers. It provides a sense of depth and stability.
*   **Secondary (Emerald Green):** Used for subtle interactive states and to represent growth and vitality in iconography.
*   **Tertiary (Luxury Gold):** Reserved exclusively for accents, call-to-actions, and premium borders. It should be used sparingly to maintain its impact.
*   **Neutral (Cream/White):** Used for primary typography and high-contrast surfaces to ensure readability against the dark background.

## Typography
The typography strategy pairings a classical serif with a modern geometric sans-serif to bridge tradition and modern efficiency.

*   **Headlines:** Utilize *Playfair Display* for all editorial titles and property names. It conveys heritage and sophistication.
*   **Body & UI:** *Montserrat* is used for all functional text, descriptions, and dashboard data. Its geometric clarity ensures legibility across digital interfaces.
*   **Styling Note:** Use "Label Caps" for section headers and small metadata to add an architectural, "stamped" feel to the interface.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop to maintain the "editorial magazine" feel, while transitioning to a fluid model for mobile devices.

*   **Grid:** A 12-column grid is used for desktop layouts, allowing for asymmetrical property showcases.
*   **Rhythm:** An 8px linear scale governs all padding and margins. 
*   **Whitespace:** Be generous with vertical padding (minimum 80px between major sections) to convey a sense of "land" and "space," echoing the farmhouse experience.
*   **Desktop vs Mobile:** On mobile, margins reduce to 16px and multi-column cards stack vertically to maintain focus on property details.

## Elevation & Depth
Elevation in the design system is achieved through **Tonal Layers** and **Subtle Gold Accents** rather than heavy shadows.

*   **Surfaces:** The base background is the darkest Green. Elevated cards use a slightly lighter shade of Green or a semi-transparent overlay to create depth.
*   **Outlines:** Use 1px "Luxury Gold" borders (#D4AF37) at 30% opacity for inactive states and 100% opacity for hover/active states.
*   **Shadows:** When used, shadows should be "Ambient" — extremely soft, using the primary dark green as the shadow tint rather than pure black (e.g., `box-shadow: 0 10px 30px rgba(1, 50, 32, 0.5)`).

## Shapes
The shape language is "Soft-Modern." Elements are predominantly rectangular to reflect architectural stability, but with a slight corner radius to remain approachable for families.

*   **Standard Radius:** 0.25rem (4px) for input fields and small UI elements.
*   **Large Radius:** 0.75rem (12px) for property cards and main containers.
*   **Buttons:** Rectangular with sharp or 2px rounded corners to maintain a professional, high-end look. Avoid pill-shaped buttons.

## Components
Consistent component styling ensures the premium brand narrative is maintained across the farmhouse booking experience.

*   **Luxury Cards:** Property cards should feature a subtle gold border and a "floating" price tag in the corner. Text within cards should be center-aligned or left-aligned with ample padding (24px+).
*   **Booking Inputs:** Modern fields with a "Floating Label" style. The bottom border should turn Gold (#D4AF37) upon focus. Backgrounds should be 5% lighter than the main page background.
*   **Elegant Buttons:** Primary buttons are Gold with White or Dark Green text. Secondary buttons are outlined in Gold. All buttons should have a subtle hover transition (e.g., slight lift or increased border opacity).
*   **Dashboard Style:** The administrative view uses high-contrast typography and thin dividers. Information density is kept low; use cards to group related data points like "Recent Bookings" or "Revenue."
*   **Chips/Tags:** Used for property amenities (e.g., "Swimming Pool," "Prayer Room"). These should be Dark Green with a 1px Cream border and small, clean icons.
*   **Family-Friendly Indicators:** Custom icons for "Kids Area," "Secure Boundary," and "Private Garden" should be rendered in thin-line Gold or Emerald Green.