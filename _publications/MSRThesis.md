---
title: "MSR Thesis: Long-Tailed 3D Detection via Multi-Modal Fusion"
collection: publications
permalink: /publications/MSR_LT3D
excerpt: ''
date: 2023-6-15
venue: 'CMU'
paperurl: ''
citation: 'Peri N. Long-Tailed 3D Detection via Multi-Modal Fusion. Carnegie Mellon University. 2023'

---

Contemporary autonomous vehicle (AV) benchmarks have advanced techniques for training 3D detectors, particularly on large-scale LiDAR data. Surprisingly, although semantic class labels naturally follow a long-tailed distribution, these benchmarks only focus on a few common classes (e.g., pedestrian and car) and neglect many rare classes in-the-tail (e.g., debris and stroller). However, in the real open world, AVs must still detect rare classes to ensure safe operation. Moreover, semantic classes are often organized within a hierarchy, e.g., tail classes such as child and construction-worker are arguably subclasses of pedestrian. However, such hierarchical relationships are often ignored, which may yield misleading estimates of performance and missed opportunities for algorithmic innovation.

We address these challenges by formally studying the problem of Long-Tailed 3D Detection (LT3D), which evaluates detection performance on all classes, including those in-the-tail. We evaluate and innovate upon popular 3D detectors, such as CenterPoint and PointPillars, adapting them for LT3D. We develop hierarchical losses that promote feature sharing across common-vs-rare classes, as well as improved detection metrics that award partial credit to “reasonable” mistakes respecting the hierarchy (e.g.,
mistaking a child for an adult). Finally, we point out that fine-grained tail class accuracy is particularly improved via multimodal fusion of RGB images with LiDAR; simply put, fine-grained classes are challenging to identify from sparse (LiDAR) geometry alone, suggesting that multimodal cues are crucial to long-tailed 3D detection.

We empirically show that (a) high-resolution RGB images help recognize rare objects, (b) LiDAR provides precise 3D localization, and (c) uni-modal detectors can be trained with more diverse examples because they do not require aligning and annotating multi-modal data. With these insights, we propose a simple late-fusion framework that combines RGB and LiDAR detections. We examine three critical components in this framework and consider whether to train 2D or 3D RGB detectors, whether to match RGB and LiDAR detections in the 2D image plane or 3D bird’s-eye-view (BEV), and how to fuse matched detections. Our modifications improve accuracy by 12.2% AP on average for all classes, and dramatically improve AP for rare classes (e.g., stroller AP improves from 0.1 to 37.7)!

[[Download Masters Thesis](https://neeharperi.com/files/lt3d_msr_thesis.pdf)] 
