---
title: "A deep-based approach for multi-descriptor feature extraction: Applications on SAR image registration" 
date: 2024-10-03
permalink: /posts/2024/10/Expert-systems-with-applications-2024/
tags:
  - Image Registration
  - SAR
  - Computer Vision
  - Deep Learning
  - Feature Detection
  - Feature Description
---


<!-- [A deep-based approach for multi-descriptor feature extraction: Applications on SAR image registration](https://www.sciencedirect.com/science/article/abs/pii/S0957417424011576) -->


Synthetic aperture radar (SAR) images have found increasing attention in various applications, such as remote
sensing, surveillance, and disaster management. Unlike optical sensors, SAR can capture images in any weather
conditions at any time, making it particularly valuable. However, it poses unique challenges for image
processing tasks, like complex speckle noise, texture, and geometric distortions. For many image processing
tasks such as image registration; feature detection and extraction are critical initial steps. In this work, we
propose a deep learning-based method for detecting and describing keypoints in SAR images, which can be
specifically applied to SAR image registration tasks. To address the challenges of SAR images, we utilize the
R2D2 network and propose a training scheme specifically tailored for these images. Furthermore, our approach
involves multiple descriptors utilization for outlier removal between image keypoints and a two-stage pipeline
consisting of coarse and fine stages for robust feature point matching of SAR images. By leveraging the coarse
registration stage, which maintains robustness, and also a fine stage that employs multiple descriptors along
with a local search technique, our approach enhances the keypoint matching accuracy. Evaluation results show
that the proposed method outperforms most of the traditional and deep learning-based methods in terms of
the percentage of correct matches, while achieving comparable or even better root mean squared error (RMSE)
results.




<!-- {% include figure image_path="/assets/papers_miscs/Expert_Systems_with_Applications_2024/Methodology.png" alt="Scheme" caption="Scheme" %}

{% include figure image_path="/assets/papers_miscs/Expert_Systems_with_Applications_2024/CoarseRegistration.png" alt="Coarse Registration" caption="Coarse Registration" %}

{% include figure image_path="/assets/papers_miscs/Expert_Systems_with_Applications_2024/FineRegistration.png" alt="Fine Registration" caption=""Fine Registration"" %}

{% include figure image_path="/assets/papers_miscs/Expert_Systems_with_Applications_2024/FeatureMatchingFineStage.png" alt="Feature Matching in Fine Stage" caption="Feature Matching in Fine Stage" %}

{% include figure image_path="/assets/papers_miscs/Expert_Systems_with_Applications_2024/PatchBasedMatching.png" alt="Patch-based Matching in Fine Stage" caption="Patch-based Matching in Fine Stage" %}

{% include figure image_path="/assets/papers_miscs/Expert_Systems_with_Applications_2024/Results.png" alt="Results" caption="Comparisons" %}
 -->
