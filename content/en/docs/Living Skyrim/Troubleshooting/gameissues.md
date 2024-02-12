---
categories: ["Living Skyrim"]
tags: ["docs"] 
title: "Gameplay Issues"
linkTitle: "Gameplay Issues"
weight: 2
description: >
  Common gameplay issues and how to fix them.
---


#### "All my saves are corrupted!"

This is a false corruption report. Please try restarting your game completely.

#### "How do I start the Main Quest?"

Talk to Jarl Balgruuf.

#### “The Main Quest doesn’t proceed after retrieving the Dragonstone.”

Read this modpage: [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704)

#### “Tolfdir doesn’t invite me to Saarthal right away.”

Read this modpage: [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704)

#### "I can't join the Stormcloaks/Imperial Legion."

Start the main quest and progress it to at least Way of the Voice. See above questions for how to start the main quest.

#### "I can't complete the First Lessons quest for the Mage College!"

Please disable the Projectile Block and Timed Projectile block options in Valhalla Combat's MCM menu, once the quest is completed you are free to turn these options back on should you wish.

#### "I can't join the Thieves Guild!"

You need to actually be a thief, please see this mod page: [Thieves Guild Requirements](https://www.nexusmods.com/skyrimspecialedition/mods/33256)

#### "I Can't power attack!"

We Use One-Click Power attack in the list, to help the MCO combo attacks work correctly. There is an .ini file in the mod folder you can adjust the keybind for this (default is Mouse 3).

#### “Can I access RaceMenu after character creation?”

Only if you are not changing your character’s gender or race. Changing gender/race will cause issues with powers and passive buffs your character has. Please use the `ShowRaceMenu` command after the MCM steps have finished.

#### “My screen is zoomed in or weirdly off-center.”

Check the SSE Display Tweaks INI file to make sure you have the resolution for your screen set correctly. You may also need to check BethINI or the Skyrim INI files to make sure they all match your screen’s resolution. If you are using an Ultrawide resolution please enable the relevant mods in the List Customization Section of Mod Organizer. If that fails, please find the SkyrimSE exe file in your Stock Game folder (located wherever you installed the list. **not your Steam folder**.) Right Click the exe file, then click Properties. On the Compatibility tab, select Disable Display Scaling On High DPI Settings, and then click OK.

#### "How can I adjust graphical/resolution settings?"

A program called BethINI is included with the Living Skyrim installation. You can find it in the `Living Skyrim\Tools\BethINI` folder. Run the program (**MAKE SURE Mod Organizer IS CLOSED**) and adjust your settings as necessary.

#### "Interiors are too dark/bright."

Instructions here are for the default ENB, if you have changed it you will need to search for the settings on your own. Open the ENB configuration menu in game with `Shift+Enter` Navigate to the `ENBEffect.fx` menu on the right side of the configuration screen. You will see two options near the top of this section, The first is the `Nights` modifier, Set this to a lower number between 0.5 and 1 to make nights brighter outdoors. Set it to a number between 1 and 2 to make them darker. Repeat this for the `Interiors` setting using the same number scale. Press **Save Configuration** in the top left and then close the menu using `Shift+Enter` again. ***DO NOT CLICK APPLY CHANGES*** This will load the configuration from the .ini file and you will lose your changes.

#### “MO2 cannot find SKSE.”

You’ll need to manually set the path for SKSE using the Edit Executables menu in MO2. Set it to `[install folder]\Stock Game\skse64_loader.exe`. Alternatively your Antivirus software may be interfering with the installation, set exceptions and/or disable as necessary.

#### “Can I use a controller?”

I strongly advise against it. With as many mods as there are in the list, you’ll need a full breadth of keyboard keys to activate and use every feature. If you absolutely must play with a controller, please, for the love of all that is holy, use Gamepad++.

#### “My game freezes when saving.”

Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

#### “Can I play this list on a 75/100/144hz screen?”

Yes. Display Tweaks SSE is included to allow higher refresh rates.

#### “Can I use this list on an ultrawide monitor?”

Yes, Nordic UI patches for 21:9 and 32:9 aspect ratios are included by default. Just make sure to enable the correct version for your aspect ratio in the left pane of MO2 under the 'Configuration Specific' seperator. Please also enable the Constructible Object Custom Keyword System - Ultrawide Aspect Ratio - 32 x 9 Patch regardless of which aspect ratio you use.

#### Nudity?

By default, Living Skyrim has every character be never nude. Underwear is worn by all NPCs and the player character and cannot be unequipped. Support is not provided for making the list Nude.
