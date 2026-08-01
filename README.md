# Locker Checking Day

A fast, mobile-friendly browser game inspired by the viral "Locker Checking
Day" videos.

## Technology

- HTML5
- CSS
- Vanilla JavaScript
- Browser `localStorage` for high scores
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

The game includes a two-part comic opening, three escalating timed locker
inspections, touch and mouse controls, scoring, grades, and saved high scores.
