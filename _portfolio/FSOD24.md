---
title: "CVPR 2024 End-to-End Forecasting Challenge"
excerpt: "<br/><img src='/images/av2.png'>"
permalink: "WAD24-End-to-End-Forecasting-Challenge"
collection: portfolio
date: 2024-6-17
---

# Challenge Summary
Object detection and forecasting are fundamental components of embodied perception. These problems, however, are largely studied in isolation. We propose a joint detection, tracking, and multi-agent forecasting benchmark from sensor data. Although prior works have studied end-to-end perception, no large scale dataset or challenge exists to facilitate standardized evaluation for this problem. In addition, self-driving benchmarks have historically focused on evaluating a few common classes such as cars, pedestrians and bicycles, and neglect many rare classes in-the-tail. However, in the real open world, self-driving vehicles must still detect rare classes to ensure safe operation.

To this end, our proposed benchmark will be the first to evaluate end-to-end perception on 26 classes defined by the AV2 ontology. Specifically, we will repurpose the AV2 sensor dataset, which has track annotations for 26 object categories, for end-to-end perception: for each timestep in a given sensor sequence, algorithms will have access to all prior frames and must produce tracks for all past sensor sweeps, detections for the current timestep, and forecasted trajectories for the next 3 s. This challenge is different from the Motion Forecasting challenge because we do not provide ground truth tracks as input, requiring algorithms to process raw sensor data. Our primary evaluation metric is Forecasting Average Precision, a joint detection and forecasting metric that computes performance averaged over static, linear, and nonlinearly moving cohorts. Unlike standard motion forecasting evaluation, end-to-end perception must consider both true positive and false positive predictions.

# Challenge Winners
**Team: NJUST KMG**

Members: Hongpeng Pan, Jinkai Li, Shifeng Yi, Bing Hu, Shouwei Yang, Yi Xu, Yang Yang
k

[[Dowload Technical Report](https://neeharperi.com/files/njustkmg_techreport_cvprw24.pdf)]

# Challenge Honorable Mentions
**Team: ZJYD CXY Vision**

Members: Qibo Chen, Jianyue Ge, Weizhong Jin, Li Yu

[[Dowload Technical Report](https://neeharperi.com/files/zjydcxyvision_techreport_cvprw24.pdf)]
