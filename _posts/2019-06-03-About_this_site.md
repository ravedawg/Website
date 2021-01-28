---
layout: post
title:  "About this website"
date:   2019-06-03 19:00:00 -0500
categories: main
---
Hello! I put this site together using the base Jekyll theme called Minima, and host it free via my GitHub pages account. I highly recommend both for a static or first website. 

Jekyll is a family of Ruby Gems that are maintained by a core team of people. Lots of options, and fairly easy to customize. Only a subset of these website templates (themes) are compatible with GitHub, but again, they are super simple to customize. Hosting on GitHub is advantageous, because it takes care of versioning and comes with a community's worth of references. And did I mention it's free? $10-$20/mo for hosting adds up fast. Use this money to "buy" a domain name instead.

You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Jekyll and Minima at GitHub:
[jekyll](https://github.com/jekyll/jekyll) /
[minima](https://github.com/jekyll/minima)

Other resources I used:
- This [tutorial](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages#github-desktop-app-) is great for installing Jekyll and its dependencies, e.g. Ruby, Xcode, Homebrew, and NodeJS. However it is woefully outdated for all GitHub related material. So go direct to [GitHub](https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll) for that.
- Jekyll uses a combination of [YAML](https://en.wikipedia.org/wiki/YAML#Basic_components) and [Liquid](https://shopify.github.io/liquid/) (a templating language) for formatting. Basically you'll find that the post and page headers are in YAML, and the pages are in Liquid. Sounds confusing, but they are both fairly intuitive, especially if you're working off templates. Check out the YAML tag feature.
- Since the Liquid community is rather small, I recommend the Shopify community's [discussion pages](https://community.shopify.com/). Shopify actually uses its own version of liquid, but it has a large community and the basics tend to translate.
- Posts are written in [Markdown](https://www.markdownguide.org/basic-syntax/#links). Specifically, the "kramdown" variant of Markdown. Make sure all references also use this flavor.

Some additional notes:
- To create a new page, duplicate *page_title.md*. Change the filename, title, and permalink, then contents. Works the same way for posts.
- To edit the template itself (customize!), copy the respective page and folder from the minima template </Library/Ruby/Gems/2.6.0/gems/minima-2.5.1> and add it to the same respective spot in your local project.
- Don't store things in the *_site folder*. This is where what is 'built' is saved, and it may save over anything you manually add.
