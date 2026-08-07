# Cyberpunk Interactive IDE Code Terminal

A sleek developer-focused code editor terminal component featuring syntax highlighting tokens, custom line numbers, and a blinking cursor.

## 1. What does this do?
This component presents code snippets inside a high-contrast Cyberpunk IDE window complete with custom traffic light controls, file tab badges, syntax token styling, and animated cursors.

## 2. How is it used?
Wrap formatted code inside `.terminal-window` structure and assign syntax token classes:

```html
<div class="terminal-window">
  <div class="terminal-body">
    <div class="line-numbers">...</div>
    <div class="code-content">
      <span class="keyword">const</span> <span class="entity">app</span> = true;
    </div>
  </div>
</div>
```

## 3. Why is it useful?
- **Developer Documentation Showcase**: Great for documentation sites, code tutorial cards, and API references.
- **Realistic Editor Look**: Custom line numbers, status bar indicators, and glowing window borders.
- **Accessible Motion**: Cursor blinking automatically pauses when `prefers-reduced-motion: reduce` is enabled.
