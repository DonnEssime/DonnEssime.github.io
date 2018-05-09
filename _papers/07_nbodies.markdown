---
title:  "Efficient n-body simulations on multi-GPU systems (2016)"
teaser: "/img/teaser/nbody.png"
authors: "Simon Donne"
comments: false
---

At the HiPEAC Computing Systems Week in the fall of 2016, students from over the world were challenged to efficiently implement n-body system simulations. We chose to do this within the [Quasar](https://gepura.io) framework, which is a high-level language that automatically generates efficient CUDA code. At the time, Quasar had just gained the capability to coordinate multiple GPUs, and in this presentation we outline how to efficiently divide the large point clouds using octrees, and how to divide those efficiently over multiple GPUs.

[Presentation](/papers/nbody_presentation.pdf)
[Video](https://www.youtube.com/watch?time_continue=2&v=WSUpbq3RcJQ)
