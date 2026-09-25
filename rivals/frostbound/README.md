# Frostbound

A custom visual replacement pack for Roblox Rivals. Every icon keeps the original
asset's game function, silhouette and on-screen footprint, so nothing shifts or
rescales in the interface.

## Visual direction

Glacial ice and frozen steel. Weapons are cut from clear blue ice with frost-etched edges, rank emblems keep their tier colour.

## Contents

- 57 replacement rules
- 57 unique PNG files
- 39 interface icons
- 18 rank emblems

Rank emblems keep their original tier colour dominant, so players recognise their
rank at a glance. The pack changes icon artwork only; weapon meshes are untouched.

## Install

Load `pack/frostbound.json` in Fleasion, then clear the Roblox cache and
relaunch. All PNG URLs point at this repository's `main` branch.

## Technical notes

- every file is a PNG with a real alpha channel
- each icon sits inside the exact canvas size and bounding box of the asset it replaces
- artwork stays inside the original footprint, so it never grows in the UI
- checked for readability down to 48 px
