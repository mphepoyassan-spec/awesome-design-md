# Notion Design System (DESIGN.md)

Notion's design system is "Warm Minimalism." It feels less like a software application and more like a high-quality paper workspace. It uses warm tones, organic accents, and flexible typography to create an inviting environment.

## 1. Visual Philosophy
- **Warm White:** Avoiding harsh blacks and whites for softer, more natural tones.
- **Organic Accents:** Use of hand-drawn icons and soft illustrations.
- **Content is King:** The UI is almost invisible until needed.
- **Flexible Context:** Support for different typography (Sans, Serif, Mono) per page.

## 2. Design Tokens

### Color Palette
- **Backgrounds:**
  - Base: `#FFFFFF`
  - Warm White: `#F6F5F4` (Sidebar/Background alternation)
  - Hover: `#EFEFEF`
- **Text:**
  - Primary: `#37352F` (Near black, but warm)
  - Secondary: `#757575`
- **Accents:**
  - Notion Blue: `#2383E2`
  - Notion Gray: `#A39E98`
- **Semantic:**
  - Red: `#EB5757`
  - Green: `#448361`
  - Yellow: `#D9730D`

### Typography
- **Primary Fonts:**
  - Sans: Inter / Segoe UI
  - Serif: Lyon-Text
  - Mono: IA Writer Duo
- **Scale:**
  - **H1:** 40px, Weight 700, `#37352F`
  - **H2:** 30px, Weight 600
  - **Body:** 16px, Weight 400
  - **Small:** 14px, Weight 400

### Spacing & Layout
- **Base Unit:** 8px
- **Scale:** `2px, 4px, 8px, 12px, 16px, 24px, 32px`
- **Border Radius:**
  - `standard`: 3px (Very subtle)
  - `card`: 12px (For feature cards on marketing pages)
- **Borders:**
  - `whisper`: 1px solid `rgba(55, 53, 47, 0.09)`

### Elevation
- **Soft Border:** `1px solid rgba(0, 0, 0, 0.1)`
- **Shadow:** `0 2px 4px rgba(0, 0, 0, 0.05)`

## 3. Component Patterns

### Buttons
- **Primary CTA:** Background `#2383E2`, White text, Radius 4px.
- **Ghost:** Transparent, Text `#37352F`, Hover background `#EFEFEF`.

### Callouts
- Background `#F1F1EF`, 4px radius, emoji icon left-aligned.

## 4. AI Implementation Instructions
- **Theme:** Default to Light Mode.
- **Typography:** Use Serif for headings and Sans for body to match the "Editorial" feel.
- **Vibe:** "Friendly, Organic, Productive, Calm."
- **Focus:** Use `#F6F5F4` for sidebars or secondary containers to create soft separation.
