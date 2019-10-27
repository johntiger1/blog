---
title: "How to make a Hugo Subsite"
date: 2019-10-26T23:18:32-04:00
draft: False
---

You may have noticed that this blog exists under my main Github personal website. How did I get it to work?

1. Github exposes your entire vitual directory by default. (This is why you can just put raw assets in the repo, and they will be served when queried directly)
2. So, I just made Hugo build the entire blog subsite to a folder in my main repo!  

In short:
1. Follow this [guide] (https://gohugo.io/hosting-and-deployment/hosting-on-github/), except get the output of a `hugo` build to go to your main github site repo.
2. This involves configuring some submodule stuff.

If there's more interest, I'll write a more in-depth resource! 
