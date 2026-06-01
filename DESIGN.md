---
name: Velocity Logistics System
colors:
  surface: '#f9f9fc'
  surface-dim: '#dadadc'
  surface-bright: '#f9f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f6'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e5'
  on-surface: '#1a1c1e'
  on-surface-variant: '#43474f'
  inverse-surface: '#2f3133'
  inverse-on-surface: '#f0f0f3'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#1b1f21'
  on-tertiary: '#ffffff'
  tertiary-container: '#303436'
  on-tertiary-container: '#999c9f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e0e3e6'
  tertiary-fixed-dim: '#c3c7ca'
  on-tertiary-fixed: '#181c1e'
  on-tertiary-fixed-variant: '#43474a'
  background: '#f9f9fc'
  on-background: '#1a1c1e'
  surface-variant: '#e2e2e5'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Montserrat
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
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

The visual identity of the design system is anchored in **Corporate Modernism** with a focus on "Precision in Motion." It targets B2B and consumer clients in the Greater Toronto Area who prioritize punctuality and professional handling. 

The aesthetic is clean, high-contrast, and utilitarian, evoking an emotional response of stability and forward momentum. By utilizing expansive whitespace and a structured grid, the interface mirrors the efficiency of a well-oiled logistics network. Visual cues like speed lines and directional shifts—inspired by the provided vehicle livery—are translated into the UI through subtle motion patterns and sharp, intentional angles.

## Colors

This design system utilizes a high-visibility palette optimized for legibility and brand recognition.

- **Primary (Deep Navy):** Used for core branding, navigation backgrounds, and primary headings to establish authority.
- **Secondary (Vibrant Orange):** Reserved for high-priority actions, status indicators (e.g., "In Transit"), and accents that signify "speed" and "urgency."
- **Backgrounds:** A crisp white (#FFFFFF) is the primary canvas, supported by a light cool-grey tertiary (#F4F7FA) for sectioning content and dashboard cards.
- **Success/Error:** While adhering to the brand palette, use standard semantic greens and reds, but keep them slightly desaturated to maintain the professional tone.

## Typography

The typography strategy pairs **Montserrat** for display roles with **Inter** for functional reading.

- **Headlines:** Montserrat’s geometric construction provides a modern, architectural feel. Use bold weights to emphasize key value propositions or tracking numbers.
- **Body:** Inter is used for all data-heavy contexts, such as delivery manifests or address forms, ensuring maximum legibility at small sizes.
- **Emphasis:** Speed and movement are reinforced by occasionally using italicized Montserrat for sub-headers or callouts, mimicking the slanted logo style on the delivery fleet.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid** grid. The content is contained within a 1280px max-width wrapper on desktop to maintain readability, while elements within that container scale fluidly.

- **Grid:** A 12-column system is used for desktop, collapsing to 4 columns for mobile devices.
- **Rhythm:** An 8px linear scale governs all padding and margins. 
- **Density:** For logistics dashboards, use a "Compact" density (8px–16px gaps) to display more data. For marketing landing pages, use "Spacious" density (32px–64px gaps) to emphasize the premium nature of the service.

## Elevation & Depth

This design system avoids heavy shadows in favor of **Tonal Layering** and **Structural Outlines**. 

- **Surface Tiers:** Use subtle background color shifts (White to Light Grey) to indicate depth.
- **Outlines:** All containers and cards use a 1px solid border (#E2E8F0) instead of a shadow to maintain a "flat and fast" aesthetic.
- **Active State:** Only the primary action buttons or "active" tracking cards receive a soft, low-opacity Deep Navy shadow (blur: 12px, y: 4px, opacity: 10%) to suggest they are physically interactable.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the "edge" off the industrial nature of logistics without appearing too playful or consumer-grade.

- **Buttons & Inputs:** Use the base `rounded` (4px) setting.
- **Feature Cards:** Use `rounded-lg` (8px) to create a distinct container for content modules.
- **Icons:** Use sharp or slightly rounded geometric icons. Avoid overly bubbly or hand-drawn styles to keep the brand feeling professional and efficient.

## Components

- **Buttons:** Primary buttons are Solid Deep Navy with White text. Secondary buttons are Outline Deep Navy. The Vibrant Orange is reserved exclusively for the "Track My Delivery" or "Book Now" CTA to drive conversion.
- **Inputs:** Use thick 2px bottom borders or full 1px outlines. Labels should be small, uppercase Inter for a "form-entry" feel common in logistics software.
- **Tracking Chips:** Small pill-shaped badges for status (e.g., "In Warehouse," "Out for Delivery"). Use the secondary orange for "Out for Delivery" to signify active movement.
- **Data Cards:** Use a left-accent border (4px width) in Deep Navy or Orange to categorize different types of shipments or priority levels.
- **Speed Indicators:** Incorporate a horizontal progress bar for tracking that uses a gradient from Deep Navy to Vibrant Orange, representing the journey from start to finish.