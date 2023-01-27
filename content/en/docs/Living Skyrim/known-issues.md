---
categories: ["Living Skyrim"]
tags: ["docs"] 
title: "Known Issues"
linkTitle: "Known Issues"
weight: 30
description: >
  Known bugs and issues with the list.
---

{{< card header="First Lessons Bug" subtitle="Severity: Minor" footer="**Will Be Fixed?:** Yes, when a fix is found.">}}

**Problem:** 

Tolfdir asks you to hold a ward while he casts firebolt at you. The firebolt hits the ward, but does not progress the scene.


**Workaround:** 

Temporarily disable projectile blocks (and possibly also timed projectile blocks) in the Valhalla Combat MCM to pass the quest. You can also just cast the ward long enough so that Tolfdir shoots the fireball and then let go of your ward, it'll smack in front of you doing no damage and clear the quest.
{{< /card >}}


{{< card header="Racial Attack Speed Variance" subtitle="Severity: Minor" footer="**Will Be Fixed?:** Yes, eventually.">}}

**Problem:** 

Some races attack slightly slower or faster than others based on animation speed.

**More Info:**

This is a tough bug to fix because it requires manually changing the animation speed of the animation in question. At the moment, we need more information regarding this bug such as which animations specifically are too fast/slow. Please open a [bug report](https://www.fgsmodlists.com/docs/living-skyrim/bugreport/) when you notice this happening and be specific about which animations are affected as well as the race(s) affected.
{{< /card >}}

{{< card header="Misplaced Water Tiles" subtitle="Severity: Minor" footer="**Will Be Fixed?:** Yes, on full release">}}

**Problem:** 

Some areas in the world have missing water tiles or misplaced water tiles.

**More Info:**

It is currently believed that this is caused due to issues related to mod updates or list changes that haven't been addressed by an update to the DynDOLOD package in the list. This should be fixed when DynDOLOD and friends are regenerated for the full release of LS4.
{{< /card >}}