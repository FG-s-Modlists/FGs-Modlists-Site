---
categories: ["Living Skyrim"]
tags: ["docs", "how do i"] 
title: "...Change hotkeys?"
linkTitle: "...Change hotkeys?"
weight: 1
description: >
  How do I change the hotkeys for various mods?
---

## MCM Changes

Mod Configuration Menus are located in the pause/system menu under "MCM". 

### True Directional Movement

TDM has several hotkeys that you may want to rebind, such as the button to lock onto enemies (default Mouse 5/Forward). You can do so in its MCM. 

## INI/JSON Changes

To edit a mod's INI or JSON, open that mod's folder. Usually INI files are located at `SKSE\Plugins\` and JSON files are located in `[Mod Name]\` within the mod's folder. Mod folders are located at `[List Install Location]\mods\`. You can use any text editor (including Notepad) to edit the INI or JSON. Don't forget to save your changes!

### TK Dodge RE

TK Dodge RE has an INI file inside its mod folder that you can use to change the hotkey used to dodge. By default this hotkey is Left Alt (56). To see a list of hotkeys the mod can use, refer to [this list.](https://wiki.nexusmods.com/index.php/DirectX_Scancodes_And_How_To_Use_Them)

The line you should edit to change its hotkey is `DodgeHotkey = 56`, replacing 56 with the desired hotkey code.

You may also edit the amount of stamina required to dodge and the duration of invincibility frames in this INI by changing `Dodge Stamina = 10` and `iFrameDuration = 0.3` respectively.

### Equipment Toggle

Equipment Toggle has a `Config.json` file its mod folder that you can use to change the hotkey used to toggle your equipment's visibility. By default this hotkey is Down Arrow (208). To see a list of hotkeys the mod can use, refer to [this list.](https://wiki.nexusmods.com/index.php/DirectX_Scancodes_And_How_To_Use_Them)

The line you should edit to change its hotkey is `"key": 208,`, replacing 208 with the desired hotkey code.

Note that whichever hotkey you set for this mod will still follow the rules set in the rest of the `Config.json`, so if you toggle the visibility manually with the hotkey, the automatic hiding and showing of equipment will continue to function afterwards.

### One-Click Power Attack

OCPA also has an INI file inside its mod folder that you can use to change the hotkey used to toggle your equipment's visibility. By default this hotkey is Middle Mouse Click (258). To see a list of hotkeys the mod can use, refer to [this list.](https://wiki.nexusmods.com/index.php/DirectX_Scancodes_And_How_To_Use_Them)

The line you should edit to change its hotkey is `ForceRightKey=258`. Replace 258 with the code for the key you would like to use to power attack. Note that One-Click Power Attack intentionally disables the "hold button to power attack" functionality, so whichever key you select will be the one you have to press and release to power attack.