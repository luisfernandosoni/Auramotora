# Design System: Auramotora Dystopian Tapestry

**Project ID:** [To be generated]

## 1. Visual Theme & Atmosphere

The aesthetic is **"Dystopian Surrealism"**—a transdisciplinary fusion of raw brutalist honesty and fluid, dreamlike illogicality. It feels like a high-fidelity digital ritual. The atmosphere is dense yet breathable, transitioning between grainy desaturated voids and hyper-saturated neon bursts. It captures the band's philosophy: a serious exploration of dark corners taken with levedad (lightness).

## 2. Color Palette & Roles

- **Void Black (#0A0A0A):** The infinite canvas. Used for deep backgrounds and negative space.
- **Holographic Slate (#1E1E26):** Secondary surfaces and glassmorphic containers. Semi-translucent.
- **Acid Green (#C1FF00):** High-frequency highlights. Used for primary calls-to-action and reactive micro-interactions.
- **Ultraviolet (#7D00FF):** The "Travesía" glow. Used for gradients, glowing particles, and spiritual-technical transitions.
- **Blood Orange (#FF4D00):** Warning signals and raw energy. Used for accents and dystopian warnings.
- **Concrete Grey (#B0B0B0):** Informational text and structural lines.

## 3. Typography Rules

- **Headlines:** **"Space Grotesk"** (Bold/Extra Bold). Angular, modernist, with slight letter-spacing tension. Occasional use of distorted/warped text for headers to imply "digital decay."
- **Body:** **"Inter"** or **"Roboto Mono"** for a utilitarian, technical feel. High contrast between weights.
- **Styling:** Heavy use of uppercase for navigation and labels to emphasize the "serious band" persona.

## 4. Component Stylings

- **Navigation:** Minimalist, floating overlays. Links react with "liquid hover" effects (warping or glowing).
- **Buttons:** Sharp, squared-off edges (rounded-none). Neon borders that pulses with Ultraviolet or Acid Green.
- **Cards/Containers:** Glassmorphic 2.0. Functional layered translucency with a subtle grainy texture overlay.
- **Media Items:** Photos and video frames have "glitch-flicker" borders and are often presented at impossible scales.

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
