---
title: 'Shelf-Supervised Cross-Modal Pre-Training for 3D Object Detection'
collection: publications
permalink: /publications/ShelfSupervised3D
excerpt: ''
date: 2024-09-01
venue: 'CoRL'
paperurl: ''
citation: 'Khurana M, Peri N, Hays J, Ramanan D. helf-Supervised Cross-Modal Pre-Training for 3D Object Detection. In: Conference on Robot Learning, CoRL 2024'

---

State-of-the-art 3D object detectors are often trained on massive labeled datasets. However, annotating 3D bounding boxes remains prohibitively expensive and time-consuming, particularly for LiDAR. Instead, recent works demonstrate that self-supervised pre-training with unlabeled data can improve detection accuracy with limited labels. Contemporary methods adapt best-practices for self-supervised learning from the image domain to point clouds (such as contrastive learning). However, publicly available 3D datasets are considerably smaller and less diverse than those used for image-based self-supervised learning, limiting their effectiveness. We do note, however, that such data is naturally collected in a multimodal fashion, often paired with images. Rather than pre-training with only self-supervised objectives, we argue that it is better to bootstrap point cloud representations using image-based foundation models trained on internetscale image data. Specifically, we propose a shelf-supervised approach (e.g. supervised with off-the-shelf image foundation models) for generating zero-shot 3D bounding boxes from paired RGB and LiDAR data. Pre-training 3D detectors with such pseudo-labels yields significantly better semi-supervised detection accuracy than prior self-supervised pretext tasks. Importantly, we show that image-based shelf-supervision is helpful for training LiDAR-only and multi-modal (RGB + LiDAR) detectors. We demonstrate the effectiveness of our approach on nuScenes and WOD, significantly improving over prior work in limited data settings.

[[Download Paper](https://neeharperi.com/files/ShelfSupervised3D.pdf)]
