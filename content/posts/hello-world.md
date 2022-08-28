---
author: "Tom Kealey"
title: "Hello World"
date: "2022-08-01"
draft: false
description: ""
tags: ["site", "play"]
categories: ["site", "play"]
series: [""]
ShowToc: false
TocOpen: false
cover:
  image: ""
  alt: ""
  caption: "<text>"
  relative: false # To use relative path for cover image, used in hugo Page-bundles

---
I've been a Squarespace subscriber for many years but never truly made much of my investment. I was keen for a low-cost alternative for a blog and stumbled upon a post that made reference to Static Site Generators [^1] and Hugo [^2] [^3]_- a fast and modern static site generator written in Go, designed to make website creation fun again._

[^1]: An Introduction to Static Site Generators - https://davidwalsh.name/introduction-static-site-generators
[^2]: What is Hugo - https://gohugo.io/about/what-is-hugo/
[^3]: The Benefits of Static Site Generators - https://gohugo.io/about/benefits/

Writing posts in Markdown and pushing them to Github to build and deploy appealed to my inner developer. The geek in me was all in. I opted for a minimalist theme [PaperMod](https://themes.gohugo.io/themes/hugo-papermod/) and set to work.

### Basic Steps

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