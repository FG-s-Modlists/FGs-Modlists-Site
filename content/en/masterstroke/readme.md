---
title: "Installation Instructions"
description: "The Masterstroke installation instructions."
lead: ""
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  masterstroke:
    parent: "Masterstroke"
weight: 20
toc: true
---

## Pre-Installation

### Steam & SSE Setup
{{< alert context="danger" icon="🛑" >}}
**WARNING!**

Before installing Masterstroke, you should make sure Skyrim: Special Edition is up to date in Steam. If you have run a downgrade patcher or not updated yet, verifying the game files using Steam will fix any issues stemming from an out of date game you may encounter during installation.
{{< /alert >}}

Before proceeding with installation, it’s important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files, Program Files (x86), Desktop, or Documents folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. For more information about how this can be problematic and how Windows protects folders, consult this link: [Click Me!](https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/controlled-folders?view=o365-worldwide) Instructions on how to move your Steam library can be found elsewhere on the internet.

Next, you’ll need a clean copy of Skyrim Special Edition. To get your copy to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall).
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Manage > Browse Local Files), delete them.
3. Install Skyrim: Special Edition.

{{< alert context="success" icon="📝" >}}
**Protip:** 

If you want to be absolutely certain you have uninstalled Skyrim completely, download and use Skyrim Shredder.
{{< /alert >}}


Afterwards, you need to disable automatic updates for Skyrim to avoid a game update breaking your copy of the game and therefore the modlist.

1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties… > General > Enable the Steam Overlay while in-game checkbox)

Once the above steps are completed, launch Skyrim SE through Steam to create any INI or registry entries the game needs. Immediately exit the launcher once it has successfully selected a graphics preset for your hardware. The INIs it just created will be overwritten by the ones included in the modlist, but this is a necessary step for Wabbajack to recognize that you have the game installed.

Last, but certainly not least, make sure you have deleted or disabled any and all Creation Club content that may have downloaded with the game.

### Wabbajack Preparations
We’ll now setup the folders needed for the installation to proceed smoothly.

1. Create two empty folders: one named Wabbajack and the other named Masterstroke.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, your Program Files (x86) folder, your Documents folder, your Downloads folder, or the Desktop.
3. Additionally, ensure that these two folders are not contained within each other.
4. Ensure that both the Wabbajack and Masterstroke folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: [Wabbajack](https://www.wabbajack.org/#/).
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

**Failure to set up these folders properly will result in the install failing. For example, `[install drive]\Wabbajack\Masterstroke` is incorrect.**
{{< /alert >}}

## Installing the List
If you are updating your existing installation of Masterstroke, skip to the [Updating Masterstroke](#updating-masterstroke) section of this document.

It’s now time to begin the installation of the list. Follow these steps:

1. Download this file and place it somewhere you can easily find it: [Masterstroke Installer](https://drive.google.com/file/d/1uGqk-UMjNiMSPsQAJYHVkR-ClZOpgELo/view?usp=sharing)
2. Find the file you just downloaded and double click it to open it in Wabbajack.
3. Set the Installation Location to the Masterstroke folder you created earlier.
4. The Download Location should populate automatically, but if it does not, select the downloads folder you created while manually downloading the above files.
5. Put a checkmark into the box that says Overwrite Installation, or, if you are prompted to overwrite the installation, click Confirm.
6. Click the play/right arrow button to begin the installation.

| With Nexus Premium | Without Nexus Premium |
| :--- | :--- |
| 9. Wabbajack will ask you to login to Nexus and authorize your API key so it can download mods for you automatically. If this doesn’t happen, it isn’t a problem and means you’ve already set this up. | 9. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take an extraordinarily long time. Current reports indicate installing the list manually takes approximately 24 hours. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Installing with Nexus Premium isn’t required, but is strongly recommended if you value your time. If you must install the list manually, put on an audiobook or a TV show and make a day of it. |
| 10. Wabbajack will now download and install all of the mods. This will take a while (3-4 hours at most). Take this opportunity to read the Important Mods You Need To Know About section of this document. | |

{{< alert context="warning" icon="⚠️" >}}
**Important!** 

Reading the Important Mods section of this document is not optional. You won't have any idea what's going on if you don't.
{{< /alert >}}

Once complete, Wabbajack will indicate it is done with a green box that says "Installation complete". You may exit Wabbajack after this appears.

If it does not complete successfully (a red box with "Installation failed"), consult the Common Issues section of this document, or visit the [Masterstroke Discord server](https://discord.gg/NdmGpGzqg8) for assistance. 

## Post-Wabbajack Install

### Mod Organizer 2
Among other things, Wabbajack has installed a copy of Mod Organizer 2 for you. This copy of Mod Organizer 2 is specific to Masterstroke and will not affect any other modlists you have installed.

1. Inside your Masterstroke folder, locate and launch ModOrganizer.exe. If this is not inside the folder, your installation has failed and you need to consult the Common Issues section of this document.
2. Mod Organizer 2 will have a dark theme already selected for you. If it does not, something has gone wrong and you will need to start over at the Installing the List section of this document.
3. A dialogue may appear and ask if you want to associate Mod Organizer with .nxm links. Click Yes. If this dialogue does not appear, it is not an issue and means you’ve likely already done this.
4. Another dialogue may appear asking you to update the game's registry path. Click Yes on this popup if it appears. If it does not appear, it is not an issue and likely means you've already done this.

### Configuration Specific

If you're using an ultrawide monitor, you can enable either of the Nordic UI Ultrawide options under the "Configuration Specific" section of the left pane of MO2. Just make sure you only enable the one that matches your monitor's resolution ratio.

### ENB

The default ENB included with Masterstroke is [Culminated ENB](https://www.nexusmods.com/skyrimspecialedition/mods/53167). Support is not provided for changing it. You may, however, disable ENB during play by loading into the game and pressing `Shift + F12`. Disabling ENB will drastically improve performance but will make the game look worse overall.

## Updating Masterstroke
If you are updating Masterstroke, the process is very similar to installing the list. Before you update, you should at a minimum backup your save files. Updating may delete any saves that are present. Additionally, make sure you are using the latest version of Wabbajack (it should automatically update itself when you launch the program).

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

**Whilst some incremental list updates are save-safe, larger updates often require a brand new save file to avoid corruption. Check the newest update announcement found in the `#Masterstroke-announcements` channel on the Discord server before updating.**
{{< /alert >}}

1. Download this file and place it somewhere you can easily find it: [Masterstroke Installer](https://drive.google.com/file/d/1uGqk-UMjNiMSPsQAJYHVkR-ClZOpgELo/view?usp=sharing)
2. Find the file you just downloaded and double click it to open it in Wabbajack.
3. Set the Installation Location to the Masterstroke folder you created earlier.
4. The Download Location should populate automatically, but if it does not, select the downloads folder where all the files for Masterstroke are downloaded.
5. Put a checkmark into the box that says Overwrite Installation, or, if you are prompted to overwrite the installation, click Confirm.
6. Click the play/right arrow button to begin the installation.

## Launching Masterstroke
To actually launch and then play Masterstroke, follow these steps:

1. Launch the copy of Mod Organizer 2 found inside your Masterstroke folder.
2. In the top-right corner of Mod Organizer, you’ll see a large dropdown menu. Select Masterstroke [SKSE] from this dropdown menu.
3. Click the large Run button.
4. This is how Masterstroke should always be launched. You can create a shortcut to this selection on your desktop, if you wish, using the Shortcut button directly below the large Run button.
5. Once Skyrim starts, create a new game.
6. Create your character and name them whatever you’d like.
7. As soon as you gain control of your character, do nothing. The mods are initializing and this can take several minutes. You’ll see a list of mods appearing in the top left corner of your screen.
8. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

**Loading a save from another modlist or from before you installed Masterstroke will corrupt that save, do not do this.**
{{< /alert >}}

## The MCM Settings
The MCMs are configured via MCM Recorder. See this document for information about how to set up the MCMs and create your character: [Click Here](/masterstroke/mcm)

## Bug Reporting, Github, and You

While we have tried out best to eliminate as many bugs and inconsistencies as possible, it is unfortunately a near certainty that at some point you will come across something that could be considered a bug. Whether it's duplicate objects overlapping, an imbalanced crafting recipe, or something else entirely, it's important that you report bugs you find on the Masterstroke Github so that it can be fixed for everyone.

To report a bug, follow these steps:

1.  Login to [Github](https://github.com/) or create an account as necessary.
2.  Open this link: [Click Here!](https://github.com/ForgottenGlory/Masterstroke/issues/new/choose)
3.  Click the green button that says "Get Started" in the line next to "Bug Report".
4.  Input a title and fill out the form in the large text box. If you need to attach a screenshot, it can be dragged from your computer to the Github post to insert it.
5.  When you have filled out the form completely, click the green "Submit new issue" button.

After that, you've filed your bug report and the LS dev team will take a look at it as soon as possible.

{{< alert context="warning" icon="⚠️" >}}
**Important!** 

Don't forget to check back on your report periodically just in case we request more information from you.
{{< /alert >}}