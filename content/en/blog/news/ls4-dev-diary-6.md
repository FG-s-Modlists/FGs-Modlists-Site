---
title: "Living Skyrim 4: Dev Diary 6"
description: ""
lead: ""
date: 2022-07-22T00:00:01-04:00
lastmod: 2022-07-22T00:00:01-04:00
draft: false
weight: 50
images: ["ls4-dev-diary-6.jpg"]
contributors: ["ForgottenGlory"]
---

### Combat and Enemies

Perhaps one of the most exciting sections of the modlist is the combat and enemies section. It's the one section that probably has the most immediate impact on overall gameplay and can make or break the list. Before I talk about what's included in LS4, I want to talk about the goals and intentions behind them.

#### Identifying Problems

It's generally agreed upon that Skyrim's combat is at minimum outdated and at worst really bad. But *why* do people say that? I think it's fair to say that there's several core issues with Skyrim's vanilla combat.

1. The animations are repetitive.
2. There's no skill involved - you either win or don't.
3. Combat boils down to mashing one mouse button until either your enemies are dead, or you are.
4. Mages and archers are too powerful.
5. There's no incentive to change armor or weapon except for higher stats or a better enchantment.
6. Dragons aren't impactful as enemies, nevermind bosses - they just have a lot of health.
7. Most other creatures are laughably weak.
8. There are "bugs" such as ice skating.

#### The "Feel" Of Combat

There are a lot of ways to overhaul Skyrim's combat to address the above problems. Some people prefer a combat system similar to Dark Souls, where fighting even a single enemy requires a ton of skill and learning. There's also the combat system of something like Path of the Dovahkiin, where within a few pieces of loot you become an unkillable, monster slaying badass. You could also go for a direction more like the recent Assassin's Creed games, where you have options but should still reasonably win against most enemies.

I'm aiming for a combination of the above. I want positioning, movement, and situational awareness to be a cornerstone of LS4 combat, similar to Dark Souls. That said, I don't want you to have to approach even single enemies in the Dark Souls way - you should still be able to take on a small group by yourself assuming you keep your head. And finally, I want the combat to be fast-paced and hard hitting like Assassin's Creed. So how do we get there? Read on to find out.

#### The Core Combat Package

Points 2, 3, 4, 5, and 8 are addressed by Living Skyrim 4's core combat package. 

We start with ADXP/MCO, which is a modern combat overhaul that is gaining significant popularity. It fixes a number of issues with Skyrim's combat, such as how you move when attacking and how attacks are executed in the game. It's heavily animation driven, which we'll talk about in a moment. Next we have True Directional Movement, which allows for more modern movement both in combat and out of combat. These two together sufficiently address the "ice skating" problem among other movement and attack commitment related issues with Skyrim's combat.

TK Dodge RE, Projectiles, and Distance Based Combat address the skill related issues with Skyrim's combat. You're now able to dodge attacks and enemies change their combat style based on their distance from the player. This requires evaluation of not only how many enemies you're facing, but what attacks they're using, how far they are from you, and so on. You can't just wade into a group of enemies anymore - constant movement, repositioning, and dodging are key to success in LS4. You'll also be forced to keep track of the positions of enemy archers and mages so you don't end up as a pincushion.

As for balancing archers and mages, we have Archery Locational Damage and Enemy Magelock. With these two mods archers are both more deadly and less deadly - if you get headshot, it will hurt. If you get hit in the leg, it will hurt less but will slow you down. Enemy Magelock makes it so that mages have to stand still to cast their spells at you, and when combined with Projectiles, you actually have a chance to dodge their spells. 

On the defensive side of things there's Resistances Rescaled, Know Your Armor Redux, and Know Your Enemy Redux.  Resistances Rescaled provides better scaling for defenses against things like magic, which can help nerf enemy mages more assuming you come prepared to fight them. Know Your Armor Redux and Know Your Enemy Redux gives incentive to change up your armor or weapons based on the resistances each armor provides and provides incentive to change up what you're using based on what your enemies are using.

For those of you who read all of that and said, "How am I supposed to keep track of all of this, it sounds too hard!" I'm happy to tell you that Simply Balanced is included which features a complete MCM so you can tweak pretty much any facet of combat. If enemies are doing too much damage, you can tone it down. If it's too easy, you can turn up the damage for enemies and turn your own damage down. And so on. Simply Balanced is the duct tape keeping everything together so that you don't get killed in a single hit unless you want it to be that way.

#### Animations

I won't list every new animation mod we're including in LS4 here, but know this: almost every single combat animation has been revamped and overhauled. Some of the mods included even add more animations depending on how many normal attacks you do before a power attack. Dynamic Animation Replacer is a hell of a mod, and I can say with confidence that you'll be very impressed with the new animation package in LS4.

#### Enemy Overhauls

While enemy variety wasn't on my list of points earlier, I do think it is a problem with Skyrim - who wants to fight a Bandit Outlaw again for the 9000th time? Not me. To that end, we're combining several mods to make every combat situation a new experience. Heritage Enemies 2, OBIS, and Skyrim Revamped - Complete Enemy Overhaul are being merged together so that no two groups of enemies will be the same. You'll be required to adapt to every new combination of enemies the game throws at you. Combine that with Arena - An Encounter Zone Overhaul, and across new playthroughs no area will play the same twice. 

As for overall enemy difficulty, Simply Balanced, Magelock, Archery Locational Damage help with that. Enemies get a brain overhaul from Combat AI and Distance Based Combat. Draugr Upgrades and Improvements, Dragon War, and SkyTEST give a new coat of paint on the more monstrous enemies in the game - they'll be smarter, more varied, and more powerful to make fighting them more impactful. Dragons especially are now much more in the territory of bosses than they were in vanilla Skyrim.

#### Population

I would be remiss if I didn't address the amount of enemies you face - this is Living Skyrim, after all. Hand Placed Enemies and Ultimate Hostile Encounters address the population of enemies in LS4. Whether in a dungeon or wandering the world, you'll come across larger groups of enemies than before. This does make it more difficult to take on large dungeons, especially places like Silent Moons Camp, but I assure you that with patience, skill, and preparation you can succeed.

Overall, I'm extremely excited to share this new combat package with you all. I'm very pleased with where it is at the moment and we're continuing to test balance and such as list development continues.

Cheers.

FG