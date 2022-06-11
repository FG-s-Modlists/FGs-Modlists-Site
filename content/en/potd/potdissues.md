---
title: "Troubleshooting POTD"
description: "The troubleshooting page for POTD."
lead: ""
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  potd:
    parent: "potd"
weight: 90
toc: true
---

## Wabbajack Issues

### “A mod failed to download.”

First, you can try restarting the install once, you may also try enabling the Network Workaround option in the settings for Wabbajack to see if it will download the file after enabling that setting.

Next, check the list of commonly failing files further down on this page, some files hosted on certain file hosting sites are prone to failing at times.

Otherwise, wait for an update to the list. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Path of the Dovahkiin is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

### "MEGA hosted files are failing to download."

If MEGA downloads are either not downloading correctly or are frozen on the completed download page download the manually from the following links and place them in your POTD download folder:

- [Smooth Random Blocking Animation](https://mega.nz/file/4LxGTALK#7I8XPLnIW0PxR_r_nXMP-9ZUnZ16MlFVMdFdgGy-gF0)
- [Smooth Random Magic Idle Animation](https://mega.nz/file/IS4EjJhC#inP4yfb3i-UO_sx790OpoFDk81x-WIRf9WcBeKxnmYo)


### “Wabbajack says I’m out of requests.”

Nexus Premium is limited to 2500 downloads in a given 24 hour timeframe. Usually this limit resets around 9PM Eastern Time. Wait for your limit to reset and you’ll be able to proceed. Usually this only occurs after attempting to download the list multiple times in a row or when attempting to download multiple lists in the same 24 hour window.

### “Can I pause the installation?”

Yes, just close Wabbajack. When you start the installation process again it will pick up from where it left off.

### “Can I delete the downloads folder after installing?”

Yes, but remember that if you need to reinstall the list you will have to download all of the mods again.

### "POTD xLODGen Output 1.0.0 fails to download."

You'll need to download this manually and put it in your download folder. A mirror link can be found here: [POTD xLODGen Output 1.0.0](https://drive.google.com/file/d/10T1yWPU7O3m85T0NPesktbrhT9oJbR6f/view?usp=sharing)

### "POTD DynDOLOD Output 1.0.0 fails to download."

You'll need to download this manually and put it in your download folder. A mirror link can be found here: [POTD DynDOLOD Output 1.3.0](https://drive.google.com/file/d/1x_auJYyP1_26zAcCodL0JEJ-qHR_BHF5/view?usp=sharing)

### "Smooth Magic Casting Animation and/or Smooth Combat Non Combat Animation fails to download."

You'll need to download these manually and put them in your download folder. Mirror links can be found here: [Smooth Magic Casting Animation 3.2](https://blog.kakaocdn.net/dn/cyDuii/btq74ntfh9i/FwXmgAkFKizXGmtyVpscZK/Smooth%20Magic%20Casting%20Animation%203.2.7z?attach=1&knm=tfile.7z) and here: [Smooth Combat Non Combat Animation](https://blog.kakaocdn.net/dn/9Tn0e/btq6pI8JGgq/RMxvJoTOF071qWFu9pc04k/Smooth%20Combat%20Animation.7z?attach=1&knm=tfile.7z)

### "ENB Series fails to download."

You'll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [ENB Series](http://enbdev.com/download_mod_tesskyrimse.htm)

### "Nemesis Unlimited Behaviour Engine fails to download."

You will need to download this manually and put it in your downloads folder. The mirror is located here: [Nemesis Unlimited Behaviour Engine](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=248867&game_id=1704)

### "Skyrim Game files are failing to download."

If your Skyrim game files (SkyrimSE.exe, Data_Skyrim.esm, Data_Skyrim - Textures0.bsa, etc.) are failing please verify your game install through Steam. Downgrade patchers are no longer required.

## Gameplay Issues

### “Can I access RaceMenu after character creation?”

Only if you are not changing your character’s gender or race. Changing gender/race will cause issues with powers and passive buffs your character has.

### "I can't use spells with a weapon equipped! I Can't power attack!"

Engarde changes the way these combat functions work. To use a spell in your characters right hand: hold the Modifier hotkey while you right click (default Shift) Please note that swapping mouse buttons for attacks can cause issues with this. You will need to configure things yourself if you do this. Power attacks have their own keybind (Default Mouse 3). These can be changed at any time in the Engarde MCM

### "I can't level up! My skills aren't increasing!"

Please read the information on leveling up in the previous pages of the readme, alternatively check the [Gold Is XP](https://www.nexusmods.com/skyrimspecialedition/mods/20084) mod page

### "How do I start the Main Quest?"

Speak to Jarl Balgruuf in Whiterun

### "It's too dark inside/at night."

You can adjust the ENB settings to brighten nights/interiors in the list (Please note if you have changed the ENB from the default you will need to search how to do this yourself.) Open the ENB configuration menu in game with `Shift+Enter` Navigate to the `ENBEffect.fx` menu on the right side of the configuration screen. You will see two options near the top of this section, The first is the `Nights` modifier, Set this to a lower number between 0.5 and 1 to make nights brighter outdoors. Set it to a number between 1 and 2 to make them darker. Repeat this for the `Interiors` setting using the same number scale. Press Save Configuration in the top left and then close the menu using `Shift+Enter` again. DO NOT CLICK APPLY CHANGES This will load the configuration from the .ini file and you will lose your changes.

### "Can I respec my character?"

Yes you can refund your perk points to redistribute them. After a certain character level 'Scrolls of Legends' may begin appearing on magical vendors that sell scrolls. You can use this to refund all spent perk points and redistribute them as you like. Be careful they may be expensive. If you're lucky, however, you may run afoul of one in the wild.

### “My screen is zoomed in or weirdly off-center.”

Check the SSE Display Tweaks INI file to make sure you have the resolution for your screen set correctly. You may also need to check BethINI or the Skyrim INI files to make sure they all match your screen’s resolution.

### "How can I adjust graphical/resolution settings?"

A program called BethINI is included with the Living Skyrim installation. You can find it in the `Living Skyrim\Tools\BethINI` folder. Run the program (**MAKE SURE Mod Organizer IS CLOSED**) and adjust your settings as necessary.

### “MO2 cannot find SKSE.”

You’ll need to manually set the path for SKSE using the Edit Executables menu in MO2. Set it to `[install folder]\Stock Game\skse64_loader.exe`

### “Can I use a controller?”

I strongly advise against it. With as many mods as there are in the list, you’ll need a full breadth of keyboard keys to activate and use every feature. If you absolutely must play with a controller, please, for the love of all that is holy, use Gamepad++.

### “My game freezes when saving.”

Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

### “Can I play this list on a 75/100/144hz screen?”

Yes. Display Tweaks SSE is included to allow higher refresh rates.

### “Can I use this list on an ultrawide monitor?”

Yes, Nordic UI patches for 21:9 and 32:9 aspect ratios are included by default. Just make sure to enable the correct version for your aspect ratio in the left pane of MO2 under the 'Configuration Specific' seperator.

