---
layout: post
title:  "Implementing comments to the blog posts"
date:   2016-11-17 18:28:00
categories: Blog
---

I registered at _Disqus_ and copied their [Universal Embed Code](http://docs.disqus.com/developers/universal/).

After that, I changed the _YAML Front Matter_ to "comments: true", added an if statement that checks if the comments is set to true then run the Universal Embed Code. Which is the comment system right below this text.


