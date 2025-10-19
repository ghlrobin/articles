---
title: Seamless workflow - Obsidian, Github, Hugo, Cloudflare Pages
date: 2025-10-15
draft: true
tags:
  - obsidian
  - github
  - hugo
  - cloudflare-pages
  - blogging
---

## Start of the journey

I will be honest. Once I made up my mind to start a blog, I was addicted to setting up the ultimate blogging setup. I had to make decisions on and learn about so many things. What tool should I use to blog? What website theme should I use? How should I publish my site?  How should I name my custom domain? On top of that, I had my wants. I wanted a minimalistic setup that requires no repetitive workflow or alt-tab'ing between apps to write articles and publish them to my blog. After a few days of frantic Google searching, forum scrounging, blogging workflow developing  and troubleshooting, I am finally done. All my requirements for my ultimate blogging setup are met.

Before I go on to describe my setup and how I implemented it, I should let you know first 

### SSG vs. CMS vs. Blogging Platform

The first decision I had to make was how I was going to create the website.

My current workflow from writing to publishing (all inside Obsidian):
1. Write a markdown file in a specific git subfolder `my-website` in Obsidian Vault that I use for my blog. (Generate a template with Hugo-friendly front matter with the `Template` plugin)
2. When I am done writing, use the `Git` community plugin to commit and push changes to my public GitHub repo with all my articles.

For those who are not aware:
1. Obsidian (markdown note-taking tool)
	- People like this note-taking app for some reason
2. Hugo (static site generator)
	- After choosing a theme and initial setup all you need to do is write markdown files.

My requirements (and solution):
- 
- I did not want to maintain multiple Obsidian vaults. I wanted a one universal vault both for my personal notes that I don't share online and notes that will be published to my blog
	- Solution: Have the git folder that I use to share in as a folder inside the vault.

## References
- https://4rkal.com/posts/obsidianhugo
- https://www.nickgracilla.com/posts/obsidian-is-my-hugo-cms/
- https://oscarmlage.com/posts/hugo-and-obsidian/