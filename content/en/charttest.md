---
title: "Chart Test"
description: ""
date: 2020-08-27T19:25:12+02:00
lastmod: 2020-08-27T19:25:12+02:00
draft: false
images: []
dataset1:
    fileLink: "content/ls3modlist.csv"
    colors: ["#627c62", "#11819b", "#ef7f1a", "#4e1154"]
    columnTitles: ["Mod Name", "URL"]
    title: "LS3 Modlist"
    baseChartOn: 2
    piechart: false
    doughnutchart: false
    bargraph: false
    table: true
---


{{< grid "3" >}} {{< chart "dataset1" "table" >}} {{< /grid >}}