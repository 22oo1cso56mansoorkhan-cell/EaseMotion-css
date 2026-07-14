# Bubble Blowing Fish

Fish blowing bubbles that rise, featuring interactive bubble blowing, 6 color palettes, speed control, and particle effects.

## Features

- **Bubble Blowing** – Fish blows bubbles when clicked
- **Rising Bubbles** – Bubbles rise with organic wobble
- **6 Color Palettes** – Rainbow, Ocean, Tropical, Galaxy, Neon, Pastel
- **4 Speed Settings** – Slow, Normal, Fast, Very Fast
- **Detailed Fish** – Animated fish with fins, eye, mouth
- **Particle Effects** – Sparkle particles on bubble blow
- **Bubble Glow** – Glowing bubble effects
- **Auto-Blow** – Fish occasionally blows bubbles automatically
- **Underwater Atmosphere** – Light rays, seaweed, sandy bottom
- **Keyboard Shortcuts** – B (blow), S (speed), C (color), R (reset), SPACE (blow)
- **FPS Counter** – Real-time frame rate display
- **Responsive** – Adapts to all screen sizes

## Technologies Used

- HTML5
- CSS3 (Animations, Gradients, Flexbox)
- Canvas API (2D context with gradients and shadows)
- Vanilla JavaScript (Particle system, Animation loop)

## Installation

1. Clone the repository:
   git clone https://github.com/yourusername/bubble-blowing-fish.git

2. Navigate to the project folder:
   cd bubble-blowing-fish

3. Open demo.html in your browser

## File Structure

bubble-blowing-fish/
├── index.html     # HTML structure with embedded JavaScript
├── style.css      # All styles and animations
└── README.md      # Documentation

## Usage

### Controls

| Action | Result |
|--------|--------|
| Click fish | Blow bubbles |
| "Blow" | Blow bubbles |
| "Speed: Normal" | Cycle through 4 speeds |
| "Color: Rainbow" | Cycle through 6 color palettes |
| "Reset" | Reset to default |
| B | Blow bubbles |
| S | Cycle speeds |
| C | Cycle colors |
| R | Reset |
| SPACE | Blow bubbles |

### Color Palettes

1. **Rainbow** – Full spectrum
2. **Ocean** – Blue/teal tones
3. **Tropical** – Warm tropical tones
4. **Galaxy** – Purple/pink tones
5. **Neon** – Bright neon colors
6. **Pastel** – Soft gentle colors

### Speed Options

- **Slow** – 0.005 (gentle bubbles)
- **Normal** – 0.02 (balanced)
- **Fast** – 0.04 (quick bubbles)
- **Very Fast** – 0.07 (rapid bubbles)

## How It Works

| Feature | Implementation |
|---------|---------------|
| Bubbles | Particle system with rising motion |
| Bubble wobble | Sine wave horizontal movement |
| Fish animation | Swimming motion with fins |
| Color palettes | HSL functions with position/time |
| Auto-blow | Random timer for bubbles |

## Customization

### Adding Color Palettes

Add to `colorPalettes` array:

```javascript
{
    name: 'MyPalette',
    body: (t) => `hsl(${value}, ${sat}%, ${light}%)`,
    fin: (t) => `hsl(${value}, ${sat}%, ${light}%)`,
    bubble: (t) => `hsla(${value}, ${sat}%, ${light}%, ${alpha})`
}