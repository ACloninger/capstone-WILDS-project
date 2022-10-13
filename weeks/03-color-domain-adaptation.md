---
layout: week
title: Week 03
doodle: /doodle.png
---

# How do we transport distributions?
Refer to [this example](https://pythonot.github.io/auto_examples/domain-adaptation/plot_otda_color_images.html#sphx-glr-auto-examples-domain-adaptation-plot-otda-color-images-py) for image color shift.

## Tasks

Complete the following tasks:
* Download the code for image domain adaptation
* Take several photos yourself of the same or similar scenes
* Take similar photos in different lighting or with a filter on
** Make sure to have at least one photo from each group that's virtually identical except with different lighting/filter.
* Create a color shift between the virtually idential photos and examine the similarity between transfered photo and the original
* Randomly select a subset of the pixels across your pool of photos (and a different subset from the pool with different lighting) and perform transfer.
** Do you think you could have made a better / more representative selection than random?
* Exampime your new pool of photos after applying the color transfer.
* Try the same using different transport solvers (EMD, Sinkhorn, etc)

## Weekly Questions

Answer the following questions
1. Did the transferred photo pools appear how you'd expect?
2. What assumptions do you think we need on the two pools to have a successful color transfer?
3. How do you think the sampling of pixels affected the performance?

