# 🔦 Light Prism – White Light Splits into Rainbow

An interactive light prism that splits white light into a vibrant rainbow spectrum on interaction. Watch as a beam of white light enters the prism and disperses into beautiful rainbow colors, with adjustable intensity, spread, and rotation. Built with pure HTML, CSS, and JavaScript – no external dependencies.

## ✨ Features

- **Realistic prism effect** – White light splits into rainbow spectrum
- **3D prism** – Rotating 3D prism with glass-like appearance
- **Rainbow dispersion** – 12 color rays spread from the prism
- **Adjustable parameters** – Light intensity (0-100%), spread (20-100%), rotation (0-360°)
- **Interactive controls** – Activate, Toggle, Reset, and Rotate buttons
- **Visual feedback** – Prism glow, color display, status messages
- **Keyboard shortcuts** – Space (Toggle), A (Activate), R (Reset)
- **Responsive design** – Adapts to any screen size

## 🚀 How to Use

1. Open `demo.html` in any modern browser (no server required).
2. Interact with the prism:
   - Click **Activate** to split white light into rainbow
   - Click **Toggle** to switch between active and idle states
   - Click **Reset** to return to default state
   - Click **Rotate** to rotate the prism
   - Click the **prism** itself to toggle
3. Adjust the sliders:
   - **Light Intensity** – Brightness of the light (0-100%)
   - **Spread** – How wide the rainbow spreads (20-100%)
   - **Rotation** – Prism rotation angle (0-360°)
4. Use **keyboard shortcuts**:
   - `Space` – Toggle
   - `A` – Activate
   - `R` – Reset

## 🧩 Files Included

- `demo.html` – complete interactive page (HTML + embedded JavaScript)
- `style.css` – all styling, prism design, and responsive layout
- `README.md` – you're reading it!

## 🧠 How It Works

- **Light beam** – White light beam enters from the bottom
- **Prism dispersion** – White light splits into 12 rainbow colors
- **3D rendering** – CSS 3D transforms create a realistic prism
- **Color rays** – Each ray has a different hue, spread, and opacity
- **Animation loop** – Uses `requestAnimationFrame` for smooth updates

## 🎨 Customization

| Parameter | Description | Default |
|-----------|-------------|---------|
| Intensity | Light brightness (0-100%) | 80% |
| Spread | Rainbow spread width (20-100%) | 60% |
| Rotation | Prism rotation (0-360°) | 0° |
| Rainbow Rays | Number of color rays | 12 |

### Modifying Rainbow Colors

```javascript
// In the HTML, modify the rainbow-ray elements
<div class="rainbow-ray" style="--hue: 0deg"></div>
<div class="rainbow-ray" style="--hue: 30deg"></div>
// Add more rays or change hue values