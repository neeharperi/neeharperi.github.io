---
title: 'I Cant Believe Its Not Scene Flow!'
collection: publications
permalink: /publications/SceneFlowMetric
excerpt: ''
date: 2024-07-01
venue: 'ECCV'
paperurl: ''
citation: 'Vedder K, Khatri I, Peri N, Ramanan D, Hays J. I Cant Believe Its Not Scene Flow! In: European Conference on Computer Vision, ECCV 2024'

---

State-of-the-art scene flow methods broadly fail to describe the motion of small objects, and existing evaluation protocols hide this failure by averaging over many points. To address this limitation, we propose Bucket Normalized EPE, a new class-aware and speed-normalized evaluation protocol that better contextualizes error comparisons between object types that move at vastly different speeds. In addition, we propose TrackFlow, a frustratingly simple supervised scene flow baseline that combines a high-quality 3D object detector (trained using standard class re-balancing techniques) with a simple Kalman filter-based tracker. Notably, TrackFlow achieves state-of-the-art performance on existing metrics and shows large improvements over prior work on our proposed metric. Our results highlight that scene flow evaluation must be class and speed aware, and supervised scene flow methods must address point-level class imbalances. 

[[Download Paper](https://neeharperi.com/files/SceneFlowMetric.pdf)]
[[Project Page](https://vedder.io/trackflow.html)]
[[Code](https://github.com/kylevedder/SceneFlowZoo)]
