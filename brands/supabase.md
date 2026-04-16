# Supabase Design System (DESIGN.md)

Supabase's design system is "Developer-Centric Excellence." It combines the technical utility of a database tool with a modern, high-polish dark theme. It feels like a high-end IDE for the web.

## 1. Visual Philosophy
- **Technical Utility:** Function over form, but with a form that is incredibly polished.
- **Emerald Precision:** Use of emerald/green accents to suggest growth, success, and "open-source energy."
- **Dashboard Density:** Efficient use of space for data-heavy interfaces.

## 2. Design Tokens

### Color Palette
- **Primary Brand:**
  - Supabase Green: `#3ECF8E`
- **Backgrounds:**
  - Base: `#1C1C1C`
  - Overlay: `#282828`
  - Card/Item: `#232323`
- **Text:**
  - Primary: `#EDEDED`
  - Secondary: `#A0A0A0`
  - Tertiary: `#707070`
- **Semantic:**
  - Success: `#3ECF8E`
  - Warning: `#F5A623`
  - Error: `#FA5252`
  - Info: `#0070F3`

### Typography
- **Primary Font:** Circular (or Inter/Geist)
- **Mono Font:** Source Code Pro (For SQL/JSON)
- **Scale:**
  - **Title:** 30px, Weight 600
  - **Section:** 20px, Weight 500
  - **Body:** 14px, Weight 400
  - **Code:** 13px

### Spacing & Layout
- **Base Unit:** 4px
- **Scale:** `4px, 8px, 12px, 16px, 24px, 32px, 48px`
- **Border Radius:**
  - `standard`: 4px
  - `large`: 8px
- **Borders:**
  - `default`: 1px solid `#303030`

### Elevation
- **Soft Shadow:** `0 4px 6px rgba(0, 0, 0, 0.2)`
- **Border Focus:** `0 0 0 2px rgba(62, 207, 142, 0.2)`

## 3. Component Patterns

### Buttons
- **Primary:** Background `#3ECF8E`, Black text, Radius 4px.
- **Secondary:** Background `#303030`, Text `#EDEDED`, Border `#404040`.

### Database Tables
- Clean borders, zebra striping (subtle background shift), mono text for data.

## 4. AI Implementation Instructions
- **Theme:** Dark Mode.
- **Vibe:** "Productive, Technical, Trustworthy, Open-Source."
- **Focus:** Data presentation should be clean and tabular.
