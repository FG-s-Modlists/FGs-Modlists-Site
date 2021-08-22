---
title: "Readme"
weight: 1
layout: "atelierbase"
---

{{< tip >}}
Atelier has been archived until further notice. It is no longer available to install through Wabbajack.
{{< /tip >}}

Current version: 1.0.1 2/8/2021

## Before You Get Started

{{< tip >}}
**Important!** 

Sections labeled important like this one will tell you when you need to pay extra attention to something.
{{< /tip >}}

{{< tip "warning" >}}
**WARNING!**

**Warning blocks like this one will warn you when you absolutely must not forget to do something. Failure to heed warning blocks is cause for disaster.**
{{< /tip >}} 

### Warnings/Disclaimers
Wabbajack no longer requires that you have Nexus Premium to install the modlist, however, having Nexus Premium will cut your install time to a fraction of what it would be instead of downloading each mod individually (and save you a couple thousand clicks or so).

The modlist requires ~174GB (46.7GB Downloads/128GB Mods) of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing onto an SSD/NVMe is not required, but strongly recommended. Download and installation times vary based on your computer and internet speeds but expect the entire process to take a few of hours.

{{< tip "warning" >}}
**WARNING!**

**This modlist contains explicit sexual content and nude character models. Proceed at your own discretion.**
{{< /tip >}} 

### System Specifications
Atelier is somewhat graphically intensive, but with how lightweight the rest of the list is, it performs very well. As a result, the following hardware can run the list at a consistent 60+ FPS with ENB. Use it to gauge how your system might run the list.

- CPU: AMD Ryzen 9 3900X @ 4.2GHz
- RAM: G.Skill TridentZ Neo 32GB DDR4 3600MHz CL16
- GPU: nVidia RTX 2080 Super 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz
- Storage: Sabrent Rocket 2TB M.2 NVMe 2280; Samsung EVO 860 250GB; SeaGate Barracuda 2TB 7200RPM

Skyrim is very heavy on processors. Generally, anything above 3GHz should be fine but I can’t guarantee it. 6GB or 8GB of VRAM should be plenty, with 4GB of VRAM probably capable of 60FPS without ENB.

### Important Links
Atelier FAQ & Troubleshooting
Atelier Bug & Suggestions Tracker
Atelier Discord
Atelier Patreon 
Atelier Changelog

One Two Three Four Five Six Seven Eight Nine Ten Eleven Twelve

## Pre-Installation
### Skyrim Setup
As with any modlist, it is strongly recommended that you start with a clean, unmodified installation of Skyrim: Special Edition. To get your Skyrim SE to this state, follow these steps:

In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall).

If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Properties… > Local Files > Browse Local Files…), delete them.

Install Skyrim: Special Edition.

Protip: If you want to be absolutely certain you have uninstalled Skyrim completely, download and use Skyrim Shredder.

Also make sure you have deleted or disabled any and all Creation Club content that may have downloaded with the game.

### Steam Setup
In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)

In Steam, disable the Steam Overlay. (Right-click > Properties… > General > Enable the Steam Overlay while in-game checkbox)

### Launching Skyrim
Launch Skyrim SE to create any INI or registry entries the game needs. Immediately exit after the launcher has successfully selected a graphics preset for your hardware. The INIs will be overwritten by the ones included in the Wabbajack installer.

### Wabbajack Preparations
Download the latest version of Wabbajack. Do not run anything until instructed to do so. Make sure you are using the latest version of Wabbajack or else Wabbajack will report a corrupted modlist.

Create a new folder in the root of the drive where you want Wabbajack to be installed. Name this folder Wabbajack.

Create a second folder called [Install Drive]\Atelier. This folder is where the modlist will be installed.

Double check that you have not placed any of these folders in your Skyrim: Special Edition installation directory.

Ensure that [Install Drive]\Atelier is completely empty.

Ensure that Wabbajack.exe is in [Install Drive]\Wabbajack.

WARNING

Failure to set up these folders properly will result in the install failing. For example, [install drive]\Wabbajack\Atelier is incorrect.

## Wabbajack Installation
If you are updating your existing installation of Atelier, skip to Updating Atelier.

Run Wabbajack.exe.

At the bottom of the window click Browse Modlists and click the download/down arrow icon on the Atelier card.

Once it finishes downloading, click the play/right arrow icon on the Atelier card.

Set the Installation Location to [install drive]\Atelier. The download location does not need to be set manually unless you have drive space limitations. Downloading to a separate folder is fine (for example, on a HDD), but as before it is recommended that the actual install be placed on a SSD. Important!: Do not install the modlist to your Skyrim SE installation folder OR the folder that Wabbajack.exe is in.

Click the play/right arrow button to begin installation.

### With Nexus Premium
Wabbajack will walk you through logging into the Nexus and authorizing an API key so it can download mods if you have not done so previously.

Let Wabbajack do its thing. This will take a little while (usually 3-4 hours at most), so go get a snack and read the Important Mods You Need to Know About section of this document.

### Without Nexus Premium
Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take a really long time, possibly more than one day. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Put on some music or a TV show and make a day of it. If you need a break during this process, grab a snack and read the Important Mods You Need to Know About section of this document.

Once complete, Wabbajack will say “Installation complete! You may exit the program.” If it does not, visit the FG’s Modlists Discord server for assistance. Don’t forget to upload your log file!

If Wabbajack fails to download a particular mod, it means that the mod has likely been updated. This also means that an update to Atelier is imminent. Be patient and wait for the new release. Do not ask other people to share older files as this is a violation of the Nexus ToS.

## Post-Wabbajack Install
### Game Folder Files
Now you have to copy some files to their correct locations. Navigate to [Install Drive]\Atelier\Game Folder Files. Copy all of the files inside the Game Folder Files folder into [Steam Install Location]\steamapps\common\Skyrim Special Edition\ and Overwrite if prompted. This folder contains SKSE and Engine Fixes part 2, which are required to use Atelier and must be placed into your Skyrim’s installation folder for the list to function.

WARNING

These files include SKSE and Engine Fixes Part 2, both of which are essential for the list to function correctly. Failure to copy these files will result in the list not working. 

### Mod Organizer 2
Navigate to [Install Drive]\Atelier and open ModOrganizer.exe. Your Mod Organizer window will have a dark theme already selected. If it doesn’t, something has gone wrong and you’ll likely need to do the Wabbajack installation again.

A dialogue will appear and ask if you want to associate Mod Organizer with nxm links. Click Yes.

### ENB
ENB is not required to run Atelier, but it is intended to be used with it. You may skip these instructions if you don’t want to use ENB.

In general, any ENB that is compatible with Obsidian Weathers will work with Atelier. My preferred ENBs are Rudy’s, Amon Reborn, Silent Horizons, and Re-Engaged if you want some recommendations.

If you wish to use ENB, follow these steps:

Download the latest ENB Binary from http://enbdev.com/download_mod_tesskyrimse.htm

Open the .zip file, go into the WrapperVersion folder, and copy ONLY d3d11.dll and d3dcompiler_46e.dll into your Skyrim SE installation folder. (Usually located at[install drive]\Steam\steamapps\common\Skyrim Special Edition)

Important!

Make sure your chosen ENB preset is compatible with Obsidian Weathers! 

Download your selected ENB preset.

Follow any installation instructions included with your Preset. Every ENB has slight variations in their requirements, so make sure to follow the instructions included for that preset.

Important!

You should not need to download any additional files other than the preset. Things like ENB Helper and Particle Patch are already included!

Ensure that ForceVsync is set to false in enblocal.ini

## Updating Atelier
If you are updating Atelier, the process is very simple. Before you update, you should at a minimum backup your saves. Updating may delete any saves that are present. Make sure you are using the latest version of Wabbajack or else Wabbajack will report a corrupted modlist.

Run Wabbajack.exe.

At the bottom of the window click Browse Modlists and click the download/down arrow icon on the Atelier card.

Once it finishes downloading, click the play/right arrow icon on the Atelier card.

Set the Installation Location to wherever you already have Atelier installed.

Important!: Set your downloads folder path to the same downloads folder location you used when you first installed Atelier. Failure to do this will make Wabbajack download every mod again, which you want to avoid if possible.

Click Run.

When prompted if you would like to overwrite the existing installation, click “Confirm.”

## BodySlides
When you first load up Atelier, there will be zero BodySlides created. You have to generate your own Bodyslides, as including them would make the Wabbajack installer file several gigabytes large.

Before you get started, if you have your own personal BodySlide preset that you like, drop the XML file into [Install Drive]\Atelier\mods\Custom Presets\Caliente Tools\BodySlide\SliderPresets alongside “Summer.xml”.

One more thing: if you get an error about BodySlide not being able to find the output path, click on the Settings button in BodySlide, click on the “Advanced” button, and set the Output Path to [Install Drive]\Atelier\mods\BodyslideOutfitStudio - Overwrite.

Launch BodySlide from MO2.

Click on the magnifying glass icon near the top of the BodySlide Window and select “Choose Groups…”

Put a checkmark into ONLY “Atelier Outfits 1”.

From the Preset dropdown, select your preferred preset. You can use the Preview button to preview what it will look like.

Make sure that the “Build Morphs” checkbox is checked at the bottom of the BodySlide window.

Click “Batch Build…” and then Build on the window that appears.

Repeat steps 3 through 6 for “Atelier Outfits 2” and “Atelier Bodies”. For Atelier Bodies you may want to select a different Bodyslide preset if you want armor/clothing to look different than the nude bodies. (Dream Angel Outfit for the armors and Dream Angel Nude for the body, for example.)

### A Note About Presets
If you have your own favorite character face/head preset, drop the JSLOT file into [Install Drive]\Atelier\mods\Custom Presets\SKSE\Plugins\CharGen\Presets alongside Anna.jslot and Summer.jslot. It will be available in RaceMenu the next time you go to make a character. Make sure to back this up before updating the list as updating will erase any added files like this. Adding presets (whether they be BodySlide or RaceMenu) does not void support for Atelier.

If you have a preset (Bodyslide or RaceMenu, doesn’t matter) that you made and you’d like it to be included in Atelier, send it to ForgottenGlory.

## Launching Atelier
The hard part is now over. Carry on, the end is in sight!

In Mod Organizer 2, select SKSE from the drop-down menu next to the Run button and click Run. This is how Atelier should always be launched. You can create a shortcut on your desktop if you wish using the Shortcut button under the Run button.

Once Skyrim starts, create a new game.

Create your character (make sure your character is female or else the list won’t work right) and name them whatever you’d like.

As soon as you gain control of your character, do nothing. The mods are loading and this can take several minutes. You’ll see a list of mods initializing in the top left of the screen.

Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.\

WARNING

Loading a save from another modlist or from before you installed Atelier will corrupt that save, do not do this. 

## The MCM Settings
Consult the Atelier MCM Configuration document and follow all listed steps. This step is required if you want the list to work properly.

Don’t forget to save your game after configuring the MCMs, I promise you don’t want to have to do this step more than once.

## The Screenshots
Screenshots are, by default, saved to your Skyrim SE installation folder. If you are sharing your screenshots, make sure to upload the PNG version of the file and not the BMP version (the BMP version is created automatically by ENB). Many places (such as Discord) don’t play nice with BMP files and prefer PNGs.

If you want some tips on how to take better screenshots, consult this link: Click Here If you’re feeling particularly fancy, you can even open up your screenshots in Photoshop or GIMP and make adjustments to get the exact feeling/color/style you’re going for.

## Adding to Atelier
The only support provided for adding mods to Atelier is for adding additional Skyrim SE outfits using the CBBE or 3BBB bodies. Adding any other mods is not supported in any way, shape or form.

WARNING

Before you add anything to Atelier, you should be familiar with the following things: Installing mods using Mod Organizer; running BodySlide; using xEdit. If you don't have all three of these skills, you need to learn how to do them. No support will be provided for learning these skills. 

To add an outfit to Atelier, follow these steps:

Find an outfit you like.

Check to make sure it is for Skyrim SE and uses the CBBE body and has BodySlide support.

Optionally, see if there is a 3BBB version of the outfit available.

Install and enable the outfit mod using the copy of Mod Organizer included with Atelier.

In general, most outfits do not need to be patched with this list in xEdit, however, you should always check for conflicts using xEdit. If you do not know how to do this, you’re out of luck if it doesn’t work.

Follow the BodySlides section of this readme to generate the meshes needed for the outfit to appear properly in game with the exception of the outfit group you choose. Choose the group your outfit is in and only generate the meshes for that outfit.

## Important Mods You Need to Know About
This section details the most important mods included in Atelier and is intended to give you a basic understanding of what to expect when you start the game.

### The Screenshot Tools
For ease of taking screenshots, the following mods are included: FreeFlyCam, ScreenshotPad SE, Weather Control, Rail Light, and AddItemMenu. With these you should be able to set up any location to be exactly what you want for the screenshots you want to take. One minor note: Rail Light is only intended to be used by female characters, equipping one of its lights on a male character will have interesting results, to say the least.

### The Pose Mods
Several pose packs are included: Halo’s Poser, Shocky Pose Pack, GomaPeroPoses, and all three are included in Poser Hotkeys Plus, which allows you to quickly and easily cycle through poses. Check the MCM for Poser Hotkeys to see the keybinds for this mod.

### The Character Customization Mods
When creating your character, you’ll find there are a lot of options that are available to you. From hairs to tattoos to eyes and more, Atelier has included a comprehensive suite of mods that allow you to tweak your character’s appearance to exactly what you want. And, if you’re struggling to figure out where to begin with character creation, a number of presets made by the Atelier community have been included for you to pick from in addition to many from Nexus. In general, you’ll have more options for everything.

There is one particular mod you need to be aware of during character creation: High Poly Head. To have your character use High Poly Head, you’ll need to change the head part using the RaceMenu slider of the same name to option 3. Note that if you do use High Poly Head, you may need to do some manual sculpting using the RaceMenu sculpt feature to remove any clipping issues with eyebrows or beards.

### The Outfits
It would be an incredible task to document every outfit included with Atelier, but you’ll find a huge assortment ranging from lore-friendly all the way up to and including outfits from entirely different video games and lores. Browse through the selection - there’s a lot!

## Final Thoughts & Best Practices
Autosaves are disabled. This save option is known to cause issues with heavily scripted games. Quicksaves are automatically turned into Manual Saves by SSE Engine Fixes. It is recommended to save early and often. Every 15 minutes and before interacting with quest NPCs, quest objects, and entering new zones should be sufficient. Old saves can be deleted, but forgetting to save loses progress forever!

Wabbajack supports updating/upgrading over an existing installation, but it will automatically delete any files that aren’t used for the modlist installation. This means if you have changed the modlist in any way, Wabbajack will delete those changes and delete your saves. Keep backups of any changes you do make and your saves (as ill-advised as making changes may be).

NEVER save right after a loading screen. Wait 30 seconds before saving to let scripts finish executing. It’s always better to save before a loading screen than after one.

NEVER use autosaves. Autosaves are unpredictable at best, and save-corrupting at worst.

## Troubleshooting & FAQ
Additions will be made to this FAQ as needed.

#### I get stuck in certain animations!

This is usually caused by script lag. There’s really no way around it, it will happen sometimes. Normally, you can open the console using the tilde key (~) on your keyboard or pause the game (Esc) for a few seconds and it will catch up. If you’re still stuck after doing that, you may need to reload an earlier save. Unfortunately the combination of mods being used can have this happen on occasion. Short of rewriting the scripts used, there’s really no way to fix it. Save frequently just in case this does happen to you.

#### What do/don’t you support?

All unmodified Wabbajack installs of Atelier are supported. Pirated copies of Skyrim are illegal and not supported. Any modlist that changes Atelier by adding/removing non-outfit mods is not supported. Manually installed reproductions of Atelier are not supported. Any ENB compatible with the weather mods installed with Atelier are supported. With extremely few exceptions, mods from LE/Oldrim are not supported and will never be included in Atelier. Converting old saves to Atelier is not supported, only new saves created after Atelier is installed are supported. The same is true of saves from previous versions of Atelier.

#### The installer isn’t working, what can I do?

The short answer: wait for an update. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Atelier is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

#### How often does Atelier update?

There’s no set schedule for Atelier updates. If a mod updates and the list requires a revision, I’ll try to get to it as quickly as possible, but I make no promises. Sometimes troubleshooting updates and rebuilding the list can take days. Anytime there is an update, it will be clearly communicated on the Wabbajack and Atelier Discord servers. That being said, as long as nothing else changes, you should be safe to continue playing an existing installation unless there is an update to Skyrim itself. Remember: the point of all modlists is to play the game. If you’re spending more time updating your list than playing, you’re doing it wrong.

#### I found a bug! How do I report it?

Check the Atelier Issues. If it’s not already on there, submit a new issue. Be as specific as possible, including screenshots if possible. If it is related to a specific mod, include the name of the mod and the exact steps to reproduce the issue. The best thing you can send for things like incorrect numbers/values or dark face NPCS (if there are any) is a screenshot of the thing in question selected with the console including the ID of the object/character. Vague reports such as “my game randomly CTDs” will be ignored if they do not include more details.

#### Can I play this list on a 75/100/144hz screen?

Yes. Display Tweaks SSE is included which allows for this.

#### The modlist updated! Do I have to update and start a new save?

If your game is working, you’re not required to update. It’s always recommended though, as updates likely fix bugs, update mods, or add new mods or remove unsatisfactory ones. As for starting a new save, it depends on the version. In general, anything that is a 2.0.x update won’t break your save, and is usually just for when a mod updates and the list needs to be recompiled to make it work again. Anything that is an 2.x.0 update adds or removes mods, which likely will break your save (unless otherwise specified). Any full version number changes, x.0.0, are major overhauls/rebuilds of the list and are guaranteed to break your save.

#### Can I stream/Let’s Play this modlist?

Have fun getting banned from whatever platform you use.

#### My game freezes when saving.

Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

#### Can I request a mod be added to Atelier?

No.

## Credits & Thanks
- Atelier created by ForgottenGlory
- Atelier Dev Team:
  - Volk
  - Melisandre
  - JaceVenture
  - Magnus Hellfire
  - Bearnard
  - Volkaru
  - Day7
  - JaxomofRuatha
- Halgari & The Wabbajack Team
  - Thank you for creating Wabbajack, you’re amazing!
  - Halgari’s Patreon
- Special Thanks
  - The TUCO Modding Team - Their modlist is a great way to get a Vanilla+ experience with a tutorial that is extremely helpful for learning the basics of creating a modlist.
  - DarkLadyLexy - Her LotD list is an invaluable resource not only for an awesome modlist, but also for learning many fundamentals of modding and compiling a modlist.
  - EzioTheDeadPoet - For their SME(FT) modlist. The ability to start from scratch on a whim while building this list has been invaluable.
- Mod Authors
  - None of this would be possible without the people who make the quality content we’ve grown to know and love. Please endorse the authors’ works.

## One Last Thing
If you read through the entire readme, congratulations! You get a cookie. If you need any further help, feel free to reach out on the Wabbajack or Atelier Discord Servers. Do not direct message ForgottenGlory or any Wabbajack staff members for support. I (ForgottenGlory) speak for myself, but I do reserve the right to ignore any requests for support direct messaged to me and block you.