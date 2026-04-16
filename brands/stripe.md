# Stripe Design System (DESIGN.md)

Stripe's design system is synonymous with "Premium Fintech." it is characterized by extreme precision, clean whitespace, and a sophisticated color palette that balances trustworthiness with modern innovation.

## 1. Visual Philosophy
- **Precision Engineering:** Every pixel matters. Borders are thin, shadows are soft but defined, and grids are strictly adhered to.
- **Trust through Clarity:** Information density is handled with generous whitespace and clear typography.
- **Dynamic Elegance:** Subtle gradients and vibrant accents (Indigo, Cyan) breathe life into a professional framework.

## 2. Design Tokens

### Color Palette
- **Primary (Brand):**
  - Indigo: `#635BFF`
  - Slate: `#0A2540` (Primary text/Dark backgrounds)
- **Backgrounds:**
  - Surface: `#FFFFFF`
  - Container: `#F6F9FC` (Secondary background/Cards)
- **Semantic:**
  - Success: `#00D924`
  - Attention: `#FFB600`
  - Critical: `#DF1B41`
  - Info: `#0073E6`
- **Neutral/Borders:**
  - Keyline: `#E6EBF1`
  - Secondary Text: `#425466`
  - Disabled: `#A3ACBA`

### Typography
- **Primary Font:** Inter (Sans-serif)
- **Scale:**
  - **Heading:** 24px-32px, Weight 600, Tracking -0.02em
  - **Subheading:** 18px-20px, Weight 500
  - **Body:** 16px, Weight 400 (Primary text)
  - **Caption:** 14px, Weight 400 (Secondary text)

### Spacing & Layout
- **Base Unit:** 4px (All spacing should be multiples of 4)
- **Scale:**
  - `xxsmall`: 2px
  - `xsmall`: 4px
  - `small`: 8px
  - `medium`: 16px (Standard gap)
  - `large`: 24px
  - `xlarge`: 32px
  - `xxlarge`: 48px
- **Border Radius:**
  - `small`: 4px (Buttons, Inputs)
  - `medium`: 8px (Cards, Modals)

### Elevation (Shadows)
- **Low:** `0 2px 5px rgba(0,0,0,0.05)`
- **Medium:** `0 7px 14px rgba(50,50,93,0.1), 0 3px 6px rgba(0,0,0,0.08)`
- **High:** `0 15px 35px rgba(50,50,93,0.1), 0 5px 15px rgba(0,0,0,0.07)`

## 3. Component Patterns

### Buttons
- **Primary:** Background `#635BFF`, Text `#FFFFFF`, Radius 4px, Transition 0.15s ease.
- **Secondary:** Background `#F6F9FC`, Text `#0A2540`, Border `#E6EBF1`.

### Cards
- Background `#FFFFFF`, Border 1px solid `#E6EBF1`, Radius 8px, Shadow (Low).

## 4. AI Implementation Instructions
- **Grid:** Use a 12-column flexbox grid with `medium` (16px) gaps.
- **Contrast:** Ensure high contrast for primary text (`#0A2540`) on light backgrounds.
- **Vibe:** "Clean, Professional, Technical, High-trust."
