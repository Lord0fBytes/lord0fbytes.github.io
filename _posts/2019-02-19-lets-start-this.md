---
layout: default
title: Let's Start This Thing
---

## Where do I begin?
I have always had trouble keeping up with projects. Mostly because I get very into them and work hard on them for many hours.
After a couple days of this, however, I have to take a break and when I come back to it I have no idea where I was.
I also tend to have way to many project going on at once that never get finished because who in their right mind actually finishes
any program.

Any I am hoping that by 'blogging' (it sounds very hipster out loud) I can use this as a means to track changes to my projects I make
with code updates and with commentary so it will be easier to pick back up after a break.

First step is to get a simple site going. Luckily I started this project a long time ago with GitHub.IO. Time to resurrect it.
I also need some format, but I do not want to put more than 60 seconds into it. Keeps me from going down that rabbit hole of
"What's the best way of categorizing, sub-categorizing, tagging, future proofing, etc., etc., etc.".
<br>
So, format is (obviously a WIP):
<br>
**Project:** github.io

**TODO:**

  - [ ] Get Ubuntu dusted off
  - [ ] Clone GIT
  - [ ] Learn how to use Jekyll
  - [ ] Update site data
  - [ ] Learn Markdown (yes, I know)
  - [ ] Publish page
  - [ ] Publish first post
  - [ ] Plan next post

**Status:** In-Progress
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

Link: https://www.keycdn.com/blog/git-cheat-sheet

*First commit from Ubuntu!*

### Learn Markdown

Useful cheat sheet:
