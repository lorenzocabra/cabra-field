# Cabra Field

An interactive particle field tool — upload any image and watch it dissolve into thousands of animated dots that react to your cursor.

![Cabra Field](https://img.shields.io/badge/status-live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

## Features

- **Image masking** — upload any image and particles fill the subject shape
- **Live cursor interaction** — dots scatter and swirl organically around your cursor
- **Zoom & pan** — scroll to zoom, space + drag to pan freely
- **Light / dark mode** — toggle between themes
- **Export** — save as transparent PNG, record as .mov, export config as JSON, or download the full HTML with your settings baked in
- **Fully configurable** — control count, dot size, variance, entropy, friction, drift, cursor radius and more

## Controls

| Control | What it does |
|---|---|
| count | Total number of particles |
| dot size | Global radius multiplier |
| size variance | Spread between smallest and largest dots |
| entropy | Cursor force strength |
| friction | How quickly particles brake after being pushed |
| drift speed | Speed of organic idle movement |
| cursor radius | Magnetic field reach of the cursor |

**Scroll** — zoom in/out toward cursor  
**Space + drag** — pan the canvas  
**Click + hold** — explosive scatter  

## Running locally

No build step needed. Just open `index.html` in any modern browser.

```bash
git clone https://github.com/YOUR_USERNAME/cabra-field.git
cd cabra-field
open index.html
```

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Your tool will be live at `https://YOUR_USERNAME.github.io/cabra-field`

## License

MIT — use it, fork it, build on it.

---

Made by [Cabra](https://github.com/YOUR_USERNAME)
