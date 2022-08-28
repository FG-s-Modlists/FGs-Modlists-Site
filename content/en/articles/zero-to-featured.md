---
title: "Comprehensive Wabbajack Guide"
description: "A comprehensive guide on how to use Wabbajack for your modlist."
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

Before we dive in, there are some basic things you should be aware of. First, this guide assumes you have completed your modlist. All the mods are installed, patches have been made, and so on. It also assumes that you will want to share your modlist with other people. If you want to use Wabbajack just to backup a copy of your modlist, some of the information here will be helpful but in general it's aimed towards authors that want to distribute their modlist.

There are some more specifics you need to know too, though, so let's begin.

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
3) That's it! If it's accepted as Featured, there are some more steps to be done to make it show up properly on the Wabbajack UI as such, but otherwise it's as easy as that.

Utility lists are special in that they don't really make many changes to the game they're for. A perfect example of this is Skyrim Modding Essentials, which is a barebones modlist for Skyrim that includes many of the basic fixes, patches, and tools required to begin building a modlist. It doesn't contain any gameplay, graphics, quests, or any other mod - it's purely fixes and tools. These are the least common list because usually a game only needs one, but if you want to make one for a game that doesn't have one yet, more power to you.

#### Github
If you want to make an Unofficial or Featured list, you'll need a [Github](https://github.com/signup) account. A lot of the things we'll be doing are done on Github, so this is a must-have. You should also make yourself familiar with these processes:

- [Making a repository](https://docs.github.com/en/get-started/quickstart/create-a-repo)
- [Creating pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
- [Creating files on a Github repository](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files)

#### Wabbajack
You'll also need a copy of [Wabbajack](http://www.wabbajack.org). You can't make an installer without it, after all. When you download Wabbajack, you should place it *in its own folder* on your computer. Ideally, the path to your copy of Wabbajack will be `C:\Wabbajack\Wabbajack.exe`, but feel free to place it in a folder at the root of any drive on your computer.

#### Mod Organizer 2
Wabbajack only supports modlists built using [Mod Organizer 2](https://www.nexusmods.com/skyrimspecialedition/mods/6194), so unfortunately if your modlist uses Vortex or another mod manager, you won't be able to create an installer file. For more information about how Mod Organizer 2 should be set up to facilitate a Wabbajack modlist, refer to the [Compiling](#compiling) section of this document. Additionally, Mod Organizer 2's archive must also exist in your `[root folder]\downloads` folder. It is strongly recommended that you obtain Mod Organizer 2 from its latest [Github release](https://github.com/ModOrganizer2/modorganizer/releases), which will give you the archive necessary for Wabbajack to be able to install Mod Organizer 2.

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

It's very important to note that ips4 should only be used as a last resort, `manualURL` is much preferred for these two sites currently due to instability with their API.

{{< alert context="danger" icon="🛑" >}}
**WARNING!**

I cannot stress this enough: ***everything in your `[root folder]\downloads` folder must have a complete `.meta` file!*** ***EVERYTHING!***
{{< /alert >}}
### Whitelisting Mods

Some mods are hosted in obscure places on the internet and Wabbajack does not have a comprehensive list of those places. Therefore, when you find a file that Wabbajack does not recognize, it must be whitelisted. The actual whitelist Wabbajack uses is found [here.](https://github.com/wabbajack-tools/opt-out-lists/blob/master/ServerWhitelist.yml) You'll notice that this list is split into sections. The two important sections are `GoogleIDs` and `AllowedPrefixes`. Whenever you want to whitelist a file hosted on Google Drive, its file ID should be added to the list under the `GoogleIDs` section. All mods found on other filehosting sites should be placed in the `AllowedPrefixes` section.

Google file IDs are contained in the URL for the file. For example, the ID for this file `https://drive.google.com/file/d/15_0njBUjHKidNnJPmLXEygzGVWsA3Zbq/view?usp=sharing` is the string of characters between the `/d/` and `/view`: `15_0njBUjHKidNnJPmLXEygzGVWsA3Zbq`. All other files (Mega, Mediafire, etc) should be added simply by using the URL for the file.

It's generally courteous to check the whitelist to see if the file you need to whitelist is already on there. If it is, you don't need to add it. If it isn't, you'll need to open a Pull Request to modify the whitelist and add the file. You should also add a comment (prefixed by #) to indicate what the file is.

Also note that every line in the whitelist is prefixed by `- `, you should do that as well. You should also group all of the files for your specific list together.

A properly formatted whitelist section looks like this:

<pre><code># Living Skyrim 3.0.0
- https://archive.org/download/Wyrmstooth1.17BSSE/Wyrmstooth%201.17B%20SSE.zip # Wyrmstooth 1.17B
- https://www.skyrim-guild.com/s/ADXP_Beta_13.zip # ADXP/MCO Beta 1.3
</code></pre>

### CDN Access

Wabbajack has a CDN (Content Delivery Network) that is available for modlist authors with Featured modlists to use. The CDN can be used to host files that you have generated for your modlist - DynDOLOD output, Grass Cache, patches, and so on. It serves as an integrated alternative to uploading those files to Nexus. To gain access, you'll need to login to Github and then follow the guide Unnoen put together, [here.](https://github.com/wabbajack-tools/wiki/wiki/Getting-CDN-Access)

Once you have access to the CDN, you can use it to upload files and then when a user installs your list, they can download it directly from the CDN instead of Nexus or another site. It is much preferred to use the CDN over filehosting sites like Google Drive, Mega, and so on because many filehosting sites limit the amount of users that can download a file before temporarily suspending access to that file. The CDN has no such restrictions.

#### Uploading a file
Once you've set up your CDN access, it's straightforward to upload a file to the CDN.

In Wabbajack, click the gear icon in the top right corner of the program. You'll be presented with the settings page for Wabbajack. Below the "Logins" box, you'll see a section for uploading files.

Simply click Select File, then find the file you want to upload. Then click Upload and wait for it to complete. *Do not close Wabbajack once the upload is complete.*

The reason you don't want to close Wabbajack yet is that once the upload finishes, you'll be given the URL to your file. This is the URL that should be placed in a `directURL .meta` to allow Wabbajack to automatically download the file you just uploaded.

#### Common Mods
Some commonly used mods are available on the CDN for you already, such as the ENB binaries. You should double-check to see if a copy of that mod already exists on the CDN and use that copy instead of uploading a new copy whenever possible.

#### Regarding Mod Permissions
While the CDN is a very powerful tool that we can use as modlist authors, it cannot be used to re-upload mods unless the permissions of that mod state it can be re-uploaded. You are always expected to obey the permissions set by mod authors while creating your modlist.

### Logo

Before you compile your modlist, you may want to create a logo for it. This can be as simple as something you put together in MS Paint or as complex as using Photoshop to create a unique and cool logo. While I won't go into the specifics of logo creation (there are only about a billion tutorials online), I will say that having an eye-catching logo is important for the branding and marketing of your modlist.

### Readme

You'll also want to make a readme for your modlist. This can be hosted on Github, your own website, or even a simple Google Doc. The readme should cover essential information relating to your modlist. If you want some examples, I can highly recommend the following readmes:

- [Living Skyrim 3](https://www.fgsmodlists.com/livingskyrim/beforeyoustart/)
- [Lost Legacy](https://github.com/Lost-Outpost/lost-legacy)
- [Ruvaak](https://github.com/chri3i/Ruvaak-Readme/blob/main/README.md)
- [Tales from the Northern Lands](https://eziothedeadpoet.github.io/Tales-from-the-Northern-Lands/)

### Compiling
The process of creating an installer file is called "compiling". 

For details about how to actually go through the compiling process, you should refer to my article about that exact topic here: [Click Me!](https://www.fgsmodlists.com/articles/compiling-a-modlist-with-wj/)

### Going Unofficial
When you have successfully created an installer file, logo, and readme, congrats! You're ready to turn your modlist into an Unofficial modlist.

#### Wabbajack UI

If you want your list to appear on Wabbajack itself, you'll need to set up a modlists.json file so that Wabbajack knows your modlist exists and can be distributed to users. To do so, follow the instructions in [this guide.](https://github.com/wabbajack-tools/wiki/wiki/Adding-a-Custom-Repository-to-Wabbajack)

Note that if your list goes from Unofficial to Featured, the custom repository you make will no longer be required and can be safely archived/deleted.

Once you've done that, give Wabbajack some time to update (anywhere from 10 minutes to an hour) and then your modlist will appear on the Wabbajack UI!

#### Nexus
You can also upload your installer to Nexus, if you so choose. Just follow the normal process for creating a new mod and upload the installer file to it. Nexus is a good alternative as there is more traffic to Nexus itself, as well as allowing you to show off screenshots, describe the list, and respond to users all in one convenient place. Note, if you do upload your list to Nexus, it is against Wabbajack's terms of service to opt the list in to Nexus's Donation Points program. 

#### Filehosting
While not ideal, you can technically just put your installer on any filehosting site and give people the link to the file. They'll be able to download and run the installer themselves through Wabbajack.

### Support
After your modlist has been distributed, it's very likely you'll have people who need assistance or have questions. Maybe they just need help installing the list, or maybe there's a technical question about how certain mods interact in your list. How you go about supporting users is, ultimately, up to you. However, here are some recommendations about things that will help you:

- [Discord](https://discord.com) - a live-chat service where you can set up your own server to handle support requests and interact with your users
- [Guilded](https://www.guilded.gg) - a slightly less popular alternative to Discord.
- Github Issues - if you make a Github repository for your modlist, you can use Github's built in issues system to track bug reports, answer questions, and so on.
- Forums - various forum softwares are available for use that you can use to set up a forum for support and discussion between yourself and users.
- [Trello](https://trello.com/home) - a free board, list, and card based system that can be used to track bugs and to-do lists.
- [Google Forms](https://docs.google.com/forms/u/0/) - a free tool to set up forms that users can fill out
  
While these are some of the most popular systems available to modlist devs to interact with users and handle bug reports, you're of course welcome to use whatever system you're comfortable with. I myself use a combination of tools to interact with my users and keep track of bugs - Asana (bug tracking), Vercel (website hosting), Discord (community and support).

### List Maintenance
Inevitably, a mod will update or be removed causing your modlist to go into Maintenance. This appears on Wabbajack as a bright yellow banner that says "Under Maintenance". All this means is that Wabbajack cannot allow a list to be installed because a file required by the modlist cannot be obtained.

The most straightforward solution to this problem is to update your modlist. You should remove the mod from your list and your `[root folder]\downloads` folder, or if a new version is available, update the mod to the newest version. When you update your modlist, you'll need to update the locations that you uploaded your modlist to. Nexus handles versioning for files fairly well, but if you're using the Wabbajack UI, you'll need to use the `modlists.json` you created earlier (or the Featured `modlists.json`) to update the metadata for your modlist so that it can continue distributing the list.

You can also use the `machineURL` field on the Wabbajack compilation screen to have Wabbajack automatically update the metadata for your modlist once compilation is complete. If your list is Unofficial, you should fill it out as follows: `repo name/list name`, following whatever naming scheme you used while setting up your custom repository. If your list is Featured, you should fill it out as `wj-featured/list name`. 

#### List Validation
"How does Wabbajack know when a mod has been removed?" You may ask. To that, I'll let you know about Wabbajack's secret weapon: Validation. Periodically, Wabbajack checks every mod in every list to make sure those files are still available. If a file isn't available, or Wabbajack can't connect to a file's host website, it marks the list as in maintenance. Depending on the stability of the host website, this may automatically resolve itself after a certain amount of time. It's up to you to verify Wabbajack's validation to see if a list update is needed.

#### List Healing
When validation for a mod on Nexus fails, Wabbajack will then check to see if that mod has been updated. If it has, Wabbajack is able to continue serving the old version of the mod. Or, if the old version is no longer available somehow, Wabbajack will try to heal the modlist. It will download the new version of the mod and then change the new version such that it matches the old version. It will then continue to serve the modlist to users, but you should really try to update the mod when possible. This process is entirely automated so you shouldn't have to worry about it too much, but it is a handy backup just in case.

#### WabbaBot
The last thing you may want to set up for your modlist is access to WabbaBot. WabbaBot is a Discord bot that allows you to quickly announce updates for your modlist. It will make the announcement for you across multiple Discord servers that have opted in to receive notifications about your list. For more information about this bot and how to set it up, you should join the [Wabbajack Discord server](https://discord.gg/wabbajack) and visit the #wabbabot-help channel.