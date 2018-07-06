---
author: Scott Burns
categories:
- lentigo
comments: false
date: 2013-04-02T00:00:00Z
title: Move to Jekyll/Octopress
---

I've spent the last several days converting this site from [Drupal][drupal] to
[Octopress][octopress].  I've done this for several reasons:

<!--more-->

1. The old site was running on Drupal 5 and I wasn't looking forward to having
to upgrade it to Drupal 6, then Drupal 7, just to keep it current.
2. Since the frequency of posting aren't exactly high there's no need to keep
maintaining a database server and Drupal install to keep it going.  Drupal is
overkill for what we use this site for.
3. I'm intrigued by the site building methods described in [this post][devseed]
by Dave Cole of Development Seed.  Deploying static files and
moving more of a site's assembly to the browser itself using best-of-breed web
services seems like a great way to weave a site into the fabric of the web
itself.

I'm sure I'll run into others as I go along. I also have a lot more fun
working in languages other than PHP.  Both Python, Ruby, and Javascript feel
much more concise and expressive.

I choose to use Octopress for this first site because it seems to be the
fastest way to get started with [Jekyll][jekyll].  I have a couple of other
sites that I will also convert, but will start with Jekyll itself as they have
existing themes that I want to keep.  I also hope to move these sites over to
Github Pages hosting so I can take advantage of deploying via git.

[drupal]: http://drupal.org
[octopress]: http://octopress.org
[devseed]: http://developmentseed.org/blog/2012/07/27/build-cms-free-websites/
[jekyll]: http://jekyllrb.com/
