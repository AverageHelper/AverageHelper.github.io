+++
title = "Changing Themes"
author = "James Robinson"
# description = "Better theme for my blog."
date = 2021-06-04T22:30:00-06:00
draft = false

[taxonomies]
categories = ["Blogging", "Tutorial"]
tags = ["blogging", "projects", "jekyll"]
[extra]
toc = true
keywords = "Blogging, Markdown, Jekyll, Theme, Chirpy"
# thumbnail = "ferris-gesture.png"
+++

I don't know what it is about Dark Mode that makes website interfaces feel so... nice.

(UPDATE Dec 2022: This article relates to an old version of the blog. Check [the git repo](https://github.com/AverageHelper/averagehelper.github.io) for the detailed history.)

Just today, I re-did this blog in the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, and I must say the experience wasn't too bad. (Even better after I got rid of the Google Analytics stuff!) The old theme was called [Mediumish](https://www.wowthemes.net/mediumish-free-jekyll-template/), and it never quite suited me. Too many images for my liking. I just wanna write!

As for the change, you should only have noticed it if you somehow found my blog just days after my first post. (If you have, I'm sorry.)

## The Steps

The transition was really simple. Cotes Chung had a really nice [Tutorial (now on the Wayback Machine)](https://web.archive.org/web/20210614025935/https://chirpy.cotes.info/posts/getting-started/) on the subject. I modified his "Fork on GitHub" directions just a little to tweak the theme to my liking:

1. **I _downloaded_ the theme code**, instead of forking it. This is my blog, not a fork of a theme, so this seemed about as reasonable as installing the theme Gem (whatever that is)

2. **I copied my posts from my old branch.** You only need to do this if, before following Chung's directions, you practice writing a post that you actually want to publish it. The install script deletes the `_posts` directory and commits the change to Git. (I was much dismayed to have discovered this.) Luckily, I use Git. Torvalds would ~~not~~ be proud.

3. **I used my avatar in lieu of the default one** for obvious reasons.

4. **I converted most of the tabs to spaces** in the HTML templates. I could write a whole blog post on why, but that's a thing to be done another day. For now, refer to [this Reddit post](https://www.reddit.com/r/javascript/comments/c8drjo/nobody_talks_about_the_real_reason_to_use_tabs/).

This was a lot of fun! I might do this again one day. I credit the webpage design to the author of [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy). However, for the sake of maintenance, I'm strongly considering re-doing this site in [Vue](https://vuejs.org/). I don't know how that will work with Jekyll, or even if it will... I just think Vue is neat.

Here's to many bright adventures!
