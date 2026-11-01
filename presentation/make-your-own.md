The game ships with four heroes and one battlefield, and it is built to take yours. Everything below happens in the workshop, in your browser.

## Your character

- Paste or open a sheet in Super Battles JSON, or in plain text or Markdown. A text sheet is kept word for word, and attributes written like "Agility d8" are picked up.
- Then pick one of the four included heroes as a starting profile, which gives your hero that hero's power (kinetic field, piercing ray, repair nanites or super speed), and adjust its numbers within the game's limits: endurance 8 to 40, power 1 to 10, range 1 to 6, movement 1 to 6, armor 0 to 3, and a proficiency die from d4 to d12.
- Squads are set before round one. Your hero can be exported again as JSON or as a Markdown sheet.

## Your battlefield

- A battlefield is a JSON file: width and height from 5 to 15 tiles, up to 80 obstacles, up to 40 cover tiles, 1 to 5 relays, and two distinct starting tiles per squad.
- The game checks it before you play: nothing may sit on an obstacle, and every starting tile must be able to reach every relay.
- Importing a battlefield starts a new match. In a LOB7 room, change it before connecting.

## Your miniature

- An STL or a self-contained GLB, up to 12 MiB and 180,000 triangles, with every texture embedded and no Draco, Meshopt or KTX2 compression. Size and height are adjusted automatically.
- A GLB keeps its colors; an STL keeps its sculpt with a pale green material.
- The file stays on your device: it is not uploaded or included in match exports, and it never changes a hero's stats. You can swap miniatures between rounds.

## Formats and your AI

The formats folder of the game's source holds character.schema.json, example-character.json, map.schema.json and example-map.json. Download them with the game's sources on this page, or browse them on [GitHub](https://github.com/codex-lm/super-battles-play). The in-game How to play page also offers a guide for your AI agent to download, so you can describe a hero or an arena and let your AI write the file.

Want a new power, map or mode? Improve the game with your AI right here on LOB7, and share your edition.
