# EaseMotion Glowing Aurora Hero Section Component

A premium, hardware-accelerated pure CSS Hero Section featuring animated fluid aurora radial light fields, gradient text clipping, high-contrast CTA buttons, and interactive code preview cards.

## 1. What does this do?
- Renders a modern landing page hero section with glowing background aurora light fields.
- Uses CSS `@keyframes` animations to produce continuous 3D blur translation of background light blobs.
- Implements staggered entrance keyframes for seamless headline and button rendering.
- Integrates a stylish frosted code snippet preview with syntax color highlights.

## 2. How is it used?
- Import `style.css` into your HTML document or build pipeline.
- Wrap your top-level hero component inside `<section class="aurora-hero">` and add the `.aurora-bg` container.
- Customize colors using CSS variables (`--aurora-1`, `--aurora-2`, `--aurora-3`).

## 3. Why is it useful?
- Instant SaaS Visual Appeal: Instantly upgrades hero landing sections with zero JS overhead.
- Lightweight & High Performance: Relies exclusively on CSS GPU-composated `transform`, `opacity`, and `filter: blur()`.
- Responsive Layout: Automatically scales typography and switches button layouts for mobile devices.
