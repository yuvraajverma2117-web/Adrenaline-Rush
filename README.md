# Adrenaline Rush

A first 2D platformer made in Godot. The playable browser build is published as **Baby Zombie**.

**Play the game:** [yuvraajverma-web.itch.io/baby-zombie](https://yuvraajverma-web.itch.io/baby-zombie)

## About the game

Adrenaline Rush is a pixel-art platformer built around a tough but fair challenge. Bright scenery and a long course of platforms lead into moving-platform sections, tricky jumps, and traps. Good timing, patience, and practice help you reach the end: it is difficult, but doable.

## Gameplay

- Navigate a side-scrolling platform course.
- Time jumps across gaps and around hazards.
- Ride platforms that move along animated paths.
- Avoid traps; touching the kill zone restarts the level.

## Controls

- Move left and right: **Left/Right Arrow**
- Jump: **Space** (`ui_accept`)

## Run the project

1. Install **Godot 4.7** (the project declares Godot 4.7 features).
2. Open `project.godot` in Godot and run the main scene.

## Project contents

- `scenes/` — game, player, platform, trap, and kill-zone scenes
- `scripts/` — player movement and hazard reset logic
- `assets/` — pixel-art sprites, music, sound effects, and fonts
- `addons/` — Godot Super-WakaTime editor add-on

The original project includes the WakaTime editor add-on. Its API key is not part of this repository; configure it separately on your own machine if you use that add-on. Asset-pack licensing and credits are in `assets/brackeys_platformer_assets/LICENSE & CREDITS.txt` (the pack states CC0).
