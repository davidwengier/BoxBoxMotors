# Box Box Motors

A mobile-friendly car pack opening and auto rental tycoon game for the browser.

Play at [wengier.com/BoxBoxMotors](https://wengier.com/BoxBoxMotors/).

## Gameplay

- Buy 23 packs, including Ferrari, BMW, Mercedes-AMG, Nissan, and McLaren
  collections, real racing go-karts, Trek and Surron bikes, 2025 Formula 1 cars,
  LEGO cars, and Fast & Furious movie cars.
- Buy packs individually or open a stack of five at once.
- Each pack has a stable pool of no more than 20 different cars.
- Every collectible car belongs to exactly one pack, with no repeats between packs.
- View every car available in a pack and track pack-specific collection completion.
- Collect exactly 300 vehicles across six rarity tiers, including 68 new BMW,
  Mercedes-AMG, Nissan, and McLaren models.
- Find five rainbow Limited-rarity production cars in existing packs.
- The main production collection uses Ford, Honda, Acura, Porsche, Chevrolet,
  Hyundai, Lamborghini, Lotus, Toyota, and Jaguar, while special packs use licensed
  movie cars and real LEGO Speed Champions models.
- Cars use distinct hatchback, SUV, roadster, sedan, muscle, supercar,
  hypercar, brick-built, go-kart, and open-wheel Formula 1 shapes.
- Car artwork adds model-specific aero, lighting, grilles, stripes,
  wheel designs, era details, and brand styling across all 300 vehicles.
- Track every obtainable car on an automatic collection checklist.
- Complete all 300 collectible vehicles to unlock the one-time black DugMobile reward,
  worth 5,000 credits per rental or 100,000 credits when sold.
- The bike pack includes a Mythic Surron Ultra Bee and a rainbow Limited
  Trek Marlin 5 Gen 3.
- The DugMobile keeps its black generated car body with a continuous row of
  matching Dug stickers from rear to front, tucked behind both wheel arches,
  and no coloured accent stripe.
- Reset the entire saved game from beside the Box Box Motors logo after
  confirming the warning.
- Store every packed copy as an individual car, including unlimited duplicates.
- Rent cars from the auto group to passive customers, with each customer choosing
  randomly from the individual cars currently available.
- Upgrade customer speed through five levels to shorten browsing and arrival times.
- Serve ten visually distinct customer types with varied clothing, skin tones,
  hairstyles, and accessories.
- Close the rental desk at any time to stop new rentals.
- Sleep to end the day, return every rented car, and see the day's income and rental totals.
- Process each returned car through interactive scanning, meter-based washing, refuelling,
  safety checks, and parking before it can be rented again.
- Hire up to five maintenance workers to process returns automatically, improving from
  five seconds per service part with one worker to one second with a full crew.
- Manual maintenance does not reset the automatic crew's current part progress.
- Sell available cars from the garage when you want immediate credits.
- Start with 10 storage spaces and buy larger warehouse expansions.
- Upgrade sourcing luck to visibly improve Epic, Legendary, and Mythic percentages.
  Limited odds stay fixed at 0.5%, except the Trek Marlin 5 Gen 3 at 1%.
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
