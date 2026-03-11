# ⬡ PhotoBender

A powerful, browser-based photo editor inspired by Adobe Lightroom — built as a single self-contained HTML file. No installs, no sign-ups, no server. Just open and edit.

**Built by [Archit Kolte](mailto:architkolte@gmail.com)**

---

## ✨ Features

### 🎨 Editing
- **Light** — Exposure, Contrast, Highlights, Shadows, Whites, Blacks, Brightness, Gamma
- **Color** — Temperature, Tint, Vibrance, Saturation
- **HSL / Color Mix** — Hue, Saturation, Luminance per channel (Red, Orange, Yellow, Green, Blue, Purple)
- **Color Grading** — Interactive shadow/midtone/highlight color wheels
- **Detail** — Sharpness, Clarity, Noise Luminance, Noise Color
- **Effects** — Vignette, Grain, Dehaze, Fade, Split Toning
- **Geometry** — Rotate CW/CCW, Flip H/V, Straighten slider

### ✂️ Crop
- Freehand crop with rule-of-thirds grid overlay
- Locked aspect ratios: FREE, 1:1, 4:3, 3:4, 16:9, 9:16, 3:2, 2:3, 5:4, 4:5, 21:9

### 🎭 Masking ⚠️ (Experimental)
> **Warning: Masking is currently unstable and glitchy. Use at your own risk — it may hang or produce unexpected results. A proper rewrite is planned.**

- **Radial** — feathered elliptical mask by dragging
- **Gradient** — linear gradient mask by dragging direction
- **Brush** — freehand paint with Size, Feather, Flow controls
- **Luminance** — auto-generate mask from brightness range
- **Color Range** — click to sample a color, adjust tolerance

### 🔁 Before / After
- Drag a split-line divider to compare original vs edited

### 🎞 Presets
- 12 built-in presets (Vivid, Matte, B&W, Moody, Cinema, Fuji, Velvia and more)
- Import real Lightroom presets (.xmp / .lrtemplate files)

### 💾 Export
- Exports at full original resolution as lossless PNG

### Other
- Undo (Ctrl+Z) with 20-step history
- Manual value entry on every slider
- Live RGB histogram
- Drag & drop image loading
- Zoom in / out / fit

---

## ⚠️ Known Issues

| Feature | Status |
|--------|--------|
| Masking | Glitchy and unstable — avoid using for now. Rewrite in progress. |

---

## 🚀 Usage

1. Download `photobender.html`
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari)
3. Drop or open an image and start editing
4. Hit **Export PNG** to download at full resolution

No internet required after the first load (fonts are loaded from Google Fonts).

---

## 🛠 Tech Stack

- Vanilla HTML + CSS + JavaScript — zero dependencies, zero frameworks
- Canvas 2D API for all image processing
- `requestAnimationFrame` for smooth, non-blocking mask rendering
- Chunked pixel processing for large images

---

## 📸 Supported Formats

Input: JPG, PNG, WEBP  
Output: PNG (lossless, full resolution)

---

## 📬 Contact

Made by **Archit Kolte** — [architkolte@gmail.com](mailto:architkolte@gmail.com)  
Found a bug or have a feature request? Open an issue or send a mail.

---

⬡ Lightroom-style photo editor in a single HTML file — presets, crop ratios, HSL, color grading & more. Masking experimental. No install needed.
