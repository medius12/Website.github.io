# Design Specification: Stellar Horizon

## 1. Visual Theme & Palette
- **Primary Background:** `#090d16` (Deep Space Navy)
- **Secondary Background / Cards:** `#111827` (Dark Charcoal Blue)
- **Accent Color:** `#38bdf8` (Cyan / Celestial Glow)
- **Secondary Accent:** `#a855f7` (Nebula Purple for highlights/borders)
- **Text Color:** `#f3f4f6` (Off-white / High contrast)
- **Muted Text:** `#9ca3af` (Starlight Gray)

## 2. Typography
- **Primary Font:** Inter, system-ui, -apple-system, sans-serif
- **Headings:** Bold weight (700), clean line spacing, slight letter-spacing on section headers.
- **Body Text:** Regular weight (400), 16px base size, 1.6 line height.

## 3. Page Structure & Components
- **Header Navigation:** Fixed/sticky dark top bar with title link on the left and smooth-scroll anchor links on the right.
- **Hero Banner:** Centered headline, descriptive subtitle, and a primary call-to-action button linking to the exploration grid.
- **Topic Cards Grid:** Responsive 3-column CSS Grid featuring individual astronomical phenomena with subtle hover transitions.
- **Deep Dive Section:** A two-column split section with a focal highlight box and key observational stats.
- **Footer:** Simple centered copyright banner with repository branding.

## 4. Responsive Rules
- Cards automatically collapse from 3 columns to 1 column on viewport widths under 768px.
- Navigation links scale down padding for smaller screens.