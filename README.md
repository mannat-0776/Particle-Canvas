# ✦ Particle Canvas

An interactive generative art tool built with pure HTML, CSS, and Canvas API. Paint with physics-based particles — no libraries, no frameworks, just the web platform.

![HTML](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=flat-square&logo=html5) ![CSS](https://img.shields.io/badge/CSS3-Pure-1572B6?style=flat-square&logo=css3) ![JS](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript)

---

## ✨ Features

- **5 color modes** — Ink, Ember, Ocean, Prism, Sakura
- **Physics-based particles** — velocity, gravity, wobble, decay
- **Trail effect toggle** — persistent art vs live strokes
- **Brush size control** — from delicate dots to bold bursts
- **Download as PNG** — save your creations
- **Keyboard shortcuts** — 1–5 for modes, C to clear, S to save, T for trails
- **Custom cursor** — scales with brush size
- **Zero dependencies** — single HTML file

---

## 🚀 Usage

Just open `index.html` in any browser. No build step, no server needed.

```bash
git clone https://github.com/yourusername/particle-canvas.git
cd particle-canvas
open index.html
```

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1` | Ink mode |
| `2` | Ember mode |
| `3` | Ocean mode |
| `4` | Prism mode |
| `5` | Sakura mode |
| `C` | Clear canvas |
| `S` | Save as PNG |
| `T` | Toggle trails |

---

## 🎨 How It Works

Each mouse movement spawns particles based on cursor velocity. Fast movement = more particles, larger spread. Each particle has velocity, gravity, wobble, and alpha decay. Trail mode uses a semi-transparent fill each frame for the smear effect.

---

Made with ✦ by Mannat
