# Super Battles

A tactical tabletop auto-battler that plays in the browser. Equip four original
superheroes, give each one a priority and a destination, then watch the round
resolve. Hold the relays or defeat the other squad. English and French.

Open `index.html` through any static web server, or play it on LOB7.

This repository is the playable edition (version 0.1.0), generated from the
development source with `tools/export-public.mjs`. `app.js` is a readable
bundle of the game code and three.js. Interface text lives in that bundle under
shared English/French keys (search for `"turn.resolve.solo"`).

- Code: MIT, see `LICENSE`.
- Miniatures, effects, sounds and music: CC BY 4.0, see `ASSETS-LICENSE.md`.
- Rules are an independent adaptation inspired by SWADE and the Super Powers
  Companion; this is not an official product and contains no rulebook text.
