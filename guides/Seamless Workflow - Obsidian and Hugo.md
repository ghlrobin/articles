---
title: "Seamless Workflow - Obsidian and Hugo"
date: "2025-10-13"
draft: true
tags: [obsidian, hugo, blogging]
---

I wanted a minimalistic setup that requires no repetitive workflow or alt-tab'ing between apps to write articles (or notes) and publish them to my blog. After a few hours of frantic Google searches and troubleshooting, I was able to succeed.

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