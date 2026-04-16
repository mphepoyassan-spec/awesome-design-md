# Coinbase Design System (DESIGN.md)

Coinbase's design system is "High-Trust Crypto." It aims to make complex financial concepts accessible and safe. It uses a clean, tech-forward blue with professional white backgrounds to create an approachable yet institutional feeling.

## 1. Visual Philosophy
- **Approachable Finance:** Complexity simplified. Use of clear language and visual aids.
- **Safety through Design:** Clean lines and high-contrast elements that suggest security and reliability.
- **Modern Institutionalism:** A professional look that appeals to both retail and institutional investors.

## 2. Design Tokens

### Color Palette
- **Primary Brand:**
  - Coinbase Blue: `#0052FF`
- **Backgrounds:**
  - Surface: `#FFFFFF`
  - Secondary: `#F4F7FA`
- **Text:**
  - Primary: `#0A0B0D`
  - Secondary: `#5B616E`
- **Semantic:**
  - Success: `#05B169`
  - Error: `#DF2E4E`
  - Info: `#0052FF`

### Typography
- **Primary Font:** Coinbase Sans (or Inter/Geist)
- **Scale:**
  - **Hero:** 42px, Weight 700, Tracked -0.02em.
  - **Heading:** 24px, Weight 600.
  - **Body:** 16px, Weight 400.
  - **Caption:** 14px, Weight 400.

### Spacing & Layout
- **Base Unit:** 8px
- **Border Radius:**
  - `standard`: 8px
  - `large`: 16px (Modals/Large Cards)
- **Borders:**
  - `soft`: 1px solid `#ECEFF1`

### Elevation & Effects
- **Shadow:** `0 12px 24px rgba(0,0,0,0.05)` (Extremely subtle, professional).
- **Glass:** Soft blurring for navigation bars.

## 3. Component Patterns

### Buttons
- **Primary:** Background `#0052FF`, White text, Radius 8px-100px (Pill).
- **Secondary:** Background `#F4F7FA`, Text `#0052FF`.

### Asset Cards
- Large icons (32px), Bold symbol, Price trend line (green/red sparkline).

## 4. AI Implementation Instructions
- **Theme:** Default to Light Mode.
- **Vibe:** "Clean, Secure, Professional, Modern."
- **Interaction:** Clear feedback for financial actions; no "game-like" animations.
- **Focus:** Use plenty of whitespace around data points.
