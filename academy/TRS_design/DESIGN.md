# The Right Seed Academy

---
name: The Right Seed Academy
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1b1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#bbcbb8'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#303032'
  outline: '#869583'
  outline-variant: '#3c4a3c'
  surface-tint: '#3ce36a'
  primary: '#3fe56c'
  on-primary: '#003912'
  primary-container: '#00c853'
  on-primary-container: '#004c1b'
  inverse-primary: '#006e2a'
  secondary: '#bdf4ff'
  on-secondary: '#00363d'
  secondary-container: '#00e3fd'
  on-secondary-container: '#00616d'
  tertiary: '#9bd89b'
  on-tertiary: '#003910'
  tertiary-container: '#80bc82'
  on-tertiary-container: '#114c1e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#69ff87'
  primary-fixed-dim: '#3ce36a'
  on-primary-fixed: '#002108'
  on-primary-fixed-variant: '#00531e'
  secondary-fixed: '#9cf0ff'
  secondary-fixed-dim: '#00daf3'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#b4f2b3'
  tertiary-fixed-dim: '#98d599'
  on-tertiary-fixed: '#002107'
  on-tertiary-fixed-variant: '#185123'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

---

# The Right Seed Academy

## Brand and Style

The design system for this digital academy is built on the philosophy of "Precision Growth"—merging the cold, calculated accuracy of neuroscience with the organic, warm progression of personal evolution. The target audience is high-performers seeking data-backed methods for habit formation and mental clarity.

The visual style is a **Hybrid of Technical Glassmorphism and Organic Minimalism**. It utilizes a deep, immersive dark theme to minimize eye strain and maximize focus ("Deep Work" mode). The emotional response should be one of quiet authority, intellectual rigor, and modern innovation. Visual elements feature crisp edges softened by deliberate rounding, subtle background blurs to suggest depth, and neon-tinged accents that simulate electrical brain activity.

## Colors

The palette is rooted in a "Obsidian & Neon" logic.

- **Base Layer:** The foundation is a deep Charcoal (#121214), providing a void-like canvas that makes content pop.
- **Growth Accents:** Emerald Mint (#00C853) is used for primary actions and success states, symbolizing the "Seedling" or flourishing stage. Sage Green (#4E8752) provides a grounded, muted secondary tone for less urgent growth indicators.
- **Neural Accents:** Electric Ice Blue (#00E5FF) is reserved for technical insights, data visualizations, and links related to neuroscience or cognitive functions.
- **Neutrals:** Grays are cool-toned to maintain a technical feel, preventing the dark mode from feeling "muddy."

## Typography

The typography system creates a "Modern Authority" hierarchy.

- **Headings:** Plus Jakarta Sans provides a wide, geometric, and friendly yet professional stature. Use `headline-xl` for hero sections to establish immediate impact.
- **Body:** Inter is used for all instructional and long-form content. Its high x-height ensures legibility against dark backgrounds.
- **Contrast:** High contrast between heading weights (Bold/ExtraBold) and body weights (Regular) is essential to guide the eye through dense scientific insights.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **single-column fluid layout** for mobile.

- **Rhythm:** An 8px linear scale governs all padding and margins (8, 16, 24, 32, 48, 64, 96, 128).
- **Density:** Insight-heavy pages (lesson content) should use tighter vertical spacing between related concepts, while marketing pages use generous 128px sections to create a premium, "breathable" feel.
- **Safe Zones:** Always maintain a minimum 24px gutter on tablets to prevent content from touching the screen edges.

## Elevation & Depth

Depth is created through **Luminance and Blur** rather than heavy drop shadows.

- **Tiers:** The background is the darkest (#121214). Cards and navigation sit on an elevated tier (#1E1E22).
- **Glassmorphism:** Navigation bars and overlays use a 20px Backdrop Blur with a 10% opacity white border to simulate frosted glass.
- **Glows:** Primary elements (active buttons or highlighted data points) emit a soft, 15px spread glow using their respective accent color at 20% opacity.
- **Outlines:** Use 1px "Inner Glow" borders (linear gradients from white/10% to white/0%) to define element edges without creating heavy visual weight.

## Shapes

The shape language is "Organic Geometric."

- **Standard Corners:** Most containers use a 0.5rem (8px) radius to maintain a professional, structured look.
- **Interactive Elements:** Buttons and small tags use a larger 1rem (16px) radius to feel more approachable and "human."
- **Icons:** Use a consistent 2px stroke width with rounded caps to match the typography's softness.

## Components

- **Sticky Navigation:** A minimalist horizontal bar with `backdrop-filter: blur(20px)`. Logo on the left, utility links on the right. Transition background opacity from 0% to 80% on scroll.
- **High-Contrast Buttons:**
  - *Primary:* Solid Emerald Mint with black text. Hover state triggers a `box-shadow` glow of the same color.
  - *Secondary:* Ghost style with an Electric Ice Blue border.
- **Interactive Cards:** Default state is grayscale or highly desaturated. On hover, the card smoothly transitions to full color (Sage/Emerald) and slightly lifts (+4px Y-axis) with a subtle 10% glow.
- **Input Widgets:** Deep charcoal backgrounds with 1px borders. On focus, the border glows Electric Ice Blue. Use "Inter" for input text to ensure clarity in technical forms.
- **Progress Bars:** Thin, 4px tall tracks. The "Seedling" progress uses a gradient from Sage Green to Emerald Mint, representing growth.
