---
title:  "Exploiting Reflectional and Rotational Equivariance in Single Image Superresolution (2017)"
teaser: "/img/teaser/SISR_equivariance.png"
authors: "Simon Donne, Laurens Meeus, Hiep Quang Luong, Bart Goossens, Wilfried Philips"
comments: false
---

Stationarity of reconstruction problems is the crux to enabling convolutional neural networks for many image processing tasks: the output estimate for a pixel is generally not dependent on its location within the image but only on its immediate neighbourhood. We expect other invariances, too. For most pixel-processing tasks, rigid transformations should commute with the processing: a rigid transformation of the input should result in that same transformation of the output. In existing literature this is taken into account indirectly by augmenting the training set: reflected and rotated versions of the inputs are also fed to the network when optimizing the network weights. In contrast, we enforce this invariance through the network design. Because of the encompassing nature of the proposed architecture, it can directly enhance existing CNN-based algorithms. We show how it can be applied to SRCNN and FSRCNN both, speeding up convergence in the initial training phase, and improving performance both for pretrained weights and after finetuning.

[Paper](/papers/SISR_equivariance.pdf)
