# EaseMotion 3D Origami Fold Card Grid Component

An interactive pure CSS 3D Origami Card Grid featuring multi-panel paper fold animations, dynamic lighting shadows, transform perspective matrices, and elastic spring keyframes.

## 1. What does this do?
- Splits card surfaces into top and bottom paper-fold panels (`fold-top` and `fold-bottom`).
- Unfolds cards along 3D X-axes upon user hover using CSS `perspective` and `transform-origin`.
- Simulates realistic paper tension shadows and dynamic lighting reflections.

## 2. How is it used?
- Add `style.css` to your web project.
- Wrap card contents using `.origami-card` with embedded `.fold-top` and `.fold-bottom` panel structures.
- Modify rotational angles in hover CSS (`rotateX(-35deg)`, `rotateX(25deg)`) to adjust fold severity.

## 3. Why is it useful?
- Tactile Interactive UX: Provides a satisfying paper fold feel for feature highlights and interactive cards.
- Pure CSS Performance: Zero JavaScript required, fully hardware-accelerated via CSS 3D matrix transforms.
- Fully Accessible & Responsive: Features clean semantic structure and responsive grid adaptation.
