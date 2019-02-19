---
layout: default
title: Let's Start This Thing
tags: [github.io, programming, aboutme]
excerpt_separator: <!--more-->
---

I have always had trouble keeping up with projects. Mostly because I get very into them and work hard on them for many hours.
After a couple days of this, however, I have to take a break and when I come back to it I have no idea where I was.
I also tend to have way to many project going on at once that never get finished because who in their right mind actually finishes
any program.<br>
So introducing Webtron Project Tracker (WIP)<!--more-->

Any I am hoping that by 'blogging' (it sounds very hipster out loud) I can use this as a means to track changes to my projects I make
with code updates and with commentary so it will be easier to pick back up after a break.

First step is to get a simple site going. Luckily I started this project a long time ago with GitHub.IO. Time to resurrect it.
I also need some format, but I do not want to put more than 60 seconds into it. Keeps me from going down that rabbit hole of
"What's the best way of categorizing, sub-categorizing, tagging, future proofing, etc., etc., etc.".Thinking about starting off like the below at the start of each post. Should create a proejct list or trackers of some kind with GitHub badges.
<hr>
**Project:** github.io

**TODO:**

  - [x] Get Ubuntu dusted off
  - [x] Clone GIT
  - [x] Learn how to use Jekyll
  - [x] Update site data
  - [x] Learn Markdown (yes, I know)
  - [x] Publish page
  - [x] Publish first post
  - [ ] Plan next post

**Status:** <span style='color:green;'><b>In-Progress (88%)</b></span>
<hr>
### Dust off Ubuntu
Done, running Ubuntu 18.10 because I like GNOME.
Running on custom desktop once used for gaming.
<br>Specs FWIW: <br>
**RAM**: 16GB <br>
**CPU**: Intel Core i5-4400 (ya, it's old and I am broke)<br>
**OS**: Ubuntu 18.10 GNOME 3.30.1 64bit<br>
**DISK**: 1TB main, 3TB data, 500GB SSD (Windows, you know for photography)<br>
**GPU**: NVIDIA 730ti something<br>
<hr>
### Clone Git
Since I did a fresh install I needed to download it and configure it.

```
sudo apt install git -y
```

Create Project folder in home and clone this repo

```
cd ~
mkdir Projects
cd Projects
git clone https://github.com/Webtron18/webtron18.github.io.git
```
Voila!

Refresh sheet on Git:
Set the username: ```git config –global user.name```

Set the user email: ```git config –global user.email```

Retrieve the most recent changes from origin and merge: ```git pull```

Add file changes to staging: ```git add (file name or . for all)```

Commit changes along with a custom message: ```git commit -m "(message)"```

[Link: ](https://www.keycdn.com/blog/git-cheat-sheet)

*First commit from Ubuntu!*

### Learn How to Use Jekyll
Done, not much to say but here is the [link](https://jekyllrb.com/docs/)

### Update Site data
Changes the Title (still work in progress)<br>
Also, changed the excerpt of the page. Needs lots of thought behind it.

<hr>
### Learn Markdown

Useful cheat sheet:
[Link to Cheatsheet](https://help.github.com/articles/basic-writing-and-formatting-syntax/#styling-text)

### Publish the Site
This was technically done and already running, but I publicly humiliated myself by posting it publicly.

### Publish First post
I guess that would be this one.

### Plan Next Post
**Ideas:**
 - Github Refresher
  - Branches and pull-requests
 - Finish Resume post
 - Clean-up Github Site
  - Remove old repos
  - Update stale ones
  - Figure out the badge things
 - Project Tracker actualy project tracking
  - List of some kind
  - Last updates
 - Jekyll
  - Templates
  - extras
  - downloads in posts
