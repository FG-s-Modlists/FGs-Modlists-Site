---
title: "Installation Instructions"
description: "Living Skyrim's installation instructions."
lead: ""
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  livingskyrim:
    parent: "living skyrim"
weight: 30
toc: true
---

## Pre-Installation

### Microsoft Visual C++
The Visual C++ Redistributable is a DLL (Dynamic Link Library) file required by programs or games built using Microsoft’s Visual Studio software development environment. As Skyrim Special Edition is a 64-bit program, elements of it - along with other aspects of the modlist - require the 64-bit version of Visual C++ in order to run.

Click the link to download the latest Visual C++ x64 Redistributable, then double-click the downloaded file and follow the instructions:
- [Microsoft Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)

### Steam & SSE Setup
{{< alert context="danger" icon="🛑" >}}
**WARNING!**

Before installing Living Skyrim, you should make sure Skyrim: Special Edition is up to date in Steam. If you have run a downgrade patcher or not updated yet, verifying the game files using Steam will fix any issues you may encounter during installation.
{{< /alert >}}

Before proceeding with installation, it’s important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files, Program Files (x86), Desktop, Documents or Download folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. Instructions on how to move your Steam library can be found elsewhere on the internet.

Next, you’ll need a clean copy of Skyrim Special Edition. To get your copy to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall).
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Manage > Browse Local Files), delete them.
3. Install Skyrim: Special Edition.

{{< alert context="success" icon="📝" >}}
**Protip!** 

If you want to be absolutely certain you have uninstalled Skyrim completely, download and use Skyrim Shredder.
{{< /alert >}}

Afterwards, you need to disable automatic updates for Skyrim to avoid a game update breaking your copy of the game and therefore the modlist.

1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties… > General > Enable the Steam Overlay while in-game checkbox)

Once the above steps are completed, launch Skyrim SE through Steam to create any INI or registry entries the game needs. Immediately exit the launcher once it has successfully selected a graphics preset for your hardware. The INIs it just created will be overwritten by the ones included in the modlist, but this is a necessary step for Wabbajack to recognize that you have the game installed.

Last, but certainly not least, make sure you have deleted or disabled any and all Creation Club content that may have downloaded with the game.

### Wabbajack Preparations
We’ll now setup the folders needed for the installation to proceed smoothly.

1. Create two empty folders: one named Wabbajack and the other named Living Skyrim.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, your Program Files (x86) folder, your Documents folder, your Downloads folder, or the Desktop.
3. Additionally, ensure that these two folders are not contained within each other.
4. Ensure that both the Wabbajack and Living Skyrim folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: Wabbajack.
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

**Failure to set up these folders properly will result in the install failing. For example, `[install drive]\Wabbajack\Living Skyrim` is incorrect.**
{{< /alert >}}

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

{{< alert context="warning" icon="⚠️" >}}
**Important!** 

Reading the Important Mods section of this document is not optional. You won't have any idea what's going on if you don't.
{{< /alert >}}

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

The first is Nordic UI 32x9 or 21x9. This should only be enabled if you are using a 21:9 or 32:9 monitor at 2560x1080 resolution or higher. Enable whichever one matches your screen's aspect ratio and only that one.

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

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

**You should only ever have one ENB preset enabled. Having multiple enabled is a recipe for a Bad Time™.**
{{< /alert >}}

Note that ENB can put a very heavy strain on weaker computers. If you would like to turn off ENB, simply disable all of the presets shown in ENB Organizer.

Support is not provided for adding additional ENB options to the modlist. If you want to add more options, you need to know how to use ENB Organizer and be familiar with the Stock Game feature that Living Skyrim uses.

## Updating Living Skyrim
If you are updating Living Skyrim, the process is very similar to installing the list. Before you update, you should at a minimum backup your save files. Additionally, make sure you are using the latest version of Wabbajack (it should automatically update itself when you launch the program).

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

**Whilst some incremental list updates are save-safe, larger updates often require a brand new save file to avoid corruption. Check the newest update announcement found in the `#ls-announcements` channel on the Living Skyrim Discord server before updating.**
{{< /alert >}}

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

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

**Loading a save from another modlist or from before you installed Living Skyrim will corrupt that save, do not do this.**
{{< /alert >}}

## The MCM Settings
Some MCM settings have been pre-set for you. See this document to set the remaining MCMs that are required for LS3 to function correctly: [Click Here](/livingskyrim/mcm)

## Common Issues

If you encounter any issues, click here to visit the [LS Troubleshooting](/livingskyrim/lsissiues) page.

### Bug Reporting

If your issue persists after consulting the Troubleshooting page, proceed here. While we have tried out best to eliminate as many bugs and inconsistencies as possible, it is unfortunately a near certainty that at some point you will come across something that could be considered a bug. Whether it's duplicate objects overlapping, an imbalanced crafting recipe, or something else entirely, it's important that you report bugs you find so that it can be fixed for everyone.

To report a bug, follow these steps:

1.  Go to this Google Form: [Click Me!](https://forms.gle/uZ2EybTjAfGVieJd7)
2.  Fill out the form and submit the form.
3.  That's it, you're done!

{{< alert context="warning" icon="⚠️" >}}
**Important!** 

If we need additional information about the bug, we will contact you via Discord.
{{< /alert >}}

## Performance Optimizations

Click here to visit the [Performance Optimizations](/livingskyrim/performanceguide) guide for Living Skyrim.
