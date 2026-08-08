# EaseMotion Frosted Glassmorphism Modal Dialog Component

An accessible, zero-JS pure CSS Frosted Glassmorphism Modal Dialog featuring backdrop blur filters, cubic-bezier spring zoom physics, and URL hash target triggers.

## 1. What does this do?
- Displays an accessible modal dialog over a blurred backdrop filter overlay (`backdrop-filter: blur(16px)`).
- Triggers modal open/close states via CSS `:target` pseudo-class without requiring JavaScript.
- Zooms and scales modal dialog boxes using CSS elastic cubic-bezier spring keyframes.

## 2. How is it used?
- Add `style.css` to your web project.
- Wrap modal elements in `<div id="modal-dialog" class="modal-overlay">` and trigger using `<a href="#modal-dialog">` links as shown in `demo.html`.
- Customize backdrop blur intensity and modal colors using CSS variables (`--modal-bg`, `--modal-border`).

## 3. Why is it useful?
- Zero JavaScript Required: Ideal for lightweight static websites and pure HTML documentation.
- High Aesthetic Quality: Combines modern frosted glassmorphism visuals with hardware-accelerated animations.
- Fully Accessible: Includes full keyboard target focusability and overlay close targets.
