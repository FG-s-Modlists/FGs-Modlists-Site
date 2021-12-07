---
title: "Readme"
weight: 1
layout: "potdbase"
---

## Before You Get Started
Before you get started installing or playing Path of the Dovahkiin, it's important to note a few things:

{{< tip >}}
**Important!** 

Sections labeled important like this one will tell you when you need to pay extra attention to something.
{{< /tip >}}

{{< tip "warning" >}}
**WARNING!**

**Warning blocks like this one will warn you when you absolutely must not forget to do something. Failure to heed warning blocks is cause for disaster.**
{{< /tip >}} 

- You are not required to have Nexus Premium to install Path of the Dovahkiin , however, it is highly recommended. Nexus Premium will cut your install time to a fraction of what it would be by automating both the mod download and mod install processes of installing the list.
- As of version 1.0.0, Path of the Dovahkiin requires 158GB of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing to an SSD/NVMe is not required, but also highly recommended. Download and installation times vary based on your computer and internet speeds, but expect the entire process to take a few hours. If you are installing the list without Nexus Premium, expect the process to take a couple of days of 8+ hour sessions downloading mods.
- To maximize performance, both Skyrim: Special Edition and Path of the Dovahkiin should be installed on the same hard drive, ideally an SSD/NVMe. This is not required, just recommended if you want the smoothest gameplay experience.
- If you are not familiar with the contents of this modlist, a complete documentation of every mod in the list including links to the mods is available on the POTD Modlist Spreadsheet.
- If you instead only wish for a brief overview of the major changes this modlist makes, you should refer to the Important Mods You Need to Know About of this document.
- Autosaves for Path of the Dovahkiin are disabled. You should make your quicksave button your best friend (usually, the F5 key).
- Continuing the last point, it is always better to save **before** entering a loading screen instead of after. After a loading screen it is very likely that scripts will be running for at least 30 seconds, so if you must save after a loading screen, at least wait that long before doing so.
- Wabbajack does support updating an existing installation of a modlist. However, as part of this process, it does delete files that don't match with what it is installing. This includes RaceMenu presets, mods you've added/changed, and possibly even save files. It is a good practice to keep backups of your save files so that you can update safely. Saves are stored within the folder you install Path of the Dovahkiin to.
- In Path of the Dovahkiin, NPCs and player characters are never nude. Underwear is worn by all NPCs and the player character and cannot be unequipped.
- Adding to, changing, or removing from Path of the Dovahkiin is not supported. See the Adding to Path of the Dovahkiin section of this document for more details.
- As many common issues as I could find have been documented in the Common Issues section of this document. Refer to this before asking for support.
- If you want some tips related to getting started playing the list, refer to the Getting Started in Path of the Dovahkiin section of this document.
- By default, Path of the Dovahkiin has the game running in exclusive fullscreen mode to assist with game performance.

### System Specifications
The following system is ForgottenGlory's personal computer and is able to run the list at a constant 60FPS including ENB at 1440p monitor resolution. Use it as a guide to determine how your own computer might run the list.

- CPU: AMD Ryzen 9 3900X @ 4.2GHz
- RAM: G.Skill TridentZ Neo 32GB DDR4 3600MHz CL16
- GPU: nVidia RTX 2080 Super 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz
- Storage: Sabrent Rocket 2TB M.2 NVMe 2280; Samsung EVO 860 250GB; SeaGate Barracuda 2TB 7200RPM

In general, it is recommended that you have a processor with a clock speed of at least 3GHz and a graphics card with at least 6GB of VRAM. 4GB graphics cards may be able to run the list if you do not use ENB, but it is not guaranteed.

As for RAM, 16GB is the minimum recommended specification for running the list. 32GB is the ideal amount, and anything more than that is honestly overkill for this list.

### Important Links
- [The Modlist Spreadsheet](https://docs.google.com/spreadsheets/d/1EielytXpSpG5tPQJU-tIbLjQKxh0XRWKc_yP2zgRQK8/edit?usp=sharing)
- [Path of the Dovahkiin Bug Tracker](https://github.com/ForgottenGlory/POTD/issues)
- [Path of the Dovahkiin Discord](https://discord.com/invite/NdmGpGzqg8)
- [Path of the Dovahkiin Patreon](https://www.patreon.com/LivingSkyrim)
- [Path of the Dovahkiin Build Planner](https://thehajo.github.io/PotD/)

### Screenshots
[Path of the Dovahkiin Screenshot Gallery](/potd/screenshots)

## Pre-Installation

### Steam & SSE Setup
{{< tip "warning" >}}
**WARNING!**

Path of the Dovahkiin is not compatible with either the Skyrim Anniversary Edition or the free Anniversary Update.

**If your Skyrim Special Edition received an update through Steam or you installed Skyrim Special Edition anytime after November 11, 2021, you have the Anniversary Update.**

You must use the FULL AE downgrade patcher - [HERE](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=243513&game_id=1704)

To prevent your game updating, change Skyrim SE's update settings in Steam to only update when launched. Never launch Skyrim SE via Steam, only via your mod manager or skse64_loader.\
{{< /tip >}}

Before proceeding with installation, it’s important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files, Program Files (x86), Desktop, or Documents folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. For more information about how this can be problematic and how Windows protects folders, consult this link: [Click Me!](https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/controlled-folders?view=o365-worldwide) Instructions on how to move your Steam library can be found elsewhere on the internet.

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

### Wabbajack Preparations
We’ll now setup the folders needed for the installation to proceed smoothly.

1. Create two empty folders: one named Wabbajack and the other named Path of the Dovahkiin.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, your Program Files (x86) folder, or the Desktop.
3. Additionally, ensure that these two folders are not contained within each other.
4. Ensure that both the Wabbajack and Path of the Dovahkiin folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: [Wabbajack](https://www.wabbajack.org/#/).
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

{{< tip "warning" >}}
**WARNING!**

**Failure to set up these folders properly will result in the install failing. For example, `[install drive]\Wabbajack\Path of the Dovahkiin` is incorrect.**
{{< /tip >}} 

## Installing the List

If you are updating your existing installation of Path of the Dovahkiin, skip to the [Updating Path of the Dovahkiin](#updating-path-of-the-dovahkiin) section of this document.

It’s now time to begin the installation of the list. Follow these steps:

1. Run Wabbajack.exe.
2. At the bottom of the window, click Browse Modlists.
3. Locate the Path of the Dovahkiin card and click the download button to download the installer file.
4. Once downloaded, click the play button.
5. Below the image you see of the Path of the Dovahkiin logo, there are three text boxes. The second and third need to be filled out.
6. Click the three dots in the second (middle) box. Navigate to your Path of the Dovahkiin folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you’ll need to use to launch the list.
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

If it does not complete successfully (a red box with "Installation failed"), consult the Common Issues section of this document, or visit the [Path of the Dovahkiin Discord server](https://discord.gg/NdmGpGzqg8) for assistance. 

## Post-Wabbajack Install

### Mod Organizer 2
Among other things, Wabbajack has installed a copy of Mod Organizer 2 for you. This copy of Mod Organizer 2 is specific to Path of the Dovahkiin and will not affect any other modlists you have installed.

1. Inside your Path of the Dovahkiin folder, locate and launch ModOrganizer.exe. If this is not inside the folder, your installation has failed and you need to consult the Common Issues section of this document.
2. Mod Organizer 2 will have a dark theme already selected for you. If it does not, something has gone wrong and you will need to start over at the Installing the List section of this document.
3. A dialogue may appear and ask if you want to associate Mod Organizer with .nxm links. Click Yes. If this dialogue does not appear, it is not an issue and means you’ve likely already done this.
4. Another dialogue may appear asking you to update the game's registry path. Click Yes on this popup if it appears. If it does not appear, it is not an issue and likely means you've already done this.

### Configuration Specific

If you're using an ultrawide monitor, you can enable either of the Nordic UI Ultrawide options under the "Configuration Specific" section of the left pane of MO2. Just make sure you only enable the one that matches your monitor's resolution ratio.

### ENB

The default ENB included with Path of the Dovahkiin is [Culminated ENB](https://www.nexusmods.com/skyrimspecialedition/mods/53167). Support is not provided for changing it. You may, however, disable ENB during play by loading into the game and pressing `Shift + F12`. Disabling ENB will drastically improve performance but will make the game look worse overall.

## Updating Path of the Dovahkiin
If you are updating Path of the Dovahkiin, the process is very similar to installing the list. Before you update, you should at a minimum backup your save files. Updating may delete any saves that are present. Additionally, make sure you are using the latest version of Wabbajack (it should automatically update itself when you launch the program).

{{< tip "warning" >}}
**WARNING!**

**Whilst some incremental list updates are save-safe, larger updates often require a brand new save file to avoid corruption. Check the newest update announcement found in the `#potd-announcements` channel on the Discord server before updating.**
{{< /tip >}} 

1. Run Wabbajack.exe.
2. At the bottom of the window, click Browse Modlists.
3. Locate the Path of the Dovahkiin card and click the download button to download the installer file.
4. Once downloaded, click the play button.
5. Below the image you see of the Path of the Dovahkiin logo, there are three text boxes. The second and third need to be filled out.
6. Click the three dots in the second (middle) box. Navigate to your Path of the Dovahkiin folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you’ll need to use to launch the list.
7. The third (bottom) box will automatically populate using the folder you just selected. This third box tells you where all of the mods will be downloaded. If you have hard drive limitations, you may change this to another folder on another hard drive by clicking the three dots in this box and selecting a new folder.
8. Click the play/right arrow button to begin the installation.
9. If you are prompted to overwrite, confirm that this is what you want to do by clicking the Confirm button.

## Launching Path of the Dovahkiin
To actually launch and then play Path of the Dovahkiin, follow these steps:

1. Launch the copy of Mod Organizer 2 found inside your Path of the Dovahkiin folder.
2. In the top-right corner of Mod Organizer, you’ll see a large dropdown menu. Select Path of the Dovahkiin [SKSE] from this dropdown menu.
3. Click the large Run button.
4. This is how Path of the Dovahkiin should always be launched. You can create a shortcut to this selection on your desktop, if you wish, using the Shortcut button directly below the large Run button.
5. Once Skyrim starts, create a new game.
6. Create your character and name them whatever you’d like.
7. As soon as you gain control of your character, do nothing. The mods are initializing and this can take several minutes. You’ll see a list of mods appearing in the top left corner of your screen.
8. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

{{< tip "warning" >}}
**WARNING!**

**Loading a save from another modlist or from before you installed Path of the Dovahkiin will corrupt that save, do not do this.**
{{< /tip >}} 

## The MCM Settings
Some MCM settings have been pre-set for you. See this document to set the remaining MCMs that are required for POTD to function correctly: [Click Here](/potd/mcm)

## Getting Started in Path of the Dovahkiin

- You get special, unique perks for completing the major questlines. Questing is highly recommended.
- Master your classes! You can master up to two classes and when you do, you keep the bonuses of the mastered class even when you switch to another one.
- Bandits are your best bet for early levels. They usually come in small enough groups to be manageable and are almost always around your level or slightly higher.
- The Whiterun/Riverwood area is best for starting out - northern areas will be significantly more difficult.
- Grind! This is supposed to be an ARPG experience, so grinding the same few dungeons a few times will help you get stronger to take on higher level dungeons. It also gives you access to more loot which can make you significantly stronger.
- If you feel like you don't have enough perk points, try seeking out and killing bosses! They give you perk points when they die. It will be challenging but the extra points are well worth it.
- If you don't like your character's perk point selections, you can sometimes find a potion that will allow you to respec your perk points available for purchase from alchemists. It's expensive though, so be certain you want to do this! 
- Overworld enemies are going to be easier and in smaller groups than dungeons, but avoid the larger overworld locations when starting out: Silent Moons Camp, Fort Greymoor, etc. Delving into caves and dungeons is a good way to get surrounded by a group of 6-10 enemies.

## Important Mods You Need To Know About

### Character Creation And Builds

Character Creation is fairly straightforward, but you should be aware that you can pick a class using [Sets of Skills](https://www.nexusmods.com/skyrimspecialedition/mods/55535) and its related MCM. By default you can master up to two classes and the classes you master are *permanent*, so plan carefully! More character builds are facilitated by [Vokriinator Black](https://www.nexusmods.com/skyrimspecialedition/mods/26702), which you'll notice in the form of the absolutely enormous perk trees. [Perks From Questing](https://www.nexusmods.com/skyrimspecialedition/mods/29402) gives you special, unique perks when you complete certain quest lines. Choose which quests to do that synergize with your character build for maximum effectiveness. 

### Leveling Up

This one's important. You don't level up like normal anymore in Path of the Dovahkiin. Instead, [Gold is XP](https://www.nexusmods.com/skyrimspecialedition/mods/20084) is used to... well, make gold into XP. When you sleep and have acquired enough gold, you'll get the option to increase whichever skills you choose. This allows you to pick exactly which direction you want to build your character into. You'll level up quickly until about level 20 or so, and then level ups will start taking longer and longer to receive. Gold is XP also counts gold you receive from selling loot, so keep that in mind. Note that because this mod is included, it's near impossible to max every skill to 100. You'll have to choose carefully and specialize to build your character.

### The Enemy Mods

In general you'll find that enemy variety and quantity is significantly increased thanks to [Increased Enemy Spawns](https://www.nexusmods.com/skyrimspecialedition/mods/2470) and [Heritage](https://www.nexusmods.com/skyrimspecialedition/mods/30017). They've also been beefed up by [Enemy Releveler](https://www.nexusmods.com/skyrimspecialedition/mods/2470). Dragons are handled by [Dragon War](https://www.nexusmods.com/skyrimspecialedition/mods/32211). That said, enemies aren't particularly more difficult, especially once your character build starts to come together. There's also a handful of mods included that increase animal/monster variety. 

Last but not least, enemies respawn every 24 in-game hours thanks to [1 Day Respawn Time](https://www.nexusmods.com/skyrimspecialedition/mods/5394). Feel free to grind and master dungeons to your heart's content!

### The Magic Mods

[Triumvirate](https://www.nexusmods.com/skyrimspecialedition/mods/39170), [Mysticism](https://www.nexusmods.com/skyrimspecialedition/mods/27839) and [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440) make up the magic package for Path of the Dovahkiin. Most spells have been overhauled and Triumvirate/EDM allow for most variety in spells and new builds based on those spells.

### The Dungeons

For your enjoyment you'll find [Hammet's Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/12186), [Forgotten Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/449), [More Bandit Camps](https://www.nexusmods.com/skyrimspecialedition/mods/1994), [Dungeons - Revisited](https://www.nexusmods.com/skyrimspecialedition/mods/51798), and [Immersive Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/16706) available to explore and conquer.

### Loot, Loot, and More Loot

No ARPG would be complete without an absolutely insane amount of loot. POTD accomplishes this by using [Halgari's RPG Loot](https://www.nexusmods.com/skyrimspecialedition/mods/37736), which provides over *one million* unique pieces of armor and weapons you can collect and use. [GOLD](https://www.nexusmods.com/skyrimspecialedition/mods/1796), [Lock Related Loot](https://www.nexusmods.com/skyrimspecialedition/mods/11342), and [Dynamic Dungeon Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308) round out the loot package by increasing the amount you'll find while dungeon delving.

To counterbalance the increased amount of loot, [Trade & Barter](https://www.nexusmods.com/skyrimspecialedition/mods/23081) is used to increase the price of items in shops and decrease the amount of gold your loot sells for.

Last but not least, if you're feeling particularly brave, a tweaked version of [MILK](https://www.nexusmods.com/skyrimspecialedition/mods/15876) is included that pulls from the Halgari's RPG Loot pool to give you random sets if items, gold, and more.

Last but not least, there are a couple of mods that add hidden treasures throughout the world that you can find.

## Bug Reporting, Github, and You

While we have tried out best to eliminate as many bugs and inconsistencies as possible, it is unfortunately a near certainty that at some point you will come across something that could be considered a bug. Whether it's duplicate objects overlapping, an imbalanced crafting recipe, or something else entirely, it's important that you report bugs you find on the Path of the Dovahkiin Github so that it can be fixed for everyone.

To report a bug, follow these steps:

1.  Login to [Github](https://github.com/) or create an account as necessary.
2.  Open this link: [Click Here!](https://github.com/ForgottenGlory/POTD/issues/new/choose)
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

First, you can also try enabling the Network Workaround option in the settings for Wabbajack to see if it will download the file after enabling that setting.

Otherwise, wait for an update to the list. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Path of the Dovahkiin is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

#### "MEGA hosted files are failing to download."

If MEGA downloads are either not downloading correctly or are frozen on the completed download page download the manually from the following links and place them in your POTD download folder:

- [Smooth Random Blocking Animation](https://mega.nz/file/4LxGTALK#7I8XPLnIW0PxR_r_nXMP-9ZUnZ16MlFVMdFdgGy-gF0)
- [Smooth Random Magic Idle Animation](https://mega.nz/file/IS4EjJhC#inP4yfb3i-UO_sx790OpoFDk81x-WIRf9WcBeKxnmYo)
- [xLODGEN.84](https://mega.nz/file/dEwQnJRS#E-qpq29rVCBw3FxT3gTOjF_Z2zYkzR2CcWhQ5OAZcwg)

#### “Wabbajack says I’m out of requests.”

Nexus Premium is limited to 2500 downloads in a given 24 hour timeframe. Usually this limit resets around 9PM Eastern Time. Wait for your limit to reset and you’ll be able to proceed. Usually this only occurs after attempting to download the list multiple times in a row or when attempting to download multiple lists in the same 24 hour window.

#### “Can I pause the installation?”

Yes, just close Wabbajack. When you start the installation process again it will pick up from where it left off.

#### “Can I delete the downloads folder after installing?”

Yes, but remember that if you need to update the list you will have to download all of the mods that have updated again.

#### "ENB Series fails to download."

You'll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [ENB Series](http://enbdev.com/download_mod_tesskyrimse.htm)

### Gameplay Issues

#### “Can I access RaceMenu after character creation?”

Only if you are not changing your character’s gender or race. Changing gender/race will cause issues with powers and passive buffs your character has.

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

By default, Path of the Dovahkiin has every character be never nude. Underwear is worn by all NPCs and the player character and cannot be unequipped. Support is not provided for making the list Nude.

## Adding to Path of the Dovahkiin

Many Skyrim modders ask the question: “Can I add mods to Path of the Dovahkiin?” (Or, “Can I remove mods from Path of the Dovahkiin?”, or, “Can I change the mods included with Path of the Dovahkiin?”)

If you are asking this question from a perspective of just installing the mod and expecting it to work, then the answer is a resounding, unequivocal NO.

The longer and slightly more technical answer is: “I don’t know, can you?”

To expand on this: nobody knows whether you can add a certain mod or not. Adding to, changing, or removing from the list isn’t a yes/no question. In 99.9% of cases, the answer is, “Yes, but…“

The “but…” part of that answer refers to the process of installing any mod and stems from a deeply rooted belief that mods are either compatible with each other, or they are not. Assuming that any mod is (or is not) compatible with any other mod is absurd. Every mod can be made to work with every other mod, the real questions you should be asking are: “How much work would it take to add this mod?” and “Do I have the knowledge, tools, and skills to add this mod?”

And unfortunately, the answer to those questions is a resounding, unequivocal, “It depends.” And it depends on the answers to these questions, which you, and only you, can answer: Does it require compatibility/consistency patching in xEdit? Does it require modifications in Creation Kit? Does it require that it be loaded in a certain place in the load order? Does it need additional mods (which also require answers to these questions) to function?

Lastly, I (ForgottenGlory) and the Path of the Dovahkiin development team do not support this in any way, shape, or form. If you’re going to add a mod to Path of the Dovahkiin, you need to be prepared to do it on your own. I understand this isn’t an ideal answer for people relatively new to modding, but you need to understand that hundreds of hours have been spent putting together Path of the Dovahkiin, making it as stable as possible with all the mods working in harmony. Adding a bunch of random mods on top of it and then expecting it to “just work” is naive at best.

“Can I add a mod to Path of the Dovahkiin?”

I don’t know, can you?

## Credits & Thanks
- Path of the Dovahkiin created by ForgottenGlory
- Path of the Dovahkiin Dev Team:
  - Volk (Boll)
  - Spandanahan (Formerly Melisandre)
  - Rite of Spring (Formerly JaceVenture)
  - Magnus Hellfire
  - Bearnard
  - Volkaru
  - JaxomOfRuatha
  - TwistedModding
  - celadoneiron
- Path of the Dovahkiin Discord Staff:
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
  - Vyktory
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

If you read through the entire readme, congratulations! You get a cookie. If you need any further help, feel free to reach out on the Wabbajack or Path of the Dovahkiin Discord Servers. **Do not direct message ForgottenGlory, any of the Path of the Dovahkiin dev team, or any Wabbajack staff members for support. I (ForgottenGlory) speak for myself, but I do reserve the right to ignore any requests for support direct messaged to me and block you.**
