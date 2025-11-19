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

## My current setup
This site is written, edited and published in [Obsidian](https://stephango.com/obsidian). Finished articles are pushed to a [GitHub](https://github.com/) repository and automatically compiled into web pages using [Hugo](https://gohugo.io/) (with [Blowfish theme](https://blowfish.page/)) and hosted with [Cloudflare Pages](https://pages.cloudflare.com/).

I only pay for the domain registration which costs me \$10.45/year from [Cloudflare Registrar](https://www.cloudflare.com/products/registrar/).

My current workflow from writing to publishing (all inside Obsidian):

1. I write my article in a Markdown file located in a git folder `my-website` in Obsidian Vault.
2. When I am done writing, I use the `Git` community plugin to commit and push changes to my public GitHub repo with all my articles.
3. And that's it!

## Start of the journey
I will be honest. Once I made up my mind to start a blog, I was addicted to setting up the ultimate blogging setup. I had to make decisions on and learn about so many things. What app should I use to write? What website theme should I use? How should I publish my site?  How should I name my domain? On top of that, I had my wants. I wanted a minimalistic setup that requires no repetitive workflow or alt-tab'ing between apps to write articles and publish them. After a few days of frantic Google searching, forum scrounging, developing  and troubleshooting, I am finally done. All my requirements are met.

### SSG vs. CMS vs. Blogging Platform
The first decision I had to make was how I was going to create the website.



My requirements (and solution):
- 
- I did not want to maintain multiple Obsidian vaults. I wanted a one universal vault both for my personal notes that I don't share online and notes that will be published to my blog
	- Solution: Have the git folder that I use to share in as a folder inside the vault.

## External Resources
- https://stephango.com/vault#publishing-to-the-web
- https://4rkal.com/posts/obsidianhugo
- https://www.nickgracilla.com/posts/obsidian-is-my-hugo-cms/
- https://oscarmlage.com/posts/hugo-and-obsidian/