---
name: Bordeaux Opulence
colors:
  surface: '#fff8f8'
  surface-dim: '#e1d8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f2'
  surface-container: '#f5eced'
  surface-container-high: '#efe6e7'
  surface-container-highest: '#e9e0e1'
  on-surface: '#1e1b1c'
  on-surface-variant: '#544244'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f8eeef'
  outline: '#877274'
  outline-variant: '#dac1c2'
  surface-tint: '#984351'
  primary: '#3d0011'
  on-primary: '#ffffff'
  primary-container: '#5b1324'
  on-primary-container: '#dc7988'
  inverse-primary: '#ffb2bb'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#3d000f'
  on-tertiary: '#ffffff'
  tertiary-container: '#620420'
  on-tertiary-container: '#ea7082'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9dd'
  primary-fixed-dim: '#ffb2bb'
  on-primary-fixed: '#400012'
  on-primary-fixed-variant: '#7a2b3b'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffd9dc'
  tertiary-fixed-dim: '#ffb2ba'
  on-tertiary-fixed: '#400011'
  on-tertiary-fixed-variant: '#842136'
  background: '#fff8f8'
  on-background: '#1e1b1c'
  surface-variant: '#e9e0e1'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '400'
    lineHeight: 38px
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 30px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.12em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.14em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-lg: 2.5rem
  margin: 1.25rem
  margin-md: 2.5rem
  margin-lg: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system establishes an intimate, haute-culinary aesthetic tailored for a premier Bosphorus-front dining destination. Rooted in contemporary editorial luxury, the visual narrative balances classical gastronomic heritage with sleek modernity. 

The emotional resonance is sensorial, serene, and prestigious. The UI prioritizes negative space, deliberate pacing, high-fashion typography, and rich tactile tones over loud interactions or utilitarian density. The overarching style fuses high-end editorial layouts with soft tonal layering, reminiscent of an embossed letterpress tasting menu illuminated by low-lit interior candelabra.

## Colors

The palette draws directly from vintage bordeaux cellar reserves, warm linen, polished brass, and evening shadows:

- **Primary (`#5B1324`)**: Deep wine/bordeaux serving as the signature brand anchor. Used for primary buttons, prominent title highlights, and prestige accent states.
- **Secondary (`#D4AF37`)**: Subtle warm brass gold. Reserved for fine culinary distinctions, Michelin-level badges, bespoke dividers, and focused states.
- **Tertiary (`#78182E`)**: Rich crimson-tinted bordeaux for dynamic interactive states (hover/active), wine-pairing tags, and subtle gradient washes.
- **Neutral (`#221E1F`)**: Deep warm charcoal for high-contrast, non-harsh typographic legibility.

### Surface System
The light canvas shifts away from sterile white to architectural warmth:
- **Base Canvas**: Champagne Cream (`#F9F6F0`)
- **Surface Level 1**: Aged Linen (`#F3EDE2`) for cards, dialogs, and elevated sections
- **Surface Level 2 / Muted**: Warm Stone (`#E8DFD3`) for secondary containers, chips, and subtle keylines
- **Border Tone**: Subtle Gold/Sand (`rgba(212, 175, 55, 0.25)` or `#E8DFD3`)

## Typography

Typography embodies the contrast between classic epicurean literature and architectural precision.

- **Headlines (`Playfair Display`)**: Evokes the traditional typography of vintage menus and editorial culinary journals. Headlines should be rendered primarily in regular (400) or medium (500) weights to preserve high-contrast elegance without becoming dense.
- **Body & Labels (`Plus Jakarta Sans`)**: A polished, modern geometric sans that ensures crystalline legibility for ingredient lists, seating details, and reservation flows.
- **Micro-Copy & Eyebrows**: Labels always employ uppercase formatting with wide tracking (`0.1em` to `0.14em`) to act as refined anchors for sections and categories.

## Layout & Spacing

The layout philosophy mirrors the spacious pacing of a multi-course dining experience. Rather than crowding information, components inhabit ample negative space to emphasize luxury and focused composition.

- **Grid Architecture**: A 12-column responsive fluid grid maxing out at `1440px` for desktop layouts, transitioning to 8 columns on tablet devices (`768px - 1024px`) and 4 columns on mobile viewports (`<768px`).
- **Margins & Gutters**: Outer canvas margins expand from `1.25rem` on mobile to `4rem` on wide displays, framing content like a museum mat board.
- **Culinary Sectioning**: Courses and menu galleries leverage alternating asymmetric column spans (e.g., 5-column narrative imagery paired with 7-column menu degustation) to prevent a monotonous e-commerce feel.

## Elevation & Depth

Visual hierarchy rejects aggressive drop shadows in favor of tonal layering and soft ambient warmth.

- **Tonal Layering**: Depth is achieved by placing cards on `#F3EDE2` against the base `#F9F6F0` background, outlined with hairlines (`1px`) colored in `#E8DFD3` or `rgba(212, 175, 55, 0.25)`.
- **Ambient Lighting**: When modals or sticky reservation bars rise above the plane, apply a diffuse, warm-tinted shadow: `0 16px 36px -8px rgba(34, 30, 31, 0.08)`.
- **Frosted Translucency**: For the primary navigation bar and floating reservation controls, use an oyster glass aesthetic: `rgba(249, 246, 240, 0.88)` with a `16px` backdrop-filter blur and a delicate bottom border of `rgba(212, 175, 55, 0.2)`.

## Shapes

The geometric framework favors architectural discipline over casual roundness. 

- **Corner Radius**: Default corners employ a subtle `4px` (`roundedness: 1`), softening digital edges while retaining the feel of crisp stationery, fine bookbinding, and marble table edges.
- **Media Containers**: Archival food imagery and sommelier profiles utilize crisp right-angled or gentle `4px` containers, occasionally contrasting with classical Mediterranean neoclassical arched top frames (`radius-top: 120px`) for hero showcases.
- **Functional Pills**: Status badges and tasting notes may adopt pill silhouettes only when explicitly containing isolated inline tags.

## Components

### Buttons
- **Primary**: Solid deep wine (`#5B1324`) background with champagne text (`#F9F6F0`), `4px` border radius, and `1px` matching border. Hover transitions to `#78182E` with a subtle elevation shift. Padding: `14px 28px`.
- **Secondary (Editorial Outline)**: Transparent background, `1px` border in `#5B1324`, warm charcoal text (`#221E1F`). On hover, fills with `rgba(91, 19, 36, 0.04)` and transitions border color to `#78182E`.
- **Tertiary / Brass Accent**: Text in `#5B1324` with a permanent `1px` underline in `#D4AF37`, utilizing `label-lg` tracking.

### Cards (Menu Items & Wine Pairings)
- Structured on `#F3EDE2` surfaces with a crisp `1px` solid border (`#E8DFD3`).
- Course cards highlight dish names in `Playfair Display` (`headline-sm`), followed by a faint brass leader line connecting to the price, with provenance details rendered below in `body-sm` (`#221E1F` at 75% opacity).

### Input Fields & Selectors
- Background: `#F9F6F0` or `#FFFFFF`.
- Border: `1px` solid `#E8DFD3`, transitioning to `#5B1324` on focus, paired with an ambient gold halo (`0 0 0 2px rgba(212, 175, 55, 0.2)`).
- Labels: Small caps / tracking `0.1em` placed above the input field.

### Selection Controls (Checkboxes & Radios)
- Custom square (`4px`) and circular toggles with `1px` `#D4AF37` outlines. Selected state fills with `#5B1324` and displays a gold accent check or center pip.

### Chips & Dietary Badges
- Minimal height (`26px`), muted cream fill (`#E8DFD3`), crisp charcoal text (`#221E1F`), zero elevation. Wine pairing badges feature a soft gold border tint (`rgba(212, 175, 55, 0.4)`).

### Bespoke Domain Components
- **Degustation Course Stepper**: Minimalist gold and wine progress nodes indicating multi-course tasting progression.
- **Reservation Concierge Drawer**: Seamless slide-over panel utilizing surface `#F3EDE2` with gold-accented calendar day cells and velvet-toned time-slot chips.