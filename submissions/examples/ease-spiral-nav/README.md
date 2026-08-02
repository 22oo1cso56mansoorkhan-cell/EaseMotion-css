# 🌀 Spiral Nav – Items in Spiral Pattern

An interactive spiral navigation menu where items are arranged in a beautiful, dynamic spiral pattern. Click items to select them, expand or collapse the spiral, and watch as items rotate and flow with smooth animations. Built with pure HTML, CSS, and JavaScript – no external dependencies.

## ✨ Features

- **Spiral arrangement** – Items positioned in a flowing spiral pattern
- **20+ item options** – Home, Explore, Gallery, Music, Videos, Profile, Settings, and more
- **Expand/Collapse** – Toggle between full spiral and collapsed view
- **Auto-rotation** – Spiral rotates slowly for dynamic feel
- **Item selection** – Click items to select, with visual feedback
- **Keyboard shortcuts** – E (Expand), C (Collapse), T (Toggle), R (Reset), Space (Toggle), 1-9 (Select items)
- **Customizable parameters** – Spiral tightness (1-10×), number of items (5-20), rotation speed (0-100%)
- **Visual feedback** – Selected item highlight, hover effects, status messages
- **Responsive design** – Adapts to any screen size

## 🚀 How to Use

1. Open `demo.html` in any modern browser (no server required).
2. Interact with the spiral:
   - **Click** any item to select it
   - Click **Expand** to show the full spiral
   - Click **Collapse** to contract the spiral
   - Click **Toggle** to switch between states
   - Click **Reset** to return to default
   - Click the **center** indicator to toggle
3. Adjust the sliders:
   - **Spiral Tightness** – How tightly wound the spiral is (1-10×)
   - **Items** – Number of items (5-20)
   - **Rotation Speed** – Auto-rotation speed (0-100%)
4. Use **keyboard shortcuts**:
   - `E` – Expand
   - `C` – Collapse
   - `T` – Toggle
   - `R` – Reset
   - `Space` – Toggle
   - `1`-`9` – Select items 1-9

## 🧩 Files Included

- `demo.html` – complete interactive page (HTML + embedded JavaScript)
- `style.css` – all styling, spiral layout, and responsive design
- `README.md` – you're reading it!

## 🧠 How It Works

- **Spiral positioning** – Items are positioned using logarithmic spiral math: `r = a + b * theta`
- **Dynamic layout** – Positions update in real-time based on tightness, count, and rotation
- **Smooth animations** – CSS transitions with cubic-bezier easing for fluid motion
- **Item data** – 20 predefined items with icons and labels
- **Selection system** – Click items to select with visual highlighting

## 🎨 Customization

| Parameter | Description | Default |
|-----------|-------------|---------|
| Tightness | Spiral tightness (1-10×) | 5× |
| Items | Number of items (5-20) | 12 |
| Rotation Speed | Auto-rotation speed (0-100%) | 30% |
| Item Data | 20 predefined items | Various |

### Modifying Item Data

```javascript
// In the ITEM_DATA array
const ITEM_DATA = [
  { label: 'Home', icon: '🏠' },
  { label: 'Custom', icon: '⭐' },
  // Add your own items
];