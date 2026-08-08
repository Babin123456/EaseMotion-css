# EaseMotion Shimmer Pulse Loader Card Component

A pure CSS Skeleton Loader UI featuring linear gradient shimmer sweeps, placeholder card layouts, and hardware-accelerated background position animations.

## 1. What does this do?
- Displays content loading placeholders (image media, user avatar, typography lines).
- Sweeps a bright gradient light shimmer across dark placeholder blocks via CSS `@keyframes shimmerSweep`.
- Provides visual continuity during asynchronous data fetching operations.

## 2. How is it used?
- Import `style.css` into your project.
- Wrap placeholder elements using `.skeleton-card` and add the `.shimmer` class to skeleton blocks (`.skeleton-media`, `.skeleton-avatar`, `.skeleton-line`).
- Adjust shimmer speed using the `animation` property.

## 3. Why is it useful?
- Enhanced Perceived Performance: Reduces user drop-off during content loading phases.
- Zero JS Dependencies: Operates entirely via pure CSS linear gradients and keyframes.
- Accessible Design: Mimics exact content shapes to minimize cumulative layout shift (CLS).
