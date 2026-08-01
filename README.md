# MaxGame

A lightweight starter for a static browser game.

## Technology

- HTML5
- CSS
- Vanilla JavaScript
- Browser `localStorage` for progress and theme preferences
- GitHub Pages-compatible static hosting

There is no framework, backend, package manager, or build step.

## Run locally

From this folder, run any static file server. For example:

```powershell
dnx dotnet-serve --port 8080 --directory .
```

Then open `http://localhost:8080/`.

## Structure

- `index.html` contains the page structure, styles, and game logic.
- `README.md` documents the starter.

The JavaScript includes a small state model, save/load helpers, theme support,
keyboard input, rendering, and a `requestAnimationFrame` game loop ready to
replace with the new game's mechanics.
