---
categories: ["Masterstroke"]
tags: ["docs", "how do i"] 
title: "...Add RaceMenu/Bodyslide Presets?"
linkTitle: "...Add RaceMenu/Bodyslide Presets?"
weight: 1
description: >
  How do I add RaceMenu/Bodyslide presets?
---

## Bodyslide
Before you do anything with Bodyslide, you should refer to [this tutorial](https://www.youtube.com/watch?v=Wkwtgp3x25s) to understand how the program works. Yes, the tutorial is for Fallout 4 but the steps are identical for Skyrim Special Edition. Note that Bodyslide is already installed in Masterstroke, so you do not need to worry about installing the program.

If you just want to add a Bodyslide preset to the available options in OBody, simply download the bodyslide preset and install it using Mod Organizer 2. If you are unfamiliar with installing mods using Mod Organizer 2, refer to [this tutorial.](https://www.youtube.com/watch?v=7v0wWVuOagA)

## RaceMenu

### Adding a preset as a mod
If you download a RaceMenu Preset from Nexus or another website, simply install it as normal in Mod Organizer 2. If you are unfamiliar with installing mods using Mod Organizer 2, refer to [this tutorial](https://www.youtube.com/watch?v=7v0wWVuOagA). Note that the presets included with Masterstroke have been verified to work with the modlist, if you download a preset from Nexus or another website it may not work perfectly with the modlist. You may need to make tweaks to the preset in RaceMenu in-game to make the preset appear correctly.

### Adding a preset as a loose file
If you download a RaceMenu preset from the [FG's Modlists Discord](https://discord.gg/thg2eRxf7z) and want it to appear in-game, download the `.jslot` file and place it into `[Your modlist install location]\mods\Masterstroke Custom RaceMenu Presets\SKSE\Plugins\CharGen\Presets\` alongside all the other presets. Presets downloaded from the Discord should not require any tweaking to work correctly with the modlist.

### Converting presets to other races

{{< alert color="info" title="Info">}}
<div class="alert-icon">ℹ️</div>
This may or may not work, depending on the preset. Especially if the races are too different (Elf <-> Orc).
{{< /alert >}}

1. Pick the race the preset was made for.
2. Go to the Sculpt tap and save the head.
3. Change to your wanted race.
4. Load the preset again.
5. Go into the "Head" section and change "Face" to part 3 (High Poly Head)
6. Go into the Sculpt tab and load the previously saved head from step 2.
7. Close and open racemenu to fix tattoos.
8. Save the game.