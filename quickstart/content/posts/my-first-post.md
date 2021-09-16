+++ 
draft = false
date = 2021-09-14T09:45:55-07:00
title = "My First Post"
description = "reinforcing knowledge and skills around static sites"
slug = ""
authors = ["Abhijit Khanna"]
tags = []
categories = []
externalLink = ""
series = []
+++

Find your why

Just to provide a little background on this, I'm going through this exercise, specifically working on a static site blog via Hugo and Netlify, under the recommendation of Ben W (https://bennotes.com/developer_projects_1/). I had reached out to Ben a few weeks ago to discuss some discomfort I was having in my career - I've basically been questioning my chops as a developer. I may flesh this out in a background page, but the TLDR is that I started out with a CS degree, had technical jobs for the first couple of years of my career, then pivoted into IT Audit. After a few years of that, I got my MBA to pursue my interest in sustainability. As these things sometimes go, I wasn't able to make that transition, and fell into various analyst roles in order to eat. But I had always tried to use my tech skills, and post-grad school was going to a lot of meetups in the DC area. I decided I wanted to move back into tech for various reasons, though the ecosystem had changed significantly since I was in school (think pre-React).So I took my current job as a starter job, with the intent of getting to see what it is to be a modern software developer. After 3 years, I find myself questioning if I have achieved that goal I set out for. I wanted to talk to an unaffiliated person in tech with no real vested interest in me, and thus the ability to provide me the unvarnished truth. We had a good conversation, and Ben told me my feelings of impostor syndrome are not uncommon, and that he had experienced this himself. He had some concrete ideas on things I could do to get some confidence in my abilities.

So here we are. I'll confess, that I'm not always comfortable putting my thoughts out there for strangers to read. But I'm pushing myself to do so in the hopes that others who have been having (or will have) similar thoughts and doubts may find it helpful to see that they are not the only one.

Here are the challenges I ran into getting this far:

Using the Hugo QuickStart instructions (https://gohugo.io/getting-started/quick-start/), one of my first challenges was Step 3, adding a theme. I got a non-descript error (unmarshal failed: toml: expected theme to be a table, not a value). As is typically the case, it was user error. I a) hadn't changed the theme value appropriately for the theme I chose (used 'coder' vs. 'hugo-coder'). After correcting this, I was still seeing an error, and slowly realized that I hadn't noticed there was an argument to the command, that also required the theme name.

Once I got that working, I was able to run the command to run the server, and I could see the site was up, though it wasn't what I was expecting based on my modifications to the my-first-post.md file. Eventually, I realized that I needed to navigate to the subdirectory 'posts' to see my content. This wasn't intuitive - for some reason I don't see the directory structure on my main page. Something to work on in the near future. I did find this tutorial on YouTube that based on the limited amount of use thus far has seemed pretty useful (https://www.youtube.com/watch?v=0GZxidrlaRM&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3&index=6). 

So my next steps are to try to deploy via Netlify, after I verify that this content is displaying. And probably pretty up my markdown.

In closing, I'll say it was all in all satisfying being able to figure out this stuff on my own, even if I had to pause a day to give my brain time to reset and subconsciously marinate. 
Another thing I'm observing is how quickly I forget vim commands without regular use of vi editor.
