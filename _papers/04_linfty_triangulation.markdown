---
title:  "Point triangulation through polyhedron collapse using the l-infinity norm (2015)"
teaser: "/img/teaser/linfty_triangulation.png"
authors: "Simon Donne, Bart Goossens, Wilfried Philips"
comments: false
---

Multi-camera triangulation of feature points based on a minimisation of the overall L2 reprojection error can get stuck in suboptimal local minima or require slow global optimisation. For this reason, researchers have proposed optimising the L-infinity norm of the L2 single view reprojection errors, which avoids the problem of local minima entirely. In this paper we present a novel method for L-infinity triangulation that minimizes the L-infinity norm of the L-infinity reprojection errors: this apparently small difference leads to a much faster but equally accurate solution which is related to the MLE under the assumption of uniform noise. The proposed method adopts a new optimisation strategy based on solving simple quadratic equations. This stands in contrast with the fastest existing methods, which solve a sequence of more complex auxiliary Linear Programming or Second Order Cone Problems. The proposed algorithm performs well: for triangulation, it achieves the same accuracy as existing techniques while executing faster and being straightforward to implement.

[Paper](/papers/linfty_triangulation.pdf) [(supp.)](/papers/linfty_triangulation_supp.pdf) [Poster](/papers/linfty_triangulation_poster.pdf)
