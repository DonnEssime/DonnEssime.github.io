---
title:  "On-line Non-Rigid Structure-from-Motion with keyframes (2014)"
teaser: "/img/teaser/ONRSFM.png"
authors: "Simon Donne, Ljubomir Jovanov, Bart Goossens, Wilfried Philips, Aleksandra Pizurica"
comments: false
---

When we wish to apply non-rigid structure-from-motion to on-line video sequences, in which we need to learn the shape basis on the fly, then pre-existing techniques break down. They estimate the shape basis from a large video in one go, and it is not immediately obvious how to compact an existing video in order to enable much more efficient estimation of the shape basis (after which incoming frames can be processed one-by-one).
In this work we outline an approach that compacts all previously seen frames into a small keyframe set, bridging the gaps between existing techniques and on-line/real-time processing.

[Paper](/papers/onrsfm.pdf)
