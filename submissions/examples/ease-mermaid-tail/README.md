# Mermaid Tail · Tail Splashes on Interaction 🧜‍♀️

An interactive mermaid tail with iridescent scales, splashing water effects, and graceful tail movement. Click or press Space to make the tail splash with sparkling water particles!

## Features

- 🧜‍♀️ **Graceful Tail** – Beautiful mermaid tail with flowing movement
- ✨ **Iridescent Scales** – Each scale shimmers with unique colors
- 💦 **Splash Effect** – Click to trigger water splash particles
- 🎨 **Colorful Animation** – Scales shift through iridescent hues
- 🎮 **Speed Control** – Adjust animation speed (1-10)
- ⏸️ **Pause/Resume** – Toggle animation with button or Space key
- 🔄 **Reset** – Reset tail and clear splash particles
- 🌊 **Underwater Environment** – Ocean background with light rays and bubbles

## How to Use

1. **Click** on the canvas or press **Space** to make the tail splash
2. Watch water particles burst from the tail
3. See the tail wave and shimmer with iridescent colors
4. Press **PAUSE** or **Space** (when not splashing) to pause/resume animation
5. Adjust **Speed** slider to control animation pace
6. Press **RESET** or **R** to reset

## Controls

| Action | Method |
|--------|--------|
| Trigger Splash | Click canvas / Space |
| Pause/Resume | Click button / Space (when paused) |
| Reset | Click reset / R key |
| Speed | Drag slider (1-10) |

## Visual Features

| Feature | Description |
|---------|-------------|
| Tail Segments | 20 segmented scales with iridescent colors |
| Scale Shimmer | Each scale has unique hue, saturation, and lightness |
| Tail Fin | Graceful fluke with flowing movement |
| Splash Particles | 30-50 water particles with physics |
| Idle Sway | Gentle tail sway when not splashing |
| Wave Motion | Organic wave animation through the tail |

## Files Included

- `index.html` – Main HTML file with embedded JavaScript
- `style.css` – All styling and animations
- `README.md` – This documentation

## Technical Details

- **Tail Rendering:** 20 segments with elliptical scales and gradients
- **Iridescence:** HSL color shifting with time-based animation
- **Splash Physics:** Particles with gravity, velocity, and life decay
- **Wave Animation:** Sinusoidal wave propagation through tail
- **Performance:** 60fps with requestAnimationFrame

## Customization

You can easily customize:
- **Tail Length:** Modify `this.tailLength = 160`
- **Segments:** Change `this.segments = 20`
- **Wave Speed:** Adjust `waveSpeed` (0.04)
- **Wave Amplitude:** Modify `waveAmplitude` (20)
- **Splash Particles:** Change particle count in `triggerSplash()`
- **Colors:** Adjust `baseHue` and scale color ranges

## Browser Support

Works in all modern browsers:
- Chrome, Firefox, Safari, Edge
- Touch support for mobile devices

## Run Locally

Simply open `index.html` in your browser – no server required!

---

*Make the mermaid tail splash with a click!*