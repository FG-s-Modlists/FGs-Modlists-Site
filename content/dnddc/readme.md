---
title: "Readme"
weight: 1
layout: "dnddcbase"
---

Current version: 10/10/2021 2.2.1

## Before You Get Started

{{< tip >}}
**Important!** 

Sections labeled important like this one will tell you when you need to pay extra attention to something.
{{< /tip >}}

{{< tip "warning" >}}
**WARNING!**

**Warning blocks like this one will warn you when you absolutely must not forget to do something. Failure to heed warning blocks is cause for disaster.**
{{< /tip >}} 

Before you get started installing or playing Dungeons & Deviousness: Director's Cut, it's important to note a few things:

{{< tip "warning" >}}
**WARNING!**

**This modlist contains explicit sexual content and a wide variety of kinks/fetishes. Proceed at your own discretion.**
{{< /tip >}} 

{{< tip >}}
**Important!** 

This modlist only functions correctly with female player characters.
{{< /tip >}}

- You are not required to have Nexus Premium to install D&DDC, however, it is highly recommended. Nexus Premium will cut your install time to a fraction of what it would be by automating both the mod download and mod install processes of installing the list.
- As of 2.0.0 D&DDC requires 264GB (71GB downloads/185GB mods/7GB Bodyslides) of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing to an SSD/NVMe is not required, but also highly recommended. Download and installation times vary based on your computer and internet speeds, but expect the entire process to take a few hours. If you are installing the list without Nexus Premium, expect the process to take a couple of days of 8+ hour sessions downloading mods.
- To maximize performance, both Skyrim: Special Edition and D&DDC should be installed on the same hard drive, ideally an SSD/NVMe. This is not required, just recommended if you want the smoothest gameplay experience.
- If you are not familiar with the contents of this modlist, a complete documentation of every mod in the list including links to the mods is available on the D&DDC Modlist Spreadsheet.
- If you instead only wish for a brief overview of the major changes this modlist makes, you should refer to the Important Mods You Need to Know About of this document.
- Autosaves for D&DDC are disabled. It will not autosave at any time. You should make your quicksave button your best friend (usually, the F5 key).
- Continuing the last point, it is always better to save before entering a loading screen instead of after. After a loading screen it is very likely that scripts will be running for at least 30 seconds, so if you must save after a loading screen, at least wait that long before doing so.
- Wabbajack does support updating an existing installation of a modlist. However, as part of this process, it does delete files that don't match with what it is installing. This includes RaceMenu presets, mods you've added/changed, and possibly even save files. It is a good practice to keep backups of your save files so that you can update safely. Saves are stored within the folder you install D&DDC to.
- All characters in D&DDC are fully nude, with everything that implies. There are sets of underwear you can craft or find, but don't expect it to stick around for very long.
- Adding to, changing, or removing from D&DDC is not supported. See the Adding to D&DDC section of this document for more details.
- As many common issues as I could find have been documented in the Common Issues section of this document. Refer to this before asking for support.
- If you want some tips related to getting started playing the list, refer to the Getting Started in D&DDC section of this document.

## System Specifications
Dungeons & Deviousness is not the most intense modlist by design - high-end graphics plus all of the scripts running is a recipe for disaster. As a result, the following hardware can run the list at a consistent 60+ FPS with ENB. Use it to gauge how your system might run the list.

- CPU: AMD Ryzen 9 3900X @ 4.2GHz
- RAM: G.Skill TridentZ Neo 32GB DDR4 3600MHz CL16
- GPU: nVidia RTX 2080 Super 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz
- Storage: Sabrent Rocket 2TB M.2 NVMe 2280; Samsung EVO 860 250GB; SeaGate Barracuda 2TB 7200RPM

Skyrim is very heavy on processors. Generally, anything above 3GHz should be fine but I can’t guarantee it. 6GB or 8GB of VRAM should be plenty, with 4GB of VRAM probably capable of 60FPS without ENB.

### Important Links
- [Dungeons & Deviousness Bug Tracker](https://github.com/ForgottenGlory/Dungeons-Deviousness/issues)
- [Dungeons & Deviousness Discord](https://discord.com/invite/NdmGpGzqg8)
- [Dungeons & Deviousness Patreon](https://www.patreon.com/LivingSkyrim)
- [D&DDC Keymap](http://www.keyboard-layout-editor.com/#/gists/c83b53f8131ae9dc1df8c0fb15149743)
- [D&DDC Widget Explanation](https://i.imgur.com/lQScKQa.jpg)

## Pre-Installation
### Steam & SSE Setup
Before proceeding with installation, it’s important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files, Program Files (x86), or Desktop folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. Instructions on how to move your Steam library can be found elsewhere on the internet.

As with any modlist, it is strongly recommended that you start with a clean, unmodified installation of Skyrim: Special Edition. To get your Skyrim SE to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall).
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Properties… > Local Files > Browse Local Files…), delete them.
3. Install Skyrim: Special Edition.

Also make sure you have deleted or disabled any and all Creation Club content that may have downloaded with the game.

### Steam Setup
1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties… > General > Enable the Steam Overlay while in-game checkbox)

### Launching Skyrim
Launch Skyrim SE to create any INI or registry entries the game needs. Immediately exit after the launcher has successfully selected a graphics preset for your hardware. The INIs will be overwritten by the ones included in the Wabbajack installer.

### Wabbajack Preparations
1. Download the latest version of Wabbajack. Do not run anything until instructed to do so. Make sure you are using the latest version of Wabbajack or else Wabbajack will report a corrupted modlist.
2. Create a new folder in the root of the drive where you want Wabbajack to be installed. (C:\ will be used as an example, but it can be placed in any drive.) Name this folder “Wabbajack”.
3. Create a second folder called C:\Dungeons & Deviousness. This folder is where the modlist will be installed.
4. Double check that you have not placed any of these folders in your Skyrim: Special Edition installation directory.
5. Ensure that C:\Dungeons & Deviousness is completely empty.
6. Ensure that Wabbajack.exe is in C:\Wabbajack.

{{< tip "warning" >}}
**WARNING!**

**Failure to set up these folders properly will result in the install failing. For example, [install drive]\Wabbajack\Dungeons & Deviousness is incorrect.**
{{< /tip >}} 

## Wabbajack Installation
If you are updating your existing installation of Dungeons & Deviousness: Director's Cut, skip to the Updating D&DDC section.

1. Run Wabbajack.exe.
2. At the bottom of the window, click Browse Modlists.
3. Locate the Dungeons & Deviousness card and click the download button to download the installer file.
4. Once downloaded, click the play button.
5. Below the image you see of the Dungeons & Deviousness logo, there are three text boxes. The second and third need to be filled out.
6. Click the three dots in the second (middle) box. Navigate to your Dungeons & Deviousness folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you’ll need to use to launch the list.
7. The third (bottom) box will automatically populate using the folder you just selected. This third box tells you where all of the mods will be downloaded. If you have hard drive limitations, you may change this to another folder on another hard drive by clicking the three dots in this box and selecting a new folder.
8. Click the play/right arrow button to begin the installation.

### With Nexus Premium
9. Wabbajack will walk you through logging into the Nexus and authorizing an API key so it can download mods if you have not done so previously.
10. Let Wabbajack do its thing. This will take a little while (usually 3-4 hours at most), so go get a snack and read the Important Mods You Need to Know About section of this document. Seriously. Read it. This isn’t optional.

### Without Nexus Premium
9. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take a really long time, possibly more than one day. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Put on some music or a TV show and make a day of it. If you need a break during this process, grab a snack and read the Important Mods You Need to Know About section of this document. Seriously. Read it. This isn’t optional.

Once complete, Wabbajack will say “Installation complete! You may exit the program.” If it does not, visit the Wabbajack Discord server for assistance. Don’t forget to upload your log file!

If Wabbajack fails to download a particular mod, it means that the mod has likely been updated. This also means that an update to Dungeons & Deviousness is imminent. Be patient and wait for the new release. Do not ask other people to share older files as this is a violation of the Nexus ToS.

## Post-Wabbajack Install
### ENB
By default, D&DDC includes Rudy's ENB for Obsidian Weathers. It is a good balance of pretty and performant and suits the list very well. Note that the Night Eye and Fog Fix for Rudy's are both already installed and included in the list. It has also been slightly tweaked to disable the letterboxing and make interiors slightly brighter.

That said, ENB can put a very heavy strain on weaker computers. If you would like to turn off ENB, all you have to do is press Shift + F12 while in-game. It will disable ENB for the duration of your play session. 

If you would like to change the ENB used in the list, place any files your chosen preset needs into the `[Your D&DDC Install Folder]\Stock Game\` folder. If you change to an ENB preset other than Rudy's, you should disable both of the Rudy's-related fixes in the left pane of Mod Organizer 2.

Further support for changing ENB is not provided, you should be certain you know what you're doing before changing ENB.

## Updating D&DDC
If you are updating D&DDC, the process is very simple. Before you update, you should at a minimum backup your saves. Updating may delete any saves that are present. Make sure you are using the latest version of Wabbajack or else Wabbajack will report a corrupted modlist.

{{< tip "warning" >}}
**WARNING!**

**Whilst some incremental list updates are save-safe, larger updates often require a brand new save file to avoid corruption. Check the newest update announcement found in the `#dnddc-announcements` channel on the [ForgottenGlory's Modlists Discord server](https://discord.gg/NdmGpGzqg8) before updating.**
{{< /tip >}} 

1. Run Wabbajack.exe.
2. At the bottom of the window, click Browse Modlists.
3. Locate the Dungeons & Deviousness card and click the download button to download the installer file.
4. Once downloaded, click the play button.
5. Below the image you see of the Dungeons & Deviousness logo, there are three text boxes. The second and third need to be filled out.
6. Click the three dots in the second (middle) box. Navigate to your Dungeons & Deviousness folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you’ll need to use to launch the list.
7. The third (bottom) box will automatically populate using the folder you just selected. This third box tells you where all of the mods will be downloaded. If you have hard drive limitations, you may change this to another folder on another hard drive by clicking the three dots in this box and selecting a new folder.

{{< tip >}}
**Important!** 

Set your downloads folder path to the same downloads folder location you used when you first installed Dungeons & Deviousness. Failure to do this will make Wabbajack download every mod again, which you want to avoid if possible.
{{< /tip >}}

8. When prompted if you would like to overwrite the existing installation, click “Confirm.”

## BodySlides

{{< tip "warning" >}}
**WARNING!**

**Failure to do either of the following options will result in your character's body turning invisible when equipped with certain outfits.**
{{< /tip >}} 

When you first load up D&DDC, there will be zero BodySlides created. You have two options here: Download the prebuilt ones I’ve made using the D&DDC Slim2Thicc preset, or make your own.

The Bodyslides, whether you build your own or use the prebuilt ones, will take approximately 7GB of space. This is already counted in the "264GB" mentioned at the beginning of the readme.

### Prebuilt Bodyslides
If you don’t really care what preset you use and/or are fine with the Slim2Thicc Body, follow these steps.

1. Close MO2 if you have it open.
2. Download this zip file: [D&DDC Prebuilt Bodyslides](https://drive.google.com/file/d/1RFxINLIjvPaG6d8o68QCXwlCPTxqWzx3/view?usp=sharing)
3. Open the ZIP file.
4. Copy everything inside the zip file (the meshes folder in its entirety, including the folder itself) into `[Your D&DDC Install Folder]\mods\BodyslideOutfitStudio - Overwrite`
5. Reopen MO2.
6. That’s it, you’re done!

### Build Your Own
If you want to build them yourself, this is a fairly straightforward process, but it can be a bit time consuming.

Before you get started, if you have your own personal BodySlide preset that you like, drop the XML file into `[Your D&DDC Install Folder]\mods\Custom Presets\Caliente Tools\BodySlide\SliderPresets alongside “Summer.xml”.`

When you open BodySlide for the first time, you may see an error message from Bodyslide stating "No read/write permission for game data path!". The steps below include a fix for this.

One more thing: if you get an error about BodySlide not being able to find the output path, click on the Settings button in BodySlide, click on the “Advanced” button, and set the Output Path to `[Your D&DDC Install Folder]\mods\BodyslideOutfitStudio - Overwrite.`

1. Launch BodySlide from MO2.
2. Click on the Settings button in BodySlide, and change the Game Data Path to point to `[Your D&DDC Install Folder]\Stock Game\Data\`. If you still get the same "No read/write permission for game data path!" error after changing the path, close BodySlide and MO2 and try launching MO2 as administrator.
3. Still in the Settings menu in BodySlide, click to expand the “Advanced” dropdown, and set the Output Path to `[Your D&DDC Install Folder]\mods\BodyslideOutfitStudio - Overwrite.`
4. Click on the magnifying glass icon near the top of the BodySlide Window and select “Choose Groups…”
5. Put a checkmark into ONLY “0. DNDDC Bodies”.
6. From the Preset dropdown, select your preferred preset. I’ve included a couple of extras on top of the default CBBE ones, or you can make your own.
7. Make sure that the “Build Morphs” checkbox is checked at the bottom of the BodySlide window.
8. Hold the CTRL key on your keyboard and click “Batch Build…”
9. Click Build on the window that appears.
10. Select your `[Your D&DDC Install Folder]\mods\BodyslideOutfitStudio - Overwrite.` folder in the window that appears.
11. The Bodyslides are broken up into groups: "0. DNDDC Bodies,” “1. DNDDC Clothes”, “2. DNDDC Armors”, and "3. DNDDC Bikinis". Repeat the above steps 4 through 10 for all of the groups, **one at a time and in order**. It's easier for your computer to process smaller groups rather than trying to do them all at once. It also means that you can choose a different preset for each category, if you want the shape of the body to change based on the kind of outfit being worn. (For example: MelaRockingArmor/MelaRockingOutfit for the Armors and Clothes, MelaRockingPhysique for the bodies). Note that if you build the groups using different presets, you may experience some misalignment of equipped items if mixing and matching. (For example: Devious Devices piercings positioned based on your body preset may appear to be floating in the wrong place when wearing armour built to a different preset.) This is purely visual and does not interfere with functionality.

### A Note About Presets
If you have your own favorite character face/head preset, drop the JSLOT file into `C:\Dungeons & Deviousness\mods\Custom Presets\SKSE\Plugins\CharGen\Presets` alongside Anna.jslot and Summer.jslot. It will be available in RaceMenu the next time you go to make a character. Make sure to back this up before updating the list as updating will erase any added files like this. Adding presets (whether they be BodySlide or RaceMenu) does not void support for Dungeons & Deviousness.

If you have a preset (Bodyslide or RaceMenu, doesn’t matter) that you made and you’d like it to be included in Dungeons & Deviousness, send them in the #dnddc-preset-sharing channel on the FG's Modlists Discord server.

## Configuration Specific
There is a mod included in the list that you can enable but should not except under very specific circumstances. That mod is Poser Hotkeys. The only time you should enable this mod is when you are not planning on actually playing whatever savegame you enable it on. It should only be enabled for the purpose of taking screenshots and nothing else. There is a significant issue with this mod that causes major Papyrus log bloat. That said, it is fully functional outside of that. If you are going to create a save game that will only be for taking screenshots, follow these steps:

1. In the left pane of Mod Organizer 2, find and enable these two mods: Poser Hotkeys SE and Poser Hotkeys Plus SSE.
2. In the right pane of MO2, locate Poser Hotkeys.esp and Poser Merged Module.esp. They should be at the bottom of the load order.
3. Move these two ESPs to priority 84 and 85 in the right pane of MO2, respectively.

{{< tip "warning" >}}
**WARNING!**

**Poser Hotkeys should only be enabled for the duration of your screenarchery. If you wish to actually play the list instead of taking screenshots, it should be disabled!**
{{< /tip >}} 

## Launching Dungeons & Deviousness
The hard part is now over. Carry on, the end is in sight!

1. In Mod Organizer 2, select D&DDC [SKSE] from the drop-down menu next to the Run button and click Run. This is how Dungeons & Deviousness should always be launched. You can create a shortcut on your desktop if you wish using the Shortcut button under the Run button.
2. Once Skyrim starts, create a new game. Loading an old save at this point will corrupt that save, do not do this.
3. Create your character (make sure your character is female or else the list won’t work right) and name them whatever you’d like.
4. As soon as you gain control of your character, do nothing. The mods are loading and this can take several minutes. You’ll see a list of mods initializing in the top left of the screen.
5. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

### The MCM Settings
1. Consult the [D&DDC MCM Configuration document](/dnddc/mcm) and follow all listed steps. This step is required if you want the list to work properly.
2. Don’t forget to save your game after configuring the MCMs, I promise you don’t want to have to do this step more than once.

{{< tip "warning" >}}
**WARNING!**

**The MCMs for Dungeons & Deviousness must be set correctly, failure to do this will result in the list not working.**
{{< /tip >}} 

## Important Mods You Need to Know About
This section details the most important mods included in Dungeons & Deviousness and is intended to give you a basic understanding of what to expect when you start the game.

### The Big Three
The first three mods you need to know about are [Frostfall](https://www.nexusmods.com/skyrimspecialedition/mods/671), [Campfire](https://www.nexusmods.com/skyrimspecialedition/mods/667), and [Realistic Needs & Diseases](https://www.nexusmods.com/skyrimspecialedition/mods/23799). These are the core survival package of D&DDC. Frostfall adds a warmth and coverage statistic to every piece of clothing and armor to protect you from the harsh cold of Skyrim. Campfire allows you to set up camp anywhere - provided you have the materials to do so. Your followers will camp with you and you'll need to do this on extended trips out of town. Realistic Needs & Diseases covers the rest of your needs - sleep, hunger, thirst, etc. It also overhauls the diseases in the game so they are harsher.

With these three mods, there's going to be a lot of things you'll need to manage to make sure you don't die traveling from point A to point B. Carry food, water, and warm clothes with you at all times, or make a follower carry them for you. You never know when you'll need to take shelter against a sudden blizzard. When you have the opportunity to stop into a town, make sure you're rested before selling your hard-earned loot to get the maximum gold you can - you'll need it.

### Other Survival Mods
You'll also find some other survival-related mods included with the list, namely [Skyrim Wayshrines](https://www.nexusmods.com/skyrimspecialedition/mods/17905), [Extended Stay](https://www.nexusmods.com/skyrimspecialedition/mods/156), [Complete Alchemy and Cooking Overhaul (CACO)](https://www.nexusmods.com/skyrimspecialedition/mods/19924), and [Loot and Degradation](https://www.nexusmods.com/skyrimspecialedition/mods/21744).

Skyrim Wayshrines places semi-lore-friendly shrines throughout the world that allow you to fast travel. Oh, didn't I mention that fast travel is disabled? Oops. There's a few materials you'll need to gather before being able to use the Wayshrines, but otherwise they function more or less as normal - teleporting you from one wayshrine to another. It should also be noted that these wayshrines won't be marked on your map at all until you actually go to them. Good luck finding them all!

Extended Stay is very simple: you can book extended stays at inns if you have the coin for them. You can book 3, 7, or 30 day stays as needed and as you can afford. These can get quite pricey very quickly - are you sure you'd rather not save up to buy a house? Or are the taxes on that too much for you to handle? Interesting questions with unclear answers.

CACO overhauls the alchemy and cooking systems in the game, granting increased variety and intricacy to making potions and food. You can even unlock more recipes the higher your cooking skill gets, so I hope you're prepared to channel your inner chef.

Loot and Degradation makes it so that your gear degrades and can even break over time. Tempering your gear isn't optional if you want it to last more than a single combat. Most blacksmiths can temper your gear for you, so speak with them often. The more you use a single blacksmith to do your tempering, though, the better they'll get at it. And the higher a temper rating your gear has, the longer it will last before needing to be tempered again. You also get some damage and armor boosts from tempering your gear.

### The (NSFW) Big Three
[SexLab](https://www.loverslab.com/topic/91861-sexlab-framework-se-163-beta-8-november-22nd-2019/), [Devious Devices](https://www.loverslab.com/files/file/5878-devious-devices-se-beta/), [More Nasty Critters](https://www.loverslab.com/files/file/5464-more-nasty-critters-special-edition/). These are the three pillars of NSFW content you'll find in D&DDC. With these, anything is possible.

SexLab by itself really doesn't do much, but it does provide the backbone framework required for all the Deviousness happening in this modlist. Devious Devices adds exactly that to the game - devices ranging from collars to harnesses to full on catsuits to the game for your character to get into trouble with. More Nasty Critters is, in essence, SexLab for creatures. It's a backbone framework to allow the aforementioned Deviousness - but with creatures instead of people.

### The Dungeons
This wouldn't be a Dungeons modlist if it didn't add dungeons! Included you'll find [Hammet's Dungeon Pack](https://www.nexusmods.com/skyrimspecialedition/mods/12186), [Forgotten Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/449), [Land of Vominheim](https://www.nexusmods.com/skyrimspecialedition/mods/31472), [EasierRider's Dungeon Pack](https://www.nexusmods.com/skyrimspecialedition/mods/2218), and [More Bandit Camps](https://www.nexusmods.com/skyrimspecialedition/mods/1994). All in all, there's over 150 new dungeons and locations to explore.

Speaking of dungeons, have you ever noticed that in traditional tabletop games that it's possible to skip days or even weeks at a time, only for combat to switch that grand scale down to mere seconds passing with each turn? We've got that, too. [Dynamic Timescales](https://www.nexusmods.com/skyrimspecialedition/mods/18922) makes game time pass more quickly while traveling and exploring, and more slowly when in combat or in town. No longer will combat take in-game hours away from you, leaving you exhausted, hungry, and thirsty. You should be able to make it through at least a few combats before needing to stop and rest and eat.

### The Deviousness
Alright, rapid-fire mod time: [SexLab Survival](https://www.loverslab.com/files/file/11053-sexlab-survival-special-edition/), [Deviously Cursed Loot](https://www.loverslab.com/topic/100032-deviously-cursed-loot-se-beta-2/), [Deviously Helpless](https://www.loverslab.com/files/file/6561-deviously-helpless-se/), [Estrus Chaurus](https://www.loverslab.com/files/file/6160-estrus-chaurus-for-se/), [Estrus Spiders](https://www.loverslab.com/files/file/2438-estrus-chaurus-spider-addon-%E2%95%B2-%E2%80%A2%CC%80-%CF%89-%E2%80%A2%CC%81-%E2%95%B1/), [Devious Followers](https://www.loverslab.com/files/file/11732-devious-followers-continued-se/), [Simple Slavery Plus Plus](https://www.loverslab.com/files/file/13531-simple-slavery-plus-plus/), [Fill Her Up](https://www.loverslab.com/files/file/6163-fill-her-up-se/), [Kyne's Blessing](https://www.loverslab.com/topic/68035-sexlab-parasites-kynes-blessing-may-2021/), [Yamete](https://www.loverslab.com/files/file/16057-yamete/), [Devious Lore](https://www.loverslab.com/files/file/16231-devious-lore-se/), [Devious Cidhna](https://www.loverslab.com/topic/31189-devious-cidhna-may-5-2018/), [Skyrim Unhinged](https://www.nexusmods.com/skyrimspecialedition/mods/31251).

Scared yet? But remember, these are just obstacles in your way as you make the climb to glory. In brief, here’s what the simple mods above do.

- Estrus Chaurus: Get spit on by a Chaurus? There’s a chance for tentacle funtimes and a Chaurus Parasite.
- Estrus Spider: Estrus Chaurus, but with Spiders.
- Simple Slavery Plus Plus: Integrates with mods to sometimes provide immersive slavery mechanics if your character is defeated in combat.
- Fill Her Up: Your character will get filled up with visual changes to match.
- Kyne's Blessing: If you sleep outside, in a cave, or other "unsafe" location, there's a chance a creepy-crawly will be joining your party for a while.
- Yamete: The defeat mod of choice for D&DDC. You can be defeated in combat instead of killed, and so can your opponents. Defeat is not guaranteed, you can and will still die occasionally.
- Devious Lore: Semi-lore-friendly integration of Devious Devices into the game.
- Devious Cidhna: Slavery storylines that integrate with Simple Slavery. Various groups can purchase you from Simple Slavery and you'll have to escape somehow.
- Skyrim Unhinged: Adds ambushes and doppelgangers throughout the world - and they're out to get you.

A few mods, however, need a bit more explanation than above. The first is Deviously Cursed Loot. It will completely change how you play the game. It features a few new questlines for you to follow, changes how NPCs behave, and completely changes how loot is distributed in the game. Depending on how this mod is configured, it can be as forgiving or brutal as you want. I’ve included a preset that is tough but fair.

That out of the way, what does Deviously Cursed Loot actually do? The answer is very simple: Any time you loot a chest, body, plant, open a door, unlock a door, search a barrel/sack/etc, there is a chance for an event to happen if your arousal is high enough. What events? Well, it could be as simple as putting a pair of shackles on your character that you need to escape from (or get a follower’s help with escaping from) before proceeding with the dungeon. It could be as complex as slapping an entire set of bondage gear onto your character, teleporting you to a random wilderness location, and expecting you to find your way back to civilization and freedom. There are of course things that can help mitigate some of these consequences, Lucky Charms are your best friend for avoiding unwanted surprises. Hoard them and use them carefully.

Devious Followers will turn the first follower you pickup into a Devious Follower. This follower will expect to be paid regularly, and if you can’t pay, guess what? That’s right - there’s a whole host of devious things they can do to you. Pay them often, pay them well, and all will be well.

SexLab Survival is a mod that, in its default state, is not fun. Sorry, but it’s not. However, if you configure it just right, it’s actually a ton of fun! With the preset included in this list, you’ll be required to have at least one follower with you to leave major cities. Oh, and you’ll also need to pay a toll to leave the city assuming you have at least one follower with you (they can pay it for you if you’re light on gold, but don’t worry, you can pay it back later). In addition, it makes cities have certain rules you’ll need to follow while inside. Usually these are pretty easy - no lockpicking visibly, keep your weapon unequipped, etc. but they can have some nasty consequences if you break the rules too many times.

Survival also integrates with Frostfall to make it so that having sex warms you up, and you can get wet from it. It also integrates with Realistic Needs & Diseases to add some interesting things that happen when your character interacts with certain fluids. Speaking of needs, it also places a Kennel in each city that you can sleep in for free if you can put up with the Kennel's inhabitants and their "interruptions".

Lastly, Survival makes it so that if you use Bikini Armor, you’ll gain experience as you wear it - but as a consequence, using regular armor becomes less effective the higher your Bikini Armor experience is. The last thing I’d like to mention: your map will not function unless you have a Map of Skyrim (or Solstheim, as the case may be). They can be bought from most general traders in major cities, or looted off of enemies rarely. Your compass will not function until you unlock it through the Skills of the Wild skill tree.

### The Other NSFW Stuff
More rapid-fire mods: [SexLab Aroused](https://www.loverslab.com/files/file/5482-sexlab-aroused-redux-sse-version-29/), [SexLab Aroused Monitor Widget](https://www.loverslab.com/files/file/11466-sexlab-aroused-monitor-widget-se/), [SexLab Solutions](https://www.loverslab.com/files/file/10742-sexlab-solutions-revisited-se/), [Devious Devices Helpers](https://www.loverslab.com/files/file/9197-devious-devices-helpers-se/), [The Book of Sex](https://www.loverslab.com/files/file/10091-the-book-of-sex-se/), [Amorous Adventures](https://www.nexusmods.com/skyrimspecialedition/mods/7305), [Maids II Deception](https://forgottenglory.github.io/readme/dnd/), [Immersive Wenches](https://www.nexusmods.com/skyrimspecialedition/mods/595), [ABC](https://www.loverslab.com/files/file/7556-animated-beasts-cocksabc-for-users-le-se/), [SOS](https://www.loverslab.com/files/file/5355-schlongs-of-skyrim-se/), [SexLab Confabulation](https://www.loverslab.com/topic/139082-sexlab-confabulation-september-16-2020/), [SexLab Separate Orgasms](https://www.loverslab.com/files/file/5929-sexlab-separate-orgasm-se/), [SexLab Sexual Fame](https://www.loverslab.com/files/file/2455-sex-lab-sexual-fame-framework/) & [Comments](https://www.loverslab.com/topic/151970-slsf-fame-comments-se/), [GenderBender](https://www.loverslab.com/topic/108099-gender-bender-se/).

In brief:

- SexLab Aroused: Your character and NPCs can get aroused. Different things happen as arousal increases.
- SexLab Aroused Monitor Widget: Adds a widget to your screen so you can constantly monitor arousal.
- SL Solutions: Adds options to a bunch of quests that let them finish on a sexy note.
- The Book of Sex: Major sexy overhaul of the quest The Book of Love.
- Amorous Adventures: Romantic and funny questlines.
- Maids II Deception: Major questline with some NSFW stuff going on.
- Immersive Wenches: Adds wenches!
- ABC: The non-acronym name of this mod should explain it.
- SOS: Same as ABC, but for regular NPCs instead of creatures.
- SexLab Confabulation: Adds dialogue and conversation topics related to sex.
- SexLab Separate Orgasms: Adds a small minigame to sex, can be set to autopilot for hands-free operation.
- SexLab Sexual Fame & Comments: Allows your character to gain notoriety for various sexual actions and gives NPCs an entire host of comments they can make if they recognize you.

### Milk Mod Economy
This one gets its own section because it needs it, there's a lot happening here. [Milk Mod Economy](https://www.loverslab.com/files/file/6103-milk-mod-economy-se/), in essence, adds another layer to Skyrim's economy - the Milk Economy. If you are a milkmaid, you can produce milk and level up to make other female NPCs into milkmaids to make milk and sell milk for you. There are milking stations in every major hold capital, orc strongholds, and you can build them using the Campfire system if you have the materials needed. You can also craft a cuirass to milk on the go. How do you become a milkmaid? Easy: drink milk, get pregnant, or get cursed. Deviously Cursed Loot has a chance to give you a Milk Mod potion which will do it, or Egg Factory/Estrus Chaurus will turn you into one. If you're struggling to make enough money to get a follower or leave town, this is a good way to do it.

As for the actual economy part, the prices of milk will fluctuate up and down, some cities will have booms and others will have slumps. Keep an eye on the market and sell where the milk is wanted to make the most gold.

But, as with many things in this list, the Milk Economy comes at a cost. [Milk Addict](https://www.loverslab.com/files/file/11621-milk-addict-se/) makes it so you can become addicted to milk (technically lactacid, but milk contains lactacid so... milk.). Without sating your addiction, your character will have all sorts of problems - it might even get so bad it'll be a miracle they can stand up straight anymore.

### Character Creation
True to its name, character creation in D&DDC feels a lot like filling out a character sheet for a traditional, tabletop roleplaying game. You'll assign attribute points using [AVA](https://www.nexusmods.com/skyrimspecialedition/mods/23329), choose a backstory with [ELSA](https://www.nexusmods.com/skyrimspecialedition/mods/23126), have a bonus based on your gender and race from [GABI](https://www.nexusmods.com/skyrimspecialedition/mods/23145) and [Aetherius](https://www.nexusmods.com/skyrimspecialedition/mods/26686), and even pick a class for your character with [Classic Classes & Birthsigns Reimagined](https://www.nexusmods.com/skyrimspecialedition/mods/41298).

To fit the theme of D&DDC, you'll also find that [Alternate Perspective](https://www.nexusmods.com/skyrimspecialedition/mods/50307) has been heavily modified to fit the theme of the list. Many items have been removed and you'll no longer be able to select a starting point. You will always start in Helgen, ready to begin your adventure. Reading the Alternate Perspective mod page for more details about how it modifies the start of the game and the main quest is highly recommended.

Additionally, quite a few RaceMenu presets are available to choose from should you find inspiration for a character lacking. Some of them won't come out right unless you load the head separately using the Sculpt menu of RaceMenu, so if something looks weird, it's probably that.

### The Magic Mods
In an effort to keep magic in D&DDC somewhat balanced, fairly minimal changes have been made to this category. [Odin](https://www.nexusmods.com/skyrimspecialedition/mods/46000) makes sweeping changes to the vanilla spells in the game and also adds some new ones to help fill in the gaps. It also adds several new scrolls and staves to the game to match these new spells, increasing the variety you'll find. To add even more variety to the spells in the game, [Elemental Destruction Magic Redux](https://www.nexusmods.com/skyrimspecialedition/mods/37211) is also included.

Learning spells is modified by [Spell Tutor](https://www.nexusmods.com/skyrimspecialedition/mods/45275), which will slow down the rate at which you learn spells. This creates and interesting dynamic where you have to choose between spending time learning spells or adventuring - and your gold isn't infinite, so this can be an impactful choice, especially early on.

Similarly to the combat category, Magic animations have also received a facelift. You'll find that idle and casting animations have been changed to increase fluidity and add a more natural look to them.

Last but not least is [SmartCast](https://www.nexusmods.com/skyrim/mods/43123), which you should definitely learn to use if you're going the mage route. SmartCast lets you prepare your magical arsenal for any challenge you're about to face and removes some of the tedium from switching spells on the fly. Think of it as spending time preparing your spellbook, choosing which spells you think you'll need over the course of an adventure.

### The Combat Mods
The combat of D&DDC is, in general, a strategic affair. Enemies are smarter and stronger across the board thanks to [Blade & Blunt](https://www.nexusmods.com/skyrimspecialedition/mods/34549), [True Armor](https://www.nexusmods.com/skyrimspecialedition/mods/15921), and [Simply Balanced](https://www.nexusmods.com/skyrimspecialedition/mods/15541). No longer is it true that one particular type of armor better than another, and some weapons are better suited to fighting certain types of armor. On the player side of things you have access to powerful tools like [Archery Gameplay Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/24296), [Dual Wield Parrying](https://www.nexusmods.com/skyrimspecialedition/mods/18264), and [Way of the Monk](https://www.nexusmods.com/skyrimspecialedition/mods/17684) if you're more unarmed-inclined.

Additionally, you'll have access to [TK Dodge](https://www.nexusmods.com/skyrimspecialedition/mods/15309) which allows you to maneuver around your enemies fluidly. Some practice at timing your dodges will go a long way to making sure you survive. And practice you'll need, as there are a whole host of new combat animations that enemies and the player character will use - no longer will melee combat be left, right, left, right. Expect attacks from all directions and maybe even some spins thrown in for good measure. Similarly, unarmed, block, sprint, and dodge animations have all been tweaked for more variety and fluidity.

The last thing I'll mention is that preparing for combat goes a long way towards success. Taking the time to configure hotkeys for spells, potions, or whatever else you have in mind is key for success.

### The Enemy Mods
The mods affecting enemies in D&DDC go hand-in-hand with the combat mods. First up is [Enemy (R)Evolution of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/37228) - which gives enemies access to a ton of things that normally only the player can do. They'll drink potions, use spells added by mods, shouts, and even some perks and standing stones bonuses. Don't ever think an enemy is defeated just because their health is low!

[Arena](https://www.nexusmods.com/skyrimspecialedition/mods/33487) rebalances encounter zones in the game to give a sort of progression to the types of dungeons you'll be delving into. Bandit-infested caves are up first, Falmer/Dwemer ruins near the middle, and at the top end Dragon Priest dungeons and Daedric dungeons. You'll also find that the levels of enemies have been uncapped so they can continue to scale with you throughout your playthrough.

Last, but certainly not least, [Deadly Dragons](https://www.nexusmods.com/skyrimspecialedition/mods/23723) makes sure that every fight with a Dragon is, well, deadly. They are powerful opponents and fights with them can take quite a while to resolve. If you're too weak, the dragon may even get bored enough to leave the fight early.

### The Economy & Loot Mods
For the economy side of things, D&DDC features these mods: [Trade & Barter](https://www.nexusmods.com/skyrimspecialedition/mods/23081) and [Evolving Value Economy](https://www.nexusmods.com/skyrimspecialedition/mods/26325). These two mods team up to make vendors pay very little for what you have to sell and sell things for quite high prices compared to vanilla Skyrim.

To balance that out, on the loot side of things, we have: [Indigent Residents In Skyrim (IRIS)](https://www.nexusmods.com/skyrimspecialedition/mods/41920), [Gold Overhaul and Loot ReDone (GOLD)](https://www.nexusmods.com/skyrimspecialedition/mods/1796), [Dynamic Dungeon Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308), and [Narrative Loot](https://www.nexusmods.com/skyrimspecialedition/mods/12812). IRIS removes many, many of the items you'd normally find sitting on shelves, crates, etc. This is to shift the focus away from grabbing every random item you can find to actively seeking out chests, strongboxes, and other containers (including dead bodies). GOLD, Dynamic Dungeon Loot, and Narrative Loot greatly increase the quantity and variety of items you find within those containers. It is entirely possible to come across something very powerful very early in your journey. Savor those moments, as they're few and far between!

One special mention I'll give is to [Morrowloot Miscellania](https://www.nexusmods.com/skyrimspecialedition/mods/27094), which removes a lot of the higher level armor you'd normally find randomly and instead hand-places it in the world for you to find. Very infrequently will you find enemies with anything much higher level than steel or leather armor.

### The Perks & Leveling Mods
There's a lot to unpack here, so strap in. We'll start with [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751), which makes it so that you only gain experience points from killing enemies, quests, and clearing dungeons. It also caps your skills from progressing past certain points if your character isn't a high enough level. You may ask about increasing your skills by reading, but then I would tell you about [Reading is Good](https://www.nexusmods.com/skyrimspecialedition/mods/42026). Instead of gaining a skill point when you read a skill book, you instead gain a bonus to how quickly that skill increases.

Next, we have [Vokrii](https://www.nexusmods.com/skyrimspecialedition/mods/26176), the perk mod of choice for D&DDC. Vokrii gives a good balance of new and interesting perks while not being completely overpowered. Speaking of perks, you can now only spend perk points and level up after sleeping for 8 hours thanks to [Sleep to Level Up](https://www.nexusmods.com/skyrimspecialedition/mods/32357). [Hand-To-Hand](https://www.nexusmods.com/skyrimspecialedition/mods/46425) also adds a new skill tree specifically for unarmed combat.

If you're looking for Vampire or Werewolf perk overhauls, you need look no further than [Scion](https://www.nexusmods.com/skyrimspecialedition/mods/41639) and [Manbeast](https://www.nexusmods.com/skyrimspecialedition/mods/44746).

Lastly, we have [Skills of the Wild](https://www.nexusmods.com/skyrimspecialedition/mods/37693). This mod adds skill trees to Campfire and Hunterborn. With it, you'll be able to unlock the ability to have your compass visible in your HUD, get bonuses to what you harvest from animals, cook more advanced meals, and even tame wild beasts if you're persistent enough. As with the Frostfall skill tree, these can be accessed by interacting with a campfire that you've made.

### The HUD and UI Mods
Continuing the theme of keeping things dangerous, the UI mods for D&DDC starts with [Skyrim Souls](https://www.nexusmods.com/skyrimspecialedition/mods/27859). By default, the only menus that will pause the game when open are your map, your perks menu, and the pause/system/journal menu. Thankfully, there's a lot of convenience packed into all of your menus. [Better Container Controls](https://www.nexusmods.com/skyrimspecialedition/mods/25271) is exactly that: better controls for searching containers. [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246) allows you to customize dialogue menus however you please and makes them easier to read. [moreHUD](https://www.nexusmods.com/skyrimspecialedition/mods/12688) and its [Inventory Edition](https://www.nexusmods.com/skyrimspecialedition/mods/18619) work to enhance the UI of your inventory page and give you some more information when looking at items you can pickup from the game world. [SSIRT](https://www.nexusmods.com/skyrimspecialedition/mods/1523) enhances the skills page giving you the ability to take a look at all of your skills at a glance.

Last, but not least for the UI, you've got [Dear Diary](https://www.nexusmods.com/skyrimspecialedition/mods/23010) and its [Wood and Paper skin](https://www.nexusmods.com/skyrimspecialedition/mods/44174). Combined with [Paper UI Sounds](https://www.nexusmods.com/skyrimspecialedition/mods/38944), it's a much more thematic UI for D&DDC.

As for the actual HUD, [A Matter of Time](https://www.nexusmods.com/skyrimspecialedition/mods/12937) (and its included preset) gives you a minimal tracker for the current time of day. [iWant Status Bars](https://www.nexusmods.com/skyrimspecialedition/mods/36460) lets you keep track of your needs and information from Frostfall like the temperature at a glance. Meanwhile, [Less Intrusive HUD](https://www.nexusmods.com/skyrimspecialedition/mods/17974) gives you an in-game customizable HUD that you can tweak to your heart's content. And for fun, [Floating Damage](https://www.nexusmods.com/skyrimspecialedition/mods/14332) gives you a sense of how much damage you're actually dealing or taking since it can be hard to judge sometimes.

### Your Fellow Party Members
Building your party is a crucial step in beginning your journey in D&DDC. So, of course, the list includes a number of NPCs you can seek out and recruit:

[Shindara](https://www.nexusmods.com/skyrimspecialedition/mods/10094), [Lady Miraak](https://www.nexusmods.com/skyrimspecialedition/mods/6835), [Rosa Round-Bottom](https://www.nexusmods.com/skyrimspecialedition/mods/13209), [Mirai](https://www.nexusmods.com/skyrimspecialedition/mods/10908), [Toccata](https://www.nexusmods.com/skyrimspecialedition/mods/12713), [Miri](https://www.nexusmods.com/skyrimspecialedition/mods/25288), [S'hani](https://www.nexusmods.com/skyrimspecialedition/mods/26935), [Nykal](https://www.nexusmods.com/skyrimspecialedition/mods/10052), [the Nord Brothers](https://www.nexusmods.com/skyrimspecialedition/mods/11106), [Cerri Steelfist](https://www.nexusmods.com/skyrimspecialedition/mods/44199), [Ceraph](https://www.loverslab.com/files/file/2992-ceraph-the-succubus-follower/), [Shandar](https://www.nexusmods.com/skyrimspecialedition/mods/8204), [Vimar](https://www.nexusmods.com/skyrimspecialedition/mods/45017), and [Azuk](https://www.nexusmods.com/skyrimspecialedition/mods/36451) all stand ready to join you in your travels. As if that wasn't enough, you also have the whole host of [Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194) available to find and recruit.

### Nether’s Follower Framework
Nether's Follower Framework is what makes the entire idea of an adventuring party work in D&DDC. With it, you can recruit several followers to join you in your adventures. Usually, 2 or 3 followers is sufficient to take on most challenges. As for interacting with those followers, it has a whole host of features you'll find useful. You can have them sell items for you, teach them spells, command them in battle, and when you're relaxing in camp they'll even take the time to get comfortable around the fire. It should also be noted that you can tweak the combat style of many followers using this framework, so if you find that you'd rather Gorr use a sword and shield instead of warhammer, you can make that tweak. As with any good adventuring party, it's good to round out the skills your party has across rogue, warrior, and mage. So if you're a warrior, you should seek out a mage and rogue to fill those deficiencies in your skillset. Or, using Nether's, you can tweak your existing party to fill those roles as needed.

### Getting Started in D&DDC
Here are some basic tips to get you started on your adventure.

- Temper your gear! This is non-negotiable if you want your gear to last more than a single combat. Blacksmiths can temper just about anything you equip for a nominal fee, or you can do it yourself. Your gear is also better while tempered, so don't be shy.
- Get a follower. Or three. You have to have at least one to be able to leave the major cities (unless you want to sneak out and risk the wrath of the guards). They'll also make your life much easier while exploring and dungeon-delving.
- Flowers are your friends! Seriously, if your arousal is low (below 25), you should harvest just about every flower and plant you come across. Even if you don't plan on going into Alchemy, this will help you a lot. You can find a variety of useful items in addition to the plant parts while harvesting.
- Going solo is a great way to end up as the helpless plaything of a bandits, monsters, or just about anything else. Strong enemies care not if you're just starting out, they'll defeat you all the same.
- There are a few questlines that are available to you from the start of the game, while many of the usual suspects (Thieves Guild, College of Winterhold, etc.) have been delayed. Some of these new questlines involve some form of NSFW entertainment. These are great ways to level up in the early game and experience new content. As usual though, starting in the Riverwood/Whiterun area can help you get some early levels before taking on harder challenges.
- You'll find that chests are overflowing with loot. While it can be tempting to take it all, being selective can increase the amount of time you spend dungeon-delving instead of making trips back to the general trader to sell your stuff. 
- Crafting is the fastest and easiest way to get better gear. Even if you don't normally play a character with skill in Smithing, you should really consider it. Either that or be prepared to give a blacksmith a lot of gold to temper your gear.
- While of course you normally want to diversify your party, I'll make a special mention for getting a healer. There's at least one dedicated healer follower you can find and you can also use NFF to change the role of a follower to healer if needed. This is especially true on higher difficulties. 

## Adding to Dungeons & Deviousness
This goes for making changes/removals to/from the list as well, but the short answer is: don’t.

The long answer is that there are several obstacles in your way if you want to add to, change, or remove from the list. The first one is that the list has been hand-sorted to make sure that everything loads in the proper order and is working properly. Running LOOT is guaranteed to break the list. If you don’t know how to open up a modlist in xEdit to find out where the mod you want to add should go, you shouldn’t be adding anything to the list.

The second is that if you want to remove something from the list, you’re probably going to break dependencies somewhere and, again, break the list. This is even more risky than adding to the list. I understand that not every kink is for everyone, but you need to understand that this list is intended to cater to pretty specific tastes. If you don’t like something the list is doing, I can highly recommend either the Licentia or Cupid. Both are much lighter-weight lists that don’t have anywhere near the level of depravity that this list does.

The last thing I’ll mention is that I’ve hand-patched pretty much the entire list to work as intended. Anything you add to the list needs to be patched as well using xEdit, or, if you’re removing from the list, you need to know how to remove things that have been patched.

I’ll say it again just in case: Adding to, removing from, or changing the list in any way other than what is laid out in the readme here is completely unsupported. You are 100% on your own if you want to go making changes to the list beyond the scope of this readme.

TL;DR?: Don’t try to change the list. If you do, you’re on your own.

## Troubleshooting & FAQ
Additions will be made to this FAQ as needed.

### Wabbajack Issues
#### “A mod failed to download.”

The short answer: wait for an update to the list. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which D&DDC is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

#### “Wabbajack says I’m out of requests.”

Nexus Premium is limited to 2500 downloads in a given 24 hour timeframe. Usually this limit resets around 9PM Eastern Time. Wait for your limit to reset and you’ll be able to proceed. Usually this only occurs after attempting to download the list multiple times in a row or when attempting to download multiple lists in the same 24 hour window.

#### “Can I pause the installation?”

Yes, just close Wabbajack. When you start the installation process again it will pick up from where it left off.

#### “Can I delete the downloads folder after installing?”

Yes, but remember that if you need to update the list you will have to download all of the mods that have updated again.

#### “The D&DDC DynDOLOD Output fails to download.”

You’ll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [D&DDC DynDOLOD 2.2.0](https://drive.google.com/file/d/1wV1aOVPg_6LuCsG0OUhosEP9V38594yf/view?usp=sharing)

#### “The D&DDC SSELODGen Output fails to download.”

You’ll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [D&DDC SSELODGen 2.0.0](https://drive.google.com/file/d/1ojSXTRem8AGD9IvTqIdvuo-Q-GbM8GUo/view?usp=sharing)

### Gameplay Issues
#### "I get stuck in certain animations!"

This is usually caused by script lag. There’s really no way around it, it will happen sometimes. Normally, you can open the console using the tilde key (~) on your keyboard or pause the game (Esc) for a few seconds and it will catch up. If you’re still stuck after doing that, you may need to reload an earlier save. Unfortunately the combination of mods being used can have this happen on occasion. Short of rewriting the scripts used, there’s really no way to fix it. Save frequently just in case this does happen to you.

#### “The Main Quest doesn’t proceed after retrieving the Dragonstone.”

Read this modpage: [Not So Fast - Main Quest](https://www.nexusmods.com/skyrimspecialedition/mods/2475)

#### “Tolfdir doesn’t invite me to Saarthal right away.”

Read this modpage: [Not So Fast - Mage Guild](https://www.nexusmods.com/skyrimspecialedition/mods/5686)

#### “Can I access RaceMenu after character creation?”

Only if you are not changing your character’s gender or race. Changing gender/race will cause issues with powers and passive buffs your character has.

#### “Can I change my attributes after starting?”

No. The choices you make are permanent. You can increase your attributes through various methods, refer to this modpage for more details: AVA

#### “My screen is zoomed in or weirdly off-center.”

Check the SSE Display Tweaks INI file to make sure you have the resolution for your screen set correctly. You may also need to check BethINI or the Skyrim INI files to make sure they all match your screen’s resolution.

#### “MO2 cannot find SKSE.”

You’ll need to manually set the path for SKSE using the Edit Executables menu in MO2. Also make sure you have followed the Game Folder Files step of this readme.

#### “Can I use a controller?”

No. And to answer your next question, because I fucking said so.

#### “My game freezes when saving.”

Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

#### “Can I play this list on a 75/100/144hz screen?”

Yes. Display Tweaks SSE is included to allow higher refresh rates.

#### “Can I use this list on an ultrawide monitor?”

No.

## Credits & Thanks
- Dungeons & Deviousness: Director's Cut created by ForgottenGlory
- Dungeons & Deviousness: Director's Cut Dev Team
  - celadoneiron
  - TheCampingOwl
  - Day7
- Halgari & The Wabbajack Team
  - Thank you for creating Wabbajack, you’re amazing!
  - Halgari’s Patreon
- Special Thanks
  - The TUCO Modding Team - Their modlist is a great way to get a Vanilla+ experience with a tutorial that is extremely helpful for learning the basics of creating a modlist.
  - DarkLadyLexy - Her LotD list is an invaluable resource not only for an awesome modlist, but also for learning many fundamentals of modding and compiling a modlist.
  - EzioTheDeadPoet - For their SME(FT) modlist. The ability to start from scratch on a whim while building this list has been invaluable.
- Mod Authors
  - None of this would be possible without the people who make the quality content we’ve grown to know and love. Please endorse the authors’ works.

### One Last Thing
If you read through the entire readme, congratulations! You get a cookie. If you need any further help, feel free to reach out on the Wabbajack or Dungeons & Deviousness Discord Servers. Do not direct message ForgottenGlory or any Wabbajack staff members for support. I (ForgottenGlory) speak for myself, but I do reserve the right to ignore any requests for support direct messaged to me and block you.

