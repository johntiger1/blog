---
title: "How to make a Hugo Subsite"
date: 2019-10-26T23:18:32-04:00
draft: False
categories: 
- Development
- Blogging
- Web Programming
tags: 
- Hugo
- Subsite
- Git submodules
---

You may have noticed that this blog exists under my main Github personal website. How did I get it to work?

1. Github exposes your entire vitual directory by default. (This is why you can just put raw assets in the repo, and they will be served when queried directly)
2. So, I just made Hugo build the entire blog subsite to a folder in my main repo!  

In short:

1. Follow this [guide] (https://gohugo.io/hosting-and-deployment/hosting-on-github/), except get the output of a `hugo` build to go to your main github site repo.

2. This involves configuring some submodule stuff, which is a crazy topic but super interesting. In fact, even though it took me a few hours to set up my Hugo blog site (compared to a much faster/easier process I suspect with Jekyll or Gatsby), the practical lessons/experience it taught me about submodules is invaluable!  

If there's more interest, I'll write a more in-depth resource! 

Resouces:
1. https://shahrajat.com/2016-06-22-install-jekyll-subdirectory-blog-github-pages/
2. https://www.impactbnd.com/blog/subdomains-vs-subfolders
