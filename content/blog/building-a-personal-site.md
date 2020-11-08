---
title: "Building a Personal Site"
date: 2020-11-08T17:22:03+01:00
draft: true

# meta description
description: "this is meta description"
image: "img/build-personal-blog/BUILDING-A-WEBSITE-FOR-YOUR-BUSINESS.jpg"
# type
type : "post"
---
Building a personal website is something I’ve wanted to do for quite some time. I’ve always seen people around my age and level of experience launch exciting brand pages and I wanted something similar. The first thing I considered was what kind of website I wanted to build.

![image](../../img/build-personal-blog/static_vs_dynamic_website.jpg)

The first option was to build a static website. These are usually used by small business with little products catalogues and prices that don’t change too frequently. They are relatively much easier to build but lack the flair attached to modern websites.

The second option was a dynamic website. These are websites that change often and are usually different each time a user visits. They usually perform some form of server-side rendering where they pull data from a database or storage system of some sort. Then they organize the data into a presentable fashion before the webpage gets sent to the user’s computer for rendering. A prime example would be something such as twitter or the CNN website. I wanted my website to have a section that would serve as my personal stash for information and ideas and thoughts I have throughout the day aka I wanted a blog.

![image](../../img/build-personal-blog/800px-Scheme_dynamic_page_en.svg.png)


A static website usually requires less work to setup and manage than a dynamic website. However, it would be difficult to manage a blog like structure if I had to build each page manually each time I needed to add or edit a post. I decided to take a look at static website generators to help automate the build process for me. After what I must admit was very little research, I decided to build my website using the static generator Hugo. According to the authors, Hugo is a fast and modern static site generator written in Go, and designed to make website creation fun again. In technical terms, Hugo takes a source directory of files and templates and uses these as input to create a complete website. Hugo sites run without the need for a database or dependencies on expensive runtimes like Ruby, Python, or PHP which proved to be very useful when it came time to finding a hosting solution for the project.

![image](../../img/build-personal-blog/hugo.png)

The next thing I had to decide on was a hosting platform. Here, I was bombarded by a plethora of hosting services. I finally settled on GitHub because first, the price was really convincing (its free). In my industry GitHub is kind of our version of LinkedIn. Ever developer has some sort of presence on GitHub and as a result having a sub domain with GitHub in the name didn’t give off a feeling of being cheap or unfinished to the website.

Another alluring feature is the website was hosted directly from my GitHub repository. Just edit, push, and your changes are live. This saves a lot of time as I don’t have to worry about redeploying my site after every change GitHub takes care of that for me.

Of course, using GitHub wasn’t without its challenges. Firstly, the platform has no server-side rendering capacities whatsoever. The pages hosted on it service had to be html, CSS and JS only. Luckily, I had already decided to create a static webpage with no need for server side rendering whatsoever thanks to Hugo.
