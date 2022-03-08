---
title: "Resources I Used To Re-build My Hugo & Blogdown Website in 2022"
subtitle: ""
excerpt: "In this blog, I list out some great resources I came across when rebuidling my hugo website. "
author: Zhaoshan "Joshua" Duan
date: 2022-01-08
slug: []
categories: ['hugo','blogdown']
tags: []
---

In March 2021, I made a portfolio/blog site using `blogdown` with Hugo's [Toha](https://toha-guides.netlify.app/) theme since every Data Science *influencer* was telling me that such website is required to break into Data Science 🤷. I fast-foodized the process by getting the site up in less than 30 mins.

I didn't write as much as I wanted, and it was *obviously* the theme's fault. My lack of motivation had nothing to do with my [impostor syndrome](https://en.wikipedia.org/wiki/Impostor_syndrome) in the tech industry, anxiety of [Data Science career choices](https://towardsdatascience.com/why-you-should-consider-being-a-data-engineer-instead-of-a-data-scientist-2cf4e19dc019?gi=1bd3ea277ed8), and [existential crisis](https://yousefgh.medium.com/the-harsh-truth-about-data-science-5f1c2ce3554) of my identity in the American society. Switching to another theme would **surely** resolve all these problems and motivate me to write again...

![](https://media.giphy.com/media/xT9IgBwI5SLzZGV2PC/giphy.gif)

Well, it **didn't**, but it was a **pleasant distraction**. For this launch, I took my time and felt so *connected* to the `rstudio::blogdown` community. All of the wonderful resources have not only made this process fun, but motivated me to write again!

Hence, to self-congratulate the launching of my new site 🏆, in this first post, I would like to share some of the best resources I came across during the process. I will talk about: 

1.  [The Best Reading Material To Start With](#start)

2.  [Live Demos and Workshops If Reading Isn't Your Thing](#demo)

3.  [All About Hugo Themes](#theme)

4.  [Frequently Used Functions](#functions)

I hope this post would help those who are also interested in building their blog and portfolio website using Hugo and `blogdown`.  

Last Updated: January 15, 2022

![](https://media0.giphy.com/media/5zf2M4HgjjWszLd4a5/giphy.gif?cid=ecf05e47qc9pcmzsdy9e9imdvn6m64x1vuzh1bkes4nyxqn3&rid=giphy.gif&ct=g)

------------------------------------------------------------------------

## 1. Start with "*Up & running with blogdown in 2021"* by Alison Hill{#start}

I wish I discover this blog post sooner. [Dr. Alison Hill's](https://www.apreshill.com/) [blog post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/) is probably **the most updated** tutorial on this topic. It is easy to read and follow for those who have no backgrounds in web development (such as me), or relatively limited technical background in general (also me). You will most likely have your site up if you follow the post through.

The walk-through uses [Hugo Academic/Wowchemy](https://wowchemy.com/), a well-known, well-maintained Hugo theme that is suitable to most users' first experimental sites. I'll write about exploring other themes [later in this post](#theme). Her [blog](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/) also shared some other great blogs early on but I think these make more sense after you have *tried* to deploy your site. 

There can be a few hiccups with all the Git-related stuff. I found most of my answers from [Happy Git with R](http://happygitwithr.com/) by Jenny Bryan et al, or just Internet searches.

**Seriously, leave this post now and go to the Dr. Hill's [post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/)**. Come back when you have your beautiful site up and 
running! However, if you don't like reading, feel free to jump to [Live Demos](#demo). 

<img src="https://media3.giphy.com/media/WTph4QyrK6jKfo9tI4/giphy.gif?cid=ecf05e47rcb6j1ru6jmddgwqcjz5a3s9rnsv2t5lchacwldj&rid=giphy.gif&ct=g" width="250" height="250"/>

------------------------------------------------------------------------

## 2. Live Demos{#demo}

Live demos are great to watch, and even better *after* you have launched your site. You will not only learn about others' workflows, but also new practices that could solve a problem you are having. The majority of the live demos online can be in two categories: with or without `blogdown`. Of course there are a lot of other great live demos. I'm only listing the ones from which I learned the most. 

### `blogdown` Folks (HIGHLY RECOMMENDED)

Using `blogdown` makes things a lot easier if you are already using Rstudio and RMarkdown. It also saves you the trouble of using terminal directly. [CradletoGraveR](https://www.cradletograver.com/) has a 27 mins video walk through. It's a fast way to get a understanding of the process and set up your initial workflow.

<iframe width="600" height="300" src="https://www.youtube.com/embed/9Jqvaoeh1W4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[CradletoGraveR](https://www.cradletograver.com/) also has a series of videos and 


Professor [Emmanuel Teitelbaum](https://www.emmanuelteitelbaum.com/) gave a Hugo workshop to a group of his graduate students. This video is also great if you don't know the web development- and/or R-related jargon. 

<iframe width="600" height="300" src="https://www.youtube.com/embed/BHpkLJieXPE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>

Last but not least, since we already talked about Dr. Alison Hill's [blog post](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/), if you prefer to have herself demonstrated it to you, you can go to this workshop she gave during one of the [R-Ladies Tunisia](https://rladies.org/tunisia-rladies/) meeting on May 26, 2021.

<iframe width="600" height="300" src="https://www.youtube.com/embed/RksaNh5Ywbo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

------------------------------------------------------------------------

### Non-`blogdown` Folks :

My first site was actually set up without `blogdown`. I don't recommend this approach unless you have interests in web development. I am only recommending this video by [Ken Jee](https://www.kennethjee.com/) and [Data Professor](https://www.youtube.com/c/DataProfessor/about) for this section.

<iframe width="600" height="300" src="https://www.youtube.com/embed/mEZ1Hj5yQ-8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>

</iframe>

------------------------------------------------------------------------

At this point, you probably have already modified the `config.toml/yaml` file of your site, updated the information in various `index.md` and `_index.md`, cleaned out the exemplary files shipped with your *chosen* theme. But you want to make it more personal, you want to change to custom font you like, or even switch to another theme without starting over. Let's explore [themes](#theme)! 

## 3. All About Themes{#theme}

This section was going to be my main focus for this first blog.

Hugo's theme can be the make-or-break component of your first launch, and choosing a well-documented theme is key to the longevity of your website. This is why I recommended *Academy/Wowchemy* for your first experimental site in [Part 1](#start). 

Except *Academy/Wowchemy* and my current theme Hugo [Apero](https://hugo-apero-docs.netlify.app/start/), all of the other themes that I've experimented with were not well-documented. 




**Unsurprisingly**, during my first launch, my limited experience and Hugo's nested directory structure have made even the smallest customization quite difficult. 

Not to mention that Hugo site structures are heavily dependent on the theme you're using. 



### Customizing Themes

I have to give you one of my least favorite to a question but it's honest: it depends.

Hugo sites are heavily dependent on the theme structure. While there are

Therefore, it is *essential* that you pick a theme

### Switching Themes

Switching themes is actually easier than I thought. I spent a lot of time researching the heavily nested Hugo directory structure



## 4. Frequently `blogdown::` Functions {#functions}

Here I list out some of the functions I used, and a brief explanation for each

- `blogdown::server_site()`: For launching a local site in the Rstudio Viewer Pane.

- `blogdown::stop_server()`: 

- `blogdown::check_config()`: Whenever I modify the `config.toml` file, I run this to make sure all changes are getting through.

- `usethis::browse_github()`


