---
title: "An Empirical Analysis of Range for 3D Object Detection"
collection: publications
permalink: /publications/range3d
excerpt: ''
date: 2023-9-1
venue: 'ICCVW'
paperurl: ''
citation: 'Peri N, Li M, Wilson B, Wang YX, Hays J, Ramanan D. An Empirical Analysis of Range for 3D Object Detection. In: International Conference on Computer Vision Workshops, ICCVW 2023'

---

LiDAR-based 3D detection plays a vital role in autonomous navigation. Surprisingly, although autonomous vehicles (AVs) must detect both near-field objects (for collision avoidance) and far-field objects (for longer-term planning), contemporary benchmarks focus only on near-field 3D detection. However, AVs must detect far-field objects for safe navigation. In this paper, we present an empirical analysis of far-field 3D detection using the long-range detection dataset Argoverse 2.0 to better understand the problem, and share the following insight: near-field LiDAR measurements are dense and optimally encoded by small voxels, while far-field measurements are sparse and are better encoded with large voxels. We exploit this observation to build a collection of range experts tuned for near-vs-far field detection, and propose simple techniques to efficiently ensemble models for long-range detection that improve efficiency by 33% and boost accuracy by 3.2% CDS.

[[Download Paper](http://neeharperi.com/files/Range3D.pdf)] 
[[Video](https://youtu.be/gCdt4dGKCOw)]
[[Poster](http://neeharperi.com/files/Range3DPoster.pdf)]
[[Code](https://github.com/neeharperi/LT3D)]
