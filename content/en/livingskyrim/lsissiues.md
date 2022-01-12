---
title: "Troubleshooting Living Skyrim"
description: ""
lead: ""
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  livingskyrim:
    parent: "living skyrim"
weight: 90
toc: true
---

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

You’ll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [LS3 DynDOLOD 3.7.0](https://drive.google.com/file/d/1OPAfHz_ql7OYiOOhvomFt9O_rfzLJsrq/view?usp=sharing)

#### “The LS3 SSELODGen Output fails to download.”

You’ll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [LS3 SSELODGen 3.0.0](https://drive.google.com/file/d/1C8shpKCM4CO2fcoxasiw501rgBQiGmAQ/view?usp=sharing)

#### “The LS3 Grass Cache fails to download.”

You’ll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [LS3 Grass Cache 3.7.0](https://drive.google.com/file/d/1spCzbhwntaaciWuYd-cDWJNwXh5rThWX/view?usp=sharing)

#### "Inconsequential NPCs Visual Overhaul fails to download."

You'll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [INPCs Visual Overhaul](https://drive.google.com/file/d/1YM0lFTQdDh6P3JvEgWleOMb3adF_pQ_i/view?usp=sharing)

#### "ENB Series fails to download."

You'll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [ENB Series](http://enbdev.com/download_mod_tesskyrimse.htm)

#### "MEGA hosted files are failing to download."

Download the files manually and put them in your downloads folder. A list of all the MEGA hosted files for the list are here:
- [Smooth Random Blocking Animation](https://mega.nz/file/4LxGTALK#7I8XPLnIW0PxR_r_nXMP-9ZUnZ16MlFVMdFdgGy-gF0)
- [Smooth Random Magic Idle Animation](https://mega.nz/file/IS4EjJhC#inP4yfb3i-UO_sx790OpoFDk81x-WIRf9WcBeKxnmYo)
- [Smooth Random Sprint Animation](https://mega.nz/file/8T4ixLCB#YKQw5EDFdL1_e-5G_JB8WgmUkJ8N0kNtpzeOwUHZcZY)
- [xLODGen.85](https://mega.nz/file/kNRCHRDY#ONIMDnlxyyBH-QsSUgatbQJWOgGGrr8F8bxWD_-bSGc)

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