---
categories: ["Living Skyrim"]
tags: ["docs", "how do i"] 
title: "...Use a controller?"
linkTitle: "...Use a controller?"
weight: 1
description: >
  How do I use a controller with the modlist?
---

ForgottenGlory's modlists are not specifically designed with controller support in mind. The amount of keybinds required by the modlist are much better suited to a keyboard and mouse, and you should use that setup if possible. 

However, if you do feel the need to use a controller, as of version 4.1.0, a controller layout may be optionally enabled, courtesy of Discord user hbkmog. To do so;

In MO2, scroll down to the List Customization separator. There you will find The Ultimate Control Scheme and Classic Sprinting Redone. Enable both of these.

There is also a file you need to move/delete. Navigate to `..\Living Skyrim 4\Stock Game`, find the ControlMap_Custom.txt, and either move it somewhere else (to back it up) or delete it.

From here, there are a few manual edits to make. Find the TK Dodge RE mod, double click it in MO2, then click over to the INI Files tab, and click on the TK Dodge RE.ini file on the left hand side and change the `EnableSprintKeyDodge=false` to `EnableSprintKeyDodge=true`. Close that window, allowing it to save.

The next step is to change an .ini file for One Click Power Attack. Following the same steps as above, change the `ForceRightKey=258` to `ForceRightKey=281`.

The last step is to load up the game. Press Escape to open the menu, then Settings. Enable "Controller" and you're good to go! Once again, thanks to hbkmog for setting this up!

The binds for this layout are as follows;
- A - activate/confirm/hold to turn on quick light
- B - hold B to sprint/tap to dodge.
- X - favorite menu
- Y - jump
- LB - left hand light attack/block when not dual wielding
- RB - right hand light attack
- LT - shout/power
- RT - power attack.
- Back - map
- Start - journal/pause menu
- Left stick - sneak
- Right stick - change POV/lock on enemy
- A+LB - inventory
- A+LT - magic
- A+RB - ready weapon
- A+back - wait
- A+start - quick save
- A+left stick - tween menu(mainly used for access statics screen)
