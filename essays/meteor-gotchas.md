---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

Meteor is not the best JavaScript framework out there. My biggest problem with Meteor is its lack of cross-platform support. At the time of writing, Windows is not supported by Meteor. You can argue that it is, because they have an installation executable file available for  download. But this is misleading. When I tried to use the installer, I encounted two problems:
1) The environment path variables were set incorrectly.
2) Connection to Meteor repository failed for whatever reason, so the actual download didn't initiate. But even so, when the installer finished it displayed no errors at all, and the application was listed in Window's Programs and Features yet still set wrong path variables.

Here's how I fixed these two problems:
1) I manually reconfigured the path variables to work with Windows. It turned out that there was an extraneous slash in the path.
2) I waited until the next day, by which the download started working again.

At this point it was already bad as it is- but when I got into the actual development process with Meteor, more problems occurred. Meteor was using an older version of 7zip and tar and was having trouble extracting its package files.. I had to spend hours on StackOverflow to find a solution to this problem. Even so, it was a leaking bandage and not a real solution to its fundamental lack of support for Windows.
