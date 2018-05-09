---
title:  "Line-constrained camera location estimation in multi-image stereomatching (2017)"
teaser: "/img/teaser/multistereo_positions.png"
authors: "Simon Donne, Bart Goossens, Wilfried Philips"
comments: false
---


Stereomatching is an effective way of acquiring dense depth information from a scene when active measurements are not possible. So-called lightfield methods take a snapshot from many camera locations along a defined trajectory (usually uniformly linear or on a regular grid-we will assume a linear trajectory) and use this information to compute accurate depth estimates. However, they require the locations for each of the snapshots to be known: the disparity of an object between images is related to both the distance of the camera to the object and the distance between the camera positions for both images. Existing solutions use sparse feature matching for camera location estimation. In this paper, we propose a novel method that uses dense correspondences to do the same, leveraging an existing depth estimation framework to also yield the camera locations along the line. We illustrate the effectiveness of the proposed technique for camera location estimation both visually for the rectification of epipolar plane images and quantitatively with its effect on the resulting depth estimation. Our proposed approach yields a valid alternative for sparse techniques, while still being executed in a reasonable time on a graphics card due to its highly parallelizable nature.

[Paper](/papers/multistereo_positions.pdf)
