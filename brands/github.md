# GitHub (Primer) Design System (DESIGN.md)

GitHub's Primer design system is "Code-Forward Clarity." It is designed for maximum utility, version control workflows, and developer productivity. It uses a neutral, highly structured layout with a focus on information density and accessibility.

## 1. Visual Philosophy
- **Information Density:** Optimized for developers who need to see large amounts of code and data at once.
- **System-Native Feel:** UI that feels like part of the developer's OS or IDE.
- **Accessibility First:** Strong emphasis on high contrast, keyboard navigation, and clear semantic states.
- **Trust and Reliability:** Predictable patterns and stable visual hierarchy.

## 2. Design Tokens

### Color Palette (Primer Light/Dark)
- **Backgrounds:**
  - Default: `#0D1117` (Dark) / `#FFFFFF` (Light)
  - Muted: `#161B22` (Dark) / `#F6F8FA` (Light)
- **Borders:**
  - Default: `#30363D` (Dark) / `#D0D7DE` (Light)
- **Accents:**
  - GitHub Blue: `#1F6FEB` (Dark) / `#0969DA` (Light)
- **Text:**
  - Primary: `#C9D1D9` (Dark) / `#1F2328` (Light)
  - Secondary: `#8B949E` (Dark) / `#656D76` (Light)
- **Semantic:**
  - Success: `#238636`
  - Warning: `#D29922`
  - Danger: `#F85149`
  - Open: `#3FB950`
  - Merged: `#8957E5`

### Typography
- **Primary Font:** -apple-system, BlinkMacSystemFont, "Segoe UI", Inter, Helvetica, Arial, sans-serif
- **Mono Font:** ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace
- **Scale:**
  - **H1:** 32px, Weight 600
  - **H3:** 20px, Weight 600
  - **Body:** 14px, Weight 400 (Dense)
  - **Code:** 12px

### Spacing & Layout
- **Base Unit:** 4px (8px, 16px, 24px, 32px)
- **Border Radius:**
  - `standard`: 6px
  - `large`: 12px (Cards/Containers)
- **Grid:** Rigid 12-column grid or flexible flex-based layouts for repository views.

### Elevation
- **Shadow:** `0 8px 24px rgba(1,4,9,0.2)` (Dark mode)
- **Border Focus:** `0 0 0 3px rgba(31,111,235,0.3)`

## 3. Component Patterns

### Buttons
- **Primary:** Background `#238636` (Green), White text, Radius 6px, Subtle inner shadow.
- **Default:** Background `#21262D`, Border `#30363D`, Text `#C9D1D9`.

### Repository Cards
- Rounded borders, 14px title in bold Blue, metadata labels (Star, Language) in 12px secondary text.

## 4. AI Implementation Instructions
- **Alignment:** Use consistent 8px/16px padding.
- **Vibe:** "Functional, Reliable, Technical, Open-Source."
- **Interaction:** Favor instant responses and clear visual focus indicators.
- **Focus:** If it looks like it belongs on GitHub.com, it's correct.
