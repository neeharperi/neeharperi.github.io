---
title: 'MonoFusion: Sparse-View 4D Reconstruction via Monocular Fusion'
collection: publications
permalink: /publications/MonoFusion
excerpt: ''
date: 2025-07-01
venue: 'ICCV'
paperurl: ''
citation: 'Z Wang, J Tan, T Khurana, N Peri, D Ramanan. MonoFusion: Sparse-View 4D Reconstruction via Monocular Fusion. In: International Conference on Computer Vision, ICCV 2025'

---

We address the problem of dynamic scene reconstruction from sparse-view videos. Prior work often requires dense multi-view captures with hundreds of calibrated cameras (e.g. Panoptic Studio). Such multi-view setups are prohibitively expensive to build and cannot capture diverse scenes in-the-wild. In contrast, we aim to reconstruct dynamic human behaviors, such as repairing a bike or dancing, from a small set of sparse-view cameras with complete scene coverage (e.g. four equidistant inward-facing static cameras). We find that dense multi-view reconstruction methods struggle to adapt to this sparse-view setup due to limited overlap between viewpoints. To address these limitations, we carefully align independent monocular reconstructions of each camera to produce time- and view-consistent dynamic scene reconstructions. Extensive experiments on PanopticStudio and Ego-Exo4D demonstrate that our method achieves higher quality reconstructions than prior art, particularly when rendering novel views.

[[Download Paper](https://neeharperi.com/files/MonoFusion.pdf)]
[[Project Page](https://imnotprepared.github.io/research/25_DSR/index.html)]
