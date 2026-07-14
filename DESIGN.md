---
name: Precision & Code
colors:
  surface: '#0d1516'
  surface-dim: '#0d1516'
  surface-bright: '#333a3c'
  surface-container-lowest: '#080f11'
  surface-container-low: '#151d1e'
  surface-container: '#192122'
  surface-container-high: '#242b2d'
  surface-container-highest: '#2e3638'
  on-surface: '#dce4e5'
  on-surface-variant: '#bac9cc'
  inverse-surface: '#dce4e5'
  inverse-on-surface: '#2a3233'
  outline: '#849396'
  outline-variant: '#3b494c'
  surface-tint: '#00daf3'
  primary: '#c3f5ff'
  on-primary: '#00363d'
  primary-container: '#00e5ff'
  on-primary-container: '#00626e'
  inverse-primary: '#006875'
  secondary: '#bec7d6'
  on-secondary: '#28313d'
  secondary-container: '#3e4754'
  on-secondary-container: '#adb6c4'
  tertiary: '#ffeac0'
  on-tertiary: '#3e2e00'
  tertiary-container: '#fec931'
  on-tertiary-container: '#6f5500'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#9cf0ff'
  primary-fixed-dim: '#00daf3'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f58'
  secondary-fixed: '#dae3f2'
  secondary-fixed-dim: '#bec7d6'
  on-secondary-fixed: '#131c27'
  on-secondary-fixed-variant: '#3e4754'
  tertiary-fixed: '#ffdf96'
  tertiary-fixed-dim: '#f3bf26'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#594400'
  background: '#0d1516'
  on-background: '#dce4e5'
  surface-variant: '#2e3638'
  surface-glass: rgba(25, 33, 44, 0.7)
  border-subtle: rgba(255, 255, 255, 0.1)
  qa-pass: '#25D366'
  qa-fail: '#FF4D4D'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  margin-page: clamp(1.5rem, 5vw, 4rem)
  gutter: 1.5rem
  stack-lg: 4rem
  stack-md: 2rem
  stack-sm: 1rem
---

## Brand & Style

This design system is tailored for **Andrian Prayoga**, a Software QA Engineer and Programmer whose work sits at the intersection of technical rigor and high-performance code. The brand personality is **meticulous, futuristic, and authoritative**, reflecting the "zero-bug" mindset of a quality assurance professional.

The visual style is a blend of **Minimalism** and **Glassmorphism**. It utilizes a "Dark Mode" foundation to reduce eye strain (essential for developers) while employing translucent layers to create a sense of digital depth. The aesthetic is high-impact, prioritizing clarity and technical precision through generous whitespace and a sharp, grid-based arrangement.

## Colors

The palette is rooted in a **Sophisticated Dark Theme**. The primary background uses a deep charcoal-gray (`#131D23`), providing a stable, professional base. 

- **Primary:** An "Electric Teal" (`#00E5FF`) is used for critical calls-to-action, progress indicators, and focal points. It represents the "spark" of logic and innovation.
- **Secondary:** A deep navy-gray used for structural containers and card backgrounds.
- **Neutral:** A range of grays from off-white (`#F5FAFF`) for high-readability text to muted slate for secondary metadata.
- **Utility:** Specific colors for QA status indicators (Pass/Fail) are included to reinforce the technical nature of the portfolio.

## Typography

This design system exclusively uses **Inter** to leverage its exceptional legibility and neutral, "engineered" appearance. 

- **Display & Headlines:** Use heavy weights (700-800) with slight negative letter spacing to create a high-impact, editorial feel for project titles and section headers.
- **Body Text:** Set with generous line height (1.5x) to ensure long-form descriptions of QA processes and technical challenges remain approachable.
- **Labels:** Used for technical tags (e.g., "Manual Testing", "API Testing") and status chips, employing uppercase styling and increased letter spacing for a "console-log" aesthetic.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a maximum content width of 1280px. 

1. **Grid Strategy:** A 12-column system is used for desktop. Technical skills are displayed in a 4-column sub-grid, while "Experience" cards span 8 or 12 columns for readability.
2. **Breakpoints:**
   - **Mobile (<768px):** Single column with 24px margins. Headlines scale down automatically.
   - **Tablet (768px - 1024px):** 8-column grid with 32px margins.
   - **Desktop (>1024px):** 12-column grid with 64px+ margins to emphasize the "Minimalist" aesthetic through whitespace.
3. **Rhythm:** Use a consistent 8px base unit for all internal component padding and smaller spatial relationships.

## Elevation & Depth

Depth is conveyed through **Glassmorphism and Tonal Layering** rather than traditional drop shadows.

- **Surface 0:** Main background (`#131D23`).
- **Surface 1 (Floating Cards):** Semi-transparent background (`rgba(25, 33, 44, 0.7)`) with a `20px` backdrop-blur. 
- **The Glow Effect:** High-priority cards (like "Featured Project") use a very subtle, low-opacity outer glow in the primary color (`#00E5FF`) to simulate a backlit terminal screen.
- **Outlines:** All containers use a 1px solid border (`rgba(255, 255, 255, 0.1)`) to define boundaries without adding visual weight.

## Shapes

The design uses a **Rounded** shape language (`0.5rem` base radius). This strikes a balance between the "sharp" nature of code and the "approachable" nature of a personal portfolio.

- **Primary Buttons:** Use the standard `rounded-lg` (1rem) for a distinct, clickable feel.
- **Skill Chips:** Use pill-shaped (full-round) geometry to differentiate them from functional cards.
- **Images/Avatars:** The profile image of Andrian should use a soft 1rem radius to match the card containers.

## Components

### Buttons
- **Primary:** Solid `#00E5FF` background with `#131D23` text. No shadow; high contrast.
- **Secondary/Ghost:** 1px border of `#00E5FF` with transparent background. Subtle hover state with a 10% opacity primary color fill.

### Cards (Experience & Projects)
- Use the **Glassmorphism** style. Include a `label-sm` header for the date range (e.g., "JUNE 2022 - PRESENT").
- Content should be bulleted using the primary color for the bullet points to draw the eye to achievements.

### Skill Chips
- Subtle dark gray background with a 1px border. 
- Include a small icon (Material Symbols) next to key skills like "Java" or "Postman" to increase visual interest.

### Code Snippets / Key Stats
- For technical metrics (e.g., "increased test coverage by 30%"), use a monospaced font variant if possible, or the `display-lg` size in the primary color to make the impact undeniable.

### Input Fields
- For the contact form: Minimalist 1px bottom border only. On focus, the border transitions to the primary color with a subtle glow.