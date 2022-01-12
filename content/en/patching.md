---
title: "How To Patch Anything"
description: ""
date: 2020-08-27T19:25:12+02:00
lastmod: 2020-08-27T19:25:12+02:00
draft: false
images: []
---

## Setup

Before you do anything, you need to make sure you open SSEEdit properly. So, launch SSEEdit and make sure you load every single ESP there is. Once everything has loaded (indicated by a "Background loader complete" message in the bottom left corner of SSEEdit), left click anywhere in the left pane of SSEEdit. Then, press Ctrl+A to select everything.

Now, right-click anywhere in the left-pane of SSEEdit and pick "Apply Filter to show Conflicts".

<img src="https://i.imgur.com/ro4SE3L.png"></img>

This may take several minutes to run. When finished, you'll see a **lot** of red. Don't panic! Red does not necessarily mean bad.

Now, pick an ESP from the list - any ESP. Start going through the list of records inside that ESP and look for yellow, green, or red. Green you can (usually) ignore. Yellow and Red is where a patch might be needed.

## Step Zero
### Do you really have to patch this?

The first step whenever you think you need to patch something is to first look at what you are patching in relation to the other mods in the load order. If you can save yourself the trouble of creating a patch by moving the mod in the load order, you should always do this instead of creating a patch.

So, how do you know if this is the case? Let's look at an example.


<img src="https://i.imgur.com/3Hxmc8n.png"></img>

The easiest way to explain what you're now looking at is this:

SSEEdit is an enormous spreadsheet handler, and every cell in the spreadsheet has a purpose in the game. For ease of reading, SSEEdit divides the spreadsheet into columns. Each column represents a separate ESM/ESP/ESL that makes a change to whatever record you have selected. The farthest right column is the lowest plugin in your load order that makes a change to the record in question (and, therefore, contains the changes that actually appear in the game). The farthest left column is the original version of that record, usually provided by vanilla Skyrim. It's not uncommon to see that several distinct plugins make changes to a single record.

Green in this view means that a given cell is identical to all of the other cells in that row and that no changes have been made within that row (AKA no conflict). Yellow indicates that changes have been made when compared to the other versions of the record, but also that no data is missing (only that the values have been changed). Red indicates that data has been added by one of the columns and that data is not present in all of the plugins modifying the record you're looking at. This isn't a perfect explanation of the colors you're seeing, but in general this is what's going on. You'll have to look at whatever row is in question to see what exactly is happening with data being added/changed/removed.

Anyway, back to our example. We can see that Blade & Blunt is loading after VioLens. You can tell this is the case because Blade & Blunt is the farthest right of the columns we see.

This isn't what we want. If we look at some other records in the Idle Animations category, we can see that moving Blade & Blunt before VioLens in the load order would allow VioLens to overwrite the changes that Blade & Blunt makes. In this instance, we don't have to patch anything because we can just change the load order to get the desired effects in game.

And conversely, how do you know if you need to make a patch? Let's look at another example.


<img src="https://i.imgur.com/QQ1Kw6m.png"></img>


{{< tip >}}
**Protip:** 

Right-click in the right pane of SSEEdit and select "Hide no conflict and empty rows" to condense the information there down to only the rows where conflicts are occurring. 
{{< /tip >}}

In this example from AI Overhaul, we can see that NPC VO Merged is missing some data that AI Overhaul has added. Because NPC VO Merged is missing that data (indicated in red), we need to make a patch to **combine** the changes AI Overhaul makes with the changes that NPC VO Merged makes.

## Step One
### Creating a Patch

The first thing you need to do if you do need to make a patch is to copy a record into a new ESP. Patches for LS3 should **always** be ESL flagged ESPs. We'll talk about that more in a moment.

So, find a record that you need to patch as described in Step Zero.

Then, right click on the header text of the farthest right column and select "Copy as override into..."

<img src="https://i.imgur.com/Dbnx4ec.png"></img>


You will be prompted to select an ESP to copy the record into. As mentioned before, you should create a **new** ESL-flagged ESP for your patch.


<img src="https://i.imgur.com/7TqRSnn.png"></img>


Name the patch as follows:

```
LS3 [Mod Name] Patch
```

Replacing [Mod Name] with an abbreviation of the name of whatever mod you are making a patch for.

<img src="https://i.imgur.com/6bb8z9H.png"></img>


Congratulations, you've made a patch! Kind-of. Now the real work begins.

## Step Two
### Patching

One of the most useful things about SSEEdit is that it allows you to drag and drop the value of any cell. So, if we extend our example from earlier where we determined we needed to combine the changes from AI Overhaul and NPC VO Merged, we would just drag the cell we need to forward into our patch and drop it into the empty cell **on the same row as the original cell**.


<img src="https://i.imgur.com/e2cjsyB.png"></img>


If SSEEdit warns you about adding a master to your patch, click Yes.


<img src="https://i.imgur.com/7XWuH2P.png"></img>


And when you do, that row should turn green:

<img src="https://i.imgur.com/pKVDW2R.png"></img>


Congratulations! You've patched a record. For this example we would repeat the drag & drop process for the other two red rows as well before moving on. The yellow rows can be ignored because the values there are provided by a merge, which is correct.

Once you have moved all of the cell values you need to move, it's time to carry on to the next record. Simply go back to the beginning of Step One and continue onwards. Note that you do not need to create a new ESP for every record you want to change - once you've made a patch's ESP the first time, you'll just need to select your patch from the window that appears when you Copy as Override to continue adding records to the patch. A patch can (and should) contain numerous records.

## Step Three
### Saving your Patch

When you've gone through the entire sea of red/yellow for the mod you wanted to patch, it's time to save your work. Close SSEEdit (yes, really). Before the program shuts down, it will show you a list of all the plugins you've made changes to and ask you if you want to save your changes to them. We're only interested in saving our patch, so if you accidentally made a change to another plugin, make sure to uncheck that plugin in the list that appears before clicking OK.

<img src="https://i.imgur.com/Or78ujU.png"></img>


Once your patch is complete, upload it in the #ls3-patch-sharing channel on the LS Discord server and I (FG) will review it and add it to the modlist.