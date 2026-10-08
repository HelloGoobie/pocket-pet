# 🐾 Pocket Pets

A tiny pet that lives on your Transport Tycoon screen. It walks along the bottom, climbs your minimap and the sides of the screen, swings across the ceiling, levels up as you play, and needs feeding with the money you earn. If you stop earning, it starves.

**Live app:** https://hellogoobie.github.io/pocket-pets/


---

## Pets

Pick one from the panel: 🐶 Dog · 🐱 Cat · 🐼 Panda · 🐧 Penguin · 🐸 Frog

Each has its own idle, walk (the frog hops), climb, ceiling swing, eating and sleeping animations, its own foods, and its own trail shape.

## Adding it

Add it as a **user app** using the live URL above. Click your pet to open its panel. Pin it to keep it on screen, or close it (F1 brings hidden apps back).

## Levelling up

- **Distance:** 1 XP for every 20 m you travel in game.
- **In-game levels:** if the game sends a `level`, `xp`, `exp` or `rank` value, the pet gets bonus XP when it goes up.
- **Petting:** click 💖 Pet for a little XP and a happy wiggle.

| Level | Unlock |
|---|---|
| 2 | Climbs over the map zone, first trail colour |
| 3 | Climbs the walls |
| 4 | Swings along the ceiling |
| 2 – 9 | A new trail colour every level |
| 10 | Top hat and the **rainbow trail** |
| 25 | Crown |

## Food, hunger and death

- Every time your **money goes up**, food falls from the top-right corner and piles up in the bottom-right corner. Bigger earnings drop more food.
- When hungry, your pet walks to the pile and eats.
- Hunger drains over about 20 minutes. At 0% it has 60 seconds left.
- If it starves it dies, **its XP resets to 0**, and it comes back after a short time at level 1.
- Don't want the risk? Turn off **Hunger** in the panel.
- Pets only fall asleep on the bottom of the screen.

### Money detection

The app watches the `money`, `cash` and `wallet` values from the game. 

## Trails

Each pet leaves its own shape: paw prints (dog, cat), leaves (panda), snowflakes (penguin), bubbles (frog). Pick any unlocked colour, **A** for auto (best unlocked) or ✕ for none.

## Settings

- **Map zone:** place the yellow box over your minimap so the pet climbs over it. Adjust left, width and height.
- **Size:** 1× – 3×.
- **Roam / Stay:** let the pet wander or keep it sitting.
- **Name:** rename your pet.

Everything is saved in your browser, so your pet keeps its level, food, hunger and settings.

## Notes

- Pets only move inside the app's window, so make the window full screen if you want them to roam the whole screen.
- Dying resets XP, which also locks your trail colours and accessories again until you level back up.

## Credits

Pixel art generated with AI image tools and cut into sprite sheets. App code and design by Goobie, built with Claude.
