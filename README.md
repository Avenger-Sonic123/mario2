# Pose-Controlled Mario — Asset Expansion

A later snapshot of the pose-controlled Mario-style game with additional sprite assets and local libraries.

**Repository created:** 2023-07-31  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2023-07-31

## Features and implementation

- Nose-based movement logic.
- Scrolling environment.
- Coin and enemy logic.
- Game sounds.
- Expanded sprite resources.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, p5.play, p5.sound, ml5.js, PoseNet.

## Project structure

| File | Purpose |
| --- | --- |
| [`characters_environment.js`](characters_environment.js) | Platformer engine and game-state functions |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`p5.min.js`](p5.min.js) | JavaScript implementation |
| [`sprites.js`](sprites.js) | Sprite and environment setup |
| [`style.css`](style.css) | Page styling |

Key functions in the source:
- `characters_environment.js`: `game()`, `startGame()`, `changeGameStatud()`, `instializeInSetup()`, `initializeCharacterStatus()`, `instializeInDraw()`, `getCoins()`, `coinVanish()`, among others.
- `main.js`: `gotPoses()`.
- `sprites.js`: `setSprites()`, `setSpriteGroups()`, `loadStaticObjects()`, `loadAnimatedObjects()`, `loadPlatforms()`, `MarioAnimation()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/mario2.git
cd mario2
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Allow camera access and follow the page instructions if the game initializes; inspect the console for missing resources.

## Current status and limitations

Existing game-engine code and assets are included, but successful execution and asset licensing have not been verified.

## Related project snapshots

Other repositories in this project family:
- [Mario](https://github.com/Avenger-Sonic123/Mario) — repository created 2023-07-31
- [mario3](https://github.com/Avenger-Sonic123/mario3) — repository created 2023-07-31

## Attribution

This repository contains game/example code and assets. Original authorship and asset licenses have not been established; preserve existing source credits and verify rights before redistribution.

---

Source reference: [`4fa0b3e4`](https://github.com/Avenger-Sonic123/mario2/tree/4fa0b3e414a88dee3780b688e7736c37a47ad6c3) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
