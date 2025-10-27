# MorePlayerLobby (Rv There Yet)

[![GitHub release](https://img.shields.io/github/v/release/shn4rk/MorePlayerLobby-RvThereYet?label=latest%20release&color=brightgreen)](https://github.com/shn4rk/MorePlayerLobby-RvThereYet/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Downloads](https://img.shields.io/github/downloads/shn4rk/MorePlayerLobby-RvThereYet/total?color=blue&label=downloads)](https://github.com/shn4rk/MorePlayerLobby-RvThereYet/releases)
![UE4SS Compatible](https://img.shields.io/badge/UE4SS-Compatible-green)
![Written in Lua](https://img.shields.io/badge/Written_in-Lua-2C2D72?logo=lua&logoColor=white)
[![Stars](https://img.shields.io/github/stars/shn4rk/MorePlayerLobby-RvThereYet?style=social)](https://github.com/shn4rk/MorePlayerLobby-RvThereYet/stargazers)

---

## 🧩 UE4SS + Mod V1.2 — **BETA Pre-release**

📢 **Update Notes**

➡️ [Download the new version here](https://github.com/shn4rk/MorePlayerLobby-RvThereYet/releases/tag/Beta)

This update automatically creates the `Game.ini` file.  
Simply set your desired player count inside `config.ini` and start the game —  
the mod will automatically generate a proper `Game.ini` with the correct value.

We recommend using the **latest stable release** once it’s available, as this version is still in testing.

If you decide to try it out, **we’d really appreciate your feedback!**

---

## ⚙️ Step-by-Step Installation Guide

> 💡 **Note:** Only the host needs to install the mod.  
> Players joining the session **don’t need** to install anything.

### 1. Prerequisites
- Game version **1.0.14337**
- Windows OS

### 2. Download
- Get the latest release of **UE4SS + Mod package** from this repository.

### 3. Install UE4SS + Mod
- Extract `UE4SS.rar`.
- Copy all files from the archive into your  
  `GameDirectory\Ride\Binaries\Win64\` folder.

### 4. Run the Game Once
- Start and then close the game to allow it to generate its config files.

### 5. Create or Edit `Game.ini`
- After the first run, navigate to:
 `C:\Users<YourUser>\AppData\Local\Ride\Saved\Config\Windows\`

- Create or edit `Game.ini` with:

```ini
[/script/engine.gamesession]
MaxPlayers=8
```


> ⚠️ The file may be deleted after restarts —  
> in **v1.2 Beta** the mod automatically recreates it based on your `config.ini`.

### 6. Launch the Game
- Start the game, host a lobby, and invite your friends.

### 7. Increase Player Limit
To raise the number of players:
- Edit the value inside both:
  - `Game.ini`
  - `ue4ss\Mods\MorePlayerLobby\config.ini`
- Maximum value: **24**
- Restart the game after editing.

---

## 🧠 Compatibility
- Tested on version **1.0.14337**
- May work on newer versions, but not guaranteed.

---

## 🏗️ Attribution / Credits

This mod uses **[UE4SS](https://github.com/UE4SS/UE4SS)** — Unreal Engine 4 Script & Hook Loader.

UE4SS is distributed under the **MIT License**.  
**Copyright (c) UE4SS contributors**

This mod wouldn’t be possible without the incredible work of the UE4SS community.  
Please consider supporting their development through the official repository.

---

## ⚠️ Disclaimer
Use of UE4SS is subject to its own license and terms.  
The author of this mod is **not responsible** for issues caused by modifying the game.

---
