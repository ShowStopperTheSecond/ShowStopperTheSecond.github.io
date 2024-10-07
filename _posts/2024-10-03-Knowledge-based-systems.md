---
title: "Beyond Outlier Removal: Integrated Ensemble Matching forAccurate Image Keypoint Correspondence" 
date: 2024-10-03
permalink: /posts/2024/10/Knowledge-based-systems-2024/
tags:
  - Deep Learning
  - Feature Detection
  - Feature Description
  - Feature Matching
---

This project presents a novel two-tier filtering approach for robust feature matching and geometric transformation estimation in computer vision tasks. Our method combines sub-descriptor matching and multi-descriptor ensembling to significantly improve the accuracy and reliability of keypoint correspondences across images. Our approach is evaluated on both classic hand- crafted algorithms and deep learning-based methods using the HPatches dataset. We use a pretrained network and enhance it to incorporate additional descriptor heads optimized for our matching strategy. The two-tier filtering strategy enables direct geometric transformation estimation without separate outlier removal in many cases, potentially streamlining computer vision pipelines. Results demonstrate that our approach substantially outperforms traditional single-descriptor methods, achieving over 95% correct matches for classic algorithm combinations and up to 96% for our enhanced learning-based approaches. Additionally, we explore applications of our method in scene matching.



{% include figure image_path="/assets/papers_miscs/Knowledge_based_systems_2024/Scheme.png" alt="Scheme" caption="" %}

{% include figure image_path="/assets/papers_miscs/Knowledge_based_systems_2024/Results.png" alt="Results" caption="" %}

