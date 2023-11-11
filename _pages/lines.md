---
title: "Research lines"
permalink: /lines/
date: 2023-11-12T11:48:41+01:00
defaults:
  # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: false # true
---

## Generative Adversarial Networks for the improvement of astronomical image.

This research line is currently addressing state of the art GAN architectures in the following cases.

### VIRTIS-M images

![image-center](/assets/images/lines/gan_virtis_1.jpg){: .align-center}
Generative networks to improve S/N ratio in Venus Express VIRTIS-M images. Lower exposure times are used to generate examples of images, base truth are images with higher exposure times and S/N ratio.

## Anomaly detection in galaxy images using GAN and Variational Autoencoders

![image-center](/assets/images/lines/anomaly_det_2.jpg){: .align-center} Normal galaxies
![image-center](/assets/images/lines/anomaly_det_2.jpg){: .align-center} Anomalous galaxies

Generative networks and autoencoders are used to reconstruct the images in a collection with mixed content (normal and anomalous real images). We prove that the reconstruction error is larger in anomalous objects. We study the design of the best anomaly metric in order to label interesting objects by setting a threshold on the measured value.


