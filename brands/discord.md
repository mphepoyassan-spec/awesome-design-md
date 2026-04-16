# Discord Design System (DESIGN.md)

Discord's design system is "Playful Community." It is built to facilitate conversation, expression, and gaming. It uses a unique "Blurple" brand color and a complex dark mode to create a cozy but dynamic digital space.

## 1. Visual Philosophy
- **Playful Utility:** The interface is fun and expressive (emojis, reactions) but stays out of the way of the conversation.
- **Deep Immersion:** Multi-layered dark themes that create a "room" or "server" feeling.
- **Dynamic Feedback:** Instant, responsive UI for chat-based interactions.

## 2. Design Tokens

### Color Palette
- **Primary Brand:**
  - Blurple: `#5865F2`
  - Fuchsia: `#EB459E`
- **Backgrounds:**
  - Sidebar: `#2B2D31`
  - Chat Area: `#313338`
  - Hover: `#35373C`
  - Darker (Channel List): `#1E1F22`
- **Text:**
  - Primary: `#F2F3F5`
  - Secondary: `#B5BAC1`
  - Muted: `#949BA4`
- **Semantic:**
  - Online: `#23A559`
  - Idle: `#F0B232`
  - Do Not Disturb: `#F23F43`

### Typography
- **Primary Font:** gg sans (Custom) or Inter
- **Scale:**
  - **Heading:** 20px-24px, Weight 700
  - **Body:** 16px, Weight 400
  - **Small:** 12px, Weight 500
- **Line Height:** 1.375 (Optimized for chat)

### Spacing & Layout
- **Base Unit:** 4px
- **Border Radius:**
  - `standard`: 8px
  - `round`: 50% (Profile pictures)
  - `squircle`: (Special 16px radius for server icons)
- **Grid:** Layout is mostly vertical lists and panels.

### Elevation
- **Low:** `0 2px 4px rgba(0,0,0,0.2)`
- **Border:** Subtle dividers using `#1E1F22`.

## 3. Component Patterns

### Buttons
- **Primary:** Background `#5865F2`, White text, Radius 4px.
- **Link:** Blue text, no background, underline on hover.

### Message Bubbles / Entries
- No bubbles (modern chat style); Hover background change; Left-aligned avatars.

## 4. AI Implementation Instructions
- **Theme:** Default to Dark Mode.
- **Vibe:** "Cozy, Playful, Social, Game-ready."
- **Interaction:** Add subtle hover background shifts for all list items.
- **Focus:** Grouping of elements should be done via background color shifts rather than borders.
