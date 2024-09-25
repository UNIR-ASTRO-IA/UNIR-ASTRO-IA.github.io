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

### Galaxy image denoising

#### Use of DDPM for the image denoising problem 

![image-center](/assets/images/lines/anomaly_det_1.jpg){: .align-center} 


This study compares the performance of DDPM and Residual Attention
UNet models in reconstructing low SNR galactic images. Results reveal the
superiority of diffusion models, according to a newly proposed metric. A
positive correlation was observed between diffusion steps and performance,
with DDPM requiring more data than UNet. Limitations were identified in
existing metrics for evaluating similarity in noisy images. In response, the
Mean Square Error of the Fourier transform is proposed as a complementary
metric, along with a method to quantify uncertainty in predictions.
The results indicate that diffusion models are effective in reconstructing
astronomical images, generating more realistic and information-dense results
than those based on UNet. The stochastic nature of DDPM allows for
obtaining more relevant statistics compared to deterministic models. These
capabilities could significantly influence future astronomical predictions.



### VIRTIS-M images

![image-center](/assets/images/lines/gan_virtis_1.jpg){: .align-center}
Generative networks to improve S/N ratio in Venus Express VIRTIS-M images. Lower exposure times are used to generate examples of images, base truth are images with higher exposure times and S/N ratio.

## Anomaly detection in galaxy images using GAN and Variational Autoencoders

Normal galaxy images
![image-center](/assets/images/lines/anomaly_det_1.jpg){: .align-center} 

Anomalous galaxy images
![image-center](/assets/images/lines/anomaly_det_2.jpg){: .align-center} 

Generative networks and autoencoders are used to reconstruct the images in a collection with mixed content (normal and anomalous real images). We prove that the reconstruction error is larger in anomalous objects. We study the design of the best anomaly metric in order to label interesting objects by setting a threshold on the measured value.


