---
title: 'UniFlow: Zero-Shot LiDAR Scene Flow for Autonomous Driving'
collection: publications
permalink: /publications/UniFlow
excerpt: ''
date: 2026-06-15
venue: 'ECCV'
paperurl: ''
citation: 'S Li, Q Zhang, I Khatri, K Vedder, E Eaton, D Ramanan, N Peri. UniFlow: Zero-Shot LiDAR Scene Flow for Autonomous Driving In: European Conference on Computer Vision, ECCV 2026'

---

LiDAR scene flow is the task of estimating per-point 3D motion between consecutive point clouds. Recent methods achieve centimeter-level accuracy on popular autonomous vehicle (AV) datasets, but are typically only trained and evaluated on a single sensor. In this paper, we aim to learn general motion priors that transfer to diverse and unseen LiDAR sensors. However, prior work in LiDAR semantic segmentation and 3D object detection demonstrate that naively training on multiple datasets yields worse performance than single dataset models. Interestingly, we find that this conventional wisdom does not hold for motion estimation, and that state-of-the-art scene flow methods greatly benefit from cross-dataset training architectural modification. We posit that low-level tasks such as motion estimation may be less sensitive to sensor configuration; indeed, our analysis shows that models trained on fast-moving objects (e.g., from highway datasets) perform well on fast-moving objects, even across different datasets. Informed by our analysis, we propose UniFlow, a feedforward model that unifies and trains on multiple large-scale LiDAR scene flow datasets with diverse sensor placements and point cloud densities. Our frustratingly simple solution establishes a new state-of-the-art on Waymo and nuScenes, improving over prior work by 5.1% and 35.2% respectively. Moreover, UniFlow achieves state-of-the-art accuracy on unseen datasets like TruckScenes and AEVAScenes, outperforming prior dataset-specific models by 30.1% and 22.5% respectively.

[[Download Paper](https://neeharperi.com/files/UniFlow.pdf)]
[[Project Page](https://lisiyi777.github.io/UniFlow/)]
[[Code](https://github.com/lisiyi777/UniFlow)]
