# CharSketch // Interactive ASCII

> **Distilling light into glyphs.** 
> A zero-footprint, client-side ASCII generator wrapped in a dark glassmorphism interface. 

CharSketch takes the chaotic pixel data of your images and forces them into an ordered matrix of text. No server-side processing. No API limits. No data leaving your machine. Just pure, immediate DOM manipulation taking place in the browser's memory.

---

## 🌑 The Architecture

Built for developers and digital artists who prefer the dark mode. CharSketch operates entirely within the void of a single HTML file. It leverages the HTML5 `<canvas>` API to read raw bitstreams, calculating the perceptual luminance of every pixel, and mapping it to a mathematical ramp of ASCII glyphs. 

It is fast, secure, and entirely self-contained.

### Core Features

*   **Phantom Processing:** 100% client-side rendering. Your images never touch a server, ensuring absolute privacy.
*   **Glass Void UI:** A deep midnight interface featuring translucent glassmorphism panels, glowing neon-cyan interactions, and custom scrollbars. 
*   **Perceptual Luminance:** Maps characters based on human eye sensitivity to RGB values (ITU-R BT.601), rather than a flat mathematical average.
*   **Algorithmic Ramps:** Choose your visual density:
    *   *Ultra-Detailed:* 70-character high-fidelity photographic mapping.
    *   *Minimalist:* 10-character high-contrast rendering.
    *   *Density Blocks:* Solid geometric shading.
    *   *Binary Matrix:* Pure `0` and `1` digital reconstruction.
*   **Fluid Interactions:** Drag-and-drop mechanics, active hover states, and seamless clipboard integration.

---

## 🛠️ The Stack

No node modules. No build steps. No bloated frameworks.

*   **Structure:** Vanilla HTML5
*   **Style:** Modern CSS3 (CSS Variables, Flexbox/Grid, Backdrop-filters)
*   **Logic:** Vanilla ES6 JavaScript

---

## ⚡ Initialization 

Because CharSketch is completely dependency-free, deployment is instantaneous.

1. Clone this repository or download the source code.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
3. The environment is now active.

```bash
# Terminal quickstart for local testing
git clone [https://github.com/yourusername/charsketch.git](https://github.com/yourusername/charsketch.git)
cd charsketch
open index.html
or just use live server extension or the deployed link
