---
title: "Living Skyrim 4: Dev Diary 2"
description: ""
lead: ""
date: 2022-05-09T00:00:01-04:00
lastmod: 2022-05-09T00:00:01-04:00
draft: false
weight: 50
images: ["ls4-dev-diary-2.jpg"]
contributors: ["ForgottenGlory"]
---

### Graphics

When I'm building a modlist, I tend to start with the graphics. Living Skyrim 4 is no different.

#### The Why

Before we talk about the how, let's talk about the why. There's a couple of big reasons I start here. First, it's easy. Graphics mods are (usually) the easiest mods to add, remove, and swap out. In almost all cases, you just install a graphics mod and then forget about it. Well, kinda. Graphics are extremely obvious once you install them, especially once you install a lot of them. But they can be (and, for the most part, are) completely independent of everything else going on in the list. Additionally, they're extremely easy to compare on the fly. I find that, before you install a lot of gameplay and content mods, the game loads faster and makes it a very simple process to boot up the game, see what a graphics mod looks like, then compare it to others in its category.

The next big reason is related to performance. If you have a bunch of graphics mods, you can see the impact your graphics mods alone have on the game before installing a bunch of mods with scripts, content, and so on. If you have performance where you want it to be with just graphics alone then you have a very good starting point for the rest of the mods in the list. For example, right now I have Living Skyrim 4 running between 50 and 65 FPS at 2560x1440 with the graphics mods I've installed. This is acceptable to me, but there is an annoying bug already: the list currently suffers from some major stuttering when you look around outside. I don't know what's causing it (yet), but I've caught it early enough in development that I know for certain it's related to the graphics mods I've installed. This makes it relatively simple to hunt down and fix.

Next, graphics are extremely fluid throughout development. Once I have a baseline I like, it's very easy to tweak and fine tune over the course of the rest of list development. If I come across a new mod I like the look of, or if something new releases that's a must have, I know for certain that the baseline is done and I don't really have to worry about that new mod so much but can easily add it and know where to put it in the load order relative to the baseline. By doing the graphics first, I basically don't have to worry about it for the rest of the list's development. Combined with the previous reason, this also allows me to take feedback during the pre-alpha and alpha phases related to graphics and performance and make adjustments on the fly. My hardware isn't the same as your hardware, and isn't the same as my staff's hardware. By having graphics remain fluid throughout development, it leaves me free to make changes to help make sure the list is reasonable to run.

Lastly, content mods pull heavily from the graphics mods you have installed - if you retexture a vanilla asset, it's extremely likely that any mods that use that asset will also be retextured. This makes sure that even when playing modded content you still have the (hopefully) consistent graphical style the rest of the list has. And then when you come across a piece of modded content that doesn't match, it's very easy to identify. Fixing the inconsistency is a bit harder, but it's possible. 

#### The How

Picking out graphics mods is, unfortunately, entirely subjective. What I like isn't going to be what someone else likes. What looks good to me isn't necessarily going to look good to someone else. That said, I do use the high concept I talked about last time to guide what graphics mods I picked.

For example, in Living Skyrim 4 I want to make sure the Life pillar is front and center. Graphics mods can make this reality, especially when it comes to landscapes, flora, and fauna. A grass mod, tree mod, and various plant retextures make the world come alive in a way that vanilla Skyrim never could.

For example, take a look at the screenshot from LS4 below.

<img src="https://cdn.discordapp.com/attachments/963467812041543740/972290910303973406/unknown.png" style='width: 100%; object-fit: contain'/><br>

This showcases an object added to the game by Lux Via, which adds various unique light sources along Skyrim's roads. If you came across this object, you'd think there's some history to the location - it was important enough to build a shrine at, so there's got to be something significant about it. In reality, this is just at a crossroads where the road heads north to the snowy mountains north of Solitude, southwest towards Dragon's Bridge, and then northeast towards Solitude. There's nothing particularly important about this location, but the addition of this shrine makes it *feel* important. Makes it *feel* like it has a story to tell. There isn't a story, of course. It's just a relatively unimportant crossroads. But the fact that it's there brings what was formerly a boring, empty crossroads to *Life*. It's been there before you came to this place, and it will be there after you've defeated Alduin.

Similarly, you can see from the screenshot that there are bushes and trees all around it. This is life in a much more literal sense than what I just described, but it's there all the same. This location is alive. This is how I pick graphics mods for Living Skyrim 4 and this is the type of theory and thought process that's going into building all of Living Skyrim 4. 

##### Consistency

Consistency in graphics is one of the hardest things in Skyrim to pull off. When you have 400 mods all retexturing different things, changing meshes, adding objects, and so on - how do you reconcile the inconsistency in artistic style, taste, and direction?

I don't have an easy answer to this question. What I feel is the correct answer is to do your best, but don't stress about the little things. I *do* stress about the little things, but they aren't usually important enough to lose sleep over. Let's look at another example, from a screenshot I posted last time.

<img src="https://i.imgur.com/O2GNvHq.jpg" style='width: 100%; object-fit: contain'/><br>

Do you see the inconsistency? I do.

Having trouble? Look closer.

<img src="https://cdn.discordapp.com/attachments/963467812041543740/971925473489715240/unknown.png" style='width: 100%; object-fit: contain'/><br>

<img src="https://cdn.discordapp.com/attachments/963467812041543740/971925946879864903/unknown.png" style='width: 100%; object-fit: contain'/><br>

The larger pillars don't match their bases or the ceiling supports. This, in the grand sceme of things, is a very minor inconsistency. But it's there. And I'll *know* it's there. So I want to fix it. I haven't decided how I'm going to fix it yet, and honestly I may end up not fixing it - when I mentioned it to my staff a few of them didn't even see it until I pointed it out. This sort of thing is the thing I look for when I'm building the graphics package for Living Skyrim. Living Skyrim 3 failed at this spectacularly - there are inconsistencies all over the place. But with Living Skyrim 4 I'm looking to correct that oversight. 

##### 512/1K/2K/4K/8K

Contrary to popular belief, not every graphics mod has to be 4K Parallax Photorealistic AI Upscaled Immersive Ultra. In fact, I argue that you specifically should *not* do this for every graphics mod. Unless you like using your computer to cook breakfast. In general, my philosophy is very simple and depends on the size of the object in question:

- Smaller than the player (silverware, food, potions, etc.): 512 or 1K
- Player-size (armor and weapons, usually): 2K
- Larger than the player (buildings, trees, etc): 4K
- Larger than a house (mountains and dragons, usually): 4K or 8K (if available)

This, for me, seems to be a very good guideline for achieving good to great looking graphics while also not lighting my computer on fire.

But I have an example for this as well.

<iframe frameborder="0" class="juxtapose" style='width: 100%; object-fit: contain' height="344" src="https://cdn.knightlab.com/libs/juxtapose/latest/embed/index.html?uid=579e92bc-cffc-11ec-b5bb-6595d9b17862"></iframe>

This is a window in Solitude. On the left you have a 2K texture, and on the right is an 8K AI Upscale I made specifically for this comparison. Obviously, the 8K version *looks* better, especially when you're as close as I was when taking these screenshots. But under normal gameplay circumstances you should *never* be close enough to see this difference. Nevermind that going from 2K to 8K textures makes the performance impact significantly higher. So which should you pick? The one that looks better under all circumstances, or the one that will realistically look "good enough"? If you picked 2K, you're correct by my measure. 

In all technicality the 8K is a better texture and will look better in game. But again, in normal gameplay you're not going to stop and get as close as you possibly can to a window. The beautiful thing about things like windows and other objects you'll never inspect this closely is that they don't *need* to be as high quality as you can make them. They just have to be high enough quality that your brain won't pick them out as obviously lower quality. In my experience, looking "good enough" is the same as looking good. 

This is why I have a hierarchy of texture sizes relative to player size. If an object is smaller than the player, it's too small to really appreciate the fine detail you get from a 2K or 4K texture, making 512 or 1K textures ideal. If it's player sized, the only time you'll see them is in third person or on enemies. This means that you'll see things from afar (in the case of third person) or in the heat of combat (in the case of enemies). If it's larger than the player - trees, buildings, etc. - it's very likely you'll spend a lot of time near these objects and they need higher quality. Additionally on large objects the difference between a 2K and 4K texture is immediately noticeable. On things smaller, you only start to notice differences when you go from 2K to 8K as an example (and why my example above was a 2K to 8K comparison instead of 1K to 4K). Finally there's a special category for mountains and dragons. Mountains, simply because of their absolutely enormous size, demand the highest quality textures you can find. Otherwise, their size isn't used as best it could be. Dragons, being arguably the most important enemy in the game, should be of the highest quality possible. You'll spend a lot of time up close to them and high quality dragon textures are a must in my opinion.

### Wrapping Up

So what happens when you combine all of this information? Well, you end up with screenshots like these:

<img src="https://cdn.discordapp.com/attachments/963467812041543740/972284596806877274/unknown.png" style='width: 100%; object-fit: contain'/><br>
<img src="https://cdn.discordapp.com/attachments/963467812041543740/972286458247409704/unknown.png" style='width: 100%; object-fit: contain'/><br>
<img src="https://cdn.discordapp.com/attachments/963467812041543740/972287599651737610/unknown.png" style='width: 100%; object-fit: contain'/><br>
<img src="https://cdn.discordapp.com/attachments/963467812041543740/972289643640918116/unknown.png" style='width: 100%; object-fit: contain'/><br>

I'll let you decide what size texture the windows are in that first one. Hint: It's 2K. You'd never know or see the difference in normal gameplay.

Cheers.

FG