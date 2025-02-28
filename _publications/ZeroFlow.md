---
title: "ZeroFlow: Scalable Scene Flow via Distillation"
collection: publications
permalink: /publications/ZeroFlow
excerpt: ''
date: 2024-1-1
venue: 'ICLR'
paperurl: ''
citation: 'Vedder K, Peri N, Chodosh N, Khatri I, Eaton E, Jayaraman D, Liu Y, Ramanan D, Hays J. ZeroFlow: Scalable Scene Flow via Distillation. In: International Conference on Representation Learning, ICLR 2024'

---

Scene flow estimation is the task of describing the 3D motion field between temporally successive point clouds. State-of-the-art methods use strong priors and test-time optimization techniques, but require on the order of tens of seconds to process full-size point clouds, making them unusable as computer vision primitives for real-time applications such as open world object detection. Feedforward methods are considerably faster, running on the order of tens to hundreds of milliseconds for full-size point clouds, but require expensive human supervision. To address both limitations, we propose Scene Flow via Distillation, a simple, scalable distillation framework that uses a label-free optimization method to produce pseudo-labels to supervise a feedforward model. Our instantiation of this framework, ZeroFlow, achieves state-of-the-art performance on the Argoverse 2 Self-Supervised Scene Flow Challenge while using zero human labels by simply training on large-scale, diverse unlabeled data. At test-time, ZeroFlow is over 1000x faster than label-free state-of-the-art optimization-based methods on full-size point clouds (34 FPS vs 0.028 FPS) and over 1000x cheaper to train on unlabeled data compared to the cost of human annotation ($394 vs ~$750,000).

[[Download Paper](https://neeharperi.com/files/ZeroFlow.pdf)] 
[[Project Page](https://vedder.io/zeroflow.html)] 
[[Code](https://vedder.io/zeroflow.html)]
