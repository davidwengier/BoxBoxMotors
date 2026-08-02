# Box Box Motors

A mobile-friendly car pack opening and auto rental tycoon game for the browser.

## Gameplay

- Buy 18 packs, including manufacturer collections, real racing go-karts,
  2025 Formula 1 cars, LEGO cars, and Fast & Furious movie cars.
- Buy packs individually or open a stack of five at once.
- Each pack has a stable pool of no more than 20 different cars.
- View every car available in a pack and track pack-specific collection completion.
- Collect 200 cars across six rarity tiers, including ten red Mythic cars.
- Find five rainbow Limited-rarity production cars in existing packs.
- The main production collection uses Ford, Honda, Acura, Porsche, Chevrolet,
  Hyundai, Lamborghini, Lotus, Toyota, and Jaguar, while special packs use licensed
  movie cars and real LEGO Speed Champions models.
- Cars use distinct hatchback, SUV, roadster, sedan, muscle, supercar,
  hypercar, brick-built, go-kart, and open-wheel Formula 1 shapes.
- Car artwork adds model-specific aero, lighting, grilles, stripes,
  wheel designs, era details, and brand styling across all 200 cars.
- Track every obtainable car on an automatic collection checklist.
- Complete all 200 pack cars to unlock the one-time black DugMobile reward,
  worth 5,000 credits per rental or 100,000 credits when sold.
- The DugMobile uses its custom Dug portrait instead of the standard car artwork.
- Use the one-time testing button on the Collection page to claim the DugMobile early.
- Store every packed copy as an individual car, including unlimited duplicates.
- Rent cars from the auto group to passive customers, with the cheapest available cars chosen first.
- Serve ten visually distinct customer types with varied clothing, skin tones,
  hairstyles, and accessories.
- Close the rental desk at any time to stop new rentals.
- Sleep to end the day, return every rented car, and see the day's income and rental totals.
- Process each returned car through interactive scanning, meter-based washing, refuelling,
  safety checks, and parking before it can be rented again.
- Hire up to five maintenance workers to process returns automatically, improving from
  five seconds per service part with one worker to one second with a full crew.
- Sell available cars from the garage when you want immediate credits.
- Start with 10 storage spaces and buy larger warehouse expansions.
- Upgrade sourcing luck for better epic and legendary chances.
- Grow the operation from a backyard car yard into a global dealer empire.
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
