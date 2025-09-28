---
title: 'Roboflow100-VL: A Multi-Domain Object Detection Benchmark for Vision-Language Models'
collection: publications
permalink: /publications/RF100VL
excerpt: ''
date: 2025-09-01
venue: 'NeurIPS'
paperurl: ''
citation: 'Robicheaux P, Popov M, Madan A, Robinson I, Nelson, J, Ramanan D, Peri N. Roboflow100-VL: A Multi-Domain Object Detection Benchmark for Vision-Language Models In: Neural Information Processing Systems, NeurIPS 2025'

---

Vision-language models (VLMs) trained on internet-scale data achieve remarkable zero-shot detection performance on common objects like car, truck, and pedestrian. However, state-of-the-art models still struggle to generalize to outof-distribution classes, tasks and imaging modalities not typically found in their pre-training. Rather than simply re-training VLMs on more visual data, we argue that one should align VLMs to new concepts with annotation instructions containing a few visual examples and rich textual descriptions. To this end, we introduce Roboflow100-VL, a large-scale collection of 100 multi-modal object detection datasets with diverse concepts not commonly found in VLM pre-training. We evaluate state-of-the-art models on our benchmark in zero-shot, few-shot, semisupervised, and fully-supervised settings, allowing for comparison across data regimes. Notably, we find that VLMs like GroundingDINO and Qwen2.5-VL achieve less than 2% zero-shot accuracy on challenging medical imaging datasets within Roboflow100-VL, demonstrating the need for few-shot concept alignment. Lastly, we discuss our recent CVPR 2025 Foundational FSOD competition and share insights from the community. Notably, the winning team significantly outperforms our baseline by 16.8 mAP! Our code and dataset are available on GitHub and Roboflow.

[[Download Paper](https://neeharperi.com/files/RF100VL.pdf)]
[[Code](https://github.com/roboflow/rf100-vl/)]
