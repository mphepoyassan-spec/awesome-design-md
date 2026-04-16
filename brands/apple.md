# Apple Design System (DESIGN.md)

Apple's design philosophy is built on "Extreme Restraint." It emphasizes content over interface, utilizing premium whitespace, subtle depth, and system-native typography to create a sense of effortless quality.

## 1. Visual Philosophy
- **Deference:** The interface should never compete with the content.
- **Clarity:** Every element has a clear purpose and hierarchy.
- **Depth:** Use of "Vibrancy" (blur/transparency) to establish layers and context.
- **Fluidity:** Smooth transitions and physics-based motion.

## 2. Design Tokens

### Color Palette (System Colors)
- **Backgrounds:**
  - Light: `#FFFFFF`
  - Dark: `#000000`
  - Secondary (Light): `#F2F2F7`
  - Secondary (Dark): `#1C1C1E`
- **Primary Accent:**
  - Apple Blue: `#007AFF`
- **Text:**
  - Primary (Light): `#000000` (85-90% opacity)
  - Primary (Dark): `#FFFFFF`
  - Secondary (Light): `#8E8E93`
  - Secondary (Dark): `#8E8E93`
- **Semantic:**
  - Success: `#34C759`
  - Warning: `#FF9500`
  - Destructive: `#FF3B30`

### Typography
- **Primary Font:** San Francisco (System)
- **Tracking:** Dynamic (tighter for large text, looser for small)
- **Scale:**
  - **Large Title:** 34px, Weight 700
  - **Title 1:** 28px, Weight 600
  - **Headline:** 17px, Weight 600
  - **Body:** 17px, Weight 400
  - **Caption:** 12px, Weight 400

### Spacing & Layout
- **Base Unit:** 8px
- **Border Radius:**
  - `standard`: 10px - 12px (Squircle/Continuous curvature)
  - `large`: 20px (Cards)
- **Whitespace:** Extremely generous vertical padding (64px - 128px between sections).

### Elevation & Effects
- **Materials:** Background Blur (10px - 20px) with 70% opacity.
- **Shadow:** `0 4px 24px rgba(0, 0, 0, 0.08)` (Very soft, almost imperceptible).

## 3. Component Patterns

### Buttons
- **Primary:** Background `#007AFF`, White text, Radius 10px-12px.
- **Plain:** Only text in Blue `#007AFF` (no border/background).

### Cards
- White background, no border, soft shadow, radius 20px.

## 4. AI Implementation Instructions
- **Alignment:** Center-aligned layouts are common for marketing/heroes.
- **Font:** Use `-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif`.
- **Vibe:** "Airy, Premium, Quiet, High-end."
- **Focus:** If in doubt, add more whitespace.
