---
title: 'Better Call SAL: Towards Learning to Segment Anything in LiDAR'
collection: publications
permalink: /publications/SAL
excerpt: ''
date: 2024-07-01
venue: 'ECCV'
paperurl: ''
citation: 'Osep A, Meinhardt T, Ferroni F, Peri N, Ramanan D, Leal-Taixe L. Better Call SAL: Towards Learning to Segment Anything in LiDAR. In: European Conference on Computer Vision, ECCV 2024'

---

We propose the SAL (Segment Anything in Lidar) method consisting of a text-promptable zero-shot model for segmenting and classifying any object in Lidar, and a pseudo-labeling engine that facilitates model training without manual supervision. While the established paradigm for Lidar Panoptic Segmentation (LPS) relies on manual supervision for a handful of object classes defined a priori, we utilize 2D vision foundation models to generate 3D supervision “for free”. Our pseudolabels consist of instance masks and corresponding CLIP tokens, which we lift to Lidar using calibrated multi-modal data. By training our model on these labels, we distill the 2D foundation models into our Lidar SAL model. Even without manual labels, our model achieves 91% in terms of class-agnostic segmentation and 54% in terms of zero-shot LPS of the fully supervised state-of-the-art. Furthermore, we outperform several baselines that do not distill but only lift image features to 3D. More importantly, we demonstrate that SAL supports arbitrary class prompts, can be easily extended to new datasets, and shows significant potential to improve with increasing amounts of self-labeled data.

[[Download Paper](https://neeharperi.com/files/SAL.pdf)]
[[Project Page](https://research.nvidia.com/labs/dvl/projects/sal/)]
[[Code](https://github.com/nv-dvl/segment-anything-lidar)]
