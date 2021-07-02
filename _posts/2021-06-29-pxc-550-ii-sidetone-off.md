---
title: 'Permanently turning off sidetone on the Sennheiser PXC 550 ii'
date: 2021-06-29
permalink: /posts/2021/06/pxc-550-ii-sidetone-off/
tags:
  - pxc 550 ii
  - sidetone
  - transparent hearing
  - call noise
---

The Sennheiser PXC 550 ii has a *"feature"* that turns on sidetone/transparent hearing when it detects the microphone being used, which for me basically means that I get to enjoy free (as in free beer) white noise without asking for it. Yay! Googling for fixes gave me lots of useless links, but there was one Reddit thread on the opposite fix (on how to boost sidetone). Thankfully it works to turn the goddamn thing off as well, so I wanted to put it up here and I pray that the SEO gods show this on your search front page.

[Here is a link](https://www.reddit.com/r/sennheiser/comments/jjy3hz/how_to_adjust_side_tone_effect_on_pxc550ii) to the Reddit thread if you'd like to follow it yourself. Sadly I could not find any references on adjusting sidetone with pipewire (on 0.3.31 right now), but hey, at least it works on Windows so I'm not complaining. The following worked for me:

* Connect the headphones to a Windows PC using USB
* Bottom bar: Right click on Sounds > Open Sound Settings
* Under Output, Headset Earphone (PXC 550-II) > Device properties
* On the right side, Related settings > Additional device properties
* Levels tab > Mute the sidetone slider

In particular, turning sidetone down to zero was not enough, and I had to mute it for the noise to vanish. Voila! A device that actually works.
