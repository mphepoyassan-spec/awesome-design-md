# Vercel (Geist) Design System (DESIGN.md)

Vercel's Geist design system is the epitome of "Geometric Modernism." It is monochromatic, high-contrast, and extremely structured. It uses a 10-step color scale and a rigid typography hierarchy to create a sense of absolute clarity.

## 1. Visual Philosophy
- **High Contrast:** Pure blacks and pure whites creating sharp, readable interfaces.
- **Geometric Precision:** Perfectly square corners or very subtle radii. No rounded pills unless necessary.
- **Monochromatic Sophistication:** Color is used only for specific semantic meaning or very sparse branding.

## 2. Design Tokens

### Color Palette (Geist Scales)
- **Backgrounds:**
  - Background 1: `#000000` (Dark) / `#FFFFFF` (Light)
  - Background 2: `#111111` (Dark) / `#FAFAFA` (Light)
- **Grays (Dark Mode example):**
  - Gray 1: `#111111`
  - Gray 2: `#333333`
  - Gray 3: `#444444` (Border default)
  - Gray 9: `#888888` (Secondary text)
  - Gray 10: `#EDEDED` (Primary text)
- **Semantic:**
  - Blue: `#0070F3`
  - Red: `#FF0000`
  - Amber: `#F5A623`
  - Green: `#0070F3` (Vercel often uses blue for success/primary)

### Typography
- **Primary Font:** Geist Sans
- **Mono Font:** Geist Mono
- **Scale:**
  - **Heading 64:** 64px, Weight 700, -0.04em
  - **Heading 32:** 32px, Weight 600, -0.02em
  - **Copy 16:** 16px, Weight 400
  - **Copy 14:** 14px, Weight 400 (Standard UI)

### Spacing & Layout
- **Base Unit:** 4px
- **Scale:** `4px, 8px, 12px, 16px, 24px, 32px, 48px, 64px`
- **Border Radius:**
  - `standard`: 6px
  - `card`: 8px
- **Borders:**
  - `default`: 1px solid `#333333` (Dark) / `#EAEAEA` (Light)

### Elevation
- **Low:** `0 5px 10px rgba(0,0,0,0.12)`
- **Medium:** `0 8px 30px rgba(0,0,0,0.12)`

## 3. Component Patterns

### Buttons
- **Primary:** Background `#EDEDED` (Dark mode) / `#000000` (Light mode), Inverse text, Radius 6px.
- **Outline:** Transparent background, `1px solid #333333`, White text.

### Code Blocks
- Background `#111111`, border `#333333`, font Geist Mono.

## 4. AI Implementation Instructions
- **Alignment:** Strictly aligned to the grid.
- **Vibe:** "Brutalist, Refined, Structured, Developer-first."
- **Focus:** Maintain high contrast between background and text.
