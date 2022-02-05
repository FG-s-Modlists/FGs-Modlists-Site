---
title: "Troubleshooting Masterstroke"
description: "The troubleshooting page for Masterstroke."
lead: ""
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  masterstroke:
    parent: "Masterstroke"
weight: 90
toc: true
---

## Wabbajack Issues

### “A mod failed to download.”

First, you can also try enabling the Network Workaround option in the settings for Wabbajack to see if it will download the file after enabling that setting.

Otherwise, wait for an update to the list. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Masterstroke is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

### "MEGA hosted files are failing to download."

If MEGA downloads are either not downloading correctly or are frozen on the completed download page download the manually from the following links and place them in your Masterstroke download folder:

- [Smooth Random Blocking Animation](https://mega.nz/file/4LxGTALK#7I8XPLnIW0PxR_r_nXMP-9ZUnZ16MlFVMdFdgGy-gF0)
- [Smooth Random Magic Idle Animation](https://mega.nz/file/IS4EjJhC#inP4yfb3i-UO_sx790OpoFDk81x-WIRf9WcBeKxnmYo)
- [xLODGEN.84](https://mega.nz/file/dEwQnJRS#E-qpq29rVCBw3FxT3gTOjF_Z2zYkzR2CcWhQ5OAZcwg)

### “Wabbajack says I’m out of requests.”

Nexus Premium is limited to 2500 downloads in a given 24 hour timeframe. Usually this limit resets around 9PM Eastern Time. Wait for your limit to reset and you’ll be able to proceed. Usually this only occurs after attempting to download the list multiple times in a row or when attempting to download multiple lists in the same 24 hour window.

### “Can I pause the installation?”

Yes, just close Wabbajack. When you start the installation process again it will pick up from where it left off.

### “Can I delete the downloads folder after installing?”

Yes, but remember that if you need to update the list you will have to download all of the mods that have updated again.

### "ENB Series fails to download."

You'll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [ENB Series](http://enbdev.com/download_mod_tesskyrimse.htm)

### "Nemesis Unlimited Behaviour Engine fails to download."

You will need to download this manually and put it in your downloads folder. The mirror is located here: [Nemesis Unlimited Behaviour Engine](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=248867&game_id=1704)

### "Skyrim Game files are failing to download."

If your Skyrim game files (SkyrimSE.exe, Data_Skyrim.esm, Data_Skyrim - Textures0.bsa, etc.) are failing to download this is most commonly caused by the Anniversary update to Skyrim Special Edition, you will need the downgrade patcher located [HERE](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=248919&game_id=1704)

## Gameplay Issues

### “Can I access RaceMenu after character creation?”

Only if you are not changing your character’s gender or race. Changing gender/race will cause issues with powers and passive buffs your character has.

### “My screen is zoomed in or weirdly off-center.”

Check the SSE Display Tweaks INI file to make sure you have the resolution for your screen set correctly. You may also need to check BethINI or the Skyrim INI files to make sure they all match your screen’s resolution.

### “MO2 cannot find SKSE.”

You’ll need to manually set the path for SKSE using the Edit Executables menu in MO2. Set it to `[install folder]\Stock Game\skse64_loader.exe`

### “Can I use a controller?”

I strongly advise against it. With as many mods as there are in the list, you’ll need a full breadth of keyboard keys to activate and use every feature. If you absolutely must play with a controller, please, for the love of all that is holy, use Gamepad++.

### “My game freezes when saving.”

Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

### “Can I play this list on a 75/100/144hz screen?”

Yes. Display Tweaks SSE is included to allow higher refresh rates.

### “Can I use this list on an ultrawide monitor?”

Yes, Complete Widescreen Fix is included by default. Just make sure to enable it in the left pane of MO2.

