---
layout: post
title: Back in the CTFing of Things
excerpt: Getting back into CTFs again.
tags: ctf capture-the-flag security atom hydrogen
---

Last weekend, I jumped back on the [CTF](https://ctftime.org/event/846) bandwagon. Or, that is to say, I tried. Despite spending nearly every weekend of the first four months of the year cutting my teeth on any-and-all CTFs that I could find (climbing that steep, yet wonderful, beginner's learning curve), I have "struggled" to find any time for CTFing over the subsequent four months.

It might already be obvious from my first couple of posts (or moreso, from the ensuing absence of posts), that I tend to live my life in phases. The *CTF* phase at the start of the year (which itself followed *French* and *Long-Service-Leave* phases the year before), was interrupted by the *Need-to-Re-Certify* phase, and more recently by the *Brain-Dead-from-Work-so-Netflix-All-Night* phase. 

Living life in phases has its benefits. It's hard not to make some progress (particularly at the start) when you're driven by a singular focus to achieve something. However, in my experience, it's important that phases get re-visited within a certain amount of time, lest everything learnt from the previous cycle be completely forgotten. That is essentially what happened on the weekend.

So far removed have I been from the CTF scene, that I initially couldn't even manage to share folders between my Kali VM and host machine (I'd misplaced the desktop shortcut that makes it super easy), nor to log into the actual CTF website (the system clock on my VM was somehow 8 hours fast, screwing with the authentication process). Once I finally got into the CTF, things didn't improve. From being unable to derive anything useful in Wireshark to forgetting basic commands in Python, it wasn't pretty. I then proceeded to spend an inordinate amount of time (over 15 hours) on a single challenge, unsuccessfully, and as it turns [out](https://github.com/p4-team/ctf/tree/master/2019-09-07-trendmicro-quals/combo_100), not even making it half-way through. Sigh.

Anyway, the one silver lining from the weekend is that it has built up the hunger again. I've since spent the entire week, ensuring my CTF environment is ready for action. My VM now has an accurate clock, can share folders, and I've even managed to setup a remote Jupyter kernel on it that I can connect to via [Atom](https://atom.io/) (using the [Hydrogen](https://atom.io/packages/hydrogen) package) on my host. All systems are go. So this weekend, I'll try my hand at another online CTF, and the weekend after, my friends and I will be competing in an on-site one. I'm excited.
