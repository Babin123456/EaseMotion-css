# EaseMotion Infinite Ticker Marquee Banner Component

A hardware-accelerated pure CSS Infinite Ticker Marquee Banner featuring bidirectional continuous scrolling, CSS mask gradient edge fading, interactive pause-on-hover physics, and responsive pill badge variations.

## 1. What does this do?
- Creates an infinite horizontal scrolling banner for brand logos, tech stacks, or announcements.
- Applies bidirectional CSS `@keyframes` (`marqueeLeft` and `marqueeRight`) for multi-row track movement.
- Uses CSS `mask-image` linear gradients to produce smooth fade-outs at left and right container edges.
- Supports instant pause-on-hover interaction without JavaScript.

## 2. How is it used?
- Add `style.css` to your project.
- Wrap ticker items in `.marquee-wrapper`, `.marquee-track`, and duplicated `.marquee-content` blocks as illustrated in `demo.html`.
- Adjust animation speed by modifying the `animation-duration` property in CSS.

## 3. Why is it useful?
- High Visual Engagement: Adds dynamic movement to modern landing page social proof sections.
- 100% Pure CSS: GPU-optimized translate3d transforms eliminate main thread lag.
- Fully Accessible: Includes `aria-hidden="true"` on duplicated loop elements for screen reader compatibility.
