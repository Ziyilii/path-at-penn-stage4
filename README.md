# Path@Penn — Stage 4: HTML/CSS Prototype

This repository contains a **static, phone-sized** HTML/CSS implementation of the **opening screen** of my high‑fidelity prototype for the Path@Penn course registration app.

> The screen includes the app bar (brand + term), a rounded search field with a magnifying glass icon, a "Recommended Course" section, three course cards with times and seat counts, and a full‑width "View Cart" button. It matches the provided high‑fidelity mock in **layout, text, colors, and example data**, but is intentionally non‑interactive per the assignment (buttons are disabled).

## How to run
Just open `index.html` in any modern browser (Chrome, Safari, Firefox, Edge). No build tools or servers required.

## Files
- `index.html` — page markup
- `style.css` — styles (vanilla CSS, mobile first)
- (no JavaScript used)

## Notes
- The phone frame is simulated with a fixed 390×844 container to keep the layout phone‑sized on desktop.
- Fonts use Google Fonts **Inter**; system fallbacks are provided.
- Colors approximate the navy/gray used in the mock; feel free to tweak constants in `:root`.

## Attributions
- I used ChatGPT (GPT-5) to help me get started with the HTML and CSS code for my prototype. It gave me a basic layout and styling ideas, and then I went through the code myself to understand it and make edits so it matched my high-fidelity design. I only used it for vanilla HTML/CSS, and I made sure I know what each part of the code does.
- Magnifying‑glass icon is inline SVG drawn by me (no external assets).

