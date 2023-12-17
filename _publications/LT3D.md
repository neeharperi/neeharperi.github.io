---
title: "Towards Long-Tailed 3D Detection"
collection: publications
permalink: /publications/LT3D
excerpt: ''
date: 2022-7-1
venue: 'CoRL'
paperurl: ''
citation: 'Peri N, Dave A, Ramanan D, Kong S. Towards Long Tailed 3D Detection. In: Conference on Robot Learning, CoRL 2022'

---

Contemporary autonomous vehicle (AV) benchmarks have advanced techniques for training 3D detectors, particularly on large-scale LiDAR data. Surprisingly, although semantic class labels naturally follow a long-tailed distribution, these benchmarks focus on only a few common classes (e.g., pedestrian and car) and neglect many rare classes in-the-tail (e.g., debris and stroller). However, in the real open world, AVs must still detect {\tt rare} classes to ensure safe operation. Moreover, semantic classes are often organized within a hierarchy, e.g., tail classes such as child and construction-worker are arguably subclasses of pedestrian. However, such hierarchical relationships are often ignored, which may yield misleading estimates of performance and missed opportunities for algorithmic innovation. We address these challenges by formally studying the problem of Long-Tailed 3D Detection (LT3D), which evaluates on all classes, including those in-the-tail. We evaluate and innovate upon popular 3D detectors, such as CenterPoint and PointPillars, adapting them for LT3D. We develop hierarchical losses that promote feature sharing across common-vs-rare classes, as well as improved detection metrics that award partial credit to "reasonable" mistakes respecting the hierarchy (e.g., mistaking a child for an adult). Finally, we point out that fine-grained tail class accuracy is particularly improved via multimodal fusion of RGB images with LiDAR; simply put, fine-grained classes are challenging to identify from sparse (LiDAR) geometry alone, suggesting that multimodal cues are crucial to  long-tailed 3D detection. Our modifications improve accuracy by 5\% AP on average for all classes, and dramatically improve AP for rare classes (e.g stroller AP improves from 0.1 to 31.6)! 

[[Download Paper](https://neeharperi.com/files/LT3D.pdf)] 
[[Download Masters Thesis](https://neeharperi.com/files/lt3d_msr_thesis.pdf)] 
[[Video](https://youtu.be/1O1pT72wnmQ)]
[[Poster](https://neeharperi.com/files/LT3DPoster.pdf)]
[[Code](https://github.com/neeharperi/LT3D)]
