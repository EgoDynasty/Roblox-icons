# Roblox icon packs

Visual replacement packs for Roblox, built for [Fleasion](https://github.com/fleasion/Fleasion).
Each pack restyles a game's interface art while keeping every asset's original
function, silhouette and on-screen footprint, so nothing shifts or rescales in play.

## Packs

### Rivals

| Pack | Files | What it looks like |
|---|---|---|
| [Lavaforged](rivals/lavaforged) | 1147 | Volcanic glass shot through with living lava |
| [Frostbound](rivals/frostbound) | 57 | Glacial ice and frozen steel |

## A note on file counts

Rivals stores most weapon icons twice: a large texture for the weapon card and a
smaller one for list views, each under its own asset id. Both are replaced, so the
new art shows up everywhere. Counted as artwork rather than as files, Lavaforged is
672 designs; counted as replaced assets, it is 1147.

## Install

1. Open Fleasion
2. Load the pack JSON, for example `rivals/lavaforged/pack/lavaforged.json`
3. Clear the Roblox cache and relaunch

All image URLs point at this repository, so nothing needs to be downloaded by hand.

## How the packs are built

- every file is a PNG with a real alpha channel
- each icon sits inside the exact canvas size and bounding box of the asset it replaces
- artwork stays inside the original footprint, so it never grows in the interface
- rank emblems keep their tier colour, so players still read their rank at a glance
- kill-feed marks stay flat single-colour silhouettes, readable at speed
- weapons that exist in two resolutions ship both, the smaller one suffixed `_256`

## Layout

```
rivals/
  lavaforged/
    assets/    PNG files, grouped by weapon slot and interface section
    pack/      the Fleasion rule file
  frostbound/
    assets/
    pack/
```
