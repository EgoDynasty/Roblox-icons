# Frostbound

A custom visual replacement pack for Roblox Rivals. Every icon keeps the original
asset's game function, silhouette and on-screen footprint, so nothing shifts or
rescales in the interface.

## Visual direction

Deep glacial ice over a dark core, with pale cyan light caught in the fractures

## Contents

- 729 replacement rules
- 729 unique PNG files
- 199 primary weapons
- 144 secondary weapons
- 143 gadgets
- 138 melee weapons
- 86 interface icons
- 19 rank emblems

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
