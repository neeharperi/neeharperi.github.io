---
title: "Long-Tailed 3D Detection via Multi-Modal Fusion"
collection: publications
permalink: /publications/LT3Dv2
excerpt: ''
date: 2025-2-1
venue: 'Under Review at TPAMI'
paperurl: ''
citation: 'Ma Y, Peri N, Wei S, Dave A, Hua W, Li Y, Ramanan D, Kong S. Long-Tailed 3D Detection via Multi-Modal Fusion. Under Review at TPAMI'

---
Contemporary autonomous vehicle (AV) benchmarks have advanced techniques for training 3D detectors, particularly on large-scale multi-modal (LiDAR + RGB) data. Surprisingly, although semantic class labels naturally follow a long-tailed distribution, existing benchmarks only focus on a few common classes (e.g., pedestrian and car) and neglect many rare but crucial classes (e.g., emergency vehicle and stroller). However, AVs must reliably detect both common and rare classes for safe operation in the open world. We address this challenge by formally studying the problem of Long-Tailed 3D Detection (LT3D), which evaluates all annotated classes, including those in-the-tail. We address LT3D with hierarchical losses that promote feature sharing across classes, and introduce diagnostic metrics that award partial credit to "reasonable" mistakes with respect to the semantic hierarchy (e.g., mistaking a child for an adult). Further, we point out that rare-class accuracy is particularly improved via multi-modal late fusion (MMLF) of independently trained \emph{uni-modal} LiDAR and RGB detectors. Importantly, such an MMLF framework allows us to leverage large-scale uni-modal datasets (with more examples for rare classes) to train better uni-modal detectors, unlike prevailing end-to-end trained multi-modal detectors that require paired multi-modal data. Finally, we examine three critical components of our simple MMLF approach from first principles and investigate whether to train 2D or 3D RGB detectors for fusion, whether to match RGB and LiDAR detections in 3D or the projected 2D image plane, and how to fuse matched detections. Extensive experiments reveal that 2D RGB detectors achieve better recognition accuracy for rare classes than 3D RGB detectors and matching on the 2D image plane mitigates depth estimation errors for better matching. Our proposed MMLF approach significantly improves LT3D performance over prior work, particularly improving rare class performance from 12.8 to 20.0 mAP!

[[Download Paper](https://neeharperi.com/files/LT3Dv2.pdf)] 
[[Project Page](https://mayechi.github.io/lt3d-lf-io/)] 
[[Code](https://github.com/mayechi/lt3d-lf)]
