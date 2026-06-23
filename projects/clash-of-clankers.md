# ClashOfClankers

**Status:** Completed  
**Repo:** [parm2006/ClashofClanker](https://github.com/parm2006/ClashofClanker)  
**License:** GPL v3

An AutoHotkey v2.0 automation bot for Clash of Clans, handling multiplayer loot farming, resource collection, and wall upgrades — with full OCR-based screen reading and interactive calibration.

## Features

- **Client-Relative Clicks**: Immune to window movement, maximized states, and scaling issues.
- **Auto Loot Search**: Scans and parses Gold and Elixir counts during matchmaking using OCR.
- **Smart Deployment**: Deploys troops, siege machines, heroes, and spells sequentially along configurable sides.
- **Automated Wall Upgrades**: Upgrades walls dynamically based on custom resource thresholds.
- **Builder Base Support**: Fully automated Builder Base attacks (Phase 1 & 2) with dynamic transitioning based on battle results and stars.
- **Automatic Base Detection**: Detects whether you're viewing the Main Village or Builder Base and runs the appropriate loop.
- **Interactive Calibration Wizards**: Step-by-step calibration for both Main Village (25 targets) and Builder Base (5 targets).
- **GUI Controls**: Runtime-configurable farming thresholds, delay tuning, randomization offsets, and troop deployment counts.

## Technical Stack

- **AutoHotkey v2.0** — scripting, GUI, hotkey management.
- **Built-in OCR** — screen-state detection for loot values and base identification.
- **INI-based config** — per-installation settings kept out of version control.

## Hotkeys

| Hotkey | Action |
|---|---|
| `Ctrl + F1` | Start / Cancel Main Village Calibration |
| `Ctrl + F2` | Start / Cancel Builder Base Calibration |
| `F1` | Unified Start (auto-detects base and starts loop) |
| `F2` | Pause Bot Loop |
| `ESC` | Exit Bot |
