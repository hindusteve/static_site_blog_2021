+++ 
draft = true
date = 2021-09-16T12:29:47-07:00
title = "Welcome to Git Hell"
description = "documenting my (mis) adventures in trying to set up a GitHub repo"
slug = ""
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++

You live, you learn

What an unexpected day. I woke up thinking, I'll head to a coffeeshop, resolve setting up a GitHub repo to track my changes on this project. Then I'll be able to deploy via Netlify, and maybe even get a start on the Django tutorial. Easy, right? What's that saying about the best laid plans? I pretty much spent 3 hours trying to resolve my Git issues. It started yesterday when I did a quick search on how to set up a GitHub repo from code that already exists on my local. I'm not sure if it is unclear documentation or user error - the command provided for git init utilizes a -b option, and when I tried to run that, it was unrecognized. I looked at help documentation, and saw there was a --b, so thought, hey, maybe that's what it is supposed to be. Little did I know I was creating a bare repository, which essentially means no working tree, and thus no ability to use git add/git status/git branch commands. And the funny thing is, 24 hours ago, I didn't even know what a bare repository or no working tree is. 

So there is that truism that I always forget and get frustrated by, that sometimes you just learn by doing, and probably more so by failing. This is the kind of thing that makes me question my developer skills. I feel like I've been using GitHub and git on and off for 3-4 years, yet I'm still making mistakes like this. On the other hand, I do feel some pride that I was able to suss through the various stackoverflow posts and other resources and figure out how to resolve it (ultimately, I removed the .git files, did a reinitialization w/o any parameters, and then used the commands under quickstart). So I think I'm rolling now, and will grab a quick bite, and maybe attempt to do the netlify deployment this evening. I probably should go into greater detail as to the errors, iterations and resolutions  for this to be useful to someone else or me in the future, but I honestly want a mental break (and food).

Also, I'm rarely accused of not being detailed enough.

I also noticed that, one of my attempted resolutions was to try to copy the files to another directory, delete the original directory, and rename the new directory back to the original directory name. As expected, the Hugo server kept trying to rebuild as I made changes, but some of my changes resulted in an error, and now I am not sure how to stop that server running, short of restarting the machine. I opened a new terminal and re-ran the commands to start the Hugo server, but since the 1313 port was already allocated, it defaulted to another one (in the grand scheme of things, not a big deal). But I do need to figure out why I can't just CTRL + C to kill the original server.
