---
title: "Using A Controller"
description: "A guide to using a controller with Living Skyrim."
lead: ""
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  livingskyrim:
    parent: "living skyrim"
weight: 80
toc: true
---

Living Skyrim supports a controller or gamepad out of the box. If you wish to use a controller, follow this guide.

## Before You Get Started
This guide assumes you are using an XBox or equivalent gamepad.  Please note that, in this guide, RB/LB are the *top* shoulder buttons, and LS/RS refer to "clicking" the left and right sticks.  Also, when using button combos (e.g. RB+LS) the first button should be pressed and held before the second button is pressed.

The current version of LS3 at the time I'm writing this guide is 3.6.0.  It should, however, mostly apply to any previous or future versions of LS3 that include Gamepad++.

## Enable Gamepad++

The first thing to do is open Mod Organizer and enable the Gamepad++ mod.  Gamepad++ is essential to get the most out of LS3 with a Gamepad.  Gamepad++ turns the LB, RB, and B buttons into "combo buttons" which greatly expands the number of functions that can be performed with the gamepad.  For example, you can press B+Y to open the Tween menu, but you can also use RB+LS to open inventory, RB+A to open the map, etc.  It is *absolutely essential* that you look at the graphic available on Gamepad++'s Nexus page or in its MCM to see what the built-in button configuration is.

The other thing Gamepad++ does is allow you to map the Directional Pad (and combos with the D-Pad) to keypresses, which is the key to getting the most out of LS3 with a gamepad.  I will upload a preset I've made for LS3 that you can load within the Gamepad++ MCM, so you can get started quickly, but feel free to configure it to your liking.

## Rhone's Gamepad Preset

First thing's first, download this preset. 

[Click Here to download the preset](https://drive.google.com/file/d/1HcuoBi-dJlOAHqi0JW7unnAQY4GUXIu0/view?usp=sharing)

{{< alert icon="🛑" >}}
**WARNING!**

**This preset must be unzipped directly into your LS3\mods folder, using an "Extract Here" option, not one that creates its own folder.**
{{< /alert >}}

## In-Game Configuration

After enabling Gamepad++, run the game.  If you are starting a new character, please make sure all scripts finish loading and follow all directions in the LS3 Readme.  Now, we're going to do some configuring.

- Settings
  - Gameplay
    - Make sure "Controller" is enabled
  - Controls
    - Check if B and/or RB are set in there.  If they are, highlight them and press T to clear them, since they will block the buttons from being used the way Gamepad++ uses them. 
- MCM
  - Dual Wield Parrying
    - Set Block Key to RB.
  - True Directional Movement
    - Target Lock
      - Set Toggle Target Lock Key to B.
  - The Ultimate Dodge Mod
    - Enable Gamepad/Controller Compatibility, and choose Sneak Style 1 or Sneak Style 2.  The result is that LS will handle both sneaking and dodging.  LS will toggle sneak while standing still, and will dodge while moving with weapons drawn.  As far as I can tell, the difference between Style 1 and Style 2 is that Style 1 will dodge with weapons drawn even while not moving, while Style 2 will only dodge while moving.  I choose Style 2, but you may prefer Style 1 if you are not using stealth and for some reason want to dodge without choosing the direction you dodge in.
  - Gamepad++
    - Controls
      - Seriously, look at this image until you understand it
  - Gamepad++
    - Presets and Info
      - After you download my preset and put in in the right spot, you can Load it here.  Otherwise, you can play around in the rest of the MCM and configure things however you like.
  - Vision
    - Set Hunter Sense Key to "[" and Night Vision Key to "]"
  - Campfire
    - Gameplay -- Set Instincts Key to "-" (the one on the number row, not numpad); this is because the new Quick Mass Follower Commands Hotkey mod takes over the apostrophe for its own use, and doesn't have an MCM to configure like Campfire does.
  - Follower Framework
    - Interaction
      - Set Open Player Chest Hotkey to "O" (the letter, not the number), and Place Player Chest Hotkey to "K".

With these settings, RB is your button for dual wield parry and B is your button for target lock.  Those buttons will still work as combo buttons, but it goes without saying that you probably don't want to map things you're going to use in combat to the RB or B combos.  Unless you know what you're doing.  Like using a hotkeyed SmartCast spell ring and mapping it to an RB combo so you can specifically fire off that spell *while* parrying.

Now you will have the following set for you:
- Hotkeys 1-4 on dpad, 5-8 on dpad double-taps.
- B+Up for Quick Mass Follower Commands Hotkey.
- All Campfire functions mapped to LB+dpad combos.
- Predator Vision, Night Vision, Open and Place Player chest on RB+dpad combos.

Credit to Rhone for the LS3 Gamepad Guide. Thanks Rhone!
