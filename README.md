# DOOMAZE

An early-development 2.5D shooter in the style of the classic 90s games, built with HTML, CSS and JavaScript on a `<canvas>`. Find your way through the maze, deal with what's in there, and reach the exit.

**Play it:** https://crouswebco-max.github.io/doomaze/ (on a computer, with a keyboard and mouse)

## Controls

| Key | Action |
|---|---|
| **W A S D** | Move |
| **← →** | Turn |
| **Click** or **Space** | Shoot (hold for automatic fire) |
| **1 2 3** | Switch weapons |
| **R** | Restart |

## What's in it

- **Raycasting** draws the 3D view: for each column of the screen, a ray is traced through the maze grid to find the nearest wall, and its distance sets how tall that slice of wall is drawn.
- A **minimap** in the corner, with you, the enemies and the exit.
- **Health, ammo and reloading**, three weapons and enemies to clear.
- A short story intro (press Space to skip).

## Status

Early development. It needs a keyboard and mouse, so it doesn't work on phones yet.

## Run it locally

Open `index.html` in a browser. There's nothing to install.
