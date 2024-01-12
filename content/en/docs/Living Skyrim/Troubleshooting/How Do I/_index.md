---
categories: ["Living Skyrim"]
tags: ["docs"] 
title: "How Do I...?"
linkTitle: "How Do I...?"
weight: 6
description: >
  Answers to all of your "How Do I...?" questions.
---

If your question isn't answered here, it may be answered on the [Wiki](https://wiki.fgsmodlists.com). If it isn't there either, please feel free to [request an addition to this page](https://github.com/ForgottenGlory/FGs-Modlists-Site/issues/new).

{{< scrollable-block id="addmods" title="How do I add mods?">}}

This is unsupported and unrecommended per Rule 11.

If you make modifications to these Modlists, you do so at your own risk. Unless otherwise specified, no support will be provided. Asking for support modding a list should be done within the Modding category on the Discord server. Additionally, do not suggest that someone break Rule 11 in an effort to fix issues with a list.

Also, if you have to ask, you probably shouldn't be trying to add mods to the list.

{{< /scrollable-block >}}

{{< scrollable-block id="gameresolution" title="How do I change the game's resolution?">}}
#### Changing Resolution
To change the resolution of the game, you should use BethINI. To launch BethINI, close Mod Organizer 2 and then navigate to the Tools folder inside your Living Skyrim install folder. BethINI can be used to tweak the game settings including resolution. Please note that if you are using the Performance profile, you will need to switch the INI Path in Bethini's Setup tab.

#### Borderless/Windowed Mode
To change the game to windowed or borderless mode, modify the INI inside the SSE Display Tweaks mod folder.
{{< /scrollable-block >}}

{{< scrollable-block id="farengar" title="How do I progress a quest?">}}
Many quests in Living Skyrim have been modified from their vanilla forms, primarily by [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704). You should familiarize yourself with this mod, but more details specific to Living Skyrim are below.

Dragonborn and Dawnguard are both delayed until you are high enough level to reasonably take them on thanks to [Timing Is Everything](https://www.nexusmods.com/skyrimspecialedition/mods/25464). You can tweak this mods' settings in its MCM if you wish.

#### Main Quest
Before anything else, you should know that the main Skyrim storyline is no longer a level 1 questline in Living Skyrim. Bleak Falls Barrow contains draugr that start at level 16 and the very first dragon fight is against a level 40 dragon. You should be at least level 10 before even considering starting the main story. Also, you should bring a follower or two just in case.

To begin the main quest, talk to Jarl Balgruuf. After speaking to him, Farengar becomes your point of contact for pretty much the entire questline. Whenever it seems that the main quest has stopped, talk to Farengar. The main storyline stops at multiple points (pretty much after every quest) to give you the opportunity to go do other things if you'd like. These breaks may also be necessary in the event you come across enemies that are far too strong for you to tackle.

#### College of Winterhold
Similar to the main quest, the College of Winterhold is not a level 1 questline. The draugr you fight in Saarthal will likely be at least level 15, if not higher. Come prepared.

The College of Winterhold questline now requires to you be a mage to actually participate in it. After First Lessons is complete, you'll need to speak to Tolfdir to begin the expedition to Saarthal. Like the main quest, the College of Winterhold has several points where it stops to allow you to go do other things. However, these stops are dictated by your magic skills. After Saarthal, you'll need a magic skill at level 50, 65, and then 90 to proceed with the subsequent quests. 

#### Thieves' Guild
The Thieves' Guild is one of the few questlines that can be done from level 1, though its later quests will definitely require you to be higher level than vanilla Skyrim.

However, to start the Thieves' Guild questline, you need to actually be a thief. Brynjolf won't speak to you about the Thieves' Guild unless you have stolen a certain amount of items, dictated by the [Thieves' Guild Requirements]() MCM. The breaks introduced to the Thieves' Guild questline are mainly dictated by the radiant quests, since they are optional to accept and complete. You'll need to complete a certain amount of radiant quests before being able to proceed with the next major quest in its line.

#### The Companions
The Companions questline can technically be started at level 1, but it depends on where the first radiant quest takes you as to what level you actually need to be to proceed with it. Regardless, the Companions questline functions very similarly to the Thieves' Guild questline - the breaks it has are dictated by radiant quests. You'll also need to complete many more radiant quests than vanilla Skyrim to proceed with the major quests in the questline. 

#### Dark Brotherhood
The Dark Brotherhood is largely unchanged, except for one major detail: "Good" characters can now complete the questline without committing a single crime, resulting in the destruction of the Dark Brotherhood. 
{{< /scrollable-block >}}

{{< scrollable-block id="hotkeys" title="How do I change hotkeys for various mods?">}}
#### MCM Changes

Mod Configuration Menus are located in the pause/system menu under "MCM". 

##### True Directional Movement

TDM has several hotkeys that you may want to rebind, such as the button to lock onto enemies (default Mouse 5/Forward). You can do so in its MCM. 

#### INI/JSON Changes

To edit a mod's INI or JSON, open that mod's folder. Usually INI files are located at `SKSE\Plugins\` and JSON files are located in `[Mod Name]\` within the mod's folder. Mod folders are located at `[List Install Location]\mods\`. You can use any text editor (including Notepad) to edit the INI or JSON. Don't forget to save your changes!

##### TK Dodge RE

TK Dodge RE has an INI file inside its mod folder that you can use to change the hotkey used to dodge. By default this hotkey is Left Alt (56). To see a list of hotkeys the mod can use, refer to [this list.](https://wiki.nexusmods.com/index.php/DirectX_Scancodes_And_How_To_Use_Them)

The line you should edit to change its hotkey is `DodgeHotkey = 56`, replacing 56 with the desired hotkey code.

You may also edit the amount of stamina required to dodge and the duration of invincibility frames in this INI by changing `Dodge Stamina = 10` and `iFrameDuration = 0.3` respectively.

##### Equipment Toggle

Equipment Toggle has a `Config.json` file its mod folder that you can use to change the hotkey used to toggle your equipment's visibility. By default this hotkey is Down Arrow (208). To see a list of hotkeys the mod can use, refer to [this list.](https://wiki.nexusmods.com/index.php/DirectX_Scancodes_And_How_To_Use_Them)

The line you should edit to change its hotkey is `"key": 208,`, replacing 208 with the desired hotkey code.

Note that whichever hotkey you set for this mod will still follow the rules set in the rest of the `Config.json`, so if you toggle the visibility manually with the hotkey, the automatic hiding and showing of equipment will continue to function afterwards.

##### One-Click Power Attack

OCPA also has an INI file inside its mod folder that you can use to change the hotkey used to toggle your equipment's visibility. By default this hotkey is Middle Mouse Click (258). To see a list of hotkeys the mod can use, refer to [this list.](https://wiki.nexusmods.com/index.php/DirectX_Scancodes_And_How_To_Use_Them)

The line you should edit to change its hotkey is `ForceRightKey=258`. Replace 258 with the code for the key you would like to use to power attack. Note that One-Click Power Attack intentionally disables the "hold button to power attack" functionality, so whichever key you select will be the one you have to press and release to power attack.
{{< /scrollable-block >}}

{{< scrollable-block id="helmet" title="How do I show my helmet?">}}
Helmets are automatically shown and hidden by [Equipment Toggle](https://www.nexusmods.com/skyrimspecialedition/mods/68540). By default helmets are hidden except for when you either draw your weapons or enter combat. When exiting combat or sheathing your weapons, the helmet will be hidden again.

To manually make your helmet show and hide, press the down arrow key.

You can also configure the Equipment Toggle INI in its mod folder to change when it shows and hides your helmet. Refer to Equipment Toggle's mod page for detailed information on how to modify its INI.
{{< /scrollable-block >}}

{{< scrollable-block id="controller" title="How do I use a controller with the modlist?">}}
ForgottenGlory's modlists are not specifically designed with controller support in mind. The amount of keybinds required by the modlist are much better suited to a keyboard and mouse, and you should use that setup if possible. 

However, if you do feel the need to use a controller, as of version 4.1.0, a controller layout may be optionally enabled, courtesy of Discord user hbkmog. To do so;

In MO2, scroll down to the List Customization separator. There you will find The Ultimate Control Scheme and Classic Sprinting Redone. Enable both of these.

There is also a file you need to move/delete. Navigate to `..\Living Skyrim 4\Stock Game`, find the ControlMap_Custom.txt, and either move it somewhere else (to back it up) or delete it.

From here, there are a few manual edits to make. Find the TK Dodge RE mod, double click it in MO2, then click over to the INI Files tab, and click on the TK Dodge RE.ini file on the left hand side and change the `EnableSprintKeyDodge=false` to `EnableSprintKeyDodge=true`. Close that window, allowing it to save.

The next step is to change an .ini file for One Click Power Attack. Following the same steps as above, change the `ForceRightKey=258` to `ForceRightKey=281`.

The last step is to load up the game. Press Escape to open the menu, then Settings. Enable "Controller" and you're good to go! Once again, thanks to hbkmog for setting this up!

The binds for this layout are as follows;
- A - activate/confirm/hold to turn on quick light
- B - hold B to sprint/tap to dodge.
- X - favorite menu
- Y - jump
- LB - left hand light attack/block when not dual wielding
- RB - right hand light attack
- LT - shout/power
- RT - power attack.
- Back - map
- Start - journal/pause menu
- Left stick - sneak
- Right stick - change POV/lock on enemy
- A+LB - inventory
- A+LT - magic
- A+RB - ready weapon
- A+back - wait
- A+start - quick save
- A+left stick - tween menu(mainly used for access statics screen)
{{< /scrollable-block >}}

{{< scrollable-block id="enbsettings" title="How do I change ENB settings?">}}
#### Changing ENB Settings
To change ENB settings, press Shift + Enter while in-game. This will open the ENB control panel. You can tweak the settings of ENB using this control panel.

#### Disabling ENB
To toggle ENB on and off while in-game, press Shift + F12. Disabling ENB can have massive performance effects, and is highly recommended for people with computer specifications close to the minimum recommended specs. 
{{< /scrollable-block >}}

{{< scrollable-block id="difficulty" title="How do I change the difficulty?">}}
You should spend some time reading the Simply Balanced MCM and tweak the settings to your liking. It can take quite some time to tune the settings to your preferences.
{{< /scrollable-block >}}

{{< scrollable-block id="brightness" title="How do I change brightness?">}}
The brightness of any given location is entirely subjective. For some, it may be too dark. For others, it may be too bright. Before anything else, you should know that this is not a bug. The perceived brightness (or darkness, as the case may be) of a location is based on a huge number of factors:

- Your monitor and its brightness/gamma settings.
- Your in-game brightness/gamma settings.
- The lighting mod being used.
- The ENB preset being used.
- Your eyes, believe it or not.
- External lighting in your room, such as lamps and windows.
- GPU settings.

It is impossible for us to design a modlist with 100% perfect lighting for everyone. If you find the brightness/darkness too much in either direction, the only thing we can recommend is to change settings until it is at an acceptable level for you. The first things you should try are switching ENB presets and adjusting brightness/gamma settings.

Living Skyrim and Masterstroke include an optional mod you can enable to make things brighter that you can try. Those lists also come with an ESP called "Lux - Even Brighter Templates.esp" that you can safely disable if you would like to make it darker. No support is provided for adjusting lighting/brightness in the modlists beyond this, and exceeding what's written here falls under Rule 11.
{{< /scrollable-block >}}

{{< scrollable-block id="autosaves" title="How do I turn on autosaves?">}}
In modlists created by ForgottenGlory, autosaves are turned off. Why? Well, autosaves can sometimes activate while scripts in the game are running. If that happens, there's a risk that you won't be able to load that saved game in the future.

To ensure your gaming progress is saved:

1. Familiarize yourself with the quicksave button. By default, it's the F5 key. Think of it as your game's safety net.
2. Always save before you hit a loading screen. Why? After a loading screen, there are often scripts running in the background. If you decide to save just after the loading screen, give it about 30 seconds. This pause ensures that all scripts have completed their actions.
3. Steer clear of saving during battles. In the thick of combat, the game is busy with many scripts. Saving during this time can risk corrupting your save.
4. And here's another tip: Don't overwrite the same save game repeatedly. This can gradually degrade the integrity of the save. Also, if you see a 'Quicksave' option in the escape menu, it's better to ignore it. Stick with the 'Save' option in the menu or use the F5 quicksave hotkey.

By following these steps, you'll make sure your game progresses smoothly and your adventures in Skyrim remain uninterrupted. Safe adventuring!
{{< /scrollable-block >}}