---
name: Antah Interior Design System
colors:
  surface: '#fef9f1'
  surface-dim: '#ded9d2'
  surface-bright: '#fef9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3eb'
  surface-container: '#f2ede5'
  surface-container-high: '#ece8e0'
  surface-container-highest: '#e7e2da'
  on-surface: '#1d1c17'
  on-surface-variant: '#57423c'
  inverse-surface: '#32302b'
  inverse-on-surface: '#f5f0e8'
  outline: '#8a726b'
  outline-variant: '#ddc0b8'
  surface-tint: '#a13f20'
  primary: '#9e3d1e'
  on-primary: '#ffffff'
  primary-container: '#be5434'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb59f'
  secondary: '#476558'
  on-secondary: '#ffffff'
  secondary-container: '#c9ead9'
  on-secondary-container: '#4d6b5d'
  tertiary: '#72590e'
  on-tertiary: '#ffffff'
  tertiary-container: '#8d7127'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb59f'
  on-primary-fixed: '#3a0a00'
  on-primary-fixed-variant: '#81280b'
  secondary-fixed: '#c9ead9'
  secondary-fixed-dim: '#adcebe'
  on-secondary-fixed: '#022016'
  on-secondary-fixed-variant: '#304d40'
  tertiary-fixed: '#ffdf95'
  tertiary-fixed-dim: '#e5c370'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#594400'
  background: '#fef9f1'
  on-background: '#1d1c17'
  surface-variant: '#e7e2da'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 32px
---

## Brand & Style

The brand personality is rooted in the concept of "Lived-In Luxury"—a philosophy that balances high-end sophistication with the soulful comfort of a well-loved home. It targets a discerning audience that values craftsmanship, intentionality, and the beauty of natural imperfections.

The design style is a blend of **Warm Minimalism** and **Tactile/Skeuomorphic** elements. This is achieved not through heavy drop shadows, but through organic shapes and rich, grainy textures that mimic physical materials like plaster, linen, and stone. The UI should feel quiet yet expressive, evoking an emotional response of serenity and groundedness.

## Colors

The palette is anchored in an earthy, chromatic foundation. The primary **Warm Terracotta** provides a sense of hearth and home, while the **Deep Forest Green** adds depth and a connection to the botanical world. **Soft Cream** replaces pure white to avoid a clinical feel, serving as the primary background for all interfaces.

**Muted Gold** is reserved for high-level accents and call-to-actions that require a touch of "luxury" without being ostentatious. The accent colors (**Dusty Rose** and **Soft Sage**) should be used sparingly in illustrative botanical elements or soft dividers. **Charcoal** provides necessary contrast for legibility and structural grounding.

## Typography

The typographic hierarchy relies on the tension between the classic, literary feel of **Noto Serif** and the modern, airy clarity of **Plus Jakarta Sans**. 

- **Headlines:** Use Noto Serif with generous leading. Headlines should feel editorial, often placed with significant whitespace to emphasize the "minimalist" aspect of the brand.
- **Body:** Plus Jakarta Sans provides a clean, contemporary counterpoint. Its slightly rounded terminals complement the organic shapes found in the brand elements.
- **Labels:** Small caps or all-caps formatting with increased letter spacing should be used for navigational labels and meta-data to maintain a sophisticated, architectural feel.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop (12 columns, 1200px max-width) and a fluid model for mobile. However, the spacing rhythm is intentionally "loose." 

To evoke "luxury," we prioritize negative space. Content blocks should be separated by `lg` or `xl` spacing units to allow the photography and organic elements to breathe. Asymmetry is encouraged—elements may overlap grid lines slightly or be offset to create a hand-curated, "lived-in" aesthetic rather than a rigid, corporate one.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Subtle Textures** rather than traditional drop shadows. 

1.  **Base Layer:** Soft Cream with a subtle grain texture overlay (2-3% opacity).
2.  **Surface Layer:** Terracotta or Sage surfaces with extremely soft, tinted ambient shadows (using the Deep Forest Green color at 5% opacity for the shadow) to create a sense of soft "lift" from the page.
3.  **Depth via Photography:** High-quality imagery of textures (linen, wood grain, stone) provides natural depth. 
4.  **Botanical Accents:** Hand-drawn botanical elements should appear as "floats"—placed as if they were pressed between glass, using light backdrop blurs (glassmorphism) when overlapping text.

## Shapes

The shape language is primarily **Organic**. While standard UI components follow a `Rounded` (0.5rem) logic for usability, larger containers and image masks should utilize non-perfect, "blob-like" organic paths or arched frames (reminiscent of architectural doorways). 

Buttons should feel "soft" to the touch, avoiding sharp corners that might feel aggressive or overly technical.

## Components

### Buttons
Primary buttons use a solid **Warm Terracotta** fill with Cream text. The hover state shifts to a slightly deeper tone. Secondary buttons use a **Deep Forest Green** outline with a "muted gold" subtle underline effect on hover.

### Cards
Cards are borderless, defined by a subtle change in background color (e.g., a Soft Sage card on a Soft Cream background) or by the container of a texture-rich photograph. Headlines within cards should always be Serif.

### Input Fields
Inputs are minimalist: a single Charcoal bottom border with a label that floats upward in the "Label-sm" style. The focus state should highlight the border in Muted Gold.

### Botanical Accents
A specialized component class for the hand-drawn botanical elements. These should be treated as "stickers"—fixed or absolute-positioned elements that break the grid to create a sense of artistry.

### Chips & Tags
Used for material types or project styles (e.g., "Mid-century," "Oak," "Linen"). These use a Soft Sage background with Forest Green text, using the Pill-shaped rounding to contrast with the more structured grid.