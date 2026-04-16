# Airbnb Design System (DESIGN.md)

Airbnb's design system is "People-First Hospitality." It is designed to feel warm, inviting, and trustworthy. It emphasizes high-quality photography, generous whitespace, and soft, rounded elements to create a sense of comfort and belonging.

## 1. Visual Philosophy
- **Belong Anywhere:** The UI should feel like a global citizen—accessible, friendly, and non-intrusive.
- **Photography-Driven:** The interface acts as a frame for beautiful, high-resolution imagery of homes and experiences.
- **Soft Precision:** Use of rounded corners and soft shadows to remove industrial "hardness."
- **Clarity and Trust:** Bold typography and clear pricing/details to build user confidence.

## 2. Design Tokens

### Color Palette
- **Primary (Brand):**
  - Airbnb Cereal (Coral): `#FF5A5F`
  - Rausch: `#FF385C` (The "active" vibrant red-pink)
- **Backgrounds:**
  - Surface: `#FFFFFF`
  - Secondary: `#F7F7F7`
- **Text:**
  - Primary: `#222222`
  - Secondary: `#717171`
- **Semantic:**
  - Success: `#008A05`
  - Attention: `#FFB400`
  - Error: `#C13515`

### Typography
- **Primary Font:** Circular (Airbnb Cereal)
- **Style:** Clean, geometric, and friendly.
- **Scale:**
  - **Large Title:** 32px, Weight 700
  - **Title:** 22px, Weight 600
  - **Body:** 16px, Weight 400
  - **Small:** 14px, Weight 400
  - **Micro:** 12px, Weight 600 (Bold labels)

### Spacing & Layout
- **Base Unit:** 8px
- **Border Radius:**
  - `standard`: 8px
  - `large`: 12px-16px (Cards, Image containers)
  - `round`: 50% (Avatars)
- **Whitespace:** Very generous. Sections are separated by clear margins and subtle dividers.

### Elevation & Effects
- **Shadow:** `0 6px 16px rgba(0,0,0,0.12)` (Soft and deep for cards).
- **Border:** `1px solid #DDDDDD` (Light and subtle).

## 3. Component Patterns

### Buttons
- **Primary (Search/Book):** Gradient from `#FF385C` to `#BD1E59`, White text, Radius 8px.
- **Secondary:** White background, Black border `1px solid #222222`, Black text.

### Cards (Stay/Experience)
- Top-rounded images (12px), title in bold `#222222`, price at bottom-left, rating at top-right.

## 4. AI Implementation Instructions
- **Images:** Prioritize large, bright, "lifestyle" imagery with `object-fit: cover`.
- **Vibe:** "Friendly, Warm, Professional, Easy-to-use."
- **Focus:** Ensure plenty of vertical rhythm; don't cram elements together.
