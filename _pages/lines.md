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

## Deep Learning for light curve processing

### Exoplanet detection using CNN and Wavelet features

Astronomy is a field of study as fascinating as it is complex; new techniques and technological advancement allow us to reach distances further than ever at an unprecedented level of detail. However, this results in larger amounts of data and specific knowledge to correctly interpret it, which limits the speed at which this data can be processed. That is why new Machine Learning techniques are being applied to deal with this exponential growth of data.

In this paper, models that allow the detection of exoplanets through the analysis of light curves are investigated and compared. To achieve this, Deep Learning is used, a subtype of Machine Learning that has gained great relevance in the last decade due to its excellent capacity to detect patterns in a multitude of data, with the ultimate goal of providing a viable solution to automatically classify exoplanets correctly from its light curves.

## Star centering problem

### Convolutional neural networks (CNN) for the start centering problem.

We present an expanded and improved deep-learning (DL) methodology for determining centers of star images on Hubble Space Telescope/Wide-Field Planetary Camera 2 (WFPC2) exposures. Previously, we demonstrated that our DL model can eliminate the pixel-phase bias otherwise present in these undersampled images; however that analysis was limited to the central portion of each detector. In the current work we introduce the inclusion of global positions to account for the point-spread function (PSF) variation across the entire chip and instrumental magnitudes to account for nonlinear effects such as charge transfer efficiency. The DL model is trained using a unique series of WFPC2 observations of globular cluster 47 Tuc, data sets comprising over 600 dithered exposures taken in each of two filters—F555W and F814W. It is found that the PSF variations across each chip correspond to corrections of the order of ∼100 mpix, while magnitude effects are at a level of ∼10 mpix. Importantly, pixel-phase bias is eliminated with the DL model; whereas, with a classic centering algorithm, the amplitude of this bias can be up to ∼40 mpix. Our improved DL model yields star-image centers with uncertainties of 8–10 mpix across the full field of view of WFPC2.

* [1] Casetti-Dinescu, D. I., Girard, T. M., Baena-Gallé, R., Martone, M., & Schwendemann, K. (2023). Star-image Centering with Deep Learning: HST/WFPC2 Images. Publications of the Astronomical Society of the Pacific, 135(1047), 054501. https://iopscience.iop.org/article/10.1088/1538-3873/acd080/meta 
* [2] Casetti-Dinescu, D. I., Baena-Gallé, R., Girard, T. M., Cervantes-Rovira, A., & Todeasa, S. (2024). Star Image Centering with Deep Learning. II. HST/WFPC2 Full Field of View. Publications of the Astronomical Society of the Pacific, 136(5), 054501.  https://iopscience.iop.org/article/10.1088/1538-3873/ad430c/meta 


## Generative Adversarial Networks for the improvement of astronomical image.

This research line is currently addressing state of the art generative architectures in the following cases.

### Galaxy image denoising using Denoising Difussion Probabilistic Models (DDPM) 

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


## Non supervised techniques

### Anomaly detection in galaxy images using GAN and Variational Autoencoders

Normal galaxy images
![image-center](/assets/images/lines/anomaly_det_1.jpg){: .align-center} 

Anomalous galaxy images
![image-center](/assets/images/lines/anomaly_det_2.jpg){: .align-center} 

Generative networks and autoencoders are used to reconstruct the images in a collection with mixed content (normal and anomalous real images). We prove that the reconstruction error is larger in anomalous objects. We study the design of the best anomaly metric in order to label interesting objects by setting a threshold on the measured value.


