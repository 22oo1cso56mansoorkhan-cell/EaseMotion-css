# README.md

## ᚠ Rune Activation

A mystical rune activation animation with runes lighting up in sequence. This component captures the ancient power of runic magic — featuring 12 Elder Futhark runes arranged in a sacred circle, sequential activation with glowing effects, connection lines, a central symbol, energy particles, and interactive controls.

---

## ✨ Features

- **12 Elder Futhark runes** – Fehu, Uruz, Thurisaz, Ansuz, Raidho, Kaunan, Gebo, Wunjo, Hagalaz, Naudiz, Isa, Jera
- **Sequential activation** – Runes light up in random order
- **Glowing effects** – Each rune pulses with warm light
- **Connection lines** – Concentric rings connecting the runes
- **Center symbol** – The Algiz (ᛉ) rune at the center
- **Energy particles** – Floating particles around the circle
- **Status display** – Shows current activation progress
- **Interactive controls** – Activate, reset, speed, and intensity
- **Clickable runes** – Click individual runes to activate them
- **Responsive** – Adapts beautifully to any screen size
- **Zero dependencies** – Pure CSS + vanilla JavaScript

---

## 🚀 How to Use

### 1. Include the CSS

```html
<link rel="stylesheet" href="style.css" />
2. Add the HTML structure
html
<div class="ra-container">
  <div class="ra-scene">
    <!-- Rune Circle -->
    <div class="rune-circle">
      <!-- 12 runes -->
      <div class="rune rune-1" data-index="0">
        <div class="rune-symbol">ᚠ</div>
        <div class="rune-glow"></div>
        <div class="rune-ring"></div>
      </div>
      <!-- ... up to rune-12 -->

      <!-- 12 connection lines -->
      <div class="connection-line cl1"></div>
      <!-- ... up to cl12 -->

      <!-- Center symbol -->
      <div class="center-symbol">ᛉ</div>
      <div class="center-glow"></div>

      <!-- 8 particles -->
      <div class="particle p1"></div>
      <!-- ... up to p8 -->
    </div>

    <div class="status-text" id="statusText">ᚠ Awaiting Activation...</div>
  </div>
</div>
3. Add the JavaScript
html
<script src="script.js"></script>
The script automatically manages rune activation, sequence, effects, controls, and interactions.

🎮 Controls
Activate Runes – Start the sequential activation sequence

Reset – Reset all runes to inactive state

Activation Speed – Adjust the speed of activation (0.3× to 3×)

Glow Intensity – Control the brightness of glows (0.3× to 2×)

Click Rune – Click any rune to toggle it individually

🎨 Customization
CSS Variables
Variable	Default	Description
--rune-duration	0.6s+	Duration of rune activation
--rune-delay	0s+	Stagger delay for runes
--line-duration	0.3s+	Duration of line activation
--glow-intensity	0.15	Intensity of rune glows
--glow-size	60px	Size of rune glows
--center-duration	1.5s	Duration of center pulse
--particle-duration	3s+	Duration of particle float
Rune List
#	Rune	Name	Symbol
1	Fehu	ᚠ	Wealth
2	Uruz	ᚢ	Strength
3	Thurisaz	ᚦ	Protection
4	Ansuz	ᚨ	Communication
5	Raidho	ᚱ	Journey
6	Kaunan	ᚲ	Transformation
7	Gebo	ᚷ	Gift
8	Wunjo	ᚹ	Joy
9	Hagalaz	ᚺ	Disruption
10	Naudiz	ᚾ	Need
11	Isa	ᛁ	Stillness
12	Jera	ᛃ	Harvest
🧩 Why It Fits EaseMotion CSS
Human‑readable — Classes like .rune, .rune-symbol, .rune-glow, .rune-ring, .connection-line, .center-symbol, and .particle are intuitive and descriptive

Animation‑first — Runes activate with CSS, glows pulse with CSS, lines animate with CSS, and particles float with CSS — all driven by the animation engine

Declarative & customizable — All timing, size, and color values are exposed via CSS custom properties

Self‑contained — Zero external dependencies — works entirely with HTML, CSS, and vanilla JavaScript

Mystical & ancient — Captures the power and mystery of runic magic

Performance‑conscious — Uses GPU-accelerated transforms for smooth activation and particle animation

📁 File Structure
text
submissions/rune-activation/
├── demo.html      # Self-contained demo
├── style.css      # All styles + keyframes
└── README.md