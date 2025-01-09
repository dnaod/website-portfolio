---
title: "Rocket Builds"
date: 2010-01-10
featured: true
description: "We created Rocket Gaming Systems first automated build system for 144 build targets and reduced the total build time from a week to just under 36 hours."
tags: ["Jenkins","Ant/Nant","distributed computing"]
image: ""
link: ""
fact: "I don't think this property ever displays.  If a reader sees it, please let me know!"
weight: 500
sitemap:
  priority : 0.8
---
At Rocket, I was selected to start a new Software Configuration Management department, picking or hiring the members, and strengthening our engineering practices across all teams.  Growing the team to 4 members, we focused on the areas of build management, branch management, version management, and release management.  Our achievements included:
- Wrangling multiple branches of source code across multiple teams with varying feature sets into a single, organized set of branches representing our software lifecycle process stages.
- Creating a TeamCity QuickBuild (and then Jenkins) -based distributed build system with spare hardware to reduce the 144 target total build time for all components from a week to 36 hours.
- Engaging with Development teams and creating documentation for training and standards of build system standards, and contracts aligning all teams to use the automated build systems, versioning systems, and processes surrounding branching and merging.

As our processes matured, I also took on team management of a new Lua script-based test automation team that was reducing testing effort and testing timelines as our games library scaled.  When ready for prime-time, the new test automation platform was integrated into the automated build and reporting system.  This reduced the amount of time for autoamted testing results to be delivered to the teams, and decreased the number of errors that were deployed to production.

![Build Stack Technology Responsibilities block diagram](/img/Build_Stack_Technology_Responsibilities.png)
