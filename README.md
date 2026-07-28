# Steamon Trainers

Steamon Trainers adds the complete **Steamon League** as a custom [RCTMod](https://srcmc.gitlab.io/rct/docs/0.18/) (Radical Cobblemon Trainers) series: **8 Gym Leaders** (each with a thematic mono/bi-type team), the **Elite Four**, and a final **Champion**, chained together by a coherent level progression from roughly level 13 up to level 70.

This is a combined datapack + resource pack: the same file provides the trainer battles, teams, dialogue, advancements, loot, and the trainer skins. There is no separate resource pack to install.

## What's included

- 1 RCTMod series: `steamon` ("Steamon League")
- 13 trainers, gated in order via `requiredDefeats`:
  `Gym 1 -> Gym 2 -> ... -> Gym 8 -> Elite Four (1-4) -> Champion`
- Custom teams, AI settings, and battle rules per trainer
- Personality dialogue for battle start / win / loss
- Per-trainer defeat advancements (`rctmod:trainers/defeat_<id>`) for quest/progression hooks
- Loot tables per trainer, richer for the later Gym Leaders, the Elite Four, and the Champion
- 13 custom trainer skins (no separate resource pack needed - RCTMod loads `assets/rctmod/textures` straight from the datapack)

## Requirements

- Minecraft **1.21.1**, **NeoForge**
- [Cobblemon](https://modrinth.com/mod/cobblemon) **1.7.3+**
- **RCTMod (Radical Cobblemon Trainers) 0.18+** and **RCTAPI**

## Installation

Drop the downloaded file into your world's `datapacks` folder:

- **Server**: `world/datapacks/steamon-trainers.zip` (or unzipped folder), then `/reload` or restart.
- **Singleplayer**: same path inside your save folder, or via the in-game "Open World Folder" then `datapacks/`.

That's it — no separate resource pack step. RCTMod reads trainer skins directly from `assets/rctmod/textures` in any active datapack, so adding this one file gives you the battles, the progression, and the skins together.

## Forcing the league at spawn

By default RCTMod lets players pick a series through the in-game Trainer Association. To make the Steamon League the one players are dropped into automatically, set in `rctmod-server.toml`:

```toml
initialSeries = "steamon"
```

## Status

Early access / alpha. This is a first release of the league — feedback on difficulty, team compositions, and pacing is welcome.

A second **villain team** series is planned for a future update and is not implemented yet.

## Credits

Built for the [Steamon](https://modrinth.com/modpack/steamon) modpack (Create x Cobblemon, 1.21.1 NeoForge).
