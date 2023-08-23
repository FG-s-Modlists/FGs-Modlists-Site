---
categories: ["Living Skyrim"]
tags: ["docs"] 
title: "1.1 - Hard Requirements"
linkTitle: "1.1 - Hard Requirements"
weight: 2
description: >
  Must-have dependencies to be able to install the list.
---

<button onclick="window.location.href='https://beta.fgsmodlists.com/docs/living-skyrim/step-1-preparations/';" class="btn btn-primary">⮜ Step 1 - Preparations</button>
<button onclick="window.location.href='https://beta.fgsmodlists.com/docs/living-skyrim/step-1-preparations/setup/';" class="btn btn-primary">1.2 - Steam, SSE, and Wabbajack Setup ⮞</button>

The following are *absolutely required* to begin installation of Living Skyrim 4. These must all be installed and up to date before you begin.

- [Skyrim Special Edition (Steam, v1.6.640)](https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/)
- [Microsoft Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)
- [.Net Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime)
- 350GB of available space on a hard drive/SSD/NVMe. (120GB downloads/217GB mods/13GB Stock Game)

More detailed instructions on installing and configuring these are further below.

<table>
  <tr>
    <th></th>
    <th style="border-bottom: 1px solid;">Minimum Specs</th>
    <th style="border-bottom: 1px solid;">Recommended Specs</th>
    <th style="border-bottom: 1px solid;">FG's Specs</th>
  </tr>
  <tr>
    <th>CPU</th>
    <td>Ryzen 3 3300U or higher</td>
    <td>i5-6600 or higher</td>
    <td>Ryzen 9 3900X</td>
  </tr>
  <tr>
    <th>GPU</th>
    <td>GTX 1650 or higher</td>
    <td>GTX 1080Ti or higher</td>
    <td>RTX 3080 10GB</td>
  </tr>
  <tr>
    <th>RAM</th>
    <td>8GB or higher</td>
    <td>16GB or higher</td>
    <td>32GB</td>
  </tr>
</table>

## Additional Requirements
### Nexus Premium
You are not required to have Nexus Premium to install Living Skyrim, however, it is highly recommended. Nexus Premium will cut your install time to a fraction of what it would be by automating both the mod download and mod install processes of installing the list.

### Storage Space
As of version 4.0.0, Living Skyrim requires approximately 347GB of hard drive space (This number *includes* the download size). Installing to an SSD/NVMe is not required, but also highly recommended. The faster the drive you install the list onto, the faster the installation process will run and the faster the game will go through loading screens when playing.

## More About System Specifications
Living Skyrim requires a good to excellent computer to run. Textures range from 512x512 to 4K and everything in between. The following system is ForgottenGlory's personal computer and is able to run the list at a constant 60FPS including ENB at 1440p monitor resolution.

- CPU: AMD Ryzen 9 3900X @ 4.2GHz
- RAM: G.Skill TridentZ Neo 32GB DDR4 3600MHz CL16
- GPU: nVidia RTX 2080 Super 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz
- Storage: Sabrent Rocket 2TB M.2 NVMe 2280; Samsung EVO 860 250GB; SeaGate Barracuda 2TB 7200RPM

In general, it is recommended that you have a processor with a clock speed of at least 3GHz and a graphics card with at least 6GB of VRAM. 4GB graphics cards may be able to run the list if you do not use ENB, but it is not guaranteed.

As for RAM, 16GB is the recommended specification for running the list. 32GB is the ideal amount, and anything more than that is honestly overkill for this list.

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
This is another runtime library required by some programs. Not having these installed can result in issues running Living Skyrim.

click the link to open a page on the Microsoft Website to download the .NET runtime files. You may need both the Desktop and Console versions, so please install both:
- [.Net Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime)

<button onclick="window.location.href='https://beta.fgsmodlists.com/docs/living-skyrim/step-1-preparations/';" class="btn btn-primary">⮜ Step 1 - Preparations</button>
<button onclick="window.location.href='https://beta.fgsmodlists.com/docs/living-skyrim/step-1-preparations/setup/';" class="btn btn-primary">1.2 - Steam, SSE, and Wabbajack Setup ⮞</button>