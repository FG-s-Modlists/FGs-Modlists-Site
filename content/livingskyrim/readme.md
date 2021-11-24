---
title: "Readme"
weight: 1
layout: "lsbase"
---

## Before You Get Started
Before you get started installing or playing Living Skyrim, it's important to note a few things:

{{< tip >}}
**Important!** 

Sections labeled important like this one will tell you when you need to pay extra attention to something.
{{< /tip >}}

{{< tip "warning" >}}
**WARNING!**

**Warning blocks like this one will warn you when you absolutely must not forget to do something. Failure to heed warning blocks is cause for disaster.**
{{< /tip >}} 

- You are not required to have Nexus Premium to install Living Skyrim, however, it is highly recommended. Nexus Premium will cut your install time to a fraction of what it would be by automating both the mod download and mod install processes of installing the list.
- As of version 3.5.0, Living Skyrim requires 257GB of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing to an SSD/NVMe is not required, but also highly recommended. Download and installation times vary based on your computer and internet speeds, but expect the entire process to take a few hours. If you are installing the list without Nexus Premium, expect the process to take a couple of days of 8+ hour sessions downloading mods.
- To maximize performance, both Skyrim: Special Edition and Living Skyrim should be installed on the same hard drive, ideally an SSD/NVMe. This is not required, just recommended if you want the smoothest gameplay experience.
- If you are not familiar with the contents of this modlist, a complete documentation of every mod in the list including links to the mods is available on the LS3 Modlist Spreadsheet.
- If you instead only wish for a brief overview of the major changes this modlist makes, you should refer to the Important Mods You Need to Know About of this document.
- Autosaves for Living Skyrim 3 are disabled. You should make your quicksave button your best friend (usually, the F5 key).
- Continuing the last point, it is always better to save **before** entering a loading screen instead of after. After a loading screen it is very likely that scripts will be running for at least 30 seconds, so if you must save after a loading screen, at least wait that long before doing so.
- Wabbajack does support updating an existing installation of a modlist. However, as part of this process, it does delete files that don't match with what it is installing. This includes RaceMenu presets, mods you've added/changed, and possibly even save files. It is a good practice to keep backups of your save files so that you can update safely. Saves are stored within the folder you install Living Skyrim to.
- Living Skyrim 3 has been updated such that NPCs and player characters are never nude. Underwear is worn by all NPCs and the player character and cannot be unequipped.
- Adding to, changing, or removing from Living Skyrim is not supported. See the Adding to Living Skyrim section of this document for more details.
- As many common issues as I could find have been documented in the Common Issues section of this document. Refer to this before asking for support.
- If you want some tips related to getting started playing the list, refer to the Getting Started in Living Skyrim section of this document.
- By default, Living Skyrim has the game running in exclusive fullscreen mode to assist with game performance.

### System Specifications
Living Skyrim v3.0.0 has been cut back severely from the performance hog it was in v2.0.0 and on. Textures range from 512x512 to 4K and everything in between. The following system is ForgottenGlory's personal computer and is able to run the list at a constant 60FPS including ENB at 1440p monitor resolution.

- CPU: AMD Ryzen 9 3900X @ 4.2GHz
- RAM: G.Skill TridentZ Neo 32GB DDR4 3600MHz CL16
- GPU: nVidia RTX 2080 Super 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz
- Storage: Sabrent Rocket 2TB M.2 NVMe 2280; Samsung EVO 860 250GB; SeaGate Barracuda 2TB 7200RPM

In general, it is recommended that you have a processor with a clock speed of at least 3GHz and a graphics card with at least 6GB of VRAM. 4GB graphics cards may be able to run the list if you do not use ENB, but it is not guaranteed.

As for RAM, 16GB is the minimum recommended specification for running the list. 32GB is the ideal amount, and anything more than that is honestly overkill for this list.

If your PC is struggling to run Living Skyrim, see the Performance Optimizations section of this document for tips and tricks to receive better performance.

### Important Links
- [The Modlist Spreadsheet](https://docs.google.com/spreadsheets/d/1PxBMg2rIApANPaS0jW5d597dnDjNy8kcHKNoprf6NDs/edit?usp=sharing)
- [LS3 Default Keymap](http://www.keyboard-layout-editor.com/#/gists/0469bf568cf28f1ea8e9e78dba13c169)
- [Living Skyrim Bug Tracker](https://github.com/ForgottenGlory/Living-Skyrim-3/issues)
- [Living Skyrim Discord](https://discord.com/invite/NdmGpGzqg8)
- [Living Skyrim Patreon](https://www.patreon.com/LivingSkyrim)

### Screenshots
- [Living Skyrim Screenshot Gallery](/livingskyrim/screenshots)

### Videos
- [LS3 Overview Video by TheMurlocKing](https://www.youtube.com/watch?v=af8UI_w6E20)
- [LS3 Showcase by DroppedIceCream](https://www.youtube.com/watch?v=lud8CfsElyE)
- [LS3 Beta Preview](https://www.youtube.com/watch?v=QOCMLid39Hw)

## Pre-Installation

### Microsoft Visual C++
The Visual C++ Redistributable is a DLL (Dynamic Link Library) file required by programs or games built using Microsoft’s Visual Studio software development environment. As Skyrim Special Edition is a 64-bit program, elements of it - along with other aspects of the modlist - require the 64-bit version of Visual C++ in order to run.

Click the link to download the latest Visual C++ x64 Redistributable, then double-click the downloaded file and follow the instructions:
- [Microsoft Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)

### Steam & SSE Setup
Before proceeding with installation, it’s important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files, Program Files (x86), or Desktop folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. Instructions on how to move your Steam library can be found elsewhere on the internet.

Next, you’ll need a clean copy of Skyrim Special Edition. To get your copy to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall).
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Manage > Browse Local Files), delete them.
3. Install Skyrim: Special Edition.

{{< tip >}}
**Protip:** 

If you want to be absolutely certain you have uninstalled Skyrim completely, download and use Skyrim Shredder.
{{< /tip >}}

Afterwards, you need to disable automatic updates for Skyrim to avoid a game update breaking your copy of the game and therefore the modlist.

1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties… > General > Enable the Steam Overlay while in-game checkbox)

Once the above steps are completed, launch Skyrim SE through Steam to create any INI or registry entries the game needs. Immediately exit the launcher once it has successfully selected a graphics preset for your hardware. The INIs it just created will be overwritten by the ones included in the modlist, but this is a necessary step for Wabbajack to recognize that you have the game installed.

Last, but certainly not least, make sure you have deleted or disabled any and all Creation Club content that may have downloaded with the game.

{{< tip "warning" >}}
**WARNING!**

Currently, fresh installations of Skyrim Special Edition will be updated to an incompatable version for the lists to install. After you have a clean install of Skyrim Special Edition you will need to use the downgrade patcher featured **[HERE](https://www.nexusmods.com/skyrimspecialedition/mods/57618)** to ensure your Skyrim Special Edition install is the correct version before continuing with the steps in the Readme 
{{< /tip >}}

### Wabbajack Preparations
We’ll now setup the folders needed for the installation to proceed smoothly.

1. Create two empty folders: one named Wabbajack and the other named Living Skyrim.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, your Program Files (x86) folder, or the Desktop.
3. Additionally, ensure that these two folders are not contained within each other.
4. Ensure that both the Wabbajack and Living Skyrim folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: Wabbajack.
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

{{< tip "warning" >}}
**WARNING!**

**Failure to set up these folders properly will result in the install failing. For example, `[install drive]\Wabbajack\Living Skyrim` is incorrect.**
{{< /tip >}} 

## Installing the List

If you are updating your existing installation of Living Skyrim, skip to the [Updating Living Skyrim](#updating-living-skyrim) section of this document.

It’s now time to begin the installation of the list. Follow these steps:

1. Run Wabbajack.exe.
2. At the bottom of the window, click Browse Modlists.
3. Locate the Living Skyrim card and click the download button to download the installer file.
4. Once downloaded, click the play button.
5. Below the image you see of the Living Skyrim logo, there are three text boxes. The second and third need to be filled out.
6. Click the three dots in the second (middle) box. Navigate to your Living Skyrim folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you’ll need to use to launch the list.
7. The third (bottom) box will automatically populate using the folder you just selected. This third box tells you where all of the mods will be downloaded. If you have hard drive limitations, you may change this to another folder on another hard drive by clicking the three dots in this box and selecting a new folder.
8. Click the play/right arrow button to begin the installation.

| With Nexus Premium | Without Nexus Premium |
| :--- | :--- |
| 9. Wabbajack will ask you to login to Nexus and authorize your API key so it can download mods for you automatically. If this doesn’t happen, it isn’t a problem and means you’ve already set this up. | 9. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take an extraordinarily long time. Current reports indicate installing the list manually takes approximately 24 hours. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Installing with Nexus Premium isn’t required, but is strongly recommended if you value your time. If you must install the list manually, put on an audiobook or a TV show and make a day of it. |
| 10. Wabbajack will now download and install all of the mods. This will take a while (3-4 hours at most). Take this opportunity to read the Important Mods You Need To Know About section of this document. | |

{{< tip >}}
**Important!** 

Reading the Important Mods section of this document is not optional. You won't have any idea what's going on if you don't.
{{< /tip >}}

Once complete, Wabbajack will indicate it is done with a green box that says "Installation complete". You may exit Wabbajack after this appears.

If it does not complete successfully (a red box with "Installation failed"), consult the Common Issues section of this document, or visit the [Living Skyrim Discord server](https://discord.gg/NdmGpGzqg8) for assistance. 

## Post-Wabbajack Install

### Mod Organizer 2
Among other things, Wabbajack has installed a copy of Mod Organizer 2 for you. This copy of Mod Organizer 2 is specific to Living Skyrim and will not affect any other modlists you have installed.

1. Inside your Living Skyrim folder, locate and launch ModOrganizer.exe. If this is not inside the folder, your installation has failed and you need to consult the Common Issues section of this document.
2. Mod Organizer 2 will have a dark theme already selected for you. If it does not, something has gone wrong and you will need to start over at the Installing the List section of this document.
3. A dialogue may appear and ask if you want to associate Mod Organizer with .nxm links. Click Yes. If this dialogue does not appear, it is not an issue and means you’ve likely already done this.
4. Another dialogue may appear asking you to update the game's registry path. Click Yes on this popup if it appears. If it does not appear, it is not an issue and likely means you've already done this.

### Configuration Specific
There are three mods that can be optionally enabled, depending on your preferences and computer configuration. 

The first is [Complete Widescreen Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1778?tab=description). This should only be enabled if you are using a 21:9 monitor at 2560x1080 resolution or higher.

The second is QuickLoot, which adds a Fallout 4 style loot menu to bodies, containers, etc. This mod provides a significant quality of life improvement to looting, however it can cause issues with mods that run scripts upon looting certain objects. Enable it, or don't, it's entirely up to your personal preference. If you do enable it, it's recommended that you also enable the retexture for it to match the rest of the Skyrim UI.

Lastly, [Gamepad++](https://www.nexusmods.com/skyrimspecialedition/mods/27007?tab=files) is included if you plan on playing the list with a controller. Reading the mod page for this mod is not optional if you're going to use it.

### ENB
By default, Living Skyrim comes bundled with six ENB presets that you can choose between: Culminated, Ominous, Pi-CHO, Re-Engaged, Silent Horizons, and TNT. ENB is turned on by default and the Culminated preset is already enabled for you.

To switch between presets, launch ENB Organizer from within Mod Organizer 2. If you receive a message about ENB Organizer being unable to update, this is normal and can be safely ignored. Now, follow these instructions:

1. Click the three lines in the top left corner of ENB Organizer.
2. Click "Presets" in the menu that appears.
3. Note that by default Silent Horizons is enabled, indicated by the blue toggle under its name. 
4. Click on the toggle for any enabled presets (it should only be one at any given time) to disable it.
5. Click on the toggle under any other preset to enable it.
6. Wait 10 seconds, then you're done!

{{< tip "warning" >}}
**WARNING!**

**You should only ever have one ENB preset enabled. Having multiple enabled is a recipe for a Bad Time™.**
{{< /tip >}} 

Note that ENB can put a very heavy strain on weaker computers. If you would like to turn off ENB, simply disable all of the presets shown in ENB Organizer.

Support is not provided for adding additional ENB options to the modlist. If you want to add more options, you need to know how to use ENB Organizer and be familiar with the Stock Game feature that Living Skyrim uses.

## Updating Living Skyrim
If you are updating Living Skyrim, the process is very similar to installing the list. Before you update, you should at a minimum backup your save files. Additionally, make sure you are using the latest version of Wabbajack (it should automatically update itself when you launch the program).

{{< tip "warning" >}}
**WARNING!**

**Whilst some incremental list updates are save-safe, larger updates often require a brand new save file to avoid corruption. Check the newest update announcement found in the `#ls-announcements` channel on the Living Skyrim Discord server before updating.**
{{< /tip >}} 

1. Run Wabbajack.exe.
2. At the bottom of the window, click Browse Modlists.
3. Locate the Living Skyrim card and click the download button to download the installer file.
4. Once downloaded, click the play button.
5. Below the image you see of the Living Skyrim logo, there are three text boxes. The second and third need to be filled out.
6. Click the three dots in the second (middle) box. Navigate to your Living Skyrim folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you’ll need to use to launch the list.
7. The third (bottom) box will automatically populate using the folder you just selected. This third box tells you where all of the mods will be downloaded. If you have hard drive limitations, you may change this to another folder on another hard drive by clicking the three dots in this box and selecting a new folder.
8. Click the play/right arrow button to begin the installation.
9. If you are prompted to overwrite, confirm that this is what you want to do by clicking the Confirm button.

## Launching Living Skyrim
To actually launch and then play Living Skyrim, follow these steps:

1. Launch the copy of Mod Organizer 2 found inside your Living Skyrim folder.
2. In the top-right corner of Mod Organizer, you’ll see a large dropdown menu. Select Living Skyrim [SKSE] from this dropdown menu.
3. Click the large Run button.
4. This is how Living Skyrim should always be launched. You can create a shortcut to this selection on your desktop, if you wish, using the Shortcut button directly below the large Run button.
5. Once Skyrim starts, create a new game.
6. Create your character and name them whatever you’d like.
7. As soon as you gain control of your character, do nothing. The mods are initializing and this can take several minutes. You’ll see a list of mods appearing in the top left corner of your screen.
8. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

{{< tip "warning" >}}
**WARNING!**

**Loading a save from another modlist or from before you installed Living Skyrim will corrupt that save, do not do this.**
{{< /tip >}} 

## The MCM Settings
Some MCM settings have been pre-set for you. See this document to set the remaining MCMs that are required for LS3 to function correctly: [Click Here](/livingskyrim/mcm)

## Getting Started in Living Skyrim
If you’re coming from a previous version of Living Skyrim (1.x.x or 2.x.x), throw out everything you thought you knew. If you’re new to Living Skyrim, welcome! It’s gonna be a bumpy ride - at first.

- Bandits are your best bet for early levels. They usually come in small enough groups to be manageable and are almost always around your level or slightly higher.
- Undead are going to be nearly impossible until you hit level 10-15. This includes skeletons, draugr, vampires, etc. Dwemer and Falmer are out of the question until higher levels as well. Dragons start at level 20 and only go up.
- Most questlines should be doable from the very beginning, but keep in mind the previous two points. Bleak Falls Barrow will present a significant challenge to low-level characters and the first dragon fight will require around level 20.
- The Whiterun/Riverwood area is best for starting out - northern areas will be significantly more difficult.
- Overworld enemies are going to be easier and in smaller groups than dungeons, but avoid the larger overworld locations when starting out: Silent Moons Camp, Fort Greymoor, etc. Delving into caves and dungeons is a good way to get surrounded by a group of 6-10 enemies.
- Followers are your friends! There’s an absolute boatload of followers for you to find and pickup - whether it’s Inigo, Garm, Mirai, Hoth, or any of the 3DNPCs, there’s bound to be at least one person in every city that you can ask to help you out. Nether’s Follower Framework also lets you recruit many of the generic mercenaries you see wandering around if you just want a temporary companion. It’s extremely easy to assemble a diverse adventuring party if you so choose. If you prefer the lone wanderer style, be prepared for things to be more difficult - having at least one follower is highly recommended.
- Specialize your character. The combination of class and customization mods lets you focus your character in a way that vanilla Skyrim never did. It’s extremely likely you’ll start with one, maybe two skills that are any good and the rest will be total garbage. Focus on what your character is good at and it will pay dividends. When selecting how to allocate your attribute points, think about the rest of your build and put points into attributes that compliment how you want to play. Many attributes provide direct bonuses to how much damage you deal with specific types of weapons, how much health/stamina/magicka you start with, and so on. Specialized characters are much better suited to the challenges of Living Skyrim than jack-of-all-trades types. This also encourages you to pick up a follower that compliments your skills. Playing a tanky two-handed character? Find a follower that can cast healing spells on you and do magic damage from the backline. Playing a stealth archer (again)? Find a beefy sword and shield warrior to keep the enemies at bay while you snipe from the shadows.
- Magic, as usual, is extremely powerful in Living Skyrim. Even if you’re playing a primarily weapon-focused character, dipping into alteration, conjuration, or illusion will likely benefit you greatly. Similarly, enchanted items are very useful and should be carefully hoarded and used frequently. Smart Cast is beneficial even for characters that aren’t primarily focused on magic.
- There’s a loading screen tip I’m fond of that says something along the lines of “Strong enemies care not if you’re just starting out, they’ll kill you all the same.” Don’t be afraid to run away.
- **Alternate Perspective** modifies how the main quest begins in Living Skyrim 3. With any start except for the Dragonborn start, Helgen will remain intact as a fully functional town until such time that you decide to start the main story. To begin the main Skyrim story, go to Helgen and speak with the innkeeper. The dialogue option ***"I'd like to rent a room (Start intro)"*** will begin the opening sequence of Skyrim with the notable change that you are a bystander that gets caught in the Alduin attack.

## Important Mods You Need To Know About

### The Population Mods
Living Skyrim includes a number of mods that increase the population of both creatures and characters in the world. The two primary mods that contribute to this are [Inconsequential NPCs](https://www.nexusmods.com/skyrim/mods/36334) and [Increased Enemy Spawns](https://www.nexusmods.com/skyrimspecialedition/mods/2470).

Next is [OBIS](https://www.nexusmods.com/skyrimspecialedition/mods/4145), which adds a ton of mid to high-level bandits to the world. In general this covers most of the overworld locations.

[Organic Factions](https://www.nexusmods.com/skyrimspecialedition/mods/10289) and its [Extension](https://www.nexusmods.com/skyrimspecialedition/mods/25471) adds groups of NPCs that dynamically expand, recruit, and find new leaders. They will spread to conquer new territory and if left unchecked can take over entire holds. Keep an eye on the notifications for this mod, as it will keep you up to date on who is in control of what regions. You can also stumble across battles between factions if their territories overlap.

Also for your consideration: [Immersive Patrols](https://www.nexusmods.com/skyrimspecialedition/mods/718), and [Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194). For creatures, you’ll find [SkyTEST](https://www.nexusmods.com/skyrimspecialedition/mods/1104) and [Animallica](https://www.nexusmods.com/skyrimspecialedition/mods/20456).

What does this mean? Well, to put it simply, there are a lot of NPCs to find and interact with now. Silent Moons Camp for example now has somewhere in the range of 30 enemies to fight. It is impossible to go more than 5 minutes without coming across an NPC of some kind be it bandits, a patrol, or an animal. Getting a follower or two (or four) is highly encouraged. You will have to revisit some dungeons once you are stronger or have more followers. The Take Notes mod is included to chronicle your adventure and also to help you remember what places you need to revisit.

### The Quest Mods
Very few quests are untouched by Living Skyrim. Whether it’s a location revamp like [Bleak Falls Barrow Revisited](https://www.nexusmods.com/skyrimspecialedition/mods/33251), or a quest rewrite like [Finding Helgi and Laelette](https://www.nexusmods.com/skyrimspecialedition/mods/28973), it’s unlikely you’ll play most quests the same as you would in vanilla. This isn’t even to mention all of the new quests added by Living Skyrim. See below for a complete list of quest-related changes and the new quests added by this list.

It would take a tome to cover every single mod here, but there are a few to be aware of in particular: [At Your Own Pace (Main Quest & Mage Guild)](https://www.nexusmods.com/skyrimspecialedition/mods/52704), [Timing is Everything](https://www.nexusmods.com/skyrimspecialedition/mods/25464), and [Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802). The first introduces an optional break into the main and mage guild questlines, giving you time to go do other things if you want a break from them. You’ll need these breaks as there’s a significant difficulty spike between Bleak Falls Barrow and your first dragon fight as well as between the First Lessons quest and the expedition to Saarthal. Timing is Everything delays the DLCs (Dragonborn and Dawnguard, specifically) and various other quests until you are strong enough to take them on.

Legacy of the Dragonborn of course requires no introduction, but if you’re somehow unaware, it adds a museum in Solitude that allows you to proudly display the various items you’ll find in Skyrim. It has a home for almost every unique item (and many non-unique items) as well as introducing its own questline, a new guild you can be the leader of, and its own player home. While Legacy of the Dragonborn is not a focus of Living Skyrim, every applicable patch has been included as well as [The Curator’s Companion](https://www.nexusmods.com/skyrimspecialedition/mods/38529) so you can easily identify items that go in the museum and you can reasonably expect to have a home for any and all items you come across. If collecting and hoarding items is your thing, Legacy of the Dragonborn is for you.

| Quest Changes | New Quests | New Lands |
| :--- | :--- | :--- |
| [Timing is Everything](https://www.nexusmods.com/skyrimspecialedition/mods/25464) | [The Falkreath Hauntings](https://www.nexusmods.com/skyrimspecialedition/mods/20733) | [Falskaar](https://www.nexusmods.com/skyrimspecialedition/mods/2057) |
| [Open Civil War](https://www.nexusmods.com/skyrimspecialedition/mods/11076) | [Vigilant](https://www.nexusmods.com/skyrimspecialedition/mods/11849) | [Hammet's Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/12186) |
| [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704) | [Become a Bard](https://www.nexusmods.com/skyrimspecialedition/mods/2303) | [Vominheim](https://www.nexusmods.com/skyrimspecialedition/mods/31472) |
| [Opulent Thieves Guild](https://www.nexusmods.com/skyrimspecialedition/mods/931) | [Helgen Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/5673) | [Wyrmstooth](https://www.nexusmods.com/skyrimspecialedition/mods/19492) |
| [The Companions - Don't be a Milk Drinker](https://www.nexusmods.com/skyrimspecialedition/mods/19490) | [Carved Brink](https://www.nexusmods.com/skyrimspecialedition/mods/24351) | [The Gray Cowl of Nocturnal](https://www.nexusmods.com/skyrimspecialedition/mods/4509) |
| [Finding Helgi and Laelette](https://www.nexusmods.com/skyrimspecialedition/mods/28973) | [The Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179) | [Moonpath to Elsweyr](https://www.nexusmods.com/skyrimspecialedition/mods/4341) |
| [Finding Susanna Alive](https://www.nexusmods.com/skyrimspecialedition/mods/32512) | [Moon and Star](https://www.nexusmods.com/skyrimspecialedition/mods/4301) |  |
| [Namira for Good Guys](https://www.nexusmods.com/skyrimspecialedition/mods/336) | [Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155) |  |
| [House of Horrors Divine Intervention](https://www.nexusmods.com/skyrimspecialedition/mods/23047) | [Project AHO](https://www.nexusmods.com/skyrimspecialedition/mods/15996) |  |
| [Even Better Quest Objectives](https://www.nexusmods.com/skyrimspecialedition/mods/159) | [Konahrik's Accoutrements](https://www.nexusmods.com/skyrimspecialedition/mods/22206) |  |
| [Thieves Guild Requirements](https://www.nexusmods.com/skyrimspecialedition/mods/33256) | [Artifacts - The Tournament of the Ten Bloods](https://www.nexusmods.com/skyrimspecialedition/mods/15264) |  |
| [All Thieves Guild Jobs Concurrently](https://www.nexusmods.com/skyrimspecialedition/mods/14883) | [The Wheels of Lull](https://www.nexusmods.com/skyrimspecialedition/mods/748) |  |
| [Paarthurnax Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/51711) | [The Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168) |  |
| [The Choice is Yours](https://www.nexusmods.com/skyrimspecialedition/mods/3850) | [Faction - Pit Fighter](https://www.nexusmods.com/skyrimspecialedition/mods/22513) |  |
| [Boethiah for Good Guys](https://www.nexusmods.com/skyrimspecialedition/mods/329) | [The Tale of Tsatampra Xiros](https://www.nexusmods.com/skyrimspecialedition/mods/36707) |  |
| [Better College Application](https://www.nexusmods.com/skyrimspecialedition/mods/5272) | [Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802) |  |
| [Headhunter - Bounties Redone](https://www.nexusmods.com/skyrimspecialedition/mods/51847) |  |  |
| [Save the Icerunner](https://www.nexusmods.com/skyrimspecialedition/mods/34681) |  |  |

### The Magic Mods

[Smart Cast](https://www.nexusmods.com/skyrimspecialedition/mods/32847) has supplanted Sustained Magic in Living Skyrim 3 for a multitude of reasons, the primary being that it works with every other magic mod out of the box. With Smart Cast you can set up specific rules and conditions under which spells will be cast for you - assuming you have the magicka to cast them. It also lets you combine spells into a single cast, again, assuming you have the magicka to cast them both at the same time. This mod has quite a few features available, reading its mod page is highly recommended.

[Spell Tutor](https://www.nexusmods.com/skyrimspecialedition/mods/45275) completely changes how your character learns new spells. Instead of "eating" the book and learning the spell, you now have to spend time studying the spell to learn it. The amount of time it takes to learn new spells is completely configurable through this mod's MCM menu, so feel free to tweak it to your liking. It also places a restriction on how high your skill needs to be before you can even attempt to learn more powerful spells. This mod's inclusion is intended to help balance magic as the combination of magic mods included in Living Skyrim make magic significantly stronger.

[Odin](https://www.nexusmods.com/skyrimspecialedition/mods/46000), [Triumvirate](https://www.nexusmods.com/skyrimspecialedition/mods/39170), and [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440) make up the mods adding new spells to Living Skyrim. Between all of these and the additional options found below, it is possible to have multiple mage playthroughs and never do the same build twice.

[Thunderchild](https://www.nexusmods.com/skyrimspecialedition/mods/1460), [Summermyst](https://www.nexusmods.com/skyrimspecialedition/mods/6285), and [Wintersun](https://www.nexusmods.com/skyrimspecialedition/mods/22506), and [Mundustar](https://www.nexusmods.com/skyrimspecialedition/mods/41674) are all included to make magic as diverse as possible with a huge breadth of options. Wintersun covers the religious aspect of the game, Summermyst covers enchantments, Thunderchild covers shouts, and Mundustar covers the various standing stones of the world.

### The Combat Mods

The core combat package of Living Skyrim is [Blade & Blunt](https://www.nexusmods.com/skyrimspecialedition/mods/34549), The Ultimate Dodge Mod (more details below), and [VioLens](http://violens). Assuming a fair fight this generally means that combat will be fast-paced and somewhat deadly. You won't get one-shot unless you're fighting an enemy that is significantly higher level than you (10+ levels above your own).

[Archery Gameplay Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/24296) completely revamps the archery system in Skyrim. You'll find it now has much more realistic gameplay including arm fatigue, the ability to spread poisons across multiple arrows, stamina drain while the bowstring is pulled, and so on. This mod is highly configurable via its MCM menu, so feel free to tweak it to suit your playstyle.

Also for your consideration: [SkyTEST](https://www.nexusmods.com/skyrimspecialedition/mods/1104), [Deadly Dragons](https://www.nexusmods.com/skyrimspecialedition/mods/23723), and [Arena - An Encounter Zone Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/33487). Enemies in general will be smarter and stronger across the board, and will dynamically update their levels to match or surpass you as appropriate.

### The Ultimate Dodge Mod

The Ultimate Dodge Mod is a very simple but powerful mod: it allows you to dodge while in combat. 

By default, TUDM hijacks the vanilla sneak key in order to have no delay or script lag when dodging. Living Skyrim by default uses the following keybinds for TUDM:

- Sneak Key: Left Shift
- Dodge: Ctrl

If you would like to change these keybinds, keep in mind that the Sneak Key you set in the vanilla controls menu will be the key you press to dodge, and the Sneak Key you set in the TUDM MCM will be the key you press to sneak.

A couple of minor notes about TUDM:

- You cannot dodge in the Alternate Perspective starting room, you must leave that cell first before being able to dodge.
- The first time you press the dodge key, you'll be stuck in a weird position in the air. Press your  \ | key twice to become unstuck.
- It is recommended to set TUDM to sidestep OR roll only in the TUDM MCM, not both.

### The Perks & Leveling Mods

[Vokrii](https://www.nexusmods.com/skyrimspecialedition/mods/26176) is the perk overhaul of choice for Living Skyrim. It is a lightweight but still complete overhaul of the perk trees allowing for an incredibly diverse amount of character customization and specialization. [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) is included to control the rate at which your skills and levels progress. By default, only clearing dungeons and completing quests will provide XP. The optional skills XP and kills XP modules should not be turned on - Living Skyrim isn't set up to use these by default and can therefore cause issues. [Achieve That](https://www.nexusmods.com/skyrim/mods/30212) is an achievement mod which gives you XP and achievement points. The XP given is almost equivalent to that of main quests, and is a great way to level up your character as the game progresses. The achievement points can be spent on rewards that permanently benefit your character which normally come as a stat boost or perk.

### The Economy & Loot Mods

There are two sides to the Skyrim economy: Loot, and trade. Loot is your primary source of income, and trade your primary source of expenditure. To address this, Living Skyrim seeks to overhaul both sides of this coin.

On the loot side, you'll find that chests and enemies are fairly abundant loot thanks to [GOLD](https://www.nexusmods.com/skyrimspecialedition/mods/1796), [Dynamic Dungeon Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308), and [Lock Related Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308). In general, chests have been overhauled such that no two chests are ever the same and contain a fantastic assortment of things you can find. You may also find powerful items significantly earlier than normal due to Dynamic Dungeon Loot. Normally this would be cause for concern, but you will also find that the amount of just randomly placed objects in the world has been significantly decreased by [Iris](https://www.nexusmods.com/skyrimspecialedition/mods/41920). The removal of most of the items placed in the world shifts the focus of loot from picking up everything in a dungeon to seeking out and opening every chest you can find.

Opposite the loot side, we have the economy side of things. Naturally, because of the increased amount of loot you'll find, the price of many items has been increased drastically. No longer will a set of steel armor cost just a couple hundred gold - instead, you'll find it costs well over 1000 gold, and higher level armors only get even more expensive. The same is true of just about everything you can purchase from a vendor. This is due to the combination of [Trade & Barter](https://www.nexusmods.com/skyrimspecialedition/mods/23081) and [Eve](https://www.nexusmods.com/skyrimspecialedition/mods/26325). Items will sell for less and cost more to buy across the board. This is necessary to make looting feel significant while also keeping some semblance of balance. In general it will be more difficult to obtain obscene amounts of gold, but it is still possible - that's just how Skyrim works without going completely overboard modifying the loot/economy. Also, for the more kleptomania-inclined among you, you'll find some helping hands in [Khajiits Steal Too](https://www.nexusmods.com/skyrimspecialedition/mods/18231).

### The HUD Mods

Living Skyrim includes a completely different UI and HUD experience than what you're used to, probably even if you've played modded Skyrim before. [Less Intrusive HUD II](https://www.nexusmods.com/skyrimspecialedition/mods/17974) is 100% customizable through an in-game menu, allowing you to change the position, size, opacity, and anything else for any HUD element. [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246) changes the dialogue menu to be easier to read and use and is also 100% configurable. See the mod description pages for EZ2C and Less Intrusive HUD II to see how to configure these to your liking. [Immersive HUD](https://www.nexusmods.com/skyrimspecialedition/mods/12440) keeps pesky HUD elements out of the way when you don't need to see them. Lastly, [Favorite Things](https://www.nexusmods.com/skyrimspecialedition/mods/27177) greatly expands the SkyUI Favorites menu to make it larger, easier to use, and more customizable.

### Character Customization Mods

When creating your character, you'll find there are a lot of options that are available to you. From hairs to tattoos to eyes and more, Living Skyrim has included a comprehensive suite of mods that allow you to tweak your character's appearance to exactly what you want. And, if you're struggling to figure out where to begin with character creation, a number of presets made by the Living Skyrim community have been included for you to pick from. In general, you'll have more options for everything.

There is one particular mod you need to be aware of during character creation: [High Poly Head](https://vectorplexus.com/files/file/283-high-poly-head/). To have your character use High Poly Head, you'll need to change the head part using the RaceMenu slider of the same name to option 3. Note that if you do use High Poly Head, you may need to do some manual sculpting using the RaceMenu sculpt feature to remove any clipping issues with eyebrows or beards.

### Player Homes

Living Skyrim includes a fairly diverse selection of player homes that are suitable for a number of different character styles. See below for a complete listing. 

Additionally, several of the quest mods included with Living Skyrim have player homes associated with them. Namely, Legacy of the Dragonborn, Helgen Reborn, and Project AHO. Make sure to investigate all of your options! 

| Player Homes |  |
| :--- | :--- |
| [Blackthorn](https://www.nexusmods.com/skyrimspecialedition/mods/2242) | [Morskom Estate](https://www.nexusmods.com/skyrimspecialedition/mods/33408) |
| [The Scarlett](https://www.nexusmods.com/skyrimspecialedition/mods/2434) | [The Raven's Breezehome](https://www.nexusmods.com/skyrimspecialedition/mods/20486) |
| [Riverside Shack](https://www.nexusmods.com/skyrimspecialedition/mods/20982) | [Mornfallow Manor](https://www.nexusmods.com/skyrimspecialedition/mods/411) |
| [Redspire Manor](https://www.nexusmods.com/skyrimspecialedition/mods/2460) | [JK's Riverfall Cottage](https://www.nexusmods.com/skyrimspecialedition/mods/34542) |
| [Gleamblossom Hollow](https://www.nexusmods.com/skyrimspecialedition/mods/26277) | [Zulfardin](https://www.nexusmods.com/skyrimspecialedition/mods/33889) |
| [Winking Skeever Loft](https://www.nexusmods.com/skyrimspecialedition/mods/41895) | [Niflholm](https://www.nexusmods.com/skyrimspecialedition/mods/8681) |
| [Mona Alta](https://www.nexusmods.com/skyrimspecialedition/mods/9883) | [Pinewood Manor](https://www.nexusmods.com/skyrimspecialedition/mods/6635) |

### Nether's Follower Framework

[Nether's Follower Framework](https://www.nexusmods.com/skyrimspecialedition/mods/18076) has too many features to list, but what you need to know is this: You can have multiple followers, you can configure just about anything about them, and you'll have a lot more flexibility with controlling your followers. You can also import followers added by mods to be able to use NFF's features on them.

{{< tip >}}
**Important!** 

Do NOT import standalone followers (Inigo, Lucien, etc.) into Nether's Follower Framework. It will 100% break them. The notable exceptions to this are Auri and any of the Interesting NPCs followers.
{{< /tip >}}

## Bug Reporting, Github, and You

While we have tried out best to eliminate as many bugs and inconsistencies as possible, it is unfortunately a near certainty that at some point you will come across something that could be considered a bug. Whether it's duplicate objects overlapping, an imbalanced crafting recipe, or something else entirely, it's important that you report bugs you find on the Living Skyrim 3 Github so that it can be fixed for everyone.

To report a bug, follow these steps:

1.  Login to [Github](https://github.com/) or create an account as necessary.
2.  Open this link: [Click Here!](https://github.com/ForgottenGlory/Living-Skyrim-3/issues/new/choose)
3.  Click the green button that says "Get Started" in the line next to "Bug Report".
4.  Input a title and fill out the form in the large text box. If you need to attach a screenshot, it can be dragged from your computer to the Github post to insert it.
5.  When you have filled out the form completely, click the green "Submit new issue" button.

After that, you've filed your bug report and the LS dev team will take a look at it as soon as possible.

{{< tip >}}
**Important!** 

Don't forget to check back on your report periodically just in case we request more information from you.
{{< /tip >}}

## Common Issues

### Wabbajack Issues

#### “A mod failed to download.”

The short answer: wait for an update to the list. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Living Skyrim is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

#### “Wabbajack says I’m out of requests.”

Nexus Premium is limited to 2500 downloads in a given 24 hour timeframe. Usually this limit resets around 9PM Eastern Time. Wait for your limit to reset and you’ll be able to proceed. Usually this only occurs after attempting to download the list multiple times in a row or when attempting to download multiple lists in the same 24 hour window.

#### “Can I pause the installation?”

Yes, just close Wabbajack. When you start the installation process again it will pick up from where it left off.

#### “Can I delete the downloads folder after installing?”

Yes, but remember that if you need to update the list you will have to download all of the mods that have updated again.

#### “The LS3 DynDOLOD Output fails to download.”

You’ll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [LS3 DynDOLOD 3.5.0](https://drive.google.com/file/d/1hQa0DgfIZLxW3MkOzPiVK82524h8EAuw/view?usp=sharing)

#### “The LS3 SSELODGen Output fails to download.”

You’ll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [LS3 SSELODGen 3.0.0](https://drive.google.com/file/d/1C8shpKCM4CO2fcoxasiw501rgBQiGmAQ/view?usp=sharing)

#### “The LS3 Grass Cache fails to download.”

You’ll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [LS3 Grass Cache 3.5.0](https://drive.google.com/file/d/1Yk3Nlq3d5775QXdZSExHVMHQI2E0zqBy/view?usp=sharing)

#### "Inconsequential NPCs Visual Overhaul fails to download."

You'll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [INPCs Visual Overhaul](https://drive.google.com/file/d/1YM0lFTQdDh6P3JvEgWleOMb3adF_pQ_i/view?usp=sharing)

#### "ENB Series fails to download."

You'll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [ENB Series](http://enbdev.com/download_mod_tesskyrimse.htm)

#### "MEGA hosted files are failing to download."

Download the files manually and put them in your downloads folder. A list of all the MEGA hosted files for the list are here:
- [Smooth Random Blocking Animation](https://mega.nz/file/4LxGTALK#7I8XPLnIW0PxR_r_nXMP-9ZUnZ16MlFVMdFdgGy-gF0)
- [Smooth Random Magic Idle Animation](https://mega.nz/file/IS4EjJhC#inP4yfb3i-UO_sx790OpoFDk81x-WIRf9WcBeKxnmYo)
- [Smooth Random Sprint Animation](https://mega.nz/file/8T4ixLCB#YKQw5EDFdL1_e-5G_JB8WgmUkJ8N0kNtpzeOwUHZcZY)
- [xLODGen.83](https://mega.nz/file/EcJhgKpY#4Q86Rd1hUepjm233r8Q_7x3fTWx9axJN2CUc8FXrBsg)

### Gameplay Issues

#### “The Main Quest doesn’t proceed after retrieving the Dragonstone.”

Read this modpage: [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704)

#### “Tolfdir doesn’t invite me to Saarthal right away.”

Read this modpage: [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704)

#### My character gets stuck when dodging!

This is a known issue with TUDM. Press the Dodge Style Toggle key (Your \ | key, by default) and your character should resume moving.

#### “Can I access RaceMenu after character creation?”

Only if you are not changing your character’s gender or race. Changing gender/race will cause issues with powers and passive buffs your character has.

#### “Can I change my attributes after starting?”

No. The choices you make are permanent. You can increase your attributes through various methods, refer to this modpage for more details: AVA

#### “My screen is zoomed in or weirdly off-center.”

Check the SSE Display Tweaks INI file to make sure you have the resolution for your screen set correctly. You may also need to check BethINI or the Skyrim INI files to make sure they all match your screen’s resolution.

#### “MO2 cannot find SKSE.”

You’ll need to manually set the path for SKSE using the Edit Executables menu in MO2. Set it to `[install folder]\Stock Game\skse64_loader.exe`

#### “Can I use a controller?”

I strongly advise against it. With as many mods as there are in the list, you’ll need a full breadth of keyboard keys to activate and use every feature. If you absolutely must play with a controller, please, for the love of all that is holy, use Gamepad++.

#### “My game freezes when saving.”

Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

#### “Can I play this list on a 75/100/144hz screen?”

Yes. Display Tweaks SSE is included to allow higher refresh rates.

#### “Can I use this list on an ultrawide monitor?”

Yes, Complete Widescreen Fix is included by default. Just make sure to enable it in the left pane of MO2.

#### Nudity?

By default, Living Skyrim has every character be never nude. Underwear is worn by all NPCs and the player character and cannot be unequipped. Support is not provided for making the list Nude.

## Adding to Living Skyrim

Many Skyrim modders ask the question: “Can I add mods to Living Skyrim?” (Or, “Can I remove mods from Living Skyrim?”, or, “Can I change the mods included with Living Skyrim?”)

If you are asking this question from a perspective of just installing the mod and expecting it to work, then the answer is a resounding, unequivocal NO.

The longer and slightly more technical answer is: “I don’t know, can you?”

To expand on this: nobody knows whether you can add a certain mod or not. Adding to, changing, or removing from the list isn’t a yes/no question. In 99.9% of cases, the answer is, “Yes, but…“

The “but…” part of that answer refers to the process of installing any mod and stems from a deeply rooted belief that mods are either compatible with each other, or they are not. Assuming that any mod is (or is not) compatible with any other mod is absurd. Every mod can be made to work with every other mod, the real questions you should be asking are: “How much work would it take to add this mod?” and “Do I have the knowledge, tools, and skills to add this mod?”

And unfortunately, the answer to those questions is a resounding, unequivocal, “It depends.” And it depends on the answers to these questions, which you, and only you, can answer: Does it require compatibility/consistency patching in xEdit? Does it require modifications in Creation Kit? Does it require that it be loaded in a certain place in the load order? Does it need additional mods (which also require answers to these questions) to function?

Lastly, I (ForgottenGlory) and the Living Skyrim development team do not support this in any way, shape, or form. If you’re going to add a mod to Living Skyrim, you need to be prepared to do it on your own. I understand this isn’t an ideal answer for people relatively new to modding, but you need to understand that hundreds of hours have been spent putting together Living Skyrim, making it as stable as possible with all the mods working in harmony. Adding a bunch of random mods on top of it and then expecting it to “just work” is naive at best.

“Can I add a mod to Living Skyrim?”

I don’t know, can you?

## Performance Optimizations

Click here to visit the [Performance Optimizations](/livingskyrim/performanceguide) guide for Living Skyrim.

## Credits & Thanks
- Living Skyrim created by ForgottenGlory
- Living Skyrim Dev Team:
  - Volk (Boll)
  - Spandanahan (Formerly Melisandre)
  - Rite of Spring (Formerly JaceVenture)
  - Magnus Hellfire
  - Bearnard
  - Volkaru
  - JaxomOfRuatha
  - TwistedModding
  - celadoneiron
- Living Skyrim Discord Staff:
  - Chanka
  - Aronax
  - goolito
  - Logan
  - Pulsefire ezreal
  - Sae the Intern
  - Day7
  - TheCampingOwl
  - Sean Misses Scotch
  - ChunkeeMunkee
  - Dace617
  - Gooala
  - scraunch
  - Shiv
  - GravenImages
- Contributors & Beta Testers:
  - Patchier
  - DwarfDude
  - Qwerrecd
  - Timboman
  - Pyrasaurus
  - Total
  - Dispo
  - Dracosaber
  - Sentrus
  - Nechrion
  - Xanza (For MCM Automation, thank you!)
  - tjbassoon
- Halgari & The Wabbajack Team
   - Thank you for creating Wabbajack, you’re amazing!
   - Halgari’s Patreon
- Special Thanks
   - The TUCO Modding Team - Their modlist is a great way to get a Vanilla+ experience with a tutorial that is extremely helpful for learning the basics of creating a modlist.
   - DarkLadyLexy - Her LotD list is an invaluable resource not only for an awesome modlist, but also for learning many fundamentals of modding and compiling a modlist.
   - EzioTheDeadPoet - For their SME(FT) modlist. The ability to start from scratch on a whim while building this list has been invaluable.
  - My Patreon patrons.
- Mod Authors
  - None of this would be possible without the people who make the quality content we’ve grown to know and love. Please endorse the authors’ works.

## One Last Thing

If you read through the entire readme, congratulations! You get a cookie. If you need any further help, feel free to reach out on the Wabbajack or Living Skyrim Discord Servers. **Do not direct message ForgottenGlory, any of the Living Skyrim dev team, or any Wabbajack staff members for support. I (ForgottenGlory) speak for myself, but I do reserve the right to ignore any requests for support direct messaged to me and block you.**
