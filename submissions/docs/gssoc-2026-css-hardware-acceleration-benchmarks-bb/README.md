# CSS Hardware Acceleration & Animation Benchmarks

An engineering documentation guide and interactive benchmark playground evaluating GPU Compositor layer promotion vs CPU layout reflow performance in EaseMotion-css.

## What does this do?
This benchmark guide analyzes browser rendering pipeline mechanics (Recalculate Style -> Layout -> Paint -> Composite). It provides interactive visual demonstrations comparing compositing-only properties (`transform`, `opacity`, `will-change`) against layout-thrashing properties (`top`, `left`, `margin`).

## How is it used?
Optimize CSS animation rules by targeting GPU compositor properties:

```css
/* Recommended: GPU Compositor Promotion */
.gpu-accelerated {
  will-change: transform;
  transform: translate3d(0, 0, 0);
  transition: transform 0.3s ease;
}

/* Avoid: CPU Reflow Trigger */
.cpu-thrash {
  position: absolute;
  transition: left 0.3s ease; /* Triggers Layout & Paint recalculations */
}
```

## Why is it useful?
- **Prevents Frame Drops**: Eliminates jank and stutter on mobile devices and low-power hardware.
- **Battery & Performance Friendly**: Offloads rendering computations from the main thread to dedicated GPU cores.
- **Maintainer Guidelines**: Establishes performance criteria for all motion contributions submitted to EaseMotion-css.
