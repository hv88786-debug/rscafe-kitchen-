---
name: Royal Rajputana Contemporary
colors:
  surface: '#fef9ef'
  surface-dim: '#dedad0'
  surface-bright: '#fef9ef'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3e9'
  surface-container: '#f2ede3'
  surface-container-high: '#ece8de'
  surface-container-highest: '#e7e2d8'
  on-surface: '#1d1c16'
  on-surface-variant: '#414846'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f5f0e6'
  outline: '#717975'
  outline-variant: '#c0c8c4'
  surface-tint: '#3f665b'
  primary: '#00251d'
  on-primary: '#ffffff'
  primary-container: '#123b32'
  on-primary-container: '#7da599'
  inverse-primary: '#a5cfc2'
  secondary: '#775a1a'
  on-secondary: '#ffffff'
  secondary-container: '#fed489'
  on-secondary-container: '#785a1b'
  tertiary: '#480003'
  on-tertiary: '#ffffff'
  tertiary-container: '#700007'
  on-tertiary-container: '#ff6f64'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecde'
  primary-fixed-dim: '#a5cfc2'
  on-primary-fixed: '#00201a'
  on-primary-fixed-variant: '#264e44'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c178'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5d4202'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ab'
  on-tertiary-fixed: '#410002'
  on-tertiary-fixed-variant: '#93000d'
  background: '#fef9ef'
  on-background: '#1d1c16'
  surface-variant: '#e7e2d8'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style
This design system captures contemporary Indian luxury hospitality, merging royal Rajasthani heritage with modern cafe culture. Tailored for an upscale cafe and kitchen in Ajmer, the visual direction channels bespoke architectural elements—jali geometric lattice motifs, polished dark marble, and antiqued brass fixtures. 

The mood balances aristocratic warmth with sleek, modern utility. It avoids gaudy ornament in favor of restrained editorial sophistication: generous white space in warm ivory tones, regal forest emerald accents, tailored hairline metallic gold trim, and precise culinary typography. The experience should evoke the unhurried elegance of an imperial salon while serving as a rapid, effortless digital ordering and reservation interface.

## Colors
The palette grounds the interface in regal natural materials:
- **Primary (`#123B32` Deep Forest Green):** The commanding anchor used for hero headers, primary buttons, structural chrome, and prominent typography. Paired with its darker variant `#0B2924` (Dark Emerald) for high-contrast nocturnal surfaces and footer sections.
- **Secondary (`#C6A15B` Antique Gold):** Used with calculated discipline for delicate borders, active state indicators, dietary badges, calligraphic embellishments, and interactive hover states.
- **Tertiary (`#D62828` RS Signature Red):** Inherited directly from the brand crest to draw sharp focus to chef recommendations, spice indicators, call-to-action flashes, and special seasonal offerings.
- **Neutral (`#F8F3E9` Warm Ivory):** The dominant canvas surface, replicating rich handmade parchment and calming eye strain compared to clinical stark whites. Pure Soft White (`#FFFFFF`) is reserved strictly for elevated food card containers.

## Typography
The system juxtaposes the literary majesty of **Playfair Display** with the geometric precision and clarity of **Plus Jakarta Sans**. 

- **Display & Section Titles:** Set in Playfair Display with classic high-contrast strokes to evoke high-end editorial menus and heritage courtliness.
- **Culinary Descriptions & Utility:** Handled by Plus Jakarta Sans to ensure swift legibility across digital handheld devices in dim ambient cafe lighting.
- **Labels & Micro-copy:** Uppercase tracked labels (`0.05em` to `0.1em`) provide architectural structure to dietary markers (Jain, Vegan, Chef's Special) and price points.

## Layout & Spacing
A 12-column fluid grid system governs desktop views with wide 48px margins and 20px gutters, transitioning to a dense 4-column structure with 20px margins on mobile screens. 

The vertical rhythm prioritizes generous breathing room between dish categories (`space-xl`), allowing high-definition culinary photography and typography to command the page without feeling congested. Compact item spacing (`space-sm` and `space-md`) within cards keeps critical dietary tags, ingredients, and call-to-actions visually unified.

## Elevation & Depth
Depth is achieved through tactile warmth rather than harsh synthetic drops. 

- **Surface Layering:** The primary canvas uses `#F8F3E9` (Warm Ivory). Interactive food cards and floating panels step forward onto crisp `#FFFFFF` surfaces trimmed with a 1px border of `#C6A15B` at 25% opacity.
- **Ambient Shadows:** Shadows mimic warm, incandescent restaurant chandelier illumination. Cards utilize an ultra-diffused dual shadow: an ambient spread of `0 12px 32px -4px rgba(18, 59, 50, 0.08)` coupled with a micro-drop of `0 2px 6px 0 rgba(11, 41, 36, 0.04)`.
- **Active & Modal Overlays:** Modals and bottom sheets utilize subtle backdrop blurs (`backdrop-filter: blur(12px)`) tinted with 60% opacity `#0B2924` (Dark Emerald) to focus guest attention on dish customizers and table reservations.

## Shapes
A "Soft" roundedness tier (`roundedness: 1`) is applied throughout. Structural elements feature 4px (`0.25rem`) corners, extending to 8px (`0.5rem`) on food display cards, and 12px (`0.75rem`) on modals. 

This restrained curvature preserves an architectural, tailored feel reminiscent of hand-cut stonework and bespoke leather-bound menu boards, avoiding the overly bubbly appearance of fast-casual apps. Dietary indicators and tags utilize micro-radii to maintain sharp legibility.

## Components

### Buttons
- **Primary Button:** Filled Deep Forest Green (`#123B32`) with Warm Ivory (`#F8F3E9`) uppercase text, 1px inset antique gold border, and 4px radius. Hover state introduces a smooth transition to Dark Emerald (`#0B2924`) with an expanded gold glow.
- **Secondary Button:** Warm Ivory surface with a 1.5px Antique Gold (`#C6A15B`) border and Deep Forest Green text.
- **Order Action / Accent Button:** RS Signature Red (`#D62828`) solid fill with white text, reserved for "Add to Cart" or "Book Table" triggers.

### Chips & Dietary Badges
- Compact rectangular badges with 4px border radius. 
- Traditional Indian green dot in a square for Vegetarian items; deep crimson dot for Non-Vegetarian.
- Chef's Special / Signature chip features an Antique Gold (`#C6A15B`) tinted background with dark emerald text and a fine metallic rim.

### Menu Cards
- Structured white surface on warm ivory canvas.
- Features high-resolution culinary photography with subtle 1px Antique Gold borders.
- Item titles in Playfair Display medium weight, accompanied by a clean price display in bold Plus Jakarta Sans and a concise ingredient overview.

### Form Inputs & Search
- Inputs feature a Warm Ivory base tinted slightly deeper than the canvas, framed by a muted 1px border (`#C6A15B` at 40%).
- On focus, the field activates a solid 1.5px Antique Gold border with an emerald-tinted ambient glow.

### Floating Cart & Order Summary Bar
- Dark Emerald (`#0B2924`) high-contrast bottom dock on mobile devices, highlighted with an Antique Gold top border hairline, containing clear typography and an RS Signature Red checkout badge.