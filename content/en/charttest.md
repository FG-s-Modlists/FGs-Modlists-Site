---
title: "Chart Test"
description: ""
date: 2020-08-27T19:25:12+02:00
lastmod: 2020-08-27T19:25:12+02:00
draft: false
images: []
[dataset1] # this key will in the chart shortcode
  fileLink = "content/ls3modlist.csv" # path to where csv is stored
  colors = ["#627c62", "#11819b", "#ef7f1a", "#4e1154"] # chart colors
  columnTitles = ["#Mod_Name", "#Mod_Nexus_URL"]
  title = "LS3 Modlist"
  table = true # show table listing the chart data
---

{{< grid " mt-2" >}}
  {{< chart "dataset1" >}}
{{< /grid >}}
...