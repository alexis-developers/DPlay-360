---
name: Premium Event Aesthetic
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#dac67d'
  on-secondary: '#3a3000'
  secondary-container: '#534608'
  on-secondary-container: '#c8b56d'
  tertiary: '#d0cdcd'
  on-tertiary: '#313030'
  tertiary-container: '#b4b2b2'
  on-tertiary-container: '#454544'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#f7e296'
  secondary-fixed-dim: '#dac67d'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#534608'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Sora
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Sora
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Sora
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
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
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  max-width: 1440px
---

## Brand & Style

This design system embodies the high-octane sophistication of luxury event technology. The personality is "Quietly Powerful"—combining the depth of an infinite black backdrop with the sharp, energetic brilliance of shimmering gold. It targets a high-end audience seeking exclusivity and technical precision.

The visual style is a fusion of **Minimalism** and **Glassmorphism**. By using deep tonal layers and subtle backdrop blurs, the interface creates a sense of physical space and "stage presence." Every element is designed to feel like a premium hardware interface or a high-end gallery exhibit, emphasizing clarity, motion, and prestige.

## Colors

The palette is anchored in a true "Rich Black" to maximize the contrast of the gold accents. 

- **Primary Gold (#D4AF37):** Used for primary actions, critical brand moments, and active states. It should be used sparingly to maintain its status as a "shimmering" highlight.
- **Secondary Gold (#F9E498):** A lighter, highlight-only shade used for gradients and specular highlights to mimic the reflection of light on metallic surfaces.
- **Surface Palette:** Layers are built using varying shades of near-black and charcoal (#1A1A1A) to provide depth without breaking the dark-mode immersion.
- **Typography:** Primary text uses a soft off-white to prevent harsh ocular fatigue, while secondary text uses muted greys.

## Typography

The design system utilizes **Sora** across all levels to reinforce a modern, geometric, and technical feel. 

- **Display & Headlines:** Use tight letter-spacing and bold weights to command attention. These levels represent the "event titles" and "key metrics."
- **Body:** Generous line-heights are applied to ensure readability against the dark background.
- **Labels:** Small caps or uppercase styling with increased letter-spacing should be used for secondary navigation and category tags to create an architectural, structured look.

## Layout & Spacing

The layout philosophy follows a **Fixed-Width Fluid** hybrid. On large screens, the content is centered within a 1440px container to ensure a premium, cinematic composition. On smaller screens, the grid fluidly adjusts.

- **Rhythm:** An 8px base unit drives all padding and margin decisions. 
- **Margins:** Large outer margins (64px+) on desktop create a "frame" effect, emphasizing the content as a featured attraction.
- **Breakpoints:** 
  - Mobile: < 768px (single column, reduced margins).
  - Tablet: 768px - 1024px (8-column grid).
  - Desktop: > 1024px (12-column grid, 24px gutters).

## Elevation & Depth

Depth is communicated through **Tonal Layering** and **Luminescent Glows** rather than traditional shadows.

1.  **Level 0 (Floor):** Pure Black (#0A0A0A). Used for the main background.
2.  **Level 1 (Plinth):** Charcoal (#141414). Used for primary cards and sections.
3.  **Level 2 (Float):** Dark Grey (#1E1E1E) with a subtle 1px border (#FFFFFF10). Used for modals and floating menus.
4.  **Accent Depth:** High-priority elements use a "Gold Aura"—a very soft, low-opacity outer glow using the primary gold color to simulate a light source in a dark room.

## Shapes

The shape language is **Rounded**, striking a balance between the precision of technology and the comfort of a premium experience.

- **Containers:** 1rem (16px) corner radius for most cards and sections.
- **Interactive Elements:** Buttons and inputs use a slightly more pronounced 1.5rem (24px) radius to make them feel "tactile" and distinct from structural containers.
- **Visual Flourishes:** Use circular shapes for "particle" decorative elements to echo the gold dust seen in the brand imagery.

## Components

- **Buttons:** Primary buttons feature a solid gold fill with black text. Secondary buttons use a "Ghost" style with a gold border and white text. Hover states should introduce a subtle glow effect.
- **Cards:** Use a semi-transparent dark background (70% opacity) with a `backdrop-filter: blur(12px)` to create a glass-like texture that lets background particles peek through.
- **Inputs:** Minimalist bottom-border only or very subtle outlined boxes. On focus, the border transitions to gold with a faint luminescent glow.
- **Chips:** Small, pill-shaped indicators with high-contrast gold backgrounds for "Live" or "Featured" event statuses.
- **Progress Bars:** Use a gold-to-white linear gradient to simulate a moving light beam, reflecting the "kinetic" nature of the product.
- **Navigation:** Top-tier navigation should be fixed with a heavy backdrop blur, ensuring content remains legible as it scrolls underneath.