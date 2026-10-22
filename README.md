# MOOing

A retro Tamagotchi-inspired ASCII cow farming webapp, built with plain HTML, CSS, and JavaScript.

## Play

Open `index.html`, or visit the GitHub Pages deployment linked in this repository.

- Care for cows and bulls: feed, play, rest, pet, milk, and forage.
- Preview pasture staking and collect simulated $ACME.
- Play Hay Catch, explore paths, craft treats, and customize your pasture.
- Pair companions and raise non-tradable calves.
- Browse all 99 catalog drawings: 80 cows and 19 bulls.
- Read the in-app Guide for action values, recipes, costs, and cooldowns.

This is a front-end prototype. Wallets, real token transfers, staking contracts, minting, ownership verification, and shared multiplayer data are not connected. Progress is saved in the current browser's local storage.

## Files

- `index.html`: UI and local game logic; no build step required.
- `cow-catalog.js`: browser-ready collection data.
- `cow-catalog.json`: collection data, including original artwork, credits, sources, and license information.
- `.nojekyll`: serves the files directly on GitHub Pages.

## GitHub Pages

Publish from the `main` branch and `/ (root)` directory in Settings → Pages.

## Artwork attribution

ASCII artwork is adapted from The Complete Guide to Cows collections hosted by ASCII Art Archive (asciiart.eu), including the Summer 1991 editions edited by David A. Bader and contributions by the original ASCII artists. The catalog retains each drawing's source, credit, modification notes, and license metadata. Some matching drawings are also distributed by Sindre Sorhus and contributors in `sindresorhus/cows`.

Names and original drawing spacing are retained. Slogans, gameplay attributes, and cow/bull designations are game design assignments.
