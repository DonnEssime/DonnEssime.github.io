---
title:  "Variational Multi-image Stereomatching (2015)"
teaser: "/img/teaser/multistereo.png"
authors: "Simon Donne, Bart Goossens, Jan Aelterman, Wilfried Philips"
comments: false
---

In two-view stereo matching, the disparity of occluded pixels cannot accurately be estimated directly: it needs to be inferred through, e.g., regularisation. When capturing scenes using a plenoptic camera or a camera dolly on a track, more than two input images are available, and - contrary to the two-view case -pixels in the central view will only very rarely be occluded in all of the other views. By explicitly handling occlusions, we can limit the depth estimation of a pixel to only use those cameras that actually observe it. We do this by extending variational stereo matching to multiple views, and by explicitly handling occlusion on a view-by-view basis. Resulting depth maps are illustrated to be sharper and less noisy than typical recent techniques working on light fields.

[Paper](/papers/multistereo_paper.pdf) [Poster](/papers/multistereo_poster.pdf)
