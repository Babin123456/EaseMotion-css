# Cyberpunk Code Terminal Block Component

A highly interactive developer code terminal component featuring tabbed syntax highlighting, custom CRT scanline overlays, line numbering, copy-to-clipboard functionality, and cyberpunk theme styling for EaseMotion-css.

## What does this do?
This component renders a sleek retro-futuristic code terminal window with multi-file code snippet tabs, syntax token highlighting, interactive copy action with visual status feedback, custom animated blinking prompt cursors, and responsive window controls.

## How is it used?
1. Include `style.css` in your HTML web application.
2. Markup your code block using the `.terminal-container` structure and `.code-panel` tabs.
3. Use the lightweight tab switcher script to allow toggling between code files.

```html
<div class="terminal-container">
  <div class="terminal-header">
    <div class="terminal-title">ease-motion-cli</div>
  </div>
  <div class="terminal-body">
    <pre class="code-block"><code><span class="token-keyword">const</span> ease = true;</code></pre>
  </div>
</div>
```

## Why is it useful?
- **Developer Documentation Ready**: Perfect for displaying code samples in open-source docs or technical landing pages.
- **Interactive UX**: Built-in tab switching and instant clipboard copying.
- **Theme Engine Tokens**: Powered by CSS Custom Properties for easy theme customization.
- **Performant**: CRT scanlines and cursor pulse use GPU-composited CSS keyframe animations.
