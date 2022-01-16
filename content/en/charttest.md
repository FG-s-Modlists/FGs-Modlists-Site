---
title: "Chart Test"
description: ""
date: 2020-08-27T19:25:12+02:00
lastmod: 2020-08-27T19:25:12+02:00
draft: false
images: []
---

+++
[dataset1] # this key will in the chart shortcode
  fileLink = \"content/ls3modlist.csv\" # path to where csv is stored
  columnTitles = [\"#Mod_Name\", \"#Mod_Nexus_URL\"]
  title = \"LS3 Modlist\"
  table = true # show table listing the chart data
+++

{{< chart "dataset1" >}}