# Super Mario Sunshine - Pitius's Cinematic Showcase Config

My configuration for recording HUD-free cinematic footage of *Super Mario Sunshine* (NTSC-U) on the Dolphin Emulator. 

## Features
* **Cinematic Visuals:**
    * HUD removed (via Texture Replacement).
    * Heatwaves & Water Refraction disabled.
    * 60FPS patch.
    * Widescreen Code.
* **Filming Tools:**
    * Save/Load Position instantly.
    * Toggle Mario/FLUDD visibility on the fly.
    * Insomnia Mode (Mario never falls asleep).

## Prerequisites
1.  **Dolphin Emulator**
2.  **Super Mario Sunshine ISO** (NTSC-U / USA Version). *Codes will not work on PAL/JP.*

## Installation

### 1. Install the Config (Cheats & Graphics Settings)
Inside `GMSE01.ini` is my actual setup, but it includes codes which are not used.

For Details about the used codes check `Codes.md`

Copy the `GMSE01.ini` file from this repo into your Dolphin **GameSettings** folder.

* **Linux**
    `~/.local/share/dolphin-emu/GameSettings/`
* **Windows:**
    `Documents\Dolphin Emulator\GameSettings\`

Feel free to modify these to your liking in the Gecko Codes section in Dolphin.

### 2. Disable the HUD
Copy the `/invisible_hud/GMSE01` folder from this repo into your Dolphin **Load/Textures** folder.

* **Linux**
    `~/.local/share/dolphin-emu/Load/Textures/`
* **Windows:**
    `Documents\Dolphin Emulator\Load\Textures\`

Make sure the Load Custom Textures and Prefetch Custom Textures options are enabled in Dolphin at `Graphics>Advanced>Utility`

## Controls & Hotkeys

This config includes specific Gecko codes that use button combinations to control the scene.

| Action | Combination | Code Author |
| :--- | :--- | :--- |
| **Save Position** | `D-Pad Left` | Dan Salvato |
| **Load Position** | `D-Pad Right` | Dan Salvato |
| **Mario Visibility** | `X` + `D-Pad Left` (On) / `Right` (Off) | Ralf |
| **FLUDD Visibility** | `X` + `D-Pad Up` (On) / `Down` (Off) | Ralf |


## Credits & Mod List

This setup relies on the incredible work of the GameCube modding community.

**Technical Settings:**
* **Texture Pack:** No HUD by Sheldon Sharpe (Modified with manual glimmer fix)
* **Widescreen Fix:** 16:9 Culling Patch
* **Framerate:** 60FPS Comprehensive

**Visual Modifiers:**
* Disable Heat Waves (1inf)
* Disable HUD Particles (1inf)
* Disable Object Culling (1inf)
* Disable Water Refraction (1inf)
* Mario Never Sleeps / Insomnia Mode (Ralf)
* Mario & FLUDD Invisible (Ralf)

**Gameplay Tools:**
* **Position Save/Load Tool:** Dan Salvato
* Infinite Air, Health, & Lives (Codejunkies)
* Infinite Water Supply (Codejunkies)
* Moon Jump (Mathew_Wi)
* Walk/Swim/Levitate Underwater (James0x57)
