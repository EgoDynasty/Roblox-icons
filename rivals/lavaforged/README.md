# Lavaforged

A custom visual replacement pack for Roblox Rivals. Every icon keeps the original
asset's game function, silhouette and on-screen footprint, so nothing shifts or
rescales in the interface.

## Visual direction

Deep volcanic glass shot through with living lava. Weapons are recast as forged obsidian with molten seams, rank emblems keep their tier colour, kill-feed marks stay flat and instantly readable.

## Contents

- 1074 replacement rules
- 1074 unique PNG files
- 315 primary weapons
- 232 secondary weapons
- 232 gadgets
- 222 melee weapons
- 48 interface icons
- 19 rank emblems
- 6 panel backgrounds

Rank emblems keep their original tier colour dominant, so players recognise their
rank at a glance. The pack changes icon artwork only; weapon meshes are untouched.

## Install

Load `pack/lavaforged.json` in Fleasion, then clear the Roblox cache and
relaunch. All PNG URLs point at this repository's `main` branch.

## Technical notes

- every file is a PNG with a real alpha channel
- each icon sits inside the exact canvas size and bounding box of the asset it replaces
- artwork stays inside the original footprint, so it never grows in the UI
- checked for readability down to 48 px
