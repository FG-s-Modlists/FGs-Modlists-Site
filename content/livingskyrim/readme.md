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
- As of version 3.0.0.1, Living Skyrim requires 224GB of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing to an SSD/NVMe is not required, but also highly recommended. Download and installation times vary based on your computer and internet speeds, but expect the entire process to take a few hours. If you are installing the list without Nexus Premium, expect the process to take a couple of days of 8+ hour sessions downloading mods.
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
- The Modlist Spreadsheet
- LS3 Default Keymap
- Living Skyrim Bug Tracker
- User Testimonials
- Living Skyrim Discord
- Living Skyrim Patreon

### Screenshots
Living Skyrim Screenshot Gallery

### Videos
- LS3 Overview Video by TheMurlocKing
- LS3 Showcase by DroppedIceCream
- LS3 Beta Preview

## Pre-Installation

### Steam & SSE Setup
Before proceeding with installation, it’s important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files or Program Files (x86) folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. Instructions on how to move your Steam library can be found elsewhere on the internet.

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
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

## Installing the List
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

## Post-Wabbajack Install
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

### Mod Organizer 2
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

### Configuration Specific
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

### ENB
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

## Updating Living Skyrim
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

## Launching Living Skyrim
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

## The MCM Settings
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.

## Getting Started in Living Skyrim
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus congue dolor, nec laoreet eros hendrerit et. Pellentesque sed justo aliquet, volutpat diam ut, vehicula elit. Sed fermentum nunc sit amet leo elementum, at cursus turpis tincidunt. Fusce id nisi hendrerit, dictum augue sed, blandit turpis. Nulla pellentesque, arcu ut rutrum pellentesque, lectus massa molestie dui, vel pulvinar turpis neque sed quam. Fusce finibus placerat nisl eu tincidunt. In lorem mauris, aliquam vel magna sed, tincidunt lacinia mauris. Donec erat nulla, sagittis in gravida iaculis, ullamcorper consequat dui.