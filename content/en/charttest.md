---
title: "Chart Test"
description: ""
date: 2020-08-27T19:25:12+02:00
lastmod: 2020-08-27T19:25:12+02:00
draft: false
images: []
dataset1:
    fileLink: "content/ls3modlist.csv"
    columnTitles: ["#Mod_Name", "#Mod_Nexus_URL"]
    title: "LS3 Modlist"
    table: true
---


{{</* grid " mt-2" */>}}
    {{< chart "dataset1" >}}
{{</* /grid */>}}