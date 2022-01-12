---
title: "Performance Guide"
weight: 7
layout: "lsbase"
---

## Disclaimers

If you need assistance with this guide, please don't hesitate to visit the Living Skyrim Discord server for help.

This guide must be done after each Living Skyrim update, assuming you update the list.

Completing the entirety of this guide will take a few hours. Some of the LOD Generation steps alone take over an hour each.

## Let's Talk About Performance

If I may wax poetical for a moment, video games are complicated, masterful works of computer science, artwork, creative vision, writing, and more. The ultimate combination of every form of art.

The reason I mention this is because a lot is happening under the hood of your computer when it's running a game and you're trying to figure out why a game isn't performing well. Much in the same way many things have to come together for a video game to exist, hardware, game settings, other software, operating system, monitor, and more all have to come together in just such a way that the game you're trying to play is running smoothly. Because of the number of settings and options available, **this guide is not guaranteed to increase your game's performance.** It will cover many of the most common things you can do to increase the game performance of Living Skyrim, but you may find that only some increase your frame rate. Some may in fact decrease it. Some may do nothing at all.

{{< tip >}}
**Important!** 

This guide can ***NOT*** be blindly followed and then expected to fix all your performance problems immediately. You will have to do some experimenting on your own to find out what combination of settings gives you the best performance.
{{< /tip >}}

## The "Easy" Stuff

### Pay To Win

There's a saying I'm fond of: "The most powerful card in any trading card game is the credit card." The same is true of computers and performance. That said - no one's finances are the same as anyone else's. Under no circumstances should you purchase things beyond your means or that would put your lifestyle in peril. Do what is possible within your means, or skip this section entirely if you have decided against or are unable to make a purchase that would upgrade your computer. 

If you *are* going to upgrade your computer, I would recommend considering upgrades in this priority order:

1. Storage (NVMe/SSD)
2. GPU (graphics card)
3. RAM
4. CPU

You might be surprised to see storage at the top of the list. The reason for this is very simple: On a "bang for buck" scale, switching from a traditional hard drive to a Solid State Drive or from a Solid State Drive to an NVMe is the best way to speed up load screens, avoid stutters, and more. You may have all the processing power in the world, but if your storage medium can't communicate that data to your processing units fast enough, it won't matter how fast your GPU or CPU are. NVMe drives are the best available, but keep in mind that you do need a dedicated slot for one on your motherboard to use one. Solid State Drives are the next best, and can be used with any motherboard with a SATA port (which, nowadays, is all of them). *External hard drives - even if they are solid state - are not recommended under any circumstances. Even an internal HDD will perform better than most external drives due to the speed limitations of USB.* Last but not least, if you're installing modlists, more storage space is never a bad thing.

As for the other three categories - it's fairly self explanatory. Newer and faster is better. If you're looking for specific hardware recommendations, this isn't the place for it. There are infinite reviews of computer hardware elsewhere on the internet.

### To ENB, or Not To ENB?

Open up Living Skyrim, load into the game, then press Shift + F12. You'll notice things look different, but you've also just gained anywhere from 10-20 FPS with a single keystroke (on average). What you've done is disabled ENB. ENB can make the game look significantly better, but it is extremely intense and can bring weak computers to their knees. It is up to you if the visuals of having ENB disabled are acceptable to you or not. 

If you'd rather not disable ENB completely, you can try some of the other ENB presets that are included with the list. Refer to the readme for more information about how to switch ENB presets. Some presets are more intense than others and still provide fantastic enhancements to the visuals of the game. You may find an acceptable improvement in performance simply by switching the ENB preset, but this is one of those areas where you'll have to do some experimentation to find what works best for you and your computer.

## Normal Difficulty

The following tweaks should be relatively easy to pull off if you have some knowledge of editing INI files and such.

### Windows 10 Tweak

Go to `[Install folder]\Stock Game` and locate the SkyrimSE.exe. Right click on it and click "Properties". On the Compatibility tab, put a check into the "Disable fullscreen optimizations" box, then click Apply and then OK.

### BethINI

This is another section that requires heavy experimentation. What settings in BethINI help you may not help others.

First of all, close any instance of Mod Organizer 2 that you have open. Head into `[install folder]\Tools\BethINI` and launch `BethINI.exe`. 

The things you'll want to change and experiment with are as follows.

#### Basic Tab 

- Put a check into the "Recommended Tweaks" box. (this should always be done regardless of anything else you change)
- Pick either the Medium or Low preset and click its respective button.
- Disable VSync.
- Enable Borderless and Windowed Mode.

#### Detail Tab

- Decal Quality: Medium or Low
- Godrays: Medium or Low
- Shadow Resolution: 1024 or lower
- Disable Water Reflections section

#### View Distance Tab

- Object Fade: 10 to 15
- Actor Fade: 10 to 12

### SSEDisplayTweaks

SSE Display Tweaks makes several changes to how Skyrim displays on your screen and how it's handled by your computer. Try the following:

- Back up your SSE Display Tweaks .ini file: [Living Skyrim 3 directory]\mods\SSE Display Tweaks\SKSE\Plugins\SSEDisplayTweaks.ini (recommended)
- Quit Skyrim if running, and search for "SSE Display Tweaks" using the search bar at the bottom of MO2
- Right-click the mod in the left-hand panel (you may need to click the arrow to the left of the "Essentials" header to see it)
- Click "Information...", then click "INI Files" in the window that appears
- Select the single file on the left, and then change the following values:
    - `#Fullscreen=false` to `Fullscreen=false`
    - `Borderless=false` to `Borderless=true` (may already be set)
    - `BorderlessUpscale=false` to `BorderlessUpscale=true`
    - `#Resolution=1920x1080` to `Resolution=[YOUR MONITOR RESOLUTION]`
    - `#ResolutionScale=0.75` to `ResolutionScale=0.9`
- Note where # has been removed and double-check you've set these correctly.

This should, in theory, cause Skyrim to run in a borderless window at your monitor's resolution, but only render the image in that window at 90%, cutting down a little on GPU strain. If that doesn't have much effect, try cutting the ResolutionScale to 0.8, but I wouldn't go much lower than that otherwise you'll end up with a very blurry game.

(Thanks to ChunkeeMunkee for the SSE Display Tweaks recommendations!)

### nVidia Control Panel

{{< tip "warning" >}}
**WARNING!**

**Changing settings in the nVidia Control Panel will affect every game you play on your computer - not just Skyrim! Be aware of this when considering making these changes. Most, if not all games on your system, will run better but look worse after changing these settings.**
{{< /tip >}} 

Open the nVidia Control Panel. 

#### Adjust image settings with preview Menu

Select "Use my preference emphasizing:" and change the slider to "Performance". *Before proceeding with any other tweaks, check to see if this has helped performance at all.*

#### Manage 3D Settings Menu

Experiment with the following settings to see what helps and what doesn't.

- Image Sharpening: Sharpening Off
- Ambient Occlusion: Off
- Antialiasing - FXAA: Off
- Antialiasing - Gamma Correction: Off
- Antialiasing Mode: Off
- Antialiasing Setting: None
- Antialiasing Transparency: None
- CUDA GPUs: All
- DSR Factors: Off
- DSR Smoothness: Off
- Low Latency mode: Ultra
- Max FPS: Off
- Multi-Frame Sampled AA (MFAA): Off
- Power management mode: Prefer max performance
- Shader Cache: On
- Texture Filtering Anisotropic Sample Optimization: On
- Texture Filtering Negative LOD Bias
- Texture Filtering Quality: High Performance
- Texture Filtering - Trilinear Optimization: On
- Threaded Optimization: On
- Triple Buffering: Off
- Vertical Sync: Off

(Thanks to LunaPapilio for the nVidia Control Panel suggestions!)

## Hard Mode

We're now getting into technical modding things specific to Skyrim SE. 

{{< tip "warning" >}}
**WARNING!**

**This is the one area of the performance guide that should be followed to the letter. Deviating from this can break the list entirely if you're not careful. Additionally, you should only proceed with the following if you are still receiving poor performance after doing all of the above steps.**
{{< /tip >}} 

### Regenerate LODs

#### Step 1: Backup Mods

Create a backup in MO2 of the following mods:

- LS3 Grass Cache
- SSELODGen Output
- TexGen Output
- DynDOLOD Output
- Occlusion Output
- Paper Maps SE V1.1

#### Step 2: Backup The List

Create a backup in MO2 of the mod list and plugin lists.

#### Step 3: Empty Folders

Delete the contents of the following mod folders:

- LS3 Grass Cache
- SSELODGen Output
- TexGen Output
- DynDOLOD Output
- Occlusion Output

#### Step 5: Run xLODGen

1. Select xLODGenx64 from the dropdown of executables in MO2 and click Run.
2. Once it loads, right click in the left pane of the window and click "select all".
3. In the right half of the window, uncheck Occlusion.
4. In the right half of the window, check "Terrain LOD".
5. Set the settings as follows:

##### LOD4

- Build Meshes: Checked
  - Quality: 2
  - Max Vertices: 32767
  - Optimize Unseen: Off
  - Protect Borders: Checked
- Build Diffuse: Checked
  - Size: 512
  - Format: BC7 Quick
  - MipMap: Unchecked
  - Brightness: 0
  - Contrast: 3
  - Gamma: 1.25
- Build Normal: Checked
  - Size: 512
  - Format: BC7 Quick
  - MipMap: Unchecked
  - Raise Steepness: Unchecked
- Bake normal-maps: Checked
  - Vertex Color: 1.00
- Default size Diffuse: 128
- Normal: 256

##### LOD8

- Build Meshes: Checked
  - Quality: 4
  - Max Vertices: 32767
  - Optimize Unseen: On
  - Protect Borders: Checked
- Build Diffuse: Checked
  - Size: 256
  - Format: BC7 Quick
  - MipMap: Unchecked
  - Brightness: 0
  - Contrast: 0
  - Gamma: 1.25
- Build Normal: Checked
  - Size: 512
  - Format: BC7 Quick
  - MipMap: Unchecked
  - Raise Steepness: Unchecked
- Bake normal-maps: Checked
  - Vertex Color: 1.00
- Default size Diffuse: 128
- Normal: 256

##### LOD16
- Build Meshes: Checked
  - Quality: 4
  - Max Vertices: 32767
  - Optimize Unseen: On
  - Protect Borders: Checked
- Build Diffuse: Checked
  - Size: 256
  - Format: BC7 Quick
  - MipMap: Unchecked
  - Brightness: 0
  - Contrast: 0
  - Gamma: 1.25
- Build Normal: Checked
  - Size: 256
  - Format: BC7 Quick
  - MipMap: Unchecked
  - Raise Steepness: Unchecked
- Bake normal-maps: Checked
  - Vertex Color: 1.00
- Default size Diffuse: 128
- Normal: 256

##### LOD32
- Build Meshes: Checked
  - Quality: 4
  - Max Vertices: 32767
  - Optimize Unseen: Off
  - Protect Borders: Checked
- Build Diffuse: Checked
  - Size: 256
  - Format: BC7 Quick
  - MipMap: Unchecked
  - Brightness: 0
  - Contrast: 3
  - Gamma: 1.25
- Build Normal: Checked
  - Size: 256
  - Format: BC7 Quick
  - MipMap: Unchecked
  - Raise Steepness: Unchecked
- Bake normal-maps: Checked
  - Vertex Color: 1.00
- Default size Diffuse: 128
- Normal: 256

##### Generate

Once all settings are set, click Generate and *wait*. This process can take in excess of an hour, especially on slower PCs.

#### Step 6: TexGen

1. Run TexGenx64 from MO2.
2. Set the following settings:

- Stitched Object LOD Textures: Checked
  - Texture Size: 256
- Rendered Object LOD Textures: Checked
  - Texture Size: 256
- Tree/Grass LOD Billboards: Checked
  - Units Per Pixel: 8
  - Min Texture Size: 128
  - Max Texture Size: 512
  - Grass: Unchecked
  - Tree: Checked
    - Direct: 135
    - Ambient: 55
  - HD Tree: Checked
    - Direct: 135
    - Ambient: 55
    - Smoothness: 0
  - Rendered: Checked
    - Direct: 50
    - Ambient: 150
    - Smoothness: 0
  - Diffuse Alpha: Default (BC7 Quick)
  - Normal Specular: Default (BC7 Quick)
  - Diffuse: Default (BC7 Quick)
  - Normal: Default (BC7 Quick)

3. Click "Start" and wait for it to finish.
4. Go to the output path you made for TexGen and copy those files into the TexGen Output mod you emptied earlier, then hit F5 in MO2 to refresh it.

#### Step 7: DynDOLOD

Run DynDOLODx64 from the dropdown menu in MO2.

1. Right-click in the top left box and click "Select All".
2. Click either Low or Medium for the preset.
3. Copy the following settings:

- Candles: Checked
- FXGlow: Checked
- Generate object LOD: Checked
- Ultra: Checked
- Generate dynamic LOD: Checked
- Glow windows: Checked
- High: Unchecked
- Prefer base record LOD assignments over rules: Unchecked
- Max Tile Size LOD: 256
- Billboard Brightness: -7
- NearGridToLoad: 11
- Fake lights selected world: Unchecked
- Upgrade NearGrid large references to FarGrid: Unchecked
- Max tile size full: 256
- Max tile size billboard: 256
- FarGridToLoad: 21
- Fake lights child world: Checked

4. Click "OK" and wait for it to finish.
5. Go to the output folder you made for DynDOLOD and copy its contents into the DynDOLOD Output you emptied earlier.
6. Press F5 in MO2 to refresh it.

#### Step 8: Occlusion

Run xLODGenx64 from the dropdown menu in MO2 in and run it.

1. In the left pane, right-click and then click "Select All".
2. Uncheck the "Terrain LOD" checkbox.
3. Check the "Occlusion" checkbox.

{{< tip >}}
**Important!** 

Make sure Occlusion is the only thing checked.
{{< /tip >}}

4. Click Generate and let it run.
5. When finished, open the SSELODGen Output mod folder and locate `Occlusion.esp`.
6. Cut and then paste `Occlusion.esp` into the Occlusion Output mod folder you emptied earlier.
7. Press F5 in MO2 to refresh it.

#### Step 9: Restore Modlist Backups

Restore the backups you made of the mod *list* and plugin *list* you made at the beginning of this process.
Restore the backup you made of the Paper Maps SE V1.1 mod.

#### Step 10: Sanity Check
After completion, you should have an *empty* and *disabled* Grass Cache mod. The rest of the folders you emptied earlier should have the new files you generated within them.

## The End

After completing this guide, you should find that performance is much better with Living Skyrim. If you are still having poor performance after completing the steps of this guide that don't require purchasing new hardware, it may well be time to look into upgrading your computer if you are able to do so.



