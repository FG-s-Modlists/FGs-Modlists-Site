---
categories: ["Masterstroke"]
tags: ["masterstroke", "changelog"] 
title: "Changelog"
linkTitle: "Changelog"
weight: 100
description: >
  The Masterstroke changelog.
---
### 8/26/2023 1.9.2
#### Incremental
- Mod Updates
    - Immersive Equipment Displays -> 1.7.2
- Additions
    - Dirt Blood & Cum
    - Open Animation Replacer - IED Conditions
    - Weapon Styles - DrawSheathe Animations for IED
- Other
    - Fixed Fine Iron Sword not being able to be placed in Weapon Plaques
    - Fixed missing { in SLEN's recording
    - Deleted unused files in the SKSE output
    - Adjusted Dirt & Blood's & Service Your Gear's MCM Recordings
        - Gear should last longer
        - Neither mod should cause Devious Devices to break due to stripping
    - Adjusted Public Whore's recording to spam the console less
        - It'll now send one message instead of three every five seconds
    - Adjusted Improved Camera's .ini settings
        - Default first-person FOV 80 -> 100
        - Disabled first-person on kill moves
        - Adjusted first-person Near Distance to remove flicker when drawing weapons/hands.
    - Regenerated FNIS and Nemesis output

### 8/22/2023 1.9.1
#### Incremental
 - Mod Updates
    - Open Animation Replacer (for real this time)
    - Fill Her Up
    - SexLab Separate Orgasms
    - Public Whore
    - Service Your Gear (fixes a debug message being spammed and certain weapon combos not breaking)
    - Egg Factory
    - Submissive Lola
- Bug Fixes
    - Adjusted Scrappies MCM to fix females not being valid for scenes
    - Fixed SexLab's recording during installation
    - Fixed SLEN's recording, specifically the SOS integration. TRX's addons weren't enabled
- Other
    - Utilized rainpants' icon for MS as SKSE icon
    - Truncated MCM Recording by merging files
    - Correctly numbered MCM files
    - Added a keybind to iHUD's recording because it works in my list and testing showed it works
    - Changed .meta files to have `?do=download` at the end for better view during LL download selection

### 7/17/2023 1.9.0
#### "Minor"
- Mod Updates
  - XP32 Maximum Skeleton for Dummies
  - Open Animation Replacer
  - Sexlab Aroused Creatures to 4.12
  - Submissive Lola to 2.1.0
  - Serana Dialogue Add-On to 4.0.2.3
  - Fill Her Up Baka Edition to 1.93
  - Horny Creatures to 2.1
  - Simply Knock DLL to 5.4
  - Survival Control Panel to 1.1.2
  - PapyrusUtil to 4.4
  - EstrusForSkyrim to AE2.2.3-ver1.6.640
  - Open Animation Replacer to 1.0.2
  - MFG Fix to 1.6.1
  - SkyUI AIO Survival to 7.4
  - The Handy Icon Collection to 1.3
  - Security Overhaul SKSE to 3.2
  - Security Overhaul Addons to 1.6
  - Splashes of Skyrim to 1.4
  - Racemenu to 0.4.19.14
  - More Informative Console to 1.1
  - Atlas Map Markers to 2.7
  - SmoothCam to 1.7
  - Classic Enhanced preset to 2.0
  - MoreHUD to Light Master 5.2.2
  - MoreHUD Inventory Edition to 2.1.2
  - HD Local Map to 1.0.2
  - Simple Dual Sheath to 1.5.6
  - True Directional Movement to 2.2.3
  - Archery Locational Damage to 2.1.5
  - Experience to 3.1
  - Nordic UI Miscellaneous Patches to 1.8.2
  - Adamant to 5.8
  - Hand to Hand to 1.5.3
  - Reading is Good to 1.1.2
  - TK Dodge RE to version 0.5Plus
  - Read or Take SKSE to 1.3
  - Use or Take SKSE to 1.2
  - SexLab Framework to 1.65
  - The Choice is Yours to 2.7
  - Twisted's Command Binders to 1.2
  - Essential Favorites to 2.3.0
  - I'm Walking Here to 1.7
  - Whose Quest is it Anyway to 1.5
  - Yes I'm Sure to 1.7
  - Hide Quest Items in Container Menu to 0.8
  - SKSE to 2.2.3
  - JContainers to 4.2.3
  - FileAccess Interface (FISSES) to 1.4.1
  - Papyrus Extended to 5.5
  - ConsoleUtilSSE to 1.4.0
  - Fuz Ro D-oh to 2.3
  - ENB Input Disabler to 1.0.3
  - Address Library to version 8
  - ScaleformTranslationPP to 1.6.0
  - Spell Perk Item Distributor to 6.6.1
  - Better Third Person Selection to 0.5.8
  - Desktop Splash Screen to 1.0.1
  - MergeMapper to 1.5
  - FormList Manipulator to 1.7
  - ENB Helper to 2.2.0
  - Custom Skills Framework to 2.0.2
  - Scrambled Bugs to version 21
  - Keyboard Shortcuts Fix to 1.0.0.3
  - Equip Enchantment Fix to 1.3.6
  - Animation Limit Crash Fix to 0.4.1
  - Assorted Mesh Fixes to 0.79
  - Actor Limit Fix to 9
  - Bug Fixes to version 10
  - Dwemer Gates Don't Reset to 1.3.7
  - Raven Rock- Fix Exit on Horseback to 1.1
  - Better Jumping SE to 1.8.6
  - SSE Display Tweaks to 0.5.12
  - USSEP to 4.2.9a
  - xedit to 4.0.4
  - BethINI to 3.6.1
  - Engine Fixes to 6.1.1
- Removed
  - Better dialog controls
  - Fix Note Icon
  - Inventory Interface Information Injector for Skyrim 1.5
  - Racemenu 0.4.16 Memory Leak Hotfix.
  - No Grass in Objects
  - XP32 Maximum Skeleton Special Extended - Fixed Scripts
  - Ambriel
- Replacements 
  - Animated Static Reload Fix -> NG version
  - Console Commands Extender -> Console Commands Extender - Anniversary Update
  - Copy and Paste in console -> ConsolePlusPlus
  - Hide Your Quests -> Hide those futile quests
  - Flat Map Markers -> Flat Map Markers AE - Updated
  - To Your Face Redux -> To Your Face SE - AE - VR
  - Mum's the Word -> Mum's the Word NG
  - Stay at the System page -> the NG version
  - Player Rotation in ShowRaceMenu -> Another Race Menu Rotation Mod
  - Notification Log -> NG version
  - DLL for CBPC rather than mess -> reinstalling this.
  - Wash that Blood Off -> Dirt and Blood
  - Better Stealing ->  Mum's the Word NG
  - Removed .NET Script Framework -> Crash Logger SSE AE VR - PDB Support
  - Quick Mass Follower Commands -> Swiftly Order Squad
  - Difficulty Balance -> Scrambled Bugs
  - Enemy Magelock -> Casting Aiming Reloading Impede Movement
  - Disable Fast Travel -> Journeyman - A Fast Travel Overhaul
- AE Swaps
  - Dual Casting Fix for AE version
  - Simple Offence Suppression for AE version
  - Favorite Misc Items for AE version
  - Equipment Toggle for AE version
  - Devious Devices for AE version
  - CBPC Anus Support for AE version
  - Keyword Item Distributor to install AE version
  - Enhanced Reanimation to install AE version
  - powerofthree's Tweaks to install AE version
  - Faster HDT-SMP to update for AE
- Additions
  - Honed Metal Community Patch.
  - Immersive Equipment Displays 1.63 AE version
  - Oxygen Meter 2 for AE version
  - AE SOS DLL
  - Better Combat Escape NG
  - MCM Helper 1.4 AE version
  - Crash Log Tools for Mod Organizer
  - AE version of Private Profile Redirector 0.5.3
  - Creation Club Anniversary Cleaned and Upscaled
  - Fishing Map Markers
  - CC Fishing Campfire Patch
  - CC Fishing - No Artifacts from Fishing
  - Skyrim Extended Cut - Saints and Seducers
  - SEC Saints and Seducers High Poly NPCs 
  - Remaining Free CC Content given High Poly Heads
  - Extended Cut - Saints and Seducers 4k - Cleaned and Upscaled Textures
  - Saints and Seducers - Mysticism Rebalance
  - Extended Cut - Saints and Seducers Paper Map for FWMF
  - CBBE 3BA Creation Club Outfits Bodyslides
  - Skimped - Saints and Seducers 
  - HIMBO Creation Club Refits for Bodyslide
  - CC Fishing Outfit HIMBO and CBBE 3BA 
  - Photo Mode
  - Improved Camera SE + Patches
- Other
  - Regenerated FNIS/Nemesis output
  - Regenerated all bodyslides
  - Synced mod order and plugin order between the profiles 

### 6/23/2023 1.8.1.2
#### Hotfix
- Mod Updates
  - Open Animation Replacer 1.2.0
  - FHU 1.93
  - Submissive Lola 2.1.0
  - Schlongs of Skyrim DLL
  - TAP Interiors 1.5.4

### 6/3/2023 1.8.1
#### Incremental
- Fixes
  - Patched SunHelm food changes
  - Fixed Sirenroot missing textures
  - Fixed not being able to nutshot male NPCs
  - Fixed many missing bodyslides
- Mod Updates
  - Simple Slavery Plus Plus 6.3.19
  - SLWidgets 2.0.8
  - HCOS 2.0A
  - Submissive Lola 2.0.64
  - Serana Dialogue Add-On 4.0.2.2
- Additions
  - Both Profiles
    - Sound Fix for Large Sector Drives
    - Mihail Soul Cairn Drainlife Crystal - Retexture
    - Dual Casting Fix
- Replacements
  - Dynamic Animation Replacer -> Open Animation Replacer
- Other
  - Cleaned up Stock Game folder a bit.
  - Simplified Ultrawide options
  - Oprah Meme: "You get a nerf! You get a nerf!" (nerfed a lot of things)

### 5/18/2023 1.8.0.1
#### Hotfix
- Fixes
  - Fixed Misa's bodyslides
  - Fixed CTDs in Whiterun and Dead Man's Drink
  - Fixed ENB Binaries not being updated
  - Fixed missing columns in inventory
  - Corrected Dint Face Part Mod load order
- Removals
  - The Heist

### 5/17/2023 1.8.0
#### "Minor"
- Fixes
  - Fixed Aura's Inventory Tweaks issues
  - Fixed Fair Skin being disabled by default on creature profile
  - Fixed incorrect Legion models not being replaced on Skimpy Bodyslides
  - Fixed Ambriel quest not starting
  - Fixed missing map markers
  - Fixed Adira missing bodyslides
  - Fixed green/dark dwemer ruin
- Mod Updates
  - Fill Her Up 1.9
  - Submissive Lola Resubmission 2.0.63
  - OSLAroused 2.3.0
  - Aura's Inventory Tweaks 3.0.3
  - PowerofThree's Tweaks 1.8.0
  - ENB Binaries v493
  - Water for ENB 1.76
  - FreeFlyCam 13.2.5
  - TNT 1.6b
  - Ominous ENB 3.0
  - PI-CHO 8.1
  - Rudy ENB 6.5a
  - Re-Engaged ENB 9.4a
  - iiENB 5.05
  - LewdMarks 2.02
  - Simple Slavery Plus Plus 6.3.18
  - SLWidgets 2.0.7
  - Address Library for SKSE v2
  - Bodyslide v5.6.0
  - Serana Dialogue Overhaul 4.0.2.0
- Additions
  - Both Profiles
    - Essentials
      - Object Categorization Framework
      - FormList Manipulator 
      - MergeMapper
      - Keyword Item Distributor
      - Inventory Interface Information Injector
      - Inventory Interface Information Injector SE 1.5
    - HUD/UI
      - The Handy Icon Collection Collective
      - B.O.O.B.I.E.S
    - Gameplay - Immersion
      - Harsher SunHelm Cold
    - Sexlab and Friends
      - SOS Female Schlongifier
      - LewdMarks Aroused
      - Devious Lore SE
    - New Questlines
      - Sirenroot
      - The Innocence Lost - Quest Expansion
      - Warden of the Coast
      - Defeat the Dragon Cult
      - Cult of the True Dragonborn
      - Cult of the World Eater
      - Maelstrom
      - Betalille's Hammerfell Quests Bundle
      - The Heist
    - Character Customization
      - Dint999's Face Part Mod
    - NPCs - Followers
      - Kitty Misa
      - Avenger of the Lost
    - Items
      - Viridian Knight
      - Daedric Chainmail
      - Kozakowy 1660 Gown
      - Kozakowy 1700 Gown
      - Kozakowy 1546 Gown
      - Kozakowy Falka Armor
      - Bonemold and Chitin Bikini Armor
      - Magpie's Immersion Books
      - Bifrost
      - Milkmaid Outfit
      - Cloud's Layered Gowns
- Removals
  - Equipped Items on Top
  - Windyridge
  - DynDOLOD Ice Piles Fix
  - Harder Lock Picking
- Replacements
  - Enhanced Night Sky -> Ethereal Cosmos
  - SkyRem IRIS -> Food Remover Plus
- Other
  - Regenerated DynDOLOD and friends
  - Regenerated FNIS/Nemesis Output
  - Regenerated Bodyslides (all of them)
  - Regenerated Synthesis Output

### 4/26/2023 1.7.2
#### Incremental
- Mod Updates
  - Trappings of Fate 1.2.0
  - TAP Interiors 1.5.2
  - The Ancient Profession 0.14

### 4/10/2023 1.7.1
#### Incremental
- Fixes
  - Fixed green overlay in some areas
  - Fixed missing Nordic UI patch (for 32x9 screens)
  - Fixed duplicate face presets
  - Fixed Animated Forge Water doing nothing
  - Fixed crash when hiding quests
  - Fixed not receiving XP when using staves
  - Fixed lighting issues on Steel Abs V
  - Fixed several BFBs
  - Fixed incorrect body skin for some NPCs
  - Possibly fixed Giant club physics
  - Fixed being unable to temper Champion of Azura sword
  - Fixed OBody not working on several NPCs
  - Fixed Speech perk tree.
- Mod Updates
  - Scrambled Bugs 17
  - Infinity UI 2.0.1
  - Compass Navigation Overhaul 2.1
  - Animated Forge Water 0.7
  - Adamant 5.7.6
  - Mysticism 2.2.3
  - Mundus 1.9.1
  - Papyrus Tweaks 4.1
  - At Your Own Pace
  - Show Player In Menus 2.0.3
  - Sets of Skills 2.0.3
  - Honed Metal Revoices 1.23
  - Favorite Misc Items 3.7.1
  - Submissive Lola Resubmission 2.0.61
  - Lair of Succubi 1.2
- Additions
  - Adamant + Leadership patch
  - Campfire + Pilgrim patch
- Removals
  - Leadership - Custom Skills Framework Extension
- Other
  - Enabled SexLab Even Actor Height by default on both profiles

### 3/15/2023 1.7.0.1
#### Hotfix- Fixes
  - Fixed invisible werewolves
- Mod Updates
  - Scrappies Matchmaker 1.5.1.1

### 3/8/2023 1.7.0
#### Minor
- Fixes
  - Corrected load order for SDA and patches
  - Fixed Aura's Inventory Tweaks + Equipped Items on Top issues
  - Fixed Silvered Ebony Helmet making heads disappear
  - Fixed missing in-game Recorder objects
  - Fixed missing rocks in White River Watch
  - Fixed Dragons turning invisible in some situations
  - Fixed jagged edges on skimpy Daedric armor
  - Fixed NPCs aggro'ing after many hits
  - Fixed missing bodyslides for several followers
  - Fixed incorrect Nord racial features
  - Fixed BFBs in Temple of Dibella
  - Fixed twitching in dialogue
  - Fixed Aroused Creature profile not loading
- Mod Updates
  - The Trappings of Fate 1.1.1
  - Simple Slavery Plus Plus 6.3.17
  - HCOS 2.0
  - BakaFactory SLAL Animations 6.01
  - Submissive Lola The Resubmission 2.0.60
  - ZAZ Animation Pack 8.0 2023
  - SexLab Parasites 2023-02-26
  - Devious Devices 5.2
  - Masterstroke Core Bodyslides 1.7.0
  - Masterstroke NPC Merge 1.7.0
  - Scion 2.1.2
- Additions
  - Both Profiles
    - dunFolgunthurBossBattle Script Fix
    - SPID - NFF - Add Ignore Token to CustomAI Followers
    - Sweeping Organizes Stuff
    - Koralina's Makeup Tweaks
    - Improved Table Transition Animations
    - Dex's Thicc 3BA Bodyslide preset
    - The Tinraa Body - Hips Don't Lie bodyslide preset
    - Demonic Bodyslide Preset
    - Amazing Curves bodyslide preset
    - Lady Miraak
    - Opulent Thieves Guild
    - Ambriel - The Lost Princess 
    - Remiel
- Other
  - Merged futa patches into their parent skin mods to make customization easier.
  - Regenerated Synthesis outputs.

### 2/2/2023 1.6.1
#### Incremental
- Fixes
  - Fixed redundant MCM for Lock Overhaul
  - Fixed missing requirements for Adira
  - fixed some signs (thanks Dace!)
  - fixed some missing TAWOBA books (thanks Dace!)
  - Kinda fixed missing functionality of Equipped Items On Top (will be refined further in a future update)
- Additions
  - Both Profiles
    - VNDKTR's Goddess Emporium - Assets

### 1/30/2023 1.6.0
#### Minor
- Fixes
  - Both Profiles
    - Fixed Lock Overhaul interactions with Hand To Hand (thanks Frosty!)
    - Fixed a stupid message from MME (thanks Frosty!)
    - Fixed LewdMarks being disabled
    - Fixed anal collision not working
    - Fixed broken Midden teleport
    - Fixed green overlay in Dwemer ruins
  - Creature Profile
    - Fixed creatures in College of Winterhold preventing sleeping (thanks Frosty!)
- Mod Updates
  - MS ROL Patch
  - CBBE 3BA 2.46
- Additions
  - Both Profiles
    - Desktop Splash Screen
    - Chubby Elf Bodyslide Preset
    - D-sney Mommy Bodyslide Preset
    - Lair of Succubi
    - Missile's Immersive Equipment Display Presets
    - Aura's Inventory Tweaks
    - Adira Follower
    - Missing Follower Dialogue Fix
    - Obscure's College of Winterhold NPC Stuck in Staircase Fix
    - DX Fetish Fashion Vol 1 and custom crafting recipe patch, thanks Frosty!
    - DX Fetish Fashion Vol 2 and custom crafting recipe patch, thanks Frosty!
    - Elven Supremacy Bodyslide preset
    - Skyrim Sewers
    - Enhanced Volumetric Lighting and Shadows (EVLaS)
- Removals
    - JK's College of Winterhold
- Replacements
  - OBody Standalone -> OBody NG

### 1/10/2023 1.5.3
#### Incremental
- Fixes
  - Fixed mismatched TRX textures & bodyslides
  - Possibly fixed missing item objects in container/barter menus
  - Probably fixed issues related to attack speed
- Mod Updates
  - Horny Creatures of Skyrim 2.0
  - Public Whore 1.2.4
  - Show Player In Menus 1.3.0
  - Let Your Hair Down 1.6
  - MoreNastyCritters 15
- Additions
  - Both Profiles
    - Animation Queue Fix
    - Lovely Lady 3BA Bodyslide Preset
    - Attack Speed Framework
- Other
  - Updated MCM Recordings
  - Regenerated FNIS/Nemesis Output

### 1/6/2023 1.5.2
#### Incremental
- Fixes
  - Fixed CTD caused by Mu Joint Fix
  - Fixed missing Vanity Mirror in ROL (Thanks Dace!)
  - Fixed some BFBs
- Mod Updates
  - moreHUD 4.1.2
  - moreHUD Inventory Edition 1.0.20
  - Administer Potions to NPCs SE 3.1
  - Improved Traps 2.5
  - Archery Locational Damage 2.1.2
  - Simple Offence Suppression 2.2.1
  - Equipment Toggle 1.1.0
  - .NET Script Framework v18
  - Assorted Mesh Fixes 0.77
  - Actor Limit Fix v5
  - Bug Fixes SSE v6
  - Better Jumping 1.7.3
  - Equip Enchantment Fix 1.3.5
  - Enhanced Reanimation 1.5.1
  - Private Profile Redirector 0.5.3
  - Spell Perk Item Distributor 6.3.0
  - Baka Defeat 1.50
  - Laura's Bondage Shop 3.41
- Additions
  - Both Profiles
    - Dark Bodyslide Preset III
    - Dark Bodyslide Preset II
    - Touched by Desire Curves Bodyslide Preset
    - My Tasteful Bodyslide Preset
    - Berry Mommy Bodyslide Preset
    - Empyrean Bodyslide Preset
    - Show Player In Menus
    - Immersive Equipment Displays
    - Let Your Hair Down
    - SDA Patch Hub
    - Damsels in Distress - The Caged Rose
    - Damsels in Distress - Follower Collection
    - TRX SOS/Futa Add-Ons
- Replacements
  - NPC AI Process Postion Fix -> NPC AI Process Position Fix NG
- Removals
  - Mu Joint Fix

### 12/30/2022 1.5.1
#### Incremental
- Fixes
  - Fixed Lux not actually doing anything
  - Fixed Dodge being weird (Sprint rebound to left Shift key)
  - Fixed College of Winterhold CTD
- Mod Updates
  - Mu Joint Fix 2.0.10
  - Laura's Bondage Shop 3.40
- Additions
  - Both Profiles
    - KSHair for Laura's Bondage Shop
    - Deviously Helpless SE
    - Missives
    - SL Dirty Deeds Missives
- Removals
  - Luminosity
- Replacements
  - Fantasy Creature Tails -> Fantasy Creature Tails 2
- Other
  - Added Masterstroke Brighter Interiors under the Customization section
  - Updated MCM/Character Creation documentation
  - Updated Customization documentation

### 12/26/2022 1.5.0
#### "Minor"
- Fixes
  - Fixed BethINI INI paths
  - Fixed mismatched Futa skin textures
  - Fixed Rosa's missing Round Bottom
  - Possibly fixed animation bug regarding yokes
- Mod Updates
  - Lux 5.3.1
  - Mod Organizer 2.4.4
  - Trappings of Fate 1.1
  - SL Aroused Creatures 4.10
- Additions
  - Both Profiles
    - Quality of Life
      - No Numpad Hotkeys
      - SkyUI Config Tweak - Equipped Items On Top SE
    - HUD/UI
      - Wash That Blood Off 2
      - Oxygen Meter 2
    - Overlays/Tattoos
      - Lyru's Tattoo Packs (1 and 2)
      - LewdMarks
    - Bodyslide Presets
      - Divine's Chosen Bodyslide Preset (HIMBO)
      - Edgar Bodyslide Preset (HIMBO)
      - Femboy HIMBO Bodyslide Preset
    - RaceMenu Presets
      - LMJ's Cutegonians
    - Gameplay Changes - Combat
      - Dual Wield Block
    - Gameplay Changes - Miscellaneous
      - Smart Training Tweaked
    - SFW Animations
      - Leviathan Animations - Sprint
      - Vanargand Animations - Dual Wield Normal and Power Attacks
      - Vanargand Animations - Dual Wield Sneak Strikes
      - Vanargand Animations - Crossbows
      - Goetia Animations - Female Idle Walk And Run
      - Goetia Animations - Male Idle Walk And Run
      - Goetia Animations - Sprint
      - Goetia Animations - Sneak Magic
      - Goetia Animations - Conditional Shouts
      - Leviathan Animations - Male Idle Walk And Run
      - Witcher Dodge Replacer
    - Graphics - Lighting & Effects
      - FleshFX
    - Graphics - Objects
      - Vanilla Table Replacers
    - Items - Armors
      - DX Morenn Outfit
      - DX Necromancer Robes
      - DX Merta Assassin Outfit
      - DX Cassandra Apocrypha Robes
      - DX Witcher Armor
      - Tera Succubus Armor
      - Stormcloak Warmaiden Armor
      - Daring Demon Hunter Armor
      - Dwemer Researcher Armor and Outfit
    - Location Expansions
      - JK's Arcadia's Cauldron
      - JK's Belethor's General Goods
      - JK's Warmaiden's
      - JK's The Drunken Huntsman
      - JK's The Bannered Mare
      - JK's Dragonsreach
      - JK's Sleeping Giant Inn
      - JK's The Winking Skeever
      - JK's Angeline's Aromatics
      - JK's Bits and Pieces
      - JK's Radiant Raiment
      - JK's Blue Palace
      - JK's Candlehearth Hall
      - JK's White Phial
      - JK's Sadri's Used Wares
      - JK's Palace of the Kings
      - JK's The Bee and Barb
      - JK's Elgrim's Elixirs
      - JK's The Pawned Prawn
      - JK's The Ragged Flagon
      - JK's Mistveil Keep
      - JK's The Temple of Mara
      - JK's Silver-Blood Inn
      - JK's Arnleif and Sons Trading Company
      - JK's The Hag's Cure
      - JK's Understone Keep
      - JK's Riverwood Trader
      - JK's Temple of Dibella
      - JK's Temple of Kynareth
      - JK's Temple of the Divines
      - JK's Temple of Talos
      - JK's Haelga's Bunkhouse
      - JK's Jorrvaskr
      - JK's High Hrothgar
      - JK's Sky Haven Temple
      - JK's College of Winterhold
      - JK's Septimus Signus's Outpost
      - JK's Sinderion's Field Laboratory
      - JK's The Bards College
      - JK's Castle Dour
      - JK's Interiors Patch Collection
      - JK's Guild HQ Interiors Patch Collection
      - JK's College of Winterhold Combo Patches
    - NPCs - Followers
      - Serana Dialogue Add-On
    - SexLab and Friends
      - CBPC Separate Anal Collision
      - The Ancient Profession
      - The Ancient Profession Interiors Project
  - Creature Profile
    - Female Draugr uses Strap Ons Special Edition
- Removals
  - Seductive Lips SE
  - Amorous Adventures SE
- Replacements
  - Both Profiles
    - Leviathan Female Idle Walk Run -> Leviathan II Female Idle Walk Run
    - Smooth Random Jump Animation -> Parkour in Skyrim
    - Smooth Staff Animation -> Goetia Animations - Enchanted Staves
    - Smooth Magic Casting Animation -> Goetia Animations - Magic Spell Casting
    - Faster Get Up/Stand Up -> Get Up With Style
- Other
  - Added to and updated MCM Recording
  - Regenerated FNIS and Nemesis Outputs
  - Regenerated Synthesis Patches
  - Added ENB Organizer and several ENB Presets (default is still Culminated)

### 12/16/2022 1.4.5
#### Incremental
- Mod Updates
  - Submissive Lola 2.0.58
  - Simple Dual Sheath 1.5.4
  - Public Whore 1.2.2
- Additions
  - Both Profiles
    - Difficulty Balance
    - TESL Loading Screens (plus custom MS loading screens)
    - Fus Ro Don't
    - Phoenix Compendium
    - Khajiit Steal Too
    - Allow Dialogue Progress Bugfix

### 12/12/2022 1.4.4
#### Incremental
- Fixes
  - Fixed NFF free crafting recipes
  - Fixed being able to use NFF to have followers sell things
- Mod Updates
  - Public Whore 1.2.1
- Additions
  - Both Profiles
    - Multicolored KS Hairdos Standalone

### 12/8/2022 1.4.3
#### Incremental
- Mod Updates
  - NL_MCM 1.1.2
  - Transformative Elixirs 1.2.0
  - MCM Helper 1.4.0
  - po3's Tweaks 1.7.5
  - Spellforge 2.2
  - Public Whore 1.2.0
- Additions
  - Both Profiles
    - Elemental Eyes
    - Koralina's Eyebrows for HPH
    - Ravens' Warpaint SE
    - Seductive Lips SE
- Replacements
  - Both Profiles
    - Minimalistic Follower Framework -> Nether's Follower Framework

### 12/1/2022 1.4.2
#### Incremental
- Fixes
  - Fixed overpowered werewolves
  - Fixed overpowered DX outfits
  - Fixed being able to select a normally unselectable object on Spellforges
  - Fixed cultists attacking too early
  - Fixed suspicious Chaurus eggs not appearing (creature profile)
  - Fixed some broken/missing bodyslides
  - Fixed males using skimpy mage robes when no skimpy option is selected
- Mod Updates
  - Devious Devices (bodyslides only)
  - Papyrus Tweaks 3.0
  - Scrappies Matchmaker 1.5
  - Rosa Round-Bottom 1.2
- Additions
  - Both Profiles
    - Heat & Hunger
    - Vanity Mirror SE
    - TERA Armors 3BA Conversion
- Other
  - Regenerated bodyslides as needed

### 11/24/2022 1.4.1.1
#### Hotfix
- Fixes
  - Fixed Enemy Magelock not working properly
  - Fixed Papyrus Tweaks NG for real this time
  - Fixed missing hand-to-hand perk tree.
  - Fixed Acoustic Space Improvement Fixes not working.
- Additions
  - Both Profiles
    - Wet Function Redux (disabled in-game by default, optional enable, requires MCM refresh on existing saves)

### 11/21/2022 1.4.1
#### Incremental
- Fixes
  - Fixed vendors not having the correct amount of spell scrolls and staves
  - Made Papyrus Tweaks NG actually work.
- Mod Updates
  - Transformative Elixirs 1.1.1
- Additions
  - Both Profiles
    - Fair Skin Makeup Overhaul
    - Whetstones
    - Infinity UI
    - Compass Navigation Overhaul
    - No Vendor Spell Tomes (Apprentice, Adept, Expert, Master only)
    - Wade in Water Redone
    - Use or Take
    - Sound Record Distributor
    - Regional Sounds Expansion
    - Reverb Interior Sounds Expansion
    - Acoustic Space Improvement Fixes
    - Enemy Magelock
- Replacements
  - Both Profiles
    - Sometimes Pick Up Books -> Read or Take

### 11/17/2022 1.4.0
#### Minor
- Fixes
  - Fixed CTD related to Honed Metal
  - Fixed jump bug after being headshot (thanks MaiNeym!)
  - Fixed CTD in Ancestral Glade (thanks Zarantha!)
  - fixed CTD during Alduin's Bane cutscene (thanks Zarantha!)
  - Fixed dog/wolf schlongs
  - Fixed incorrect main menu
  - Fixed SL Drunk applying to followers
  - Fixed CTD with Necromancer class
  - Fixed followers and many NPCs not using OBody (thanks MaiNeym!)
- Updates
  - Faster HDT-SMP
  - MoreNastyCritters 12.8A
  - Lux 5.2
  - Sets of Skills 2.0.2
  - Papyrus Extender 5.4.0
  - Submissive Lola 2.0.57
  - SLWidgets 2.0.6
  - Scion 2.0.1
- Additions
  - Both Profiles
    - Papyrus Tweaks NG
    - Better Third Person Selection
    - Simple Werewolf Favourite Howls Menu
    - Galaxy Cosmic Eyes
    - Fantasy Creature Overlay
    - Fantasy Creature HDT-SMP Tails
    - Vanillla Warpaints Absolution SE
    - Realistic Hair Colors
    - Realm of Lorkhan Better Bridges
  - Creature Profile
    - Estrus Retexture
    - Aradia Living Armor Retexture
    - SL Aroused Creatures
- Other
  - Updated some hotkeys that need to be set manually on the MCM page of the documentation.

### 11/5/2022 1.3.2
#### Incremental
- Fixes
  - Possibly Fixed an issue with Valmilia's body not conforming to OBody
- Updates
  - Trappings of Fate 1.0.3
  - Baka ABC
  - HCOS 1.31
- Removals
  - Removed Hank's Gamepad & Controller Fixes


### 10/10/2022 1.3.1
#### Incremental
- Fixes
  - Fixed invisible Futa Milking cuirass
  - Fixed some issues with BD's overwriting vanilla meshes on non-skimpy bodyslides
  - Fixed armbinder animations
  - Fixed immortal rabbits
  - Fixed duplicate copies of Routa
  - Fixed Lock Overhaul not using correct skill
  - Possibly fixed unable to do Dragons
  - Fixed SLP bodyslides
  - Fixed some errors with merchant chest leveled lists
  - Fixed Laura's shop item issues
  - Fixed over-eager NPCs
- Additions
  - Both Profiles
    - RaceMenu 0.4.16 Memory Leak Hotfix (SE)
    - Sidequests of Skyrim
    - Honed Metal
- Removals
  - State of Dress (was unused)
- Mod Updates
  - The Trappings of Fate 1.0.2
  - Billyy's SLAL Animations 6.1
  - TrueHUD 1.1.8
  - CBBE 3BA 2.45
  - CBPC 1.5.6
  - Nordic UI Misc Patches 1.7.0
- Other
  - Updated MCM Recording to fix a few things
  - Regenerated FNIS/Nemesis output

### 9/13/2022 1.3.0
#### Minor
- Fixes
  - Fixed some BFBs
  - Fixed missing armor textures (including panties)
  - Fixed clipping in Realm of Lorkhan
  - Fixed misaligned body textures for Maids NPCs
- Additions
  - Creature Profile
    - FNIS Creature Pack
    - Creature Framework
    - More Nasty Critters
    - Baka's ABC
    - Estrus Chaurus
    - Estrus Spider
    - Horny Creatures of Skyrim
    - EggFactory
    - CO More Creatures
    - SL Parasites
    - Billyy's SLAL Creature Animations
    - Babo Creature Animations
    - SL Pheromones
  - Both Profiles
    - Nemesis Unlimited Behavior Engine
    - HD Local Map
    - Configurable Notification Messages
    - Survival Control Panel
    - Simple Offence Suppression
- Mod Updates
  - CBBE 3BA 2.43
  - CBPC 1.5.2
  - CBPC Firm Preset 3.0
  - Sets of Skills 2.0.1
  - DX Outfits 3BA 2.3
  - Hand to Hand 1.3.3
  - Thaumaturgy 1.2.1
  - Pilgrim 1.1.0.1
  - Apothecary 1.3.3
  - Mundus 1.8.2
  - Adamant 5.6.1
  - Mysticism 2.1.2
  - Aetherius 2.8.2
  - TrueHUD 1.1.6
  - Nordic-Ish 1.1.1
  - The Trappings of Fate 1.0.1
  - Simple Slavery Plus Plus 6.3.16
- Replacements
  - Both Profiles
    - Engarde -> Valhalla Combat + TK Dodge RE
    - SL Aroused Redux -> OSL Aroused
- Other
  - Completely rebuilt all Bodyslides. All issues should be fixed with them now. (including panties)
  - Updated MCMs
  - Updated documentation to reflect new profile and new combat.
  - Updated RaceMenu INI to add more functionality.
  - Updated various output mods to use the new [FG's Modlists Output Repository](https://www.nexusmods.com/skyrimspecialedition/mods/75106) for more consistent downloads during installation.

### 9/3/2022 1.2.2
#### Incremental
- Fixes
  - Fixed CTD caused by Equipment Toggle + SMP Hair.
- Additions
  - Amorous Adventures Text and Player Dialogue Revision
- Mod Updates
  - Billyy's SLAL Animations 6.0
  - Submissive Lola the Resubmission 2.0.55
  - Lux 5.0

### 7/30/2022 1.2.1
#### Incremental
- Fixes
  - Fixed panty issue.
- Mod Updates
  - FurnAnim SLAL Pack v14

### 7/30/2022 1.2.0
#### Minor
- Fixes
  - Removed a duplicate DD Patch
  - Fixed Fall Damage being broken
  - Fixed CK dependency to install list
  - Fixed Tower Stone breaking scenes
  - Fixed missing bodyslides for Nibenean armors
  - Fixed mismatched Argonian male textures
  - Fixed schlong shenanigans
  - Fixed Maids + 3DNPC Conflict
  - Fixed Follower Command Hotkey
  - Fixed map textures for non-Skyrim worldspaces
  - Fixed panties conflicting with body armor
- Mod Updates
  - Devious Devices 5.2 Beta 7
  - The Trappings of Fate 1.0
  - Submissive Lola The Resubmission 2.0.53
- Removals
  - SOS Uncloaked
  - XP32 Weapon Styles Uncloaked
- Additions
  - Recorder - Bugfix Patch SSE
- Other
  - Regenerated Core Bodyslides
  - Added several new community-created RaceMenu and Bodyslide presets

### 7/9/2022 1.1.0
#### Minor
- Fixes
  - Check v1.1.0 [closed issues on Github](https://github.com/ForgottenGlory/Masterstroke/milestone/5?closed=1)
- Mod Updates
  - Realistic AI Detection v3
- Removals
  - Helps to Have A Compass
- Additions
  - Recorder SOS Patch
  - Laura's Bondage Shop
  - SoS and XPMSSE Uncloaked
- Other
  - Revised MCMs.
  - Revised included RaceMenu presets to add some males and remove some broken ones.

### 7/5/2022 1.0.2
#### Incremental
- Mod Updates
  - SL Baka Defeat
  - Billyy's SLAL Animations
  - BakaFactory SLAL Animations
  - Fill Her Up SE

### 6/27/2022 1.0.1
#### Incremental
- Fixes
  - Check v1.0.1 [closed issues on Github](https://github.com/ForgottenGlory/Masterstroke/milestone/4?closed=1)
- Mod Updates
  - Helps to Have A Map (and Compass) 2.2
  - At Your Own Pace Thieves' Guild 1.3.3TG
  - Faster HDT-SMP 1.44
- Other
  - Rebalanced Realm of Lorkhan
  - Rebalanced Valmilia
  - Rebalanced Archery's arrows
  - Made it so that maps/compasses don't need to be equipped to be used
  - Tweaked some MCM values to make keys easier to find and fix annoying visual effects

### 6/24/2022 1.0.0
- Official release.
