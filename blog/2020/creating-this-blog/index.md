---
title: Creating this blog
description: Why should I write this blog? - A GitHub page for my blog
---

## Why should I write this blog?

As a developer I've learned how important it is 
- to stay focused on my (or my companies) goals
- to frequently recap what I've done and how succesful it was
- to see and remember the progress and not only what's missing
- and to keep the balance between great ideas and concepts on one side and the ability to react to upcoming needs on the other side

So a great part of this work is just thinking and making decisions. And that's one reason to write this blog: **to keep myself on this road**.

And another important reason is my hope that this blog will one day **help others on their way**. Today there is so much free content in the internet and such a great community sharing it. This makes learning and development available for everybody. I benefit from this since years.  

## A GitHub page for my blog

To keep things easy I decided to use [GitHub Pages](https://pages.github.com) for this blog. I created a new git repository on GitHub and choose the main branch as page source and the [cayman theme](https://github.com/pages-themes/cayman) as Jekyll theme. All this can be done in the *Settings / Github Pages* section of the repository.

In this repository I created a directory structure for my future posts and made my adaptations in the *index.md* (as the home page of the blog) and *_config.yml* (the theme configuration). For layout customization I copied the *_layouts/default.html* from the [origin theme repository](https://github.com/pages-themes/cayman) into my repository and made my (minor) changes.

So I could create my first post (*\*.md*) and reference it in my home page of the blog (*index.md*). The posts are written in the markdown syntax of the github platform. You can find a short markdown guide [here](https://guides.github.com/features/mastering-markdown/).

When I began to fill my first post with content I changed my procedure. Before that moment I did all editing via browser in the GitHub web site. But then I changed to my local computer. I used my *Git Bash* to clone the repository and made my editing locally with *Visual Studio Code*. There is a very nice extension called *Markdown All in One* which helps you writing pages in the markdown syntax. Now - when ready for publishing - I only have to push my content to the origin repository. The page updates automatically.


