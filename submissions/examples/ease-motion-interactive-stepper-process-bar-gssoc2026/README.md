# EaseMotion Interactive Animated Stepper Process Bar Component

An interactive multi-step process navigation UI featuring glowing connector track fills, step node spring animations, and state transitions for completed and active phases.

## 1. What does this do?
- Displays multi-step wizard progress (`step-completed`, `step-active`, `step-pending`).
- Fills connector line tracks with an animated linear gradient progress bar (`progress-fill`).
- Scales step node indicators using CSS spring bounce keyframes when activated.

## 2. How is it used?
- Add `style.css` to your stylesheet or page header.
- Render workflow step items using `.stepper-track` and `.step-item` containers as shown in `demo.html`.
- Update `.progress-fill` width percentage and apply `.step-completed`/`.step-active` classes to reflect user state.

## 3. Why is it useful?
- Seamless Checkout & Onboarding: Keeps users informed of multi-step form progression.
- Pure CSS Motion: Operates smoothly using hardware-accelerated CSS `transform` and `box-shadow` keyframes.
- Mobile Responsive: Automatically resizes nodes and text for small screen viewports.
