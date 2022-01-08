---
title: "Resources I Used To Re-build My Hugo & Blogdown Website in 2021"
subtitle: ""
excerpt: "In this blog, I list out some great resources I came across when rebuidling my hugo website. "
author: Zhaoshan Duan
date: 2021-11-22
slug: []
categories: ['hugo','blogdown']
tags: []
---

In March 2021, I made a Portfolio and Blog site using `blogdown` with Hugo's [Toha](https://toha-guides.netlify.app/) theme since everybody and their grandmothers told me you need a portfolio website to break into Data Science 🤷. I fast-foodized the process by getting the site up and running as soon as possible (in less than 30 mins).

I didn't write nearly as much as I wanted, and it was *obviously* the theme's fault. My lack of motivation had nothing to do with my [impostor syndrome](https://en.wikipedia.org/wiki/Impostor_syndrome), anxiety of [Data Science career choices](https://towardsdatascience.com/why-you-should-consider-being-a-data-engineer-instead-of-a-data-scientist-2cf4e19dc019?gi=1bd3ea277ed8), and existential crisis of whether this field is really for me :weary:.

Switching to another theme would **surely** solve all of my problems and motivates me to write again?

![](https://media.giphy.com/media/xT9IgBwI5SLzZGV2PC/giphy.gif)

Well, it **didn't**, but it was a **pleasant distraction**. I took my time this time, and I didn't expect to feel so *connected* to the `rstudio::blogdown` community. All of the wonderful resources have not only made this process fun, but also motivated me to write again! 😳

Hence, to self-congratulate the launching of my new site 🏆, in this first post, I would like to share the best resources I came across on this subject. I will talk about the following topics: 

1.  [What You Should Read to Start](#start)

2.  [Good Live Demos if Reading Isn't Your Thing](#demo)

3.  [Switching Up Hugo Theme](#theme)

4.  [Frequently Used Functions](#functions)

Hopefully this post could help those who want to experiment building portfolio and blogging website. 

Last Updated: November 22, 2021

![](https://media0.giphy.com/media/5zf2M4HgjjWszLd4a5/giphy.gif?cid=ecf05e47qc9pcmzsdy9e9imdvn6m64x1vuzh1bkes4nyxqn3&rid=giphy.gif&ct=g)

------------------------------------------------------------------------

# 1. Start with "*Up & running with blogdown in 2021"* by Alison Hill{#start}

Dr Hill's [blog post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/) is probably **the most updated**, **easy-to-read-and-follow material** on this topic. I only wish I knew about this blog post earlier. You will most likely have your site up if you follow it through.

The [post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/) shared some other great blogs early on but I think these make more sense after you have at least *tried* to deploy your site. 

The post also uses [Hugo Academic/Wowchemy](https://wowchemy.com/), a well-known, well-maintained Hugo theme. Hugo's theme can be the make-or-break component to your website, and it can get quite complicated. I found it to be a good first theme to experiment. I recommend exploring other themes *after* you have the site up. I will talk about switching themes [later](#theme).

There can be a few hiccups with all the Git-related stuff. I found most of my answers from [Happy Git with R](http://happygitwithr.com/) by Jenny Bryan et al, or just Internet searches.

**Seriously, leave this post now and go to the Dr. Hill's [post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/)**. Come back after you have your beautiful site up and running ! But if you don't like reading, feel free to jump to [Live Demos](#demo)

------------------------------------------------------------------------

*Welcome back!* Wasn't that a great read ?! 

Now we could be saying goodbye from here 😿. If you already have your site up and want to explore other themes, [click  here](#theme) where I talk about switching up your themes *somewhat* painlessly. Or, riding on the excitement of launching your own site, start writing your first blog just like what I'm doing right now !

# 2. Good Live Demos{#demo}

![](https://media3.giphy.com/media/WTph4QyrK6jKfo9tI4/giphy.gif?cid=ecf05e47rcb6j1ru6jmddgwqcjz5a3s9rnsv2t5lchacwldj&rid=giphy.gif&ct=g)

Live demos are great to watch, and even better *after* you have your site launched. You not only learn about others' experiences, and workflows, but also new practices that could potentially solve a problem you are facing.

There are a lot of live demos out there. I found they are primarily in two categories on this topic: with or without `blogdown`. Here I will list three vidoes that I found the most useful. 

## `blogdown` Folks (HIGHLY RECOMMENDED)

Using `blogdown` makes things a lot easier if you are already using Rstudio and RMarkdown. 

If you don't want to read Dr. Alison Hill's [blog post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/), and prefer to have herself demonstrated it to you, you can go to this workshop she gave during one of the [R-Ladies Tunisia](https://rladies.org/tunisia-rladies/) meeting on May 31, 2021. 

<iframe width="600" height="300" src="https://www.youtube.com/embed/RksaNh5Ywbo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Professor [Emmanuel Teitelbaum's](https://www.emmanuelteitelbaum.com/) workshop is great if you don't know the web development- and/or R-related jargon. 

<iframe width="600" height="300" src="https://www.youtube.com/embed/BHpkLJieXPE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

----

## Non-`blogdown` Folks :

I actually set up my first site without `blogdown`. I don't recommend this method unless you have interest in web development. Unsurprisingly, my limited web dev experience and Hugo's nested directory structure have made even the smallest changes to the site quite difficult. Not to mention that Hugo site structures are heavily dependent on the theme you're using.

With that being said, I recommend this video by Ken Jee and Data Professor.

<iframe width="600" height="300" src="https://www.youtube.com/embed/mEZ1Hj5yQ-8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# 3. Switching themes{#theme}

At this point, you probably already modified the `config.toml/yaml` file of your site. 

This section was going to be my main focus for this post. 


Switching themes is actually easier than I thought. I spent a lot of time researching the heavily nested Hugo directory structure


# 4. Frequently `blogdown::` Functions {#functions}

Here I list out some of the functions I used, and a brief explanation for each

- `blogdown::server_site()`: For launching a local site in the Rstudio Viewer Pane. 
- `blogdown::stop_server()`: 

- `blogdown::check_config()`: Whenever I modify the `config.toml` file, I run this to make sure all changes are getting through. 

- `usethis::browse_github()`
