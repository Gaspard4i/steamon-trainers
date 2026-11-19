# Steamon Trainers

The trainers of the Steamon SMP, as a datapack for [Radical Cobblemon Trainers](https://modrinth.com/mod/rctmod).

You arrive on Steamos through a rift and pick a side: **Spark**, the inventors, **Relic**, the treasure hunters, or **Might**, the warriors. The same story plays out in each version, from your first duel to the fight against Team Flare and the league of the three leaders, with rivals, the Lanugo and a few surprises on the way. The original **Steamon League** (8 Gym Leaders, the Elite Four and a Champion) is still included.

## What it adds

- Three story series, `steamos_spark`, `steamos_relic` and `steamos_might`, about 60 trainers each, chained step by step
- The Steamon League series, `steamon`
- Teams, dialogue, defeat advancements (`rctmod:trainers/defeat_<id>`) and custom trainer types for Team Flare and the Lanugo
- Trainer skins for the league, loaded straight from the datapack

## Requirements

- Minecraft **1.21.1**, **NeoForge**
- [Cobblemon](https://modrinth.com/mod/cobblemon) **1.8.x**
- **RCTMod 0.19.2-beta** and **RCTAPI**
- **Mega Showdown** (some trainers Mega Evolve or Gigantamax)
- Late story fights use levels above 100: raise `maxPokemonLevel` in the Cobblemon config, and place those trainers persistently, or they will not appear naturally

## Installation

Drop the file into your world's `datapacks` folder (`world/datapacks/` on a server, then `/reload` or restart). To start a story, use the Trainer Association or `/rctmod player set series steamos_spark` (or `steamos_relic`, `steamos_might`). To drop every new player into one automatically, set `initialSeries` in `rctmod-server.toml`.

## Status

Early access. The new story trainers have not been played in game yet. Feedback on difficulty and pacing is welcome.

## Credits

Built for the [Steamon](https://modrinth.com/modpack/steamon) modpack (Create x Cobblemon, 1.21.1 NeoForge).
