---
title:  "Fast and Robust Optical Flow for High-Resolution images using SLIC Superpixels (2015)"
teaser: "/img/teaser/highres_OF.png"
authors: "Simon Donne, Jan Aelterman, Bart Goossens, Wilfried Philips"
comments: false
---

We show how pixel-based methods can be applied to a sparse image representation resulting from a superpixel segmentation. On this sparse image representation we only estimate a single motion vector per superpixel, without working on the full-resolution image. This allows the accelerated processing of high-resolution content with existing methods. The use of superpixels in optical flow estimation was studied before, but existing methods typically estimate a dense optical flow field -- one motion vector per pixel -- using the full-resolution input, which can be slow. Our novel approach offers important speed-ups compared to dense pixel-based methods, without significant loss of accuracy.

[Paper](/papers/highres_OF.pdf)
