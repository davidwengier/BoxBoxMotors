# Box Box Motors

A mobile-friendly car pack opening and factory tycoon game for the browser.

## Gameplay

- Buy 15 packs, including manufacturer collections, LEGO cars, and
  Fast & Furious movie cars.
- Collect 100 cars across four rarity tiers.
- Every car is from Ford, Honda, Acura, Porsche, Chevrolet, Hyundai,
  Lamborghini, Lotus, or Toyota.
- Cars use distinct hatchback, SUV, roadster, sedan, muscle, supercar,
  hypercar, and brick-built shapes.
- Track every obtainable car on an automatic collection checklist.
- Store every packed copy as an individual car, including unlimited duplicates.
- Sell cars from the garage to earn credits.
- Start with 10 storage spaces and buy larger warehouse expansions.
- Upgrade factory pack luck for better epic and legendary chances.
- Grow the operation from a backyard workshop into a global auto empire.
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
