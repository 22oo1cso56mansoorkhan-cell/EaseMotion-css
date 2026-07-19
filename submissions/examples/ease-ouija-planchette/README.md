 README.md

## 🔮 Ouija Planchette

A mystical ouija planchette moving on board animation. This component captures the eerie, mysterious atmosphere of a spirit board session — featuring a detailed ouija board with letters, numbers, and symbols, a movable planchette that glides across the board, glowing effects, and messages that spell out words letter by letter.

---

## ✨ Features

- **Detailed ouija board** – Letters A-Z, numbers 0-9, corner symbols, YES/NO, GOODBYE
- **Moving planchette** – Glides across the board with smooth animation
- **Message spelling** – Spells out words letter by letter
- **Highlight ring** – Pulsing ring around selected letters
- **Glowing effects** – Planchette and board with pulsing glow
- **Mystical atmosphere** – Dark, mysterious aesthetic
- **Interactive controls** – Move, reset, speed, and intensity
- **Click to move** – Click the board to trigger movement
- **Responsive** – Adapts beautifully to any screen size
- **Zero dependencies** – Pure CSS + vanilla JavaScript

---

## 🚀 How to Use

### 1. Include the CSS

```html
<link rel="stylesheet" href="style.css" />
2. Add the HTML structure
html
<div class="op-container">
  <div class="op-scene">
    <!-- Ouija Board -->
    <div class="ouija-board">
      <div class="board-texture"></div>

      <div class="board-border">
        <div class="board-corner bc-tl"></div>
        <div class="board-corner bc-tr"></div>
        <div class="board-corner bc-bl"></div>
        <div class="board-corner bc-br"></div>
      </div>

      <div class="board-title">OUIJA</div>
      <div class="board-subtitle">~ Mystifying Oracle ~</div>

      <!-- Letter grid (A-Z) -->
      <div class="letter-grid">
        <div class="letter">A</div>
        <!-- ... up to Z -->
      </div>

      <!-- Number row (0-9) -->
      <div class="number-row">
        <div class="number">1</div>
        <!-- ... up to 0 -->
      </div>

      <!-- Corner symbols -->
      <div class="corner-symbol cs-tl">☀</div>
      <div class="corner-symbol cs-tr">☽</div>
      <div class="corner-symbol cs-bl">★</div>
      <div class="corner-symbol cs-br">✦</div>

      <div class="answer answer-yes">YES</div>
      <div class="answer answer-no">NO</div>
      <div class="goodbye">GOODBYE</div>

      <!-- Planchette -->
      <div class="planchette" id="planchette">
        <div class="planchette-body">
          <div class="planchette-point"></div>
          <div class="planchette-hole hole-1"></div>
          <div class="planchette-hole hole-2"></div>
        </div>
        <div class="planchette-glow"></div>
        <div class="planchette-trail"></div>
      </div>

      <div class="highlight-ring" id="highlightRing"></div>
      <div class="board-glow"></div>
    </div>

    <div class="message-display" id="messageDisplay">
      <span class="message-text" id="messageText">⚡</span>
    </div>
  </div>
</div>
3. Add the JavaScript
html
<script src="script.js"></script>
The script automatically manages planchette movement, message spelling, controls, and interactions.

🎮 Controls
Move Planchette – Trigger a random movement and spell a message

Reset – Reset the planchette to center

Movement Speed – Adjust the speed of movements (0.3× to 3×)

Glow Intensity – Control the brightness of glows (0.3× to 2×)

Click on Board – Click anywhere on the board to trigger movement

🎨 Customization
CSS Variables
Variable	Default	Description
--move-duration	0.8s	Duration of planchette movement
--highlight-duration	0.5s	Duration of highlight ring
--glow-intensity	0.15	Intensity of board glow
--glow-size	400px	Size of board glow
--planchette-glow-size	60px	Size of planchette glow
Messages
The component includes a list of messages to spell:

text
HELLO, GOODBYE, YES, NO, HELP, LOVE, DREAM, STAR, MOON, SUN, FIRE, WATER, EARTH, WIND, SOUL, LIGHT, DARK, PEACE, HOPE, FAITH
🧩 Why It Fits EaseMotion CSS
Human‑readable — Classes like .ouija-board, .planchette, .letter-grid, .letter, .highlight-ring, and .board-glow are intuitive and descriptive

Animation‑first — The planchette moves with CSS, the highlight ring pulses with CSS, and the glow pulses with CSS — all driven by the animation engine

Declarative & customizable — All timing, size, and color values are exposed via CSS custom properties

Self‑contained — Zero external dependencies — works entirely with HTML, CSS, and vanilla JavaScript

Mystical & eerie — Captures the mysterious atmosphere of a spirit board session

Performance‑conscious — Uses GPU-accelerated transforms for smooth planchette movement

📁 File Structure
text
submissions/ouija-planchette/
├── demo.html      # Self-contained demo
├── style.css      # All styles + keyframes
└── README.md