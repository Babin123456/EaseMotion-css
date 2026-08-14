# Holographic Glassmorphism Card Deck Component

An interactive 3D holographic tilt card deck component built with pure CSS hardware acceleration, dynamic glare reflection tracking, theme switching tokens, category filtering, and full accessibility support for EaseMotion-css.

## What does this do?
This component provides a sleek, futuristic 3D card layout with backdrop-filter glassmorphism effects, mouse-driven hardware-accelerated tilt transformations (`perspective: 1200px`), interactive lighting glare layers, dynamic theme token selection, and responsive grid reflow.

## How is it used?
1. Include the `style.css` in your HTML file or import it into your CSS stylesheet.
2. Structure your card deck using semantic HTML elements (`<article class="holo-card">`).
3. (Optional) Use the provided lightweight JavaScript event listeners to attach dynamic mouse coordinates (`--mouse-x`, `--mouse-y`, `--rot-x`, `--rot-y`) for 3D tilt tracking and theme toggling.

```html
<article class="holo-card">
  <div class="holo-card-inner">
    <div class="holo-glare"></div>
    <div class="card-badge">Web3 Protocol</div>
    <h2 class="card-title">Quantum Ledger</h2>
    <p class="card-desc">Zero-knowledge proof validation protocol.</p>
  </div>
</article>
```

## Why is it useful?
- **High Visual Impact**: Delivers modern glassmorphism aesthetics with dynamic 3D depth.
- **Hardware-Accelerated**: Smooth 60fps animations utilizing GPU-promoted layer transformations.
- **Fully Accessible**: Implements keyboard focus states, ARIA roles, and respects `prefers-reduced-motion`.
- **Customizable**: Built using scoped CSS Custom Properties for theme tokens, blur amounts, and glare intensity.
