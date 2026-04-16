# Linear Design System (DESIGN.md)

Linear's design system is the benchmark for "Engineer Aesthetic." It is ultra-minimal, high-precision, and focused on speed and focus. It favors dark themes with subtle, electric accents.

## 1. Visual Philosophy
- **Focus & Speed:** Elimination of unnecessary decoration. Fast interactions, keyboard-first feel.
- **Precision Minimalism:** Thin lines (0.5px - 1px), tight letter-spacing, and perfectly aligned components.
- **Electric Dark Mode:** Deep blacks and grays punctuated by vibrant purple and neon accents.

## 2. Design Tokens

### Color Palette
- **Backgrounds:**
  - Base: `#0C0C0E` (True dark)
  - Surface: `#161618` (Cards/Modals)
  - Elevated: `#222224`
- **Brand/Accent:**
  - Linear Purple: `#5E6AD2`
  - Purple Glow: `rgba(94, 106, 210, 0.15)`
- **Text:**
  - Primary: `#F7F8F8` (Off-white)
  - Secondary: `#8A8F98` (Muted gray)
  - Tertiary: `#4B4E54`
- **Semantic:**
  - Success: `#4ADE80` (Green)
  - Warning: `#FACC15` (Yellow)
  - Error: `#F87171` (Red)

### Typography
- **Primary Font:** Inter (Sans-serif)
- **Letter Spacing:** -0.011em (Tight for professional feel)
- **Scale:**
  - **Hero:** 48px-64px, Weight 700, Tracking -0.04em
  - **Section Title:** 24px, Weight 600
  - **Body:** 14px, Weight 400 (Standard)
  - **Small/Label:** 12px, Weight 500 (Mono for IDs)

### Spacing & Layout
- **Base Unit:** 4px
- **Border Radius:**
  - `standard`: 6px
  - `pill`: 100px
- **Borders:**
  - `subtle`: 1px solid `rgba(255, 255, 255, 0.08)`
  - `divider`: 1px solid `rgba(255, 255, 255, 0.05)`

### Elevation (Shadows & Effects)
- **Shadow:** `0 10px 30px rgba(0, 0, 0, 0.5)`
- **Border Glow:** `inset 0 0 0 1px rgba(255, 255, 255, 0.1)`

## 3. Component Patterns

### Buttons
- **Primary:** Background `#5E6AD2`, Text `#FFFFFF`, Radius 6px, Subtle inner shadow.
- **Ghost:** Background `transparent`, Border `1px solid rgba(255, 255, 255, 0.1)`, Text `#F7F8F8`.

### Sidebar/Nav
- Background `#0C0C0E`, right border `#161618`, icons `#8A8F98`, active state white text with purple left accent.

## 4. AI Implementation Instructions
- **Theme:** Default to Dark Mode.
- **Lines:** Use extremely thin dividers and borders.
- **Vibe:** "Mechanical, Professional, Stealthy, High-performance."
- **Interaction:** Hover states should be subtle (slight background brightening).
