# README.md

## 🪴 Smudge Stick Smoke

A mystical animated visualization of sage smoke with swirling patterns. This component captures the calming, spiritual essence of smudging — featuring a detailed sage stick with glowing ember, 30 smoke particles rising with organic swirling motion, 6 flowing smoke trails, and a soft ambient glow that creates a meditative atmosphere.

---

## ✨ Features

- **Detailed smudge stick** – Sage bundle with wrapping and texture
- **Glowing ember** – Pulsing glow at the tip of the stick
- **30 smoke particles** – Rising with organic swirling patterns
- **6 smoke trails** – Flowing streams of smoke
- **Ambient glow** – Soft pulsing glow around the stick
- **Interactive controls** – Burn, reset, speed, and density
- **Responsive** – Adapts beautifully to any screen size
- **Zero dependencies** – Pure CSS + vanilla JavaScript

---

## 🚀 How to Use

### 1. Include the CSS

```html
<link rel="stylesheet" href="style.css" />
2. Add the HTML structure
html
<div class="ss-container">
  <div class="ss-scene">
    <!-- Smudge Stick -->
    <div class="smudge-stick">
      <div class="stick-base"></div>
      <div class="stick-body">
        <div class="stick-texture"></div>
        <div class="stick-wrap wrap-1"></div>
        <div class="stick-wrap wrap-2"></div>
        <div class="stick-wrap wrap-3"></div>
      </div>
      <div class="ember-glow"></div>

      <!-- 30 smoke particles -->
      <div class="smoke-particle sp1"></div>
      <!-- ... up to sp30 -->

      <!-- 6 smoke trails -->
      <div class="smoke-trail st1"></div>
      <!-- ... up to st6 -->

      <div class="ambient-glow"></div>
    </div>
  </div>
</div>
3. Add the JavaScript
html
<script src="script.js"></script>
The script automatically manages smoke particles, trails, controls, and interactions.

🎮 Controls
Burn Sage – Start/stop the smoke animation

Reset – Reset to the initial state

Smoke Speed – Adjust the speed of smoke rise (0.3× to 3×)

Smoke Density – Control the density and opacity of smoke (0.3× to 2×)

🎨 Customization
CSS Variables
Variable	Default	Description
--smoke-duration	3s+	Duration of smoke particle rise
--smoke-delay	0s+	Stagger delay for particles
--smoke-size	4px	Size of smoke particles
--smoke-opacity	0.15	Opacity of smoke particles
--trail-duration	2.5s+	Duration of smoke trail rise
--trail-opacity	0.04	Opacity of smoke trails
--trail-width	2px	Width of smoke trails
--ember-duration	1.2s	Duration of ember pulse
--ambient-duration	3s	Duration of ambient glow pulse
--ambient-intensity	0.05	Intensity of ambient glow
Particle Colors
Smoke particles use a subtle sage-green color palette:

rgba(200, 220, 180, 0.06)

rgba(180, 200, 160, 0.03)

rgba(160, 180, 140, 0.01)

🧩 Why It Fits EaseMotion CSS
Human‑readable — Classes like .smudge-stick, .stick-body, .smoke-particle, .smoke-trail, .ember-glow, and .ambient-glow are intuitive and descriptive

Animation‑first — Smoke particles rise with CSS, trails flow with CSS, and glows pulse with CSS — all driven by the animation engine

Declarative & customizable — All timing, size, and color values are exposed via CSS custom properties

Self‑contained — Zero external dependencies — works entirely with HTML, CSS, and vanilla JavaScript

Mystical & calming — Captures the spiritual essence of smudging

Performance‑conscious — Uses GPU-accelerated transforms for smooth particle and trail animation

📁 File Structure
text
submissions/smudge-stick-smoke/
├── demo.html      # Self-contained demo
├── style.css      # All styles + keyframes
└── README.md      # This file