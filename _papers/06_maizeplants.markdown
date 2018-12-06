---
title:  "Efficient and automatic reconstruction of maize plants (2016)"
teaser: "/img/teaser/BAHAMAS.png"
authors: "Simon Donne, Hiep Quang Luong, Bart Goossens, Stijn Dhondt, Nathalie Wuyts, Dirk Inze, Wilfried Philips"
comments: false
---

In order to efficiently study the impact of environmental changes, or the differences between various genotypes, large numbers of plants need to be measured. At the VIB (Flemish Institute for Biotechnological research), a system named PhenoVision was built to automatically image plants during their growth. This system is used to evaluate the impact of drought on different maize genotypes. To this end, we require 3D reconstructions of the maize plants. Over several submissions and presentations we outline how our system achieves this efficiently.

In the end we have a mix of careful calibration, machine learning for segmentation, voxel carving for rough cloud reconstruction, and subsequently a particle system for the leaf tracing and finally a bezier fitting to selected leaf candidates.
Over the fitted leaves, we also model their width.
In the end, we can automatically measure leaf lengths and areas for the plants, as fast as the PhenoVision system is able to image them.

[Abstract1](/papers/BAHAMAS_abstract_1.pdf)
[Poster1](/papers/BAHAMAS_poster_1.pdf)
[Abstract2](/papers/BAHAMAS_abstract_2.pdf)
[Poster2](/papers/BAHAMAS_poster_2.pdf)
[Poster3](/papers/BAHAMAS_poster_3.pdf)
[Video](/video/BAHAMAS.mp4)
