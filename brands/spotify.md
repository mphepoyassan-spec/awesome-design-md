# Spotify Design System (DESIGN.md)

Spotify's design system is "Immersive Darkness." It is designed to recede and let the vibrant artwork of music and podcasts take center stage. It uses bold typography and a signature green to create a high-energy, media-rich experience.

## 1. Visual Philosophy
- **Media-First:** The UI is a canvas for album art and photography.
- **Bold Immersion:** Use of gradients that "sample" color from images.
- **Vibrant Energy:** Spotify Green on deep blacks creates a "nightclub" or "concert" atmosphere.

## 2. Design Tokens

### Color Palette
- **Primary Brand:**
  - Spotify Green: `#1DB954`
- **Backgrounds:**
  - Base: `#121212` (Off-black)
  - Surface: `#181818`
  - Elevated: `#282828`
- **Text:**
  - Primary: `#FFFFFF`
  - Secondary: `#B3B3B3`
- **Accents:**
  - Pure Black: `#000000`

### Typography
- **Primary Font:** Circular (or Montserrat/Inter)
- **Style:** Bold and geometric.
- **Scale:**
  - **Large Title:** 48px-96px, Weight 900 (Extra Bold)
  - **Section Title:** 24px, Weight 700
  - **Body:** 16px, Weight 400
  - **Metadata:** 12px, Weight 400

### Spacing & Layout
- **Base Unit:** 8px
- **Border Radius:**
  - `standard`: 4px-8px
  - `pill`: 500px (Buttons)
  - `round`: 50% (Profile/Artist images)
- **Grid:** Card-based grid with 16px-24px gaps.

### Effects
- **Gradients:** `linear-gradient(rgba(255,255,255,0.1) 0%, #121212 100%)`
- **Hover Scale:** `scale(1.04)` for album art cards.

## 3. Component Patterns

### Buttons
- **Primary (Play):** Background `#1DB954`, Black text, Pill shape, Scale on hover.
- **Outline:** Border `1px solid #B3B3B3`, White text, Pill shape.

### Playlists / Cards
- Background `#181818`, Radius 8px, Hover background `#282828`, Transition 0.3s.

## 4. AI Implementation Instructions
- **Theme:** Dark Mode Only.
- **Vibe:** "Loud, Immersive, Smooth, Dynamic."
- **Focus:** Use bold, large typography for headers and ensure album art/images have subtle shadows or depth.
