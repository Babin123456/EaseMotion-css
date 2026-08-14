# Interactive Morphing Stepper Component

An interactive multi-step progress indicator featuring smooth CSS clip-path morphing transitions, active node pulse ripples, completion badges, and responsive vertical/horizontal layout switching for EaseMotion-css.

## What does this do?
This component renders an interactive step progress tracker with animated step connectors, active step ring animations, completed state checkmarks, keyboard control accessibility, and responsive container layout shifts.

## How is it used?
1. Include `style.css` in your HTML document.
2. Structure your step sequence using `<ol class="stepper-list">` and `<li class="step-item">`.
3. Add class `.active` or `.completed` to indicate progress states.

```html
<ol class="stepper-list">
  <li class="step-item active" aria-current="step">
    <div class="step-circle"><span class="step-num">1</span></div>
    <div class="step-details"><span class="step-title">Account</span></div>
  </li>
</ol>
```

## Why is it useful?
- **Multi-step Forms**: Ideal for checkout flows, onboarding wizards, and setup forms.
- **Responsive Layout**: Seamlessly transforms from horizontal layout to vertical step layout on mobile devices.
- **Hardware-Accelerated**: Utilizes GPU transitions for connector fill animations.
- **Accessible**: Provides `aria-current="step"` indicators for screen readers.
