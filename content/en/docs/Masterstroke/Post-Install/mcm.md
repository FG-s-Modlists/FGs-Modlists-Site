---
categories: ["Masterstroke"]
tags: ["docs"] 
title: "MCM Setup"
linkTitle: "MCM Setup"
weight: 1
description: >
  The required MCM configuration steps for Masterstroke.
---

{{< alert color="important" title="Important!">}}
<div class="alert-icon">⚠️</div>

It's important that you do the following steps in the order they are presented. Skipping around or going out of order is bad.
{{< /alert >}}

## MCM Configuration

1. When you are finished making your character, a bunch of text will start scrolling in the top left-hand corner of the screen. **Wait for all text to disappear from the top left before proceeding.** If you receive any pop-up messages during this wait, click through them.
2. Now, *save your game*. Then *load the new save.*
3. If a popup appears from SexLab - Sexual Fame talking about a consistence check of Papyrus location storage failing. This popup can be safely ignored, the issue will be resolved in a moment by MCM Recorder.
4. Once again, text will appear in the top left hand corner of the screen. **Wait for all text to disappear from the top left before proceeding.**
5. Now, go into the MCM and find MCM Recorder.

![MCM Recorder](https://i.imgur.com/l2BGXX0.png)

5. Click on the Masterstroke MCM option. You'll be prompted to exit the MCM. Do so. You'll then receive a popup with information about the MCM preset you've chosen. Click "Run Recording".
6. If you see a message saying "`Could not find MCM Option: Mod name: Sexlab Field name SSL__ClickHere`", nothing is wrong, simply press continue and allow the recording to continue.

![MCM sexlab](https://i.imgur.com/xZAgSth.png)

7. Once again, ***WAIT.*** This can take up to 10 minutes to complete. During this wait, if you receive any pop-up messages, click through them. When it is finished, you will receive one final pop-up message stating the MCMs are now configured.

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

