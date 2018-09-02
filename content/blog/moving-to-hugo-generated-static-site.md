---
title: "Moving to Hugo and Netlify"
date: 2018-09-02T11:54:42-04:00
draft: false
---
It's been a long time since I've posted anything here and it's time to
wake this thing back up. Evidence suggests I only do this when changing
how the site is hosted and this time is no different.

So...

After a period of generating this site using Jekyll/Octopress and
hosting it on a Linode, I'm switching the generator to [Hugo][hugo]
and hosting it on Netlify.

I like Linodes and have maintained my trusty host ***glyph*** for
years. After converting my old Drupal site to a static site, though, my
primary interaction with *glyph* involves reading log analysis reports
and applying software updates. These repetitive tasks are better left
to the machines themselves.

I chose Hugo because of its speed and a desire to learn more about
the [Go][go] programming language. I chose [Netlify][netlify] for its
features. I like that it watches the Github [repository][repo] I use to
store this site for commits; then pulls, generates, and deploys the latest
version to its CDN. I write posts in markdown formatted text files and
commit them to my repository. Netlify takes care of everything else and,
for my little site, does it for free.

I still need to work on the theming and structure a bit. And post more.
...s.

[hugo]:https://gohugo.io/
[go]:https://golang.org/
[netlify]:https://www.netlify.com/
[repo]:https://github.com/spottybones/lentigo_hugo/
