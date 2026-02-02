# Design System: Auramotora Dystopian Tapestry

**Project ID:** [To be generated]

## 1. Visual Theme: A24 Cinematic Ritual

The aesthetic is **"Atmospheric Cinema"**—inspired by the high-end, moody visual language of A24 films. It moves away from "punk collage" into a sophisticated, clean, and hauntingly beautiful experience. Think: **Symmetrical compositions, elegant serifs, deep shadows, and high-fidelity cinematic film grain.** The goal is to make the website feel like a cinematic opening sequence for an avant-garde dystopian masterpiece.

## 2. Color Palette & Roles

- **Void Black (#0A0A0A):** The infinite canvas. Used for deep backgrounds and negative space.
- **Holographic Slate (#1E1E26):** Secondary surfaces and glassmorphic containers. Semi-translucent.
- **Acid Green (#C1FF00):** High-frequency highlights. Used for primary calls-to-action and reactive micro-interactions.
- **Ultraviolet (#7D00FF):** The "Travesía" glow. Used for gradients, glowing particles, and spiritual-technical transitions.
- **Blood Orange (#FF4D00):** Warning signals and raw energy. Used for accents and dystopian warnings.
- **Concrete Grey (#B0B0B0):** Informational text and structural lines.

## 3. Typography Rules

- **Display (Atmospheric):** **"EB Garamond"** (Italic, Medium). Used for cinematic quotes and section titles. It should feel historical, elegant, and slightly haunting.
- **Headlines (Structural):** **"Space Grotesk"** (Light/Medium). Tracked out (0.3em+) for a high-end, technical look.
- **Body:** **"Inter"** or **"Space Grotesk"** (Regular). Minimalist, legible, and desaturated.
- **Styling:** Minimalist labels. Avoid uppercase "shouting"; use lowercase or balanced tracking for a premium feel.

## 4. Component Stylings: The Cinematic Ritual

- **Navigation:** Deeply minimalist. Centered or symmetrically balanced in the corners. Use very fine lines (0.5px) for borders.
- **Hero Presence:** The **Band Logo** as a "Monolith." Centered, massive, but handled with extreme elegance—subtle breathing animations, atmospheric glow, and lens-blur depth.
- **Media Items:** Cinematic crops. Use letterboxing or "wide-angle" aspect ratios. Colors should be graded: deep blacks, high contrast, and desaturated midtones.
- **Atmosphere:** Universal high-fidelity film grain. Avoid "dirty" noise; use "cinematic" grain that feels like it's moving through a projector.

## 5. Layout Principles

- **The Shattered Journey:** Break the traditional grid. Content flows along a central "travesía" (path) but branches off into asymmetrical side-nodes.
- **Fluid Transitions:** Sections should bleed into each other using WebGPU-style fluid simulations or gradient dissipations.
- **Reactive Density:** Elements move and scale slightly in response to scroll and mouse position, creating a "live" environment.

---

## 6. Design System Notes for Stitch Generation

When generating screens for Auramotora, always:

- Use `dark` color mode.
- Prioritize `rounded-none` or very subtle `rounded-sm` for structural elements.
- Inject CSS for "noise" patterns on backgrounds: `background: radial-gradient(circle, transparent 20%, #0A0A0A 20%, #0A0A0A 80%, transparent 80%, transparent) 0% 0% / 1px 1px`.
- Maintain a "high contrast" between the Void Black background and the Acid/Ultra highlights.
- Ensure interactive elements feel like "physics-defying experiments" through reactive hover states.
