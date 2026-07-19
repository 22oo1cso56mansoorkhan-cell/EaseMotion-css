# README.md

## 🧪 Potion Brewing

A magical animated potion brewing with bubbling and color changes. This component captures the enchanting experience of alchemy — featuring a glowing potion flask with bubbling liquid, color-changing potions, steam rising, sparkles, and interactive controls that make every brew feel magical.

---

## ✨ Features

- **Glowing potion flask** – Detailed flask with glass effect and glow
- **Bubbling liquid** – 20 bubbles rising through the potion
- **Color changes** – 8 vibrant colors to choose from
- **Brew animation** – Cork pops, bubbles intensify, steam bursts
- **Steam particles** – 8 rising steam trails
- **Sparkle effects** – 10 sparkles on color change
- **Interactive controls** – Brew, change color, reset, and speed
- **Responsive** – Adapts beautifully to any screen size
- **Zero dependencies** – Pure CSS + vanilla JavaScript

---

## 🚀 How to Use

### 1. Include the CSS

```html
<link rel="stylesheet" href="style.css" />
2. Add the HTML structure
html
<div class="pb-container">
  <div class="pb-scene">
    <!-- Potion -->
    <div class="potion">
      <div class="flask">
        <div class="flask-body">
          <div class="flask-glass"></div>
          <div class="potion-liquid" id="potionLiquid">
            <div class="liquid-color"></div>
            <div class="liquid-surface"></div>
            <!-- 20 bubbles -->
            <div class="bubble b1"></div>
            <!-- ... up to b20 -->
          </div>
          <div class="flask-neck"></div>
          <div class="flask-rim"></div>
          <div class="cork"></div>
        </div>
        <div class="flask-glow"></div>
        <!-- 8 steam particles -->
        <div class="steam s1"></div>
        <!-- ... up to s8 -->
        <!-- 10 sparkles -->
        <div class="sparkle sp1"></div>
        <!-- ... up to sp10 -->
      </div>
      <div class="potion-label" id="potionLabel">✨ Potion</div>
      <div class="color-indicator">
        <span class="color-dot" id="colorDot"></span>
        <span class="color-name" id="colorName">Purple</span>
      </div>
    </div>

    <!-- Controls -->
    <div class="potion-controls">
      <button id="brewBtn">⚗️ Brew</button>
      <button id="changeColorBtn">🎨 Change Color</button>
      <button id="resetBtn">⟳ Reset</button>
      <label>Speed <input type="range" id="speedControl" /></label>
    </div>
  </div>
</div>
3. Add the JavaScript
html
<script src="script.js"></script>
The script automatically manages brewing, color changes, bubbles, controls, and interactions.

🎮 Controls
Brew – Trigger the brewing animation

Change Color – Cycle through 8 colors

Reset – Reset to the default color

Brew Speed – Adjust the speed of animations (0.3× to 3×)

🎨 Customization
CSS Variables
Variable	Default	Description
--bubble-duration	1.5s+	Duration of bubble rise
--bubble-delay	0s+	Stagger delay for bubbles
--steam-duration	2s+	Duration of steam rise
--sparkle-duration	1.2s+	Duration of sparkle flash
--glow-duration	1.5s	Duration of glow pulse
--cork-duration	0.4s	Duration of cork pop
Colors
Color	Hex
Purple	#8a5acc
Blue	#4a8acc
Green	#4acc6a
Red	#cc4a4a
Gold	#ccaa4a
Pink	#cc4a8a
Cyan	#4acccc
Orange	#cc7a4a
🧩 Why It Fits EaseMotion CSS
Human‑readable — Classes like .potion, .flask, .potion-liquid, .bubble, .steam, .sparkle, and .flask-glow are intuitive and descriptive

Animation‑first — Bubbles rise with CSS, steam flows with CSS, sparkles flash with CSS, and glows pulse with CSS — all driven by the animation engine

Declarative & customizable — All timing, size, and color values are exposed via CSS custom properties

Self‑contained — Zero external dependencies — works entirely with HTML, CSS, and vanilla JavaScript

Magical & enchanting — Captures the wonder of alchemy and potion-making

Performance‑conscious — Uses GPU-accelerated transforms for smooth bubble, steam, and sparkle animations

📁 File Structure
text
submissions/potion-brewing/
├── demo.html      # Self-contained demo
├── style.css      # All styles + keyframes
└── README.md