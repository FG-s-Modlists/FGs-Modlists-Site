---
categories: ["Path of the Dovahkiin"]
tags: ["docs"] 
title: "Pre-Installation"
linkTitle: "Pre-Installation"
weight: 2
description: >
  Steps to complete before beginning installation.
---

### Pagefile Configuration

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger pagefile.

A pagefile is a file on your disk Windows will use when there is not enough RAM available.

Never disable the pagefile - this may lead to various issues on your system, including Skyrim crashes.

To set the pagefile up properly for this modlist, follow these steps:

1. Press Windows + R on your keyboard and enter `sysdm.cpl ,3`
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. Set a custom size for your fastest drive and increase the initial and maximum size to be at least 20GB (20000MB).
6. Restart your computer to make sure the changes have taken effect.

If you have more than one drive, try enabling it for at least one more drive as a backup (make sure it has a decent bit of free space, like 15GB). Set the size to 'System managed size'.

### Microsoft Visual C++
The Visual C++ Redistributable is a DLL (Dynamic Link Library) file required by programs or games built using Microsoft’s Visual Studio software development environment. As Skyrim Special Edition is a 64-bit program, elements of it - along with other aspects of the modlist - require the 64-bit version of Visual C++ in order to run.

Click the link to download the latest Visual C++ x64 Redistributable, then double-click the downloaded file and follow the instructions:
- [Microsoft Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)

### Microsoft .Net Runtime
This is another runtime library required by some programs. Not having these installed can result in issues running Path of the Dovahkiin.

click the link to open a page on the Microsoft Website to download the .NET runtime files. You may need both the Desktop and Console versions, so please install both:
- [.Net Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime)

### Steam & SSE Setup
{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>

Before installing Path of the Dovahkiin, you should make sure Skyrim: Special Edition is up to date in Steam. If you have run a downgrade patcher or not updated yet, verifying the game files using Steam will fix any issues you may encounter during installation.
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

Last, but certainly not least, make sure you have installed the Skyrim Special Edition Creation Kit in Steam.

### Wabbajack Preparations
We’ll now setup the folders needed for the installation to proceed smoothly.

1. Create two empty folders: one named Wabbajack and the other named Path of the Dovahkiin.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, your Program Files (x86) folder, your Documents folder, your Downloads folder, or the Desktop.
3. Additionally, ensure that these two folders are not contained within each other.
4. Ensure that both the Wabbajack and Path of the Dovahkiin folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: Wabbajack.
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>

Failure to set up these folders properly will result in the install failing. For example, `[install drive]\Wabbajack\Path of the Dovahkiin` is incorrect.
{{< /alert >}}

<hr style="background-color: #dee2e6;"></hr>