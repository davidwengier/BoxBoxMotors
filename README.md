# Box Box Racing

A mobile-friendly car pack opening and racing game for the browser.

## Gameplay

- Buy six packs, including JDM, European, American muscle, and hypercar collections.
- Collect 22 real production cars across four rarity tiers.
- Cars use distinct hatchback, SUV, roadster, sedan, muscle, supercar, and hypercar shapes.
- Pull duplicates to level up cars and improve their stats.
- Select any owned car from the garage.
- Drive time trials from a behind-the-car view with steering, throttle, and braking.
- Earn larger credit payouts for faster circuit times.
- Buy licenses to unlock advanced circuits with higher rewards.
- Save a personal-best lap time for every circuit.
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
