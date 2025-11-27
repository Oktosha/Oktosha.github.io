---
layout: post
title:  "Mansonry wall demo"
date:   2025-10-07 20:05:29 +0100
---

*project repo: [github.com/Oktosha/bricks](https://github.com/Oktosha/bricks)*

In spring 2025 I built a visualisation of building a masonry wall as a home assignment for an interview to [Monumental](https://www.monumental.co). I failed later stages of the interview process but I'm still very happy with what I built.

The visualisation had to show how a robot would lay out bricks for different types of bonds: stretcher bond, English Cross bond, Flemish bond, wild bond.

![pictures demonstrating different types of mansonry bond](/assets/2025-10-07-mansonry-wall/types-of-bond.png)

The robot has a working window within which it can reach the wall. The order of laying the bricks should minimise the amount of movements the robot has to do.

![screenshot of the visualisation](/assets/2025-10-07-mansonry-wall/basic-usage.png)

I came up with the algorithm for the robot to decide the order of laying the bricks and built the visualisation. When you run the visualisation hitting `enter` lays a brick and hitting `backspace` goes a step back. You can download and run it: [github.com/Oktosha/bricks](https://github.com/Oktosha/bricks). All the instructions on running and using the visualisation are in README in the repo.
