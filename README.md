# Box Box Racing

A mobile-friendly car pack opening and racing game for the browser.

## Gameplay

- Buy Street, Sport, and Elite car packs.
- Collect 12 fictional cars across four rarity tiers.
- Pull duplicates to level up cars and improve their stats.
- Select any owned car from the garage.
- Race on three circuits and use nitro to compete for credits.
- Progress is saved in browser `localStorage`.

## Technology

- HTML5
- CSS
- Vanilla JavaScript
- GitHub Pages-compatible static hosting

There is no framework, backend, package manager, or build step.

## Run locally

From this folder, run any static file server. For example:

```powershell
dnx dotnet-serve -- --port 8080 --directory .
```

Then open `http://localhost:8080/`.

## Structure

- `index.html` contains the page structure, styling, game data, and game logic.
- `README.md` documents the game.
