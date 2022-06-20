---
title: Find Verts Weighted To Bone Function
author: Felipe Nogueira
date: 2022-06-20 19:30:00 +0000
categories:
- Tutorial
- Blogging
tags:
- Scripts
- 3D Studio Max
- Maxscript
render_with_liquid: true

---
Here is a little function I wrote that will go through all selected meshes and find all the vertices weighted to a given bone. I had to write this to find all the meshes that had a specific bone in their skin mod, but not just that! I needed to know which of those meshes had verts weighted to this specific bone.

The main task was to remove the influence of that bone from all meshes not necessarily remove the bone as the engine export strips out any bone that has no vertices weighted to it.

There are also ways to get the influenced verts of selected bone by hand, but I needed a way to go through hundreds to thousands of meshes in a timely manner.

<iframe src="https://player.vimeo.com/video/60972226" width="640" height="400" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
..

<script <script src="https://gist.github.com/pepetd/7c05ca8f442869a188a342a94b38f837.js"></script>