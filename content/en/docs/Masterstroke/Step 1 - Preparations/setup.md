---
categories: ["Masterstroke"]
tags: ["docs"] 
title: "1.2 - Steam, SSE, and Wabbajack Setup"
linkTitle: "1.2 - Steam, SSE, and Wabbajack Setup"
weight: 3
description: >
  Steps to complete before beginning installation.
---

### Steam & SSE Setup
{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>

Before installing Masterstroke, you should make sure Skyrim: Special Edition is up to date in Steam. If you have run a downgrade patcher or not updated yet, verifying the game files using Steam will fix any issues you may encounter during installation.
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

1. Create two empty folders: one named Wabbajack and the other named Masterstroke.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, your Program Files (x86) folder, your Documents folder, your Downloads folder, or the Desktop.
3. Additionally, ensure that these two folders are not contained within each other.
4. Ensure that both the Wabbajack and Masterstroke folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: Wabbajack.
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

{{< alert color="danger" title="Warning!" >}}
<div class="alert-icon">🛑</div>

Failure to set up these folders properly will result in the install failing. For example, `[install drive]\Wabbajack\Masterstroke` is incorrect.
{{< /alert >}}