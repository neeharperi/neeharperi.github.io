---
title: 'Towards Learning to Complete Anything in LiDAR'
collection: publications
permalink: /publications/CAL
excerpt: ''
date: 2025-05-01
venue: 'ICML'
paperurl: ''
citation: 'A Takmaz, C Saltori, N Peri, T Meinhardt, RD Lutio, L Leal-Taixe, A Osep. Towards Learning to Complete Anything in LiDAR In: International Conference on Machine Learning, ICML 2025'

---

We propose CAL (Complete Anything in Lidar) for Lidar-based shape-completion in-the-wild. This is closely related to Lidar-based semantic/panoptic scene completion. However, contemporary methods can only complete and recognize objects from a closed vocabulary labeled in existing Lidar datasets. Different to that, our zero-shot approach leverages the temporal context from multi-modal sensor sequences to mine object shapes and semantic features of observed objects. These are then distilled into a Lidar-only instance-level completion and recognition model. Although we only mine partial shape completions, we find that our distilled model learns to infer full object shapes from multiple such partial observations across the dataset. We show that our model can be prompted on standard benchmarks for Semantic and Panoptic Scene Completion, localize objects as (amodal) 3D bounding boxes, and recognize objects beyond fixed class vocabularies.

[[Download Paper](https://neeharperi.com/files/CAL.pdf)]
[[Project Page](https://research.nvidia.com/labs/dvl/projects/complete-anything-lidar/)]
