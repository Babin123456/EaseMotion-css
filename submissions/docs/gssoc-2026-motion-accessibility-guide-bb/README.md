# Motion Accessibility & Reduced-Motion Integration Guide

A comprehensive architectural guide and interactive diagnostic component for implementing accessible web animations and handling `prefers-reduced-motion` media queries in EaseMotion-css.

## What does this do?
This documentation guide demonstrates how to build accessible CSS animations that respect vestibular safety guidelines. It includes an interactive system media query detector, simulation toggle, safe opacity fade fallback patterns, and code snippets for WCAG 2.2 Criterion 2.3.3 compliance.

## How is it used?
Apply the `@media (prefers-reduced-motion: reduce)` CSS media query wrapper around motion-heavy CSS keyframes:

```css
/* Standard smooth animation */
.animated-element {
  animation: slideIn 0.5s ease-out;
}

/* Reduced motion preference override */
@media (prefers-reduced-motion: reduce) {
  .animated-element {
    animation: fadeIn 0.2s ease-out; /* Safe fallback */
  }
}
```

## Why is it useful?
- **WCAG Compliance**: Helps developers meet accessibility standards for users sensitive to motion.
- **Vestibular Safety**: Reduces risks of motion-induced vertigo, nausea, and disorientation.
- **Best Practices**: Provides actionable code patterns for open-source component authors in EaseMotion-css.
