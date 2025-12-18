# Password Generator (Vite + React + javascript + html + css)

A clean, responsive password generator with secure randomness (Web Crypto), entropy-based strength meter, copy-to-clipboard, show/hide, and fully customizable character sets.

## Features
- Secure RNG via `crypto.getRandomValues` (fallback to `Math.random` only if unavailable)
- Strength meter using entropy (bits) with clear labels
- Include/exclude: lowercase, uppercase, numbers, symbols
- “Exclude ambiguous” option (e.g., 0/O, 1/l/I)
- Length slider (4–128) + numeric input
- One-click generate, copy, show/hide, and reset
- Keyboard: **Enter** = regenerate, **Cmd/Ctrl+C** = copy
- Accessible labels/aria; responsive, minimal UI

## Tech
- Vite, React (JS), vanilla CSS, and HTML5.

## Quick Start
```bash
npm i
npm run dev
# build
npm run build
npm run preview
