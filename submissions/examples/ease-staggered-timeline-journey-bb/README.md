# Staggered Timeline Journey

An alternating left-right milestone roadmap featuring staggered entrance keyframes, glowing node markers, and glassmorphic cards.

## 1. What does this do?
This component renders an interactive vertical timeline where roadmap milestones alternate cleanly on left and right sides of a central glowing spine line with responsive mobile fallbacks.

## 2. How is it used?
Link `style.css` in your document head and construct your roadmap using `.timeline-container`:

```html
<link rel="stylesheet" href="style.css">

<div class="timeline-container">
  <div class="spine-line"></div>
  <article class="timeline-card card-left">
    <div class="node-marker">⚡</div>
    <div class="card-body">
      <h2>Milestone Title</h2>
    </div>
  </article>
</div>
```

## 3. Why is it useful?
It provides product release roadmaps, corporate history timelines, and portfolio milestone displays with clean CSS responsiveness and keyboard focus accessibility.
