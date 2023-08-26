---
categories: ["Masterstroke"]
tags: [] 
title: "Step 4 - Gameplay"
linkTitle: "Step 4 - Gameplay"
weight: 7
description: >
  Steps that need to be completed after installing Masterstroke.
---

To actually launch and then play Masterstroke, follow these steps:

1. Launch the copy of Mod Organizer 2 found inside your Masterstroke folder.
2. In the top-right corner of Mod Organizer, you’ll see a large dropdown menu. Select Masterstroke [SKSE] from this dropdown menu.
3. Click the large Run button.
4. A message box may appear asking you to update the game's registry path. Click Yes on this popup if it appears. If it does not appear, it is not an issue and likely means you've already done this.
5. This is how Masterstroke should always be launched. You can create a shortcut to this selection on your desktop, if you wish, using the Shortcut button directly below the large Run button.
6. Once Skyrim starts, create a new game.
7. Create your character and name them whatever you’d like.
8. As soon as you gain control of your character, do nothing. The mods are initializing and this can take several minutes. You’ll see a list of mods appearing in the top left corner of your screen.
9.  Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>

Masterstroke requires that the MCMs be configured for the list to work properly. Many features are disabled or incorrectly configured when a new game is created. The MCM Recording is not optional. For details about this process, please refer to the [MCM configuration](https://www.fgsmodlists.com/docs/masterstroke/post-install/mcm/) page for Masterstroke.
{{< /alert >}}

{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>
Loading a save from another modlist or from before you installed Masterstroke will corrupt that save, do not do this.
{{< /alert >}}

## Character Creation

{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>
The following steps should only be completed after you have completed the MCM steps for Masterstroke.
{{< /alert >}}

### Sets of Skills

Sets of Skills is a class mod that I encourage you to read the mod page about. It will allow you to select a class for your character that will give you buffs as you level up. Be sure to read the options carefully. To select a class, open the Sets of Skills MCM and pick a class from the dropdown menu.

### OBody

You likely want to customize the body of your character. To do so, *with all menus closed*, press the `letter U` key. A menu will appear with all of the installed body presets. You can select whichever one you like and can change it at any time by pressing the `letter U` key to open the menu again. This also works for NPCs - aim your crosshair at the NPC whose body you would like to change, press the `letter U` key and then pick a new body preset for them. 

### SexLab

The SexLab MCM contains an option for your character to be heterosexual, bisexual, or homosexual. You should open the MCM for SexLab and select your character's preference under the Sex Diary menu.

## MCM Configuration

{{< alert color="important" title="Important!">}}
<div class="alert-icon">⚠️</div>

It's important that you do the following steps in the order they are presented. Skipping around or going out of order is bad.
{{< /alert >}}

When you are finished making your character, a bunch of text will start scrolling in the top left-hand corner of the screen. **Wait for all text to disappear from the top left before proceeding.** If you receive any pop-up messages during this wait, click through them.

Now, *save your game*. Then *load that save.*

A popup will appear from SexLab - Sexual Fame talking about a consistence check of Papyrus location storage failing. This popup can be safely ignored, the issue will be resolved in a moment by MCM Recorder.

Once again, text will appear in the top left hand corner of the screen. **Wait for all text to disappear from the top left before proceeding.**

Now, go into the MCM and find MCM Recorder.

Click on the Masterstroke MCM option. You'll be prompted to exit the MCM. Do so. You'll then receive a popup with information about the MCM preset you've chosen. Click "Run Recording".

If you see a message saying "`Could not find MCM Option: Mod name: Sexlab Field name SSL__InstallUpdateSexlab(1.63)`", nothing is wrong, simply press continue and allow the recording to continue.

Once again, ***WAIT.*** This can take up to 10 minutes to complete. During this wait, if you receive any pop-up messages, click through them. When it is finished, you will receive one final pop-up message stating the MCMs are now configured.

Now *save your game*. Then *load that save.* Yes, this must be done a second time.

Now, configure your hotkeys per below and then move on to Character Creation.

### Hotkeys

Unfortunately MCM Recorder does not like setting hotkeys, so the following hotkeys must be set manually:

#### Take Notes!
- Controls
  - Open Journal: B

#### Immersive HUD
  - Toggle: RAlt

{{< alert color="info" title="Info">}}
<div class="alert-icon">ℹ️</div>
This is used to toggle the compass.
{{< /alert >}}
 
#### Valhalla Combat

- Compatibility
  - Alternate Blocking Key: V

If you wish you use the Executions feature of Valhalla Combat, you should set its hotkey in the Valhalla Combat MCM.

#### TK Dodge RE

If you wish to change the default dodge key from Left Alt to something else, use the `TK_Dodge_RE.ini` located in `[Install Folder]\mods\TK Dodge RE\SKSE\Plugins` to change it. A list of DirectX Scancodes for keyboard keys can be found [here.](https://wiki.nexusmods.com/index.php/DirectX_Scancodes_And_How_To_Use_Them)

#### Dual Wield Block
- Hotkey: V

#### SL Tools
- Tool key: O