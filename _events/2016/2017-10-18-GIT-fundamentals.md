---
layout: event
title:  "GIT fundamentals"
meetingDate:  2017-10-24
meetingPlace: Davis, Downtown
instructor: Lukas Hejtmanek
category: upcoming
img: 2017/git-fundamentals-davis.png
tagged: git
calendar: https://calendar.google.com/calendar/event?action=TEMPLATE&tmeid=MzFmZjVhYjF1djZ1dmIzNXZjaHY5amhjdmUgbzQwNXU4anZsNTA0MGhvNXB1cWQ1MWMzOGtAZw&tmsrc=o405u8jvl5040ho5puqd51c38k%40group.calendar.google.coms
iteration: 1
---
This seminar will teach you basics of GIT hands on. Git is a distributed version control system which is widely used in all software development areas (e.g. Linux is sourced in GIT). It allows you to track changes, save and load code in certain positions, safely test new ideas etc.

## What we will do
1. Basics - staging, commiting, pushing, pulling, branching
2. Saving our butts - reset, remove, checkout, rewinding history

Despite git having few useful and neat GUI to work with, we will be doing EVERYTHING in bash. So prepare mentally you might need to write some commands into your command prompts :) There are reasons why I think this approach is necessary. 

Besides these skills, we should talk about conventions, how often commits shoudl happen, what are good practices etc. We will work on examples in R. I expect you to know R so that you can write your own functions and do some basic stats and graphs. 

## What to do in advance?
-----------
Firstly, you will need your own laptop to run things we will do. So bring those and have them ready by following steps bellow:

1. Download git from https://git-scm.com/ or using Linux command line.

2. Check if it's working by opening the git command line and running following commands

``` shell
cd #path - use cd command to get to the path you want to start the repository at
mkdir git-test
cd git-test
git init
touch file.txt
git status
git add --all
git commit -m "Initial commit"
git log
```

## Important

Although You don't need any repository account to run git, You will eventually want to "save" your progress online and share it with people. You will need an account for that. Possibilities include:

- [GitHub](https://github.com/)
- [BitBucket](https://bitbucket.com/)
- [GitLab](https://gitlab.com/)

Alternatively you can run your own git server somewhere on Azure, AWS or Google cloud, but I'd strongly recommend you to start with one of the above solutions. They are free and quite popular. I'll be using github for everything, because it is simply the closest one (based in SF).
