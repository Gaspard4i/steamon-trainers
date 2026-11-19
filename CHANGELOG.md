# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [2.0.0] - 2026-11-19

### Added

- The Steamos story in three team versions, as RCTMod series `steamos_spark`, `steamos_relic` and `steamos_might` (184 trainers in total, chained by `requiredDefeats`).
- Teams, dialogue and defeat advancements for every new trainer.
- Custom trainer types `team_flare` and `lanugo`.

### Changed

- Requirements: Cobblemon 1.8.x, RCTMod 0.19.2-beta, RCTAPI and Mega Showdown. Late story fights use levels above 100 and need Cobblemon `maxPokemonLevel` raised.
- README rewritten as a short project summary.
- The publish workflow now checks all four series and publishes to Modrinth only; a new workflow updates the Modrinth page.

### Fixed

- The dialogue of the Steamon League trainers moved to `dialogs/trainers/single/`, the folder RCTMod reads for per-trainer dialogue.

## [1.0.0] - 2026-07-28

### Added

- Initial release of the Steamon League as a standalone RCTMod series.
- 8 Gym Leaders with thematic mono/bi-type teams, chained by `requiredDefeats`.
- Elite Four (4 trainers) and a final Champion.
- Per-trainer dialogue, defeat advancements, and loot tables.
- 13 custom trainer skins bundled in the same datapack.
