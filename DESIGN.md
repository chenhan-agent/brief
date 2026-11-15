---
version: alpha
name: Brief Deals - Stitch Design System
description: High-signal, clean, modern design system for Brief Deals aggregator inspired by Google Stitch.

colors:
  primary: "#2563eb"
  primary-hover: "#1d4ed8"
  primary-light: "#eff6ff"
  background: "#f8fafc"
  surface: "#ffffff"
  surface-subtle: "#f1f5f9"
  surface-hover: "#f8fafc"
  border: "#e2e8f0"
  border-strong: "#cbd5e1"
  text-primary: "#0f172a"
  text-body: "#334155"
  text-muted: "#64748b"
  steam-bg: "#ecfdf5"
  steam-text: "#065f46"
  steam-border: "#a7f3d0"
  toy-bg: "#fdf2f8"
  toy-text: "#9d174d"
  toy-border: "#fbcfe8"
  flight-bg: "#faf5ff"
  flight-text: "#6b21a8"
  flight-border: "#e9d5ff"
  hotel-bg: "#fffbeb"
  hotel-text: "#92400e"
  hotel-border: "#fde68a"
  tech-bg: "#eff6ff"
  tech-text: "#1e40af"
  tech-border: "#bfdbfe"

typography:
  h1:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', 'PingFang TC', 'Noto Sans TC', sans-serif"
    fontSize: "32px"
    fontWeight: 800
    lineHeight: 1.25
    letterSpacing: "-0.02em"
  h2:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', 'PingFang TC', 'Noto Sans TC', sans-serif"
    fontSize: "18px"
    fontWeight: 700
    lineHeight: 1.45
    letterSpacing: "-0.01em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', 'PingFang TC', 'Noto Sans TC', sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.65
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Segoe UI', 'PingFang TC', 'Noto Sans TC', sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.5

rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  full: "9999px"

spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  xxl: "48px"

components:
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-body}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "#ffffff"
    rounded: "{rounded.md}"
    padding: "8px 16px"
  badge-hero:
    backgroundColor: "{colors.primary-light}"
    textColor: "{colors.primary}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "4px 12px"
  search-bar:
    backgroundColor: "{colors.background}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "10px 14px"
  filter-pill:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-body}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "6px 14px"
  tag-steam:
    backgroundColor: "{colors.steam-bg}"
    textColor: "{colors.steam-text}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "3px 10px"
  tag-toy:
    backgroundColor: "{colors.toy-bg}"
    textColor: "{colors.toy-text}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "3px 10px"
  tag-flight:
    backgroundColor: "{colors.flight-bg}"
    textColor: "{colors.flight-text}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "3px 10px"
  tag-hotel:
    backgroundColor: "{colors.hotel-bg}"
    textColor: "{colors.hotel-text}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "3px 10px"
  tag-tech:
    backgroundColor: "{colors.tech-bg}"
    textColor: "{colors.tech-text}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "3px 10px"
---

## Overview
Brief Deals Design System is an AI-native design system built on Google Stitch principles. It prioritizes clarity, content hierarchy, and immediate scanability for high-signal discount information. Every visual treatment emphasizes signal-to-noise ratio: eliminating distractions, highlighting concrete savings, and conveying timeliness.

## Colors
- **Primary (`#2563eb`) & Primary Light (`#eff6ff`)**: Used for branding, active states, and focal actions.
- **Surface (`#ffffff`) & Background (`#f8fafc`)**: Neutral background hierarchy creating clean separation between layout canvas and interactive deal cards.
- **Text Primary (`#0f172a`) & Text Body (`#334155`)**: High-contrast typography ensuring effortless readability under all lighting conditions.
- **Category Semantic Accents**:
  - `steam` (Emerald/Green): Represents gaming value and historical low discounts.
  - `toy` (Pink/Rose): Collectibles, LEGO exhibitions, and toys.
  - `flight` (Purple/Violet): Bug fares and airline promotions.
  - `hotel` (Amber/Yellow): Hotel vouchers and travel accommodations.
  - `tech` (Indigo/Blue): Durable electronics and appliances.

## Typography
Use the native platform sans-serif stack (`-apple-system`, `PingFang TC`, `Noto Sans TC`) for zero web-font latency and crisp rendering on high-DPI displays.
- **H1**: Bold page hero header with slight negative letter spacing.
- **H2**: Card titles, structured for 2-line maximum scannability.
- **Body & Caption**: Clear, tabular-number-friendly typography for prices, timestamps, and deal quotes.

## Layout & Spacing
Built on a consistent 4px/8px modular scale (`xs: 4px`, `sm: 8px`, `md: 16px`, `lg: 24px`, `xl: 32px`).
Cards are organized in an adaptive CSS Grid with responsive columns (1 column on mobile, 2 columns on tablet/desktop, max container width 960px).

## Elevation & Depth
Stitch emphasizes subtle, tactile elevation rather than heavy drop shadows:
- **Level 0 (Flat)**: Background and subtle containers.
- **Level 1 (Card default)**: `box-shadow: 0 1px 3px rgba(0,0,0,0.04), 0 1px 2px rgba(0,0,0,0.02);` with a crisp `1px solid var(--border)` boundary.
- **Level 2 (Card hover)**: `box-shadow: 0 10px 25px -5px rgba(0,0,0,0.06), 0 8px 10px -6px rgba(0,0,0,0.03);` accompanied by a smooth `translateY(-2px)` elevation.

## Shapes
- `sm` (4px): Subtle micro-controls and inner borders.
- `md` (8px): Action buttons, inputs, and search fields.
- `lg` (12px): Standard deal cards and control panels.
- `full` (9999px): Category tags, filter pills, and live indicator badges.

## Components
### Deal Card
The atomic unit of the dashboard. Contains header metadata (category tag + post timestamp), bold title, highlight badge (e.g. -90% 史低), summary description, quoted original post context, and external action link.

### Live Status Indicator
A header badge featuring an animated pulse dot (`#10b981`) and human-readable last-updated timestamp alongside the 7-day rolling window policy.

### Filter Pills & Search Input
Fast, tactile client-side controls providing zero-latency filtering by category and instant full-text search across titles, descriptions, and quotes.

## Do's and Don'ts
- **Do**: Always display exact post timestamps and concrete savings percentages.
- **Do**: Ensure all category tags maintain high color contrast with WCAG AA compliance.
- **Don't**: Introduce heavy dark shadows, loud animated banners, or intrusive ads.
- **Don't**: Clutter cards with irrelevant diary text or unverified discount claims.
