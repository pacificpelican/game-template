# Browser Game Template

<p align="center">
  <img src="art/browser-game-template.svg" alt="Browser Game Template logo" width="640">
</p>

This repository is a starting point for designing and building a browser-based game. It contains a project prompt and a set of game-design standards for [Alta Redwood](https://altaredwood.work); it does not yet include a playable game or application code.

## Project files

- [`prompt.md`](prompt.md) — Instructions for the game-design task. Replace `*GAME_TITLE*` with the chosen title, add details about the planned game, and consult the standards before building.
- [`spec/alta-redwood-standards-for-game-design-v2.md`](spec/alta-redwood-standards-for-game-design-v2.md) — Guidance for the intended architecture, controls, menus, settings, visual design, persistence, and exports.
- `art/` — Optional location for project artwork. The prompt asks contributors to consult it if it exists.

## Getting started

1. Choose a game title and update `*GAME_TITLE*` in [`prompt.md`](prompt.md), then add to the file's text with instructions for the planned game's design, gameplay, flow, and details about functionality.  The more specific a walkthrough of the game's expected experience the better.
2. Read the design standards in [`spec/`](spec/).
3. If an `art/` directory is present, review its contents and use relevant artwork to inform the game's visual direction.  If you have art that should influence the game design, add it to the directory.
4. Use the prompt and standards to implement the game. Update this README with the actual setup, run, and test instructions when an application is added.

## Design direction

The standards describe a responsive desktop- and mobile-friendly browser game, with HTML5/JavaScript canvas as the frontend and PHP as the backend. They recommend local-first persistence with a path to MySQL/MariaDB, and a tiered NPC AI approach that can fall back to deterministic behavior.

They also outline shared conventions for touch and keyboard controls, pause and settings menus, screenshots and printable exports, account and save management, and visual direction. Treat these as design guidance for the game being built—not as features already implemented in this repository.
