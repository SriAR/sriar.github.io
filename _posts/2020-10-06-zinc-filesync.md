---
title: 'Zinc - A Custom Filesyncer'
date: 2021-10-06
permalink: /posts/2021/10/zinc-filesync/
tags:
  - linux
  - zinc
  - dotfiles
---

The problem I had was this: I had to download all the books/papers I needed for my coursework/research work three times, once on my laptop, once on my iPad, and for the times when I cannot carry either along, on my phone. Maybe a fourth time if I was in the computer lab at CMI. This was fucking annoying. Who would want to search online for the same paper four times.

Now you might say, "Well isn't that what Google Drive is for?". True, but I would like to also read my pdfs on zathura on my laptop, iBooks on my iPad, and Moon+ on my phone. If I am using a free cloud solution available online, I would have to resort to using their pdf viewers for convenience. Why would you take the easy way out when you can create your solution by case-#!/bin/bash™ing. [zinc](https://github.com/SriAR/dotfiles/blob/master/bin/zinc), an rsync based script to sync pdfs between all your devices! It uses your university-provided space as a pseudo cloud storage (so you'd need an always on storage with ssh capabilities).

