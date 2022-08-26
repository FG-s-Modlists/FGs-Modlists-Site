---
title: "From Zero to Featured"
description: "A comprehensive guide on how to go from completed modlist to the Wabbajack UI as a featured modlist."
lead: "By ForgottenGlory"
date: 2022-08-10T00:00:01-04:00
lastmod: 2022-08-10T00:00:01-04:00
draft: false
images: []
menu:
  articles:
    parent: "articles"
weight: 50
toc: true
---

### Requirements & Info You Need To Know

Before we dive in, there are some basic things you should be aware of. First, this guide assumes you have completed your modlist. All the mods are installed, patches have been made, and so on. It also assumes that you will want to share your modlist with other people. 

There are some more specifics you need to know though, so let's begin.

#### Terminology

##### Installer
When I say "installer", what I mean is this: Wabbajack creates a file with the `.wabbajack` extension. That file is used by Wabbajack to allow a modlist to be installed. So when I say an "installer file", that's what I'm referring to. The installer file for Living Skyrim 3, for example, is `living_skyrim.wabbajack`.

##### Root Folder

A root folder is the base folder on a computer that a modlist is inside. For example, Living Skyrim 3's root folder (for me) is `C:\Modlists\Living Skyrim 3`. When I refer to the root folder, I mean the folder that contains the `ModOrganizer.exe` for your modlist. Later in this guide you'll see this referred to in this way, or in similar ways: `[root folder]\downloads`, `[root folder]\Stock Game`, etc.

##### Unofficial, Featured, and Utility Lists
There are officially three kinds of modlist when it comes to Wabbajack.

Unofficial lists are those maintained by a person without any guarantee of support for that modlist. Unofficial also covers lists that aren't ready for "primetime" yet: alphas, betas, tests, and so on. Unofficial lists aren't required to be on the Wabbajack UI, but it can be done if you so choose. Unofficial lists can be distributed as easily as giving people access to the installer file via Google Drive or another filesharing site. We'll dig into the specifics of this later, but for now, know that any list that isn't one of the following two types is an Unofficial list.

Featured lists are modlists that have been vetted in some way. In the past this meant that the list had been tested by some of the Wabbajack staff. Nowadays, it tends to mean lists that have been recognized as stable with many installs. 

The actual process for a list to become Featured is as follows:

1) It is an Unofficial list currently.
2) You contact a member of the Wabbajack staff and request that it be made Featured.
3) That's it! If it's accepted as Featured, there are some more steps to be done to make it show up properly on the Wabbajack UI, but otherwise it's as easy as that.

Utility lists are special in that they don't really make many changes to the game they're for. A perfect example of this is Skyrim Modding Essentials, which is a barebones modlist for Skyrim that includes many of the basic fixes, patches, and tools required to begin building a modlist. It doesn't contain any gameplay, graphics, quests, or any other mod - it's purely fixes and tools. These are the least common list because usually a game only needs one, but if you want to make one for a game that doesn't have one yet, more power to you.

#### Github
If you want to make an Unofficial or Featured list, you'll need a [Github](https://github.com/signup) account. A lot of the things we'll be doing are done on Github, so this is a must-have.

#### Wabbajack
You'll also need a copy of [Wabbajack](http://www.wabbajack.org). You can't make an installer without it, after all. When you download Wabbajack, you should place it *in its own folder* on your computer. Ideally, the path to your copy of Wabbajack will be `C:\Wabbajack\Wabbajack.exe`, but feel free to place it in a folder at the root of any drive on your computer.

#### Mod Organizer 2
Wabbajack only supports modlists built using [Mod Organizer 2](https://www.nexusmods.com/skyrimspecialedition/mods/6194), so unfortunately if your modlist uses Vortex or another mod manager, you won't be able to create an installer file. For more information about how Mod Organizer 2 should be set up to facilitate a Wabbajack modlist, refer to the [Compiling](#compiling) section of this document. Additionally, Mod Organizer 2 must also exist in your `[root folder]\downloads` folder. It is strongly recommended that you obtain Mod Organizer 2 from its latest Github release, which will give you the archive necessary for Wabbajack to be able to install Mod Organizer 2.

#### Stock Game
Wabbajack has a feature called Stock Game, which is a way to keep the default install folder of a game clean for users while still having a modded copy of the game. It also allows users to install multiple modlists for the same game at the same time in the event they wish to switch. For more details on setting up Stock Game, you should read [The Animonculory's guide](https://github.com/The-Animonculory/Modding-Resources/blob/main/Stock%20Game%20Setup.md) to setting up Stock Game.

### Metas
When you download a mod archive (`.7z`, `.zip`, `.rar`, etc.) from Nexus, Mod Organizer 2 automatically creates a `.meta` file for that mod. The Meta file tells Mod Organizer 2, and more importantly, Wabbajack, where that mod came from and how to obtain the archive. Similarly, if you download a mod from a site that is *not* Nexus, Mod Organizer 2 will still create a `.meta` file for that mod, but it will *not* contain any of the required information of where that archive came from. For mods that do not come from Nexus, you will have to manually update Meta files such that they contain the required information for Wabbajack to know where to obtain that archive.

We'll now take a look at some non-Nexus `.meta` files.

#### Direct URL
<pre><code>[General]
removed=false
installed=true
directURL=adirectURL</code></pre>

`directURL=` is primarily used for files obtained via Google Drive, Mediafire, Mega, Github, and other file hosting sites. Files that use `directURL` must be whitelisted, which we'll talk about in a bit. In the above example, to properly configure the `.meta`, you would simply replace `adirectURL` with the URL of the file you want to download. It's important to note that `directURL` also allows Wabbajack to automatically download the file in question.

Note that `directURL` does *not* work with sites like Lover's Lab or Vector Plexus.

#### Manual URL
<pre><code>[General]
installed=true
uninstalled=false
manualURL=amanualURL
prompt=Please click Download on this page.</code></pre>

The above should look fairly familiar. Manual URL works exactly the same as Direct URL except that Wabbajack will *not* automatically download the file in question. Instead, Wabbajack will present the webpage you provide when replacing `amanualURL` and ask the user to download the indicated file. The `prompt=` field can contain any text, but try to keep it short and sweet (the Wabbajack window is only so big, after all). For example, you might say `prompt=Please click Download on this page.` or `prompt=Please download FileName_X-Y-Z.7z`. 

Note that `manualURL` *does* work with sites like Lover's Lab or Vector Plexus and is preferred for those sites.

#### ips4
<pre><code>[General]
ips4Site=Lovers Lab
ips4Mod=12345
ips4File=File Name.7z</code></pre>

ips4 is unique in that it is only for two specific websites: Lover's Lab, and Vector Plexus. These two websites are based on the ips4 framework. `ips4Site=` should be used to indicate which website Wabbajack should try to retrieve the file from, either `Lovers Lab` or `Vector Plexus`. `ips4Mod=` should be filled out with the file ID for the file. This is obtained from the URL of the webpage the file is on. So for example, if we have `https://www.loverslab.com/files/file/18156-llapc-loverslab-attachment-patch-compendium/`, the file ID is `18156` - the number directly before the name of the mod. Last, the `ips4File=` should be the *exact* name of the file you want Wabbajack to download. From the previous example, you might want `FSF + SLSO Script Patcher.7z`.

It's very important to note that ips4 should only be used as a last resort, `manualURL` is much preferred for these two sites currently.

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

I cannot stress this enough: ***everything in your `[root folder]\downloads` folder must have a complete `.meta` file!*** ***EVERYTHING!***
{{< /alert >}}



### Whitelisting mods
### CDN Access
### Uploading a file
### Regarding Mod Permissions
### Downloading from the CDN
### Outputs (DynDOLOD etc)
### Compiling

For details about how to actually go through the compiling process, you should refer to my article about that exact topic here: [Click Me!](https://www.fgsmodlists.com/articles/compiling-a-modlist-with-wj/)

### Creating a modlists.json

### Logo


### Readme
### Support
### Handling Bug Reports
### Distribution
#### WJ UI
#### Nexus
#### GDrive
### List Maintenance
#### List Validation
#### List Healing
#### WabbaBot