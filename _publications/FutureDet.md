---
title: "Forecasting from LiDAR via Future Object Detection"
collection: publications
permalink: /publications/FutureDet
excerpt: ''
date: 2022-3-1
venue: 'CVPR'
paperurl: ''
citation: 'Peri N, Jonathon Luiten, Mentian Li, Aljosa Osep, Laura Leal-Taixe, Deva Ramanan. Forecasting from LiDAR via Future Object Detection. In: International Conference on Computer Vision and Pattern Recognition, CVPR 2022'

---

Object detection and forecasting are fundamental components of embodied perception. These two problems, however, are largely studied in isolation by the community. In this paper, we propose an end-to-end approach for detection and motion forecasting based on raw sensor measurement as opposed to ground truth tracks. Instead of predicting the current frame locations and forecasting forward in time, we directly predict future object locations and backcast to determine where each trajectory began. Our approach not only improves overall accuracy compared to other modular or end-to-end baselines, it also prompts us to rethink the role of explicit tracking for embodied perception. Additionally, by linking future and current locations in a many-to-one manner, our approach is able to reason about multiple futures, a capability that was previously considered difficult for end-to-end approaches. We conduct extensive experiments on the popular nuScenes dataset and demonstrate the empirical effectiveness of our approach. In addition, we investigate the appropriateness of reusing standard forecasting metrics for an end-to-end setup, and find a number of limitations which allow us to build simple baselines to game these metrics. We address this issue with a novel set of joint forecasting and detection metrics that extend the commonly used AP metrics from the detection community to measuring forecasting accuracy.

[[Download Paper](https://neeharperi.com/files/FutureDet.pdf)] 
[[Video](https://youtu.be/sDfJo_yC4qM)]
[[Poster](https://neeharperi.com/files/FutureDetPoster.pdf)]
[[Code](https://github.com/neeharperi/FutureDet)]
