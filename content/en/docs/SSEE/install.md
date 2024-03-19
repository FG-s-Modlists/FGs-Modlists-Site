---
categories: ["SSEE"]
tags: ["docs", "ssee"] 
title: "Installation Instructions"
linkTitle: "Installation Instructions"
weight: 2
description: >
  How to install SSEE.
---

### Hard Requirements

The following are *absolutely required* to begin installation of SSEE. These must all be installed and up to date before you begin.

- [Skyrim Special Edition (Steam, v1.6.1170)](https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/)
- [Microsoft Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)
- [.Net Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime)
- 18GB of available space on a hard drive/SSD/NVMe. (1.11GB downloads/1.75GB mods/13GB Stock Game)


### Microsoft Visual C++
The Visual C++ Redistributable is a DLL (Dynamic Link Library) file required by programs or games built using Microsoft’s Visual Studio software development environment. As Skyrim Special Edition is a 64-bit program, elements of it - along with other aspects of the modlist - require the 64-bit version of Visual C++ in order to run.

Click the link to download the latest Visual C++ x64 Redistributable, then double-click the downloaded file and follow the instructions:
- [Microsoft Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)

### Microsoft .Net Runtime
This is another runtime library required by some programs. Not having these installed can result in issues running SSEE.

click the link to open a page on the Microsoft Website to download the .NET runtime files. You may need both the Desktop and Console versions, so please install both:
- [.Net Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime)

### Steam & SSE Setup
{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>

Before installing SSEE, you should make sure Skyrim: Special Edition is up to date in Steam. If you have run a downgrade patcher or not updated yet, verifying the game files using Steam will fix any issues you may encounter during installation.
{{< /alert >}}

Before proceeding with installation, it’s important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files, Program Files (x86), Desktop, Documents or Download folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. Instructions on how to move your Steam library can be found elsewhere on the internet.

Next, you’ll need a clean copy of Skyrim Special Edition. To get your copy to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall).
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Manage > Browse Local Files), delete them.
3. Install Skyrim: Special Edition.

Afterwards, you need to disable automatic updates for Skyrim to avoid a game update breaking your copy of the game and therefore the modlist. You will also need to ensure the game is running in English, as that is the only language the modlist supports.

1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties… > General > Enable the Steam Overlay while in-game checkbox)
3. In Steam, configure Skyrim's language to English. (Right-click > Properties… > Language > Select 'English' in the dropdown list)

Once the above steps are completed, launch Skyrim SE through Steam to create any INI or registry entries the game needs. Immediately exit the launcher once it has successfully selected a graphics preset for your hardware. The INIs it just created will be overwritten by the ones included in the modlist, but this is a necessary step for Wabbajack to recognize that you have the game installed.

### Wabbajack Preparations
We’ll now setup the folders needed for the installation to proceed smoothly.

1. Create two empty folders: one named Wabbajack and the other named SSEE.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, your Program Files (x86) folder, your Documents folder, your Downloads folder, or the Desktop.
3. Additionally, ensure that these two folders are not contained within each other.
4. Ensure that both the Wabbajack and SSEE folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: [Wabbajack.](https://www.wabbajack.org/)
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

{{< alert color="info" title="Wabbajack.exe">}}
<div class="alert-icon">ℹ️</div>

![](https://i.imgur.com/FQFVfVi.png)
{{< /alert >}}


{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>

Failure to set up these folders properly will result in the install failing. For example, `[install drive]\Wabbajack\SSEE` is incorrect.
{{< /alert >}}

### List Installation

It’s now time to begin the installation of the list. Follow these steps:

1. Run Wabbajack.exe.
2. At the bottom of the window, click Browse Modlists.
3. Put a check into the "Show Unofficial Lists" checkbox at the top of the window.
4. Locate the SSEE card and click the download button to download the installer file.
5. Once downloaded, click the play button.
6. Below the image you see of the SSEE logo, there are three text boxes. The second and third need to be filled out.
7. Click the three dots in the second (middle) box. Navigate to your SSEE folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you’ll need to use to launch the list.
8. The third (bottom) box will automatically populate using the folder you just selected. This third box tells you where all of the mods will be downloaded. If you have hard drive limitations, you may change this to another folder on another hard drive by clicking the three dots in this box and selecting a new folder.
9. Click the play/right arrow button to begin the installation.

| With Nexus Premium | Without Nexus Premium |
| :--- | :--- |
| 10. Wabbajack will ask you to login to Nexus and authorize your API key so it can download mods for you automatically. If this doesn’t happen, it isn’t a problem and means you’ve already set this up. | 10. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take an extraordinarily long time. Current reports indicate installing the list manually takes approximately 24 hours. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Installing with Nexus Premium isn’t required, but is strongly recommended if you value your time. If you must install the list manually, put on an audiobook or a TV show and make a day of it. |
| 11. Wabbajack will now download and install all of the mods. This will take a while (3-4 hours at most). | |

Once complete, Wabbajack will indicate it is done with a green box that says "Installation complete". You may exit Wabbajack after this appears.

{{< alert color="success" title="Installation Complete">}}
<div class="alert-icon">✅</div>

![](https://i.imgur.com/s3ELgZB.png)
{{< /alert >}}

If it does not complete successfully (a red box with "Installation failed"), visit the [SSEE Discord server](https://discord.gg/thg2eRxf7z) for assistance. 

{{< alert color="danger" title="Installation Failed" >}}
<div class="alert-icon">🛑</div>


![](https://i.imgur.com/nIUXD8h.png)
{{< /alert >}}


### Post-Install

Among other things, Wabbajack has installed a copy of Mod Organizer 2 for you. This copy of Mod Organizer 2 is specific to SSEE and will not affect any other modlists you have installed.

1. Inside your SSEE folder, locate and launch ModOrganizer.exe. If this is not inside the folder, your installation has failed and you need to consult the Common Issues section of this document.

{{< alert color="info" title="MO2 EXE">}}
<div class="alert-icon">ℹ️</div>

![](https://i.imgur.com/tN1FqLH.png)
{{< /alert >}}

2. Mod Organizer 2 will have a dark theme already selected for you. If it does not, something has gone wrong and you will need to start over at the Installing the List section of this document.
3. A dialogue may appear and ask if you want to associate Mod Organizer with .nxm links. Click Yes. If this dialogue does not appear, it is not an issue and means you’ve likely already done this.
4. Another dialogue may appear asking you to update the game's registry path. Click Yes on this popup if it appears. If it does not appear, it is not an issue and likely means you've already done this.

{{< alert color="info" title="Registry Pop-up">}}
<div class="alert-icon">ℹ️</div>

![](https://i.imgur.com/LNIgW8o.png)
{{< /alert >}}
