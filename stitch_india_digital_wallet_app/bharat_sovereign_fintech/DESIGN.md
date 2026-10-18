---
name: Bharat Sovereign FinTech
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#44474d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002113'
  on-tertiary-container: '#009668'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
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
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-numeric:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system targets hundreds of millions of Indian consumers and merchants navigating daily financial transactions—from high-velocity UPI QR micro-payments to Bharat BillPay (BBPS) utility settlements and financial investments. The emotional core must project institutional solidity, bank-grade cryptographic security, and immediate clarity. 

The aesthetic blends **Modern Corporate FinTech** with **Tactile Digital Utility**:
- **Trust-First Architecture**: Avoids gamified clutter in favor of crisp financial data hierarchies, visible security seals, and high-legibility transaction feeds.
- **Speed & Assurance**: Instant visual feedback on every tap, state transitions that reassure users of settlement finality, and unambiguous balance displays.
- **Indian Financial Fluency**: Built from the ground up around the Indian Rupee (₹) symbol hierarchy, standard Indian numbering formatting (Lakhs and Crores), and recognizable national rail iconography (UPI, BBPS, RuPay).

## Colors
The palette balances institutional authority with dynamic transactional clarity across light surfaces.

- **Primary (`#0A192F` - Deep Sovereign Navy)**: The core anchor. Represents institutional trust, security, and permanence. Used for primary app bar surfaces, primary text, prominent header cards, and authoritative authentication states.
- **Secondary (`#2563EB` - Electric Action Blue)**: The interactive trigger. Used for interactive buttons, primary CTAs, active tab indicators, hyperlinked transaction IDs, and navigation rails.
- **Tertiary (`#10B981` - Emerald Growth Green)**: Transactional affirmation. Dedicated strictly to positive wallet credits, UPI payment success indicators, received cashback, and active verification badges.
- **Accent Warm Gold (`#F59E0B`)**: Used selectively for scratch cards, BBPS due alerts, loyalty reward tiers, and promotional cashback banners.
- **Surfaces & Neutrals (`#F8FAFC` base, `#64748B` neutral slate)**: Clean, cool tinted background (`#F8FAFC`) with layered container whites (`#FFFFFF`) to prevent eye fatigue while preserving stark separation between utility cards.

## Typography
The system utilizes **Plus Jakarta Sans** for primary human-interface typography, offering geometric balance with open apertures that remain crisp on entry-level Android panels. 

For transaction reference IDs, UTR numbers, UPI IDs, IFSC strings, and monetary figures, the system pairs **JetBrains Mono** to ensure zero ambiguity between numbers and characters (e.g., `0` vs `O`, `1` vs `l`).

### Indian Rupee (₹) Formatting Rule
- When rendering balances and payment sums, the currency symbol `₹` must match the font-weight of the numeric integer but render at 85% of its font size, aligned to the cap-height of the preceding figure.
- Numeric integers must follow the Indian numbering comma system: `₹12,45,678.00` (groups of two digits after the initial thousand).

## Layout & Spacing
The layout model follows a structured, density-conscious fluid grid engineered for responsive transitions across compact smartphones, standard foldable screens, and tablet merchant dashboards:

- **Mobile Viewport (< 600px)**: 4-column fluid layout with `1rem` outer margins and `0.75rem` column gutters. Core functional grids (such as the quick send/receive actions or BBPS bill categories) adhere to a 4-column icon-matrix.
- **Tablet / Large Mobile (600px - 1024px)**: 8-column layout with `1.5rem` margins and `1rem` gutters. Splits screens into primary balance/transfer flow (5 columns) and recent activity stream (3 columns).
- **Desktop / Merchant Portal (> 1024px)**: 12-column layout capped at a maximum container width of `1200px` centered with variable margins.

All component padding and vertical stacks must align strictly with the 4px baseline sub-rhythm derived from `space-xs` through `space-xl`.

## Elevation & Depth
Elevation conveys transactional security and tactile separation. Flat grey drop-shadows are strictly prohibited; all elevation models incorporate deep navy and slate tinted diffusion.

- **Level 0 (Flat Surface)**: `#F8FAFC` base application background. Used for page view canvases.
- **Level 1 (Card Canvas - Resting)**: Pure `#FFFFFF` card surfaces sitting on `#F8FAFC`. Structured via a 1px composite outline border of `#E2E8F0` layered with an ambient shadow: `0px 1px 3px rgba(10, 25, 47, 0.04), 0px 4px 8px rgba(10, 25, 47, 0.02)`.
- **Level 2 (Interactive Modules / Floating Action Bars)**: Raised payment drawers, BBPS category popovers, and sticky bottom sheets. Constructed using `0px 8px 24px -4px rgba(10, 25, 47, 0.08), 0px 4px 12px -2px rgba(10, 25, 47, 0.04)`.
- **Level 3 (Modals & Critical Pin Confirmations)**: UPI PIN input dialogs and biometric prompts. Elevated with `0px 16px 36px -6px rgba(10, 25, 47, 0.16)` overlaying a `#0A192F` scrim at 60% opacity with 4px backdrop blur.
- **Hero Sovereign Card**: The primary digital wallet balance surface utilizes a deep gradient from `#0A192F` to `#1E293B` accented with a subtle inner rim light (`inset 0 1px 0 rgba(255, 255, 255, 0.12)`) and a directional blue glow shadow: `0px 12px 32px -8px rgba(37, 99, 235, 0.25)`.

## Shapes
The visual identity embraces a geometric, rounded form factor that softens technical financial primitives while maintaining strict structural boundaries.

- **Standard Containers & Cards**: Set to `rounded-xl` (1.5rem / 24px) to form signature rounded cards for account overviews, BBPS biller lists, and promo banners.
- **Controls & Form Elements**: Input fields, transaction rows, and secondary notification capsules use `rounded-md` (0.5rem / 8px) or `rounded-lg` (1rem / 16px).
- **Interactive Action Pills**: Quick-filter chips, biometric trigger buttons, and payment channel selector badges utilize full pill geometry (`rounded-full` / 9999px).

## Components

### Buttons & Action Controls
- **Primary Action (Payment/Transfer)**: Solid Electric Action Blue (`#2563EB`) with white text, 48px minimum touch height on mobile, `rounded-xl`, bold font weight. Hover/Active transforms down to `#1D4ED8`.
- **Destructive/Critical Action**: Outlined in red with soft rose wash fill (`#FEF2F2`), border `#FCA5A5`, text `#DC2626`.
- **Quick Send / UPI Pay CTA**: Large circular button (56px) wrapped in `#0A192F` with vibrant emerald or electric blue icon center, accompanied by bold sub-labels.

### Cards & Financial Modules
- **Account Balance Hero Card**: Wrapped in sovereign navy with subtle micro-patterns mimicking rupee micro-printing. Contains: Primary available balance in `headline-lg`, quick toggle for hidden balance, linked bank account chip with bank logo mark, and instant 'Add Money' and 'Transfer' pill triggers.
- **BBPS Biller Card**: Rounded 24px white card featuring the official Bharat BillPay trust mark in the top-right header, bold categorization (Electricity, Water, DTH, Fastag), and an urgency indicator badge when an invoice is pending.

### Badges & Verification Elements
- **BBPS Certified Badge**: High-density pill featuring a dual-tone layout: official BBPS icon against pure `#FFFFFF` alongside an `#0A192F` background with `#F8FAFC` micro-typography reading "BBPS ASSURED".
- **Transaction Status Badges**:
  - *Success*: `#ECFDF5` surface, `#047857` border, `#065F46` label with tertiary emerald check mark.
  - *Pending / Processing*: `#FFFBEB` surface, `#FDE68A` border, `#92400E` label with clock icon.
  - *Failed*: `#FEF2F2` surface, `#FECACA` border, `#991B1B` label with alert icon.

### Form Inputs & Monetary Entry
- **Amount Input Display**: Massively scaled centered monetary input field utilizing `display-lg` typography, anchored with a static `₹` symbol in `#64748B`. Underline states animate between `#CBD5E1` and `#2563EB`.
- **UPI PIN Entry**: Discrete 4 or 6-digit passcode container blocks using isolated 52x52px `rounded-lg` boxes with `#F1F5F9` surfaces, turning to deep navy borders upon character insertion.
- **Bank / VPA Selector**: Horizontal list view with bank avatar icon, masked account identifier (`•• 4821`), primary bank radio checkmark, and live bank server health signal (e.g., green dot for "Bank CBS UP").