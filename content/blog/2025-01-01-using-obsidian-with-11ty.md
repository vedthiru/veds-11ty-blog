---
title: Using Obsidian with 11ty
description: Publishing an 11ty blog by creating the posts in Obsidian sounds like a perfect workflow
date: 2025-01-01
preview: ""
draft: false
tags:
  - Obsidian
  - PKM
  - 11ty
categories: 
type: default
---
## What this post is:

This post is just going to be a log of events along with my thoughts. Nothing preachy. 

#### Q1 2024:
- I dove into the productivity, PKM rabbit hole around Feb last year (right now it is Jan 1, 2025)
- Checked out Obsidian, Bear (for the apple ecosystem), Notion, Apple notes, Capacities, Logseq
- Started using Obsidian and Bear quite heavily, alternating between the two
- Spent a LOT of time customizing Obsidian to my liking, wrote my own custom CSS and theme, got frustrated with it and stopped using the tool completely.

#### Q2 2024:
- Started a blog because I wanted to document my thoughts and explorations online
- Checked out Wordpress and [11ty](https://www.11ty.dev/)
- Setup my blog here, where you're reading this, with 11ty
- Rolled my own theme by modifying the base theme
- But the workflow to publish a post was too cumbersome: write -> post to a markdown IDE, check formatting, git push, wait to see if it appears ok
- Because it was so convoluted, I kind of abandoned this blog

#### Q3 and Q4 2024:
- I setup another blog on wordpress
- It was easy to write posts over there, so published a few posts
- But none of the themes were simple enough, too many features and too much "battling the system" to get a simple look
- Gave up wordpress
- But I kept writing my thoughts and ideas on Notion and Obsidian anyway, just without publishing

#### Q4 Turning point
- End of the year, I came back to this blog, I have always loved this minimalist look
- Thought I need to simplify the publishing flow
- Bear notes had a workflow to publish to wordpress straight from the app: "Could I do 11ty with Obsidian? After all it's such a flexible tool"
- **Turns out, I CAN!!!!**
- Kicking myself for not thinking of this earlier

#### How I'm doing this now OR How to publish to your 11ty blog from Obsidian

**NOTE: I'm assuming some basic Obsidian and 11ty knowledge**

- Create a blog with 11ty using any of the many methods available
- Publish posts via Github
- Now, open the 11ty blog as a vault in Obsidian
- In Obsidian settings > Files and Links > Folder to create new notes : point it to content/blog
- Add markdown frontmatter to every post from an Obsidian Template: create a template with front matter tags like this
```js

---
title: My post
date: 2020-02-23
published: true
tags:
- Tag 1
- Tag2

---

```
- Install the plugin "Templater" on Obsidian, and set it up to use this frontmatter template for every new file
- Also install a Github Plugin on Obsidian, so you can publish with a git push via the plugin

That's it.
Now write your post, and click on the github plugin button. It pushes the code, and then onto your publishing process. 

