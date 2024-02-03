---
author: "Tom Kealey"
title: "Hello Hugo"
date: "2023-01-01"
draft: false
description: ""
tags: ["site", "play"]
categories: ["site", "play"]
series: [""]
ShowToc: true
TocOpen: false
cover:
  image: ""
  alt: ""
  caption: "<text>"
  relative: false # To use relative path for cover image, used in hugo Page-bundles

---

![Hugo](image.png)

In search of a platform for this blog, I stumbled upon [Hugo](https://gohugo.io/about/what-is-hugo/) and got cosy with [Static Site Generators](https://gohugo.io/about/benefits/). Hugo promised a fast and modern static site generator written in Go, designed to make website creation fun again. The inner geek in me was excited by that and the secret nerdy joy of writing posts in [Markdown](https://www.markdownguide.org/) and pushing them to [Github Pages](https://pages.github.com/) to build and deploy appealed to me.

I opted for a minimalist Hugo theme called [PaperMod](https://themes.gohugo.io/themes/hugo-papermod/) and set to work on breathing life into my new pet project.

## Basic Steps

1. Create `tomkealey.github.io` repository in GitHub
2. Install Hugo `brew install hugo`
3. Create site `hugo new site <sitename>`
4. Initialise Github `git init`
5. Install [PaperMod](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation)
6. Build locally `hugo -D`
7. Serve locally `hugo server -D` << *ideal for viewing the site locally*
8. Configure Github Actions
9. Push site to Github
10. Deploy to https://tomkealey.github.io
11. Create a post or two
12. Tweak theme
13. Change CNAME, A and AAAA to map www.tomfoolery.se to https://tomkealey.github.io
