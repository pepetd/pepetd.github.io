---
title: Group Nodes - Maya Python
author: Felipe Nogueira
date: 2022-06-20 17:10:00 -0400
categories:
- Development
- Blogging
tags:
- Autodesk Maya
- Python
- Snippets
render_with_liquid: true

---
Hey guys!

Here is a quick snippet to just group nodes under their own little group hierarchie, which will provide us with a driver group and a x_form group. The x_form group is the one that contains the offset values from the parent node while the driver is the group we will use for all connections needed (sometime I even have two driver groups).

..
<script src="https://gist.github.com/pepetd/933ba1cf6775dfac369bde311cb0b370.js"></script>