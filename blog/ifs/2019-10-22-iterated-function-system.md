---
title: 'Iterated Function Systems in finite state Markov Chains'
date: 2019-10-22
permalink: /posts/2019/10/iterated-function-system/
tags:
  - math
  - probability
  - stochastic
---

Hey! So there is this interesting problem that was an exercise in my Stochastic Processes course, and I thought it would be nice to share it here.

Consider a finite set $S$ and finitely many functions $ \{ f_i : 1 \le i \le k \} $ from $S$ to $S$ and a probability vector $ (p_i : 1 \le i \le k) $. Here is a Markov Chain with state space $S$. If you are at a $s$, select one of the functions using the probability vector. New state is value of the selected function at $s$. This is called Iterated Function System IFS for short. Show that we do indeed have a Markov chain. What is its transition Matrix?

Conversely, show that given any transition matrix $P$ you can produce an IFS (i.e. finitely many functions) which give back your Markov chain with transition matrix $P$.

The forward direction is fairly straightforward (heh), but how do you do the other direction? I'll write up my solution here eventually, but you can find [my approach here](https://sriar.github.io/files/SP1_IFS.pdf).
