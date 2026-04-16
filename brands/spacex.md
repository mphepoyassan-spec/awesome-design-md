# SpaceX Design System (DESIGN.md)

SpaceX's design system is "Mission-Critical Minimalism." It is brutalist, futuristic, and purely functional. It reflects the aesthetics of aerospace engineering—high-contrast, monochromatic, and focused on data accuracy.

## 1. Visual Philosophy
- **Aerospace Functionalism:** Every element is designed for maximum legibility in high-stress environments.
- **Futuristic Brutalism:** Stark blacks, whites, and occasional technical blues.
- **Data over Decoration:** No unnecessary shadows or gradients. Pure information density.

## 2. Design Tokens

### Color Palette
- **Backgrounds:**
  - True Black: `#000000`
  - Deep Space: `#0F1112`
  - Slate Gray: `#181C1F`
- **Text:**
  - Primary: `#FFFFFF`
  - Secondary: `#A7A9AC` (Metallic Silver)
- **Accents:**
  - Mission Blue: `#005288`
- **Semantic:**
  - Nominal: `#FFFFFF` (White)
  - Critical: `#FF0000` (Red)

### Typography
- **Primary Font:** Custom Sans-Serif (Industry/Roboto/Inter)
- **Style:** Monospaced and bold weights preferred.
- **Scale:**
  - **Header:** 36px+, Weight 900, All-caps.
  - **Label:** 12px, Weight 700, All-caps, Tracked out (+0.1em).
  - **Body/Data:** 14px-16px, Weight 400.

### Spacing & Layout
- **Base Unit:** 10px (A more rigid, "engineering" scale)
- **Border Radius:**
  - `none`: 0px (Sharp corners for a more industrial feel)
  - `micro`: 2px
- **Borders:**
  - `technical`: 1px solid `#FFFFFF` or `#A7A9AC`

### Elevation & Effects
- **Shadow:** None (Space has no soft shadows).
- **Glass:** High-transparency dark overlays for "HUD" (Heads-Up Display) feel.

## 3. Component Patterns

### Buttons
- **Primary:** White background, Black text, All-caps, Sharp corners.
- **Outline:** `1px solid #FFFFFF`, White text, No background.

### Data Tables / HUD
- Thin borders, high contrast, monospaced numbers, all-caps labels.

## 4. AI Implementation Instructions
- **Theme:** Dark Mode Only.
- **Vibe:** "Cold, Precise, Technical, Ambitious."
- **Interaction:** Instant state changes (no slow transitions).
- **Focus:** If it looks like a cockpit display or a technical blueprint, it's correct.
