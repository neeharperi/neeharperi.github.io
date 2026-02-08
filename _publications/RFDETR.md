---
title: 'RF-DETR: Neural Architecture Search for Real-Time Detection Transformers'
collection: publications
permalink: /publications/RFDETR
excerpt: ''
date: 2026-01-01
venue: 'ICLR'
paperurl: ''
citation: 'Robinson I, Robicheaux P, Popov M, Ramanan D, Peri N. RF-DETR: Neural Architecture Search for Real-Time Detection Transformers. In: International Conference on Learning Representations, ICLR 2026'

---

Open-vocabulary detectors achieve impressive performance on COCO, but often fail to generalize to real-world datasets with out-of-distribution classes not typically found in their pre-training. Rather than simply fine-tuning a heavyweight vision-language model (VLM) for new domains, we introduce RF-DETR, a light-weight specialist detection transformer that discovers accuracy-latency Pareto curves for any target dataset with weight-sharing neural architecture search (NAS). Our approach fine-tunes a pre-trained base network on a target dataset and evaluates thousands of network configurations with different accuracy-latency tradeoffs without re-training. Further, we revisit the “tunable knobs” for NAS to improve the transferability of DETRs to diverse target domains. Notably, RF-DETR significantly improves over prior state-of-the-art real-time methods on COCO and Roboflow100-VL. RF-DETR (nano) achieves 48.0 AP on COCO, beating D-FINE (nano) by 5.3 AP at similar latency, and RF-DETR (2x-large) outperforms GroundingDINO (tiny) by 1.2 AP on Roboflow100-VL while running 20× as fast. To the best of our knowledge, RF-DETR (2x-large) is the first real-time detector to surpass 60 AP on COCO. 

[[Download Paper](https://neeharperi.com/files/RFDETR.pdf)]
[[Code](https://github.com/roboflow/rf-detr/)]
