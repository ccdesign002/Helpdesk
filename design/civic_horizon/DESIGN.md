---
name: Civic Horizon
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#40484e'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#70787f'
  outline-variant: '#c0c7cf'
  surface-tint: '#10658b'
  primary: '#004967'
  on-primary: '#ffffff'
  primary-container: '#086288'
  on-primary-container: '#a5dbff'
  inverse-primary: '#8bcef9'
  secondary: '#19648f'
  on-secondary: '#ffffff'
  secondary-container: '#8fcdfd'
  on-secondary-container: '#005881'
  tertiary: '#685e3c'
  on-tertiary: '#ffffff'
  tertiary-container: '#b8aa83'
  on-tertiary-container: '#483f20'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c6e7ff'
  primary-fixed-dim: '#8bcef9'
  on-primary-fixed: '#001e2d'
  on-primary-fixed-variant: '#004c6b'
  secondary-fixed: '#cae6ff'
  secondary-fixed-dim: '#8fcdfd'
  on-secondary-fixed: '#001e30'
  on-secondary-fixed-variant: '#004b70'
  tertiary-fixed: '#f1e2b7'
  tertiary-fixed-dim: '#d4c69d'
  on-tertiary-fixed: '#221b02'
  on-tertiary-fixed-variant: '#504627'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a digital standard for regional public service complaint portals, balancing administrative integrity with citizen-first accessibility. The visual language blends Modern Corporate clarity with Humanist Warmth, eliminating institutional opacity in favor of transparency, reliability, and approachability.

### Brand Attributes
- **Authoritative & Trustworthy:** Anchored by balanced proportions, disciplined grids, and structured typographic hierarchy that communicate governance, reliability, and security.
- **Approachable & Empathetic:** Softened edges, generous whitespace, and human-centric color highlights that invite citizens of all digital literacy levels to voice concerns without friction.
- **Efficient & Purposeful:** High-contrast text, clear visual pathways, and decisive status tracking that minimize cognitive load during civic interactions.

### Aesthetic Approach
The interface uses a clean, light-canvas architecture supported by subtle structural borders and micro-depth. Avoid aggressive brutalist outlines or hyper-skeuomorphic widgets; instead, use purposeful elevations, crisp borders, and subtle hue transitions to convey operational readiness and administrative dignity.

## Colors

The palette balances administrative authority with responsive civic engagement. Light mode serves as the primary canvas to ensure standard civic readability and compliance with public accessibility mandates.

### Core Swatches
- **Primary Deep Teal (`#086288`):** The institutional core. Communicates reliability, executive governance, and legal authority. Used for primary interactive actions, high-level navigation, and prominent branding.
- **Secondary Medium Blue (`#4D8DBA`):** The functional complement. Manages secondary actions, table row hover indicators, active tab markers, and informational callouts.
- **Tertiary Accent Warm Cream (`#FFEFC4`):** An empathetic highlight tone. Breaks visual sterility, drawing attention to alerts, citizen tips, and key status notices.
- **Neutral Charcoal (`#1E293B`):** High-density text neutral providing contrast against white and off-white backgrounds without the harshness of pure black.

### Supporting Semantic Tokens
- **Canvas Base:** `#F8F9FA` creates structural separation against pure white cards (`#FFFFFF`).
- **Muted Body Text:** `#64748B` handles metadata, field helper notes, timestamps, and secondary captions.
- **Border & Divide:** `#E2E8F0` delivers hairline separations between data cells, card outlines, and component wrappers.
- **Surface Accent Ice:** `#97D7FF` acts as an interactive focus ring, active badge underlay, and subtle atmospheric wash.

### Status Tones for Public Complaints
- **Baru (Submitted):** Background `#E0F2FE`, Text `#0369A1` (Cyan/Sky)
- **Diverifikasi (Verified):** Background `#E0F7FE`, Text `#0284C7` (Light Teal)
- **Ditugaskan (Assigned):** Background `#EEF2FF`, Text `#4338CA` (Indigo)
- **Diproses (In Progress):** Background `#E0EEF9`, Text `#086288` (Primary Blue)
- **Menunggu Konfirmasi (Pending Confirmation):** Background `#FEF3C7`, Text `#B45309` (Amber/Warm Yellow)
- **Selesai (Resolved):** Background `#DCFCE7`, Text `#15803D` (Emerald Green)
- **Ditolak (Rejected):** Background `#FFE4E6`, Text `#BE123C` (Rose Red)

## Typography

The pairing combines **Plus Jakarta Sans** for display, structural titles, and form labels, with **Inter** for dense transactional bodies, reporting logs, and document text.

### Implementation Principles
- **Editorial Headings:** Use `Plus Jakarta Sans` with tight negative letter tracking (`-0.02em` on large sizes) to evoke authority, structure, and editorial elegance.
- **Documented Narrative Body:** Set long citizen complaints, administrative responses, and formal terms in `Inter` with relaxed line-heights (minimum `1.5x` the font size) to prevent reading fatigue during complex dispute reviews.
- **Interactive UI Labels:** Buttons, input identifiers, table headers, and badges use `Plus Jakarta Sans` in `600` or `700` weights to keep interactive elements crisp against surrounding prose.

## Layout & Spacing

The layout is built on an **8-point spatial system** with a 12-column responsive grid architecture for desktops and structured vertical stacks for mobile devices.

### Grid Specifications
- **Desktop (1200px+):** 12-column fluid grid, max-width `1280px` centered, `1.5rem` (`24px`) gutters, and `2rem` (`32px`) page canvas margins.
- **Tablet (768px - 1199px):** 8-column layout, `1.25rem` (`20px`) gutters, `1.5rem` (`24px`) page canvas margins.
- **Mobile (Below 768px):** 4-column layout, `1rem` (`16px`) gutters, `1rem` (`16px`) horizontal canvas padding.

### Sectioning Philosophy
1. **Administrative Workspace:** Admin tables and triage queues utilize wide viewports up to `1440px` with fixed left rail navigation (`260px`) and flexible data view areas.
2. **Citizen Submission Flow:** Centers all submission inputs inside constrained read-optimized bounds (`max-width: 680px` to `768px`) to minimize cognitive fatigue and streamline document uploads.

## Elevation & Depth

Visual hierarchy uses a refined multi-layered technique: pure `#FFFFFF` structural containers rest on an off-white `#F8F9FA` canvas, outlined by crisp `#E2E8F0` micro-borders and soft ambient shadows.

### Elevation Hierarchy
- **Level 0 (Flat / Canvas):** Applied to the main backdrop (`#F8F9FA`). No shadow, no outline.
- **Level 1 (Surface / Card Container):** Applied to complaint cards, dashboard panels, and administrative tables. 
  - Border: `1px solid #E2E8F0`
  - Shadow: `0 1px 3px 0 rgba(8, 98, 136, 0.03), 0 1px 2px -1px rgba(8, 98, 136, 0.03)`
- **Level 2 (Interactive Hover / Floating Panels):** Applied to active cards on hover, sticky search bars, and dropdown menus.
  - Border: `1px solid #CBD5E1`
  - Shadow: `0 4px 6px -1px rgba(8, 98, 136, 0.06), 0 2px 4px -2px rgba(8, 98, 136, 0.06)`
- **Level 3 (Modals / Overlays):** Applied to detail preview panels, verification modals, and confirmation dialogues.
  - Border: `1px solid #CBD5E1`
  - Shadow: `0 20px 25px -5px rgba(8, 98, 136, 0.1), 0 8px 10px -6px rgba(8, 98, 136, 0.08)`
  - Backdrop Blur: `backdrop-filter: blur(4px); background-color: rgba(30, 41, 59, 0.4)`

## Shapes

The design uses standard **Level 2 Roundedness** to project modern warmth while maintaining civic gravitas. Sharp 90-degree corners are avoided to preserve approachability, while overly spherical shapes are reserved for compact status tags.

### Corner Radius Mapping
- **Input Fields & Buttons:** `rounded-md` (`8px`) creates structured, dependable click targets.
- **Content Cards & Data Tables:** `rounded-xl` (`16px`) delivers clear, approachable containment boundaries for complex tickets.
- **Modals & Dialogs:** `rounded-xl` (`16px`) keeps structural consistency across layered UI surfaces.
- **Badges, Status Pills & Avatar Rings:** `rounded-full` (`9999px`) provides visual contrast against rectangular cards and structural tables.

## Components

### Buttons
- **Primary Action:** Solid background `#086288` (or an ultra-subtle vertical gradient from `#0A6C96` to `#086288`), text `#FFFFFF`, font `Plus Jakarta Sans Semibold`, padding `10px 20px`, radius `8px`. Hover states deepen the fill to `#064F6E` with a micro-elevation (`0 2px 4px rgba(8, 98, 136, 0.2)`).
- **Secondary Action:** Transparent fill with `1.5px` border `#4D8DBA`, text `#086288`. Hover transitions to light tint `#F0F7FB`.
- **Ghost/Tertiary:** No border, text `#086288`. Hover adds an ultra-light tint `#F1F5F9`.

### Status Badges (Pills)
- Height: `24px` to `28px`.
- Padding: `4px 12px`.
- Shape: Full capsule pill (`rounded-full`).
- Text Style: `label-sm` (`11px` / `Plus Jakarta Sans Bold` / uppercase tracking `0.03em`).
- Visual Configuration: Pale background paired with dark, high-contrast text conforming to the WCAG AAA standard. Include a `6px` solid circle indicator preceding the status text for quick visual scanning.

### Input Fields & Controls
- **Text Inputs & Textareas:** Background `#FFFFFF`, border `1px solid #E2E8F0`, corner radius `8px`, font `Inter 14px`, text `#1E293B`.
- **Placeholder Text:** `#94A3B8`.
- **Focus State:** Border `#086288`, box-shadow `0 0 0 3px rgba(151, 215, 255, 0.45)` (Accent Soft Light Blue halo).
- **Checkboxes & Radios:** Unchecked border `#CBD5E1`. Checked background `#086288` with white checkmark/dot. Focus state triggers the primary brand outline.

### Complaint Cards
- Container: Base `#FFFFFF`, border `1px solid #E2E8F0`, radius `16px`, padding `20px`.
- Layout: Top bar displays Ticket ID (`#64748B`, monospace tracking) and Status Pill. The middle area contains the Subject Heading (`headline-sm`, `#1E293B`) and a 2-line truncated complaint preview (`body-md`, `#64748B`). The bottom bar holds Category metadata, Location tag, and Citizen submission timestamp.

### Administrative Data Table
- **Header:** Background `#F8F9FA`, bottom border `2px solid #E2E8F0`, typography `label-md` uppercase, text `#64748B`.
- **Row Styling:** Minimum height `56px`, horizontal cell padding `16px 20px`, alternating rows unified in white with light hover state `#F1F8FC`.
- **Action Column:** Structured split actions featuring a "Tinjau" (Review) quick action alongside an ellipsis menu trigger for deeper administrative workflows.