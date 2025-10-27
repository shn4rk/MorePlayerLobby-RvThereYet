
**UE4SS + Mod V1.2 - BETA Pre-release**  

📢 UPDATE NOTE

New version: https://github.com/shn4rk/MorePlayerLobby-RvThereYet/releases/tag/Beta

This update automatically creates Game.ini.
Simply set your desired player count in config.ini and start the game — the mod will automatically generate Game.ini with the correct value.

We recommend using the latest stable release as this version is still in testing.

If you decide to try it out, we’d really appreciate your feedback!
---
---
## STEP-BY-STEP INSTALLATION GUIDE

**Important Note:**  
The mod should only be installed by the player hosting the session. Other players joining the session do not need to install the mod.

## Compatibility

- Tested on version 1.0.14337.
- If you're using a different version, the mod may work, but I cannot guarantee functionality.

---

1. **Prerequisites**
   - You must own the game version 1.0.14337.
   - Windows OS (as required by the game).
   - Ability to copy files into the game folder (admin rights may be required).

2. **Download**
   - Download the latest Release of UE4SS + Mod package from this git

3. **Install UE4SS + Mod**
   - Extract `UE4SS.rar`.
   - Copy all the file from the RAR into "GameDirectory\Ride\Binaries\Win64\" directory.

4. **Run the game once**
   - Start the game one time and then close it. This ensures the game generates the user config.

5. **Create / edit Game.ini**
   - After the first run, open (or create) the file "Game.ini" with this content in the path Yourusername\AppData\Local\Ride\Saved\Config\Windows :
     ```
     [/script/engine.gamesession]
     MaxPlayers=8  
     ```
     **Important Note:**
     The Game.ini may be removed when you restart your computer, so make sure it is present when you want to play.
     
6. **Run the game**
   - Start the game and start a lobby, invite from Steam not from the game.


7. **Increase Number of Player**
   - For increase the number of player just increase the value inside the Game.ini and inside the config.ini of the Mod on this path ue4ss\Mods\MorePlayerLobby\config.ini (The Max is 24), after that just restart the game.

## Attribution / Credits

This mod uses **UE4SS** (Unreal Engine 4 Script/Hook loader) for its functionality.

**UE4SS** is distributed under the **MIT License**.

- **Copyright (c) UE4SS contributors**
- **Repository:** [https://github.com/UE4SS/UE4SS](https://github.com/UE4SS/UE4SS)

This mod would not be possible without the incredible work of the UE4SS community.
Please consider supporting the development of UE4SS by visiting the official repository and contributing to the project.

---

**IMPORTANT:**  
The use of UE4SS is subject to its terms and conditions. The modder does not take responsibility for issues caused by using UE4SS or modifying the game.

---
