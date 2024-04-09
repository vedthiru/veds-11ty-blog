---
title: Simple blog setup using 11ty
description: Why I chose 11ty for my blog
date: 2024-04-09
tags:
  - Blog
  - 11ty
---

{% image "./assets/11ty.png", "11ty" %}

After evaluating multiple options like Jekyll, Hugo and Quartz, I've finalized on using [[11ty]] to setup my blog. My main requirements were :
- It should be simple in a way that I can understand it. I do have some rudimentary knowledge of Javascript, so  I could read the documentation and figure out what to do or what to search. So 11ty fit the bill here. 
- Should be simple to setup and test. Jekyll was pretty good too, but because of Ruby version complications, I kept running into errors setting it up on my mac. I just couldn't get a plugin to work. It kept resulting in unreadable errors. 11ty was much more straightforward. No dependency hell (at least so far).

So I setup a basic blog with it. I also write on [[Obsidian]], so I wanted a way to use backlinks on my blog. I discovered this cool plugin called [Eleventy Plugin Interlinker](https://github.com/photogabble/eleventy-plugin-interlinker?tab=readme-ov-file). It was a struggle to set it up, because I was unaware of some 11ty basics. Plus the documentation is confusing on this. Very poor across the board. I'll write a separate post on it later. But after a few hours I was able to figure this out. 

___

#### Next steps:
- Work on the looks (CSS of course) to beautify, I'm a designer after all