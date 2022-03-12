---
title: "Contributing to LS3"
description: ""
date: 2020-08-27T19:25:12+02:00
lastmod: 2020-08-27T19:25:12+02:00
draft: false
images: []
---

## Introduction

In secret Dace, Cela and I have been working on something that will revolutionize Wabbajack modlist development. Using an insane fusion of Github and Wabbajack, I am please to introduce truly collaborative list development. Within this document you'll find all the information needed to set up your development environment, how to contribute to the modlist, how to review changes people have made and replicate them, and how to document your own changes. Read on to find out more.

### How Does This Work? 

In short, you make changes to your local copy of Living Skyrim. Then, using Github, you sync those changes which can then be downloaded and replicated across developers.

## Setting up Your Dev Environment

### Your Living Skyrim Install

To begin, you need to install Living Skyrim using Wabbajack. Follow all related instructions from the Living Skyrim documentation.

There is one major difference however that you *must* do if you want to set up the dev environment correctly.

The folder where all the mods get downloaded cannot be combined with any other downloads folder - this means that your Living Skyrim installation must be 100% independent from any other list, downloads folder, or anything else.

To be perfectly clear, you should install Living Skyrim to its own folder as normal and *contained within that folder* should be a `downloads` folder that contains all of the downloads for Living Skyrim.

When you're finished you should end up with the following:

- `C:\Living Skyrim\[installed list here]`
- `C:\Living Skyrim\downloads\[downloaded files here]`

### Github Integration

First, request and accept an invitation to contribute from me (ForgottenGlory) on the [LS3 Dev Branch](https://github.com/ForgottenGlory/LS3-Dev-Branch).

Now, you need to download this file: [Click Me!](https://drive.google.com/file/d/1Z6p8E0kzm5_2ndtqRkGW9EBt1rg51A3k/view?usp=sharing)

This file must be extracted into `C:\Living Skyrim`. When finished, the path to this folder and file should look like this:

- `C:\Living Skyrim\.github\`
- `C:\Living Skyrim\.gitignore`

Now, download and install [Github Desktop (GHD)](https://desktop.github.com/). Login to Github Desktop using your Github login.

In Github Desktop, follow these steps:

1. Click "Add Existing Repository..."
2. Navigate to your Living Skyrim install folder and select that folder.
3. Github Desktop will now show you all the files that have changed relative to what you have installed.
4. Click "Fetch Origin" at the top of Github Desktop to bring your installed copy of LS3 up to date with the development copy.
5. Click the button at the top of GHD that says "Current Branch".
6. Click "New Branch" and name it after your username. Make sure it is based on the `main` branch.

And that's it! You're now set up to use the development environment of Living Skyrim 3.

## Making Changes to LS3

Now that you've set up your development environment, you're prepared to begin making changes to Living Skyrim. 

You should feel free to install mods, create patches, and so on as normal. Github Desktop will track all the changes you make.

### Pushing Your Changes

Once you're satisfied with your changes, you should now push your changes to Github. 

In Github Desktop, follow these steps:

1. In the lower left corner, you'll see a box that says "Summary (required)" and "Description"
2. In the Summary box, create a two or three word summary of your changes.
3. In the Description box, create a *detailed* description of all of your changes. This should include a list of *all* mods added/removed, patches created, FOMOD options selected, and so on. Do not be shy, please document *everything* you've done.
4. When you've documented everything, click "commit to [your username]"
5. In the right pane of GHD, it will ask you to publish your branch. Do so by clicking the blue button.
6. Now that blue section will change to "Create Pull Request". Do so by clicking the blue button.
7. Your changes will now be pushed as a pull request to the main LS3 Dev Branch. Everyone who is developing LS3 will be able to review the changes and I (ForgottenGlory) will merge the pull request if it is acceptable. If not I'll send it back to you to refine further.

### Documenting Your Changes

Once you have opened your Pull Request, you should feel free to add additional documentation as needed as a comment on your Pull Request. As I stated before, you should not be shy about documenting things. Screenshots of FOMOD options, additional comments, and more are all welcome.

{{< alert context="warning" icon="⚠️" >}}
**Important!** 

You do NOT need to document things like load order or modlist order. All of this information is tracked for you by Github! The only things you need to document are an overview of what mods you added/removed, patches you created, or FOMOD options.
{{< /alert >}}

## Bringing Your Copy Up To Date

If you notice in Github Desktop that your dev copy is out of date compared to Github, you should bring it up to date through these steps:

1. Click "Fetch Origin" in Github Desktop. This will do most of the hard work for you including syncing load order and mod order, adding patches that have been created, merge changes, and so on.
2. Open the "History" tab in Github Desktop. This shows you all of the changes that have been made to the main branch.
3. Go through the history and look for any changes related to `.meta` files. These changes will tell you what downloads have been removed or added.
4. If you find a download that has been removed or added compared to your copy, you should remove or add the appropriate files. The name of the `.meta` file will tell you what archive(s) has been added so you can grab the exact archive necessary. These archives should be obtained from Nexus directly.
5. Now you need to install any new archives or remove any existing mods in the left pane of MO2 so that your copy matches. Review comments on pull requests or commits to see any additional information like FOMOD options.

Note: The `.meta`s on your computer will be automatically deleted by MO2 if you do not have the archive associated with that meta in the downloads folder. Therefore, you should rely on Github Desktop's history to tell you what has been added and removed and *not* MO2. The metas will be recreated when you download/install the mod.

## Releases

Eventually, enough changes will have been made such that I release the update publicly. Once this happens, we start the whole process over. When a release happens, bring your copy up to date one more time and then you should be good to continue iterating for the next inevitable update. *You should never have to install the list through Wabbajack unless you need a clean slate to start from.*