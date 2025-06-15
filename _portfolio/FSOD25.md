---
title: "CVPR 2025 Foundational Few-Shot Object Detection Challenge"
excerpt: "<br/><img src='/images/fsod.png'>"
permalink: "VPLOW25-Foundational-FSOD-Challenge"
collection: portfolio
date: 2025-6-11
---

# Challenge Summary
Can foundation models replace human annotators for 2D data annotation? Vision-Language Models (VLMs) like GroundingDINO have demonstrated remarkable zero-shot 2D detection performance on standard benchmarks like COCO. However, such foundational models may still be sub-optimal for specific target applications like medical and aerial image analysis Indeed, this well-known observation has created the ad-hoc practice of prompt engineering, where users actively search for a textual prompt that elicits the desired zero-shot behavior. Instead, we argue that one can principally address the challenge of aligning foundational models to target concepts through the lens of few-shot recognition by presenting VLMs with a few visual examples of the target concept. Crucially, such examples can be multi-modal, using both text and visual cues, mimicking the natural few-shot multi-modal instructions that are often given to human annotators when defining a target concept of interest. Concretely, we evaluate how well foundation models can learn from multi-modal annotator instructions using the Roboflow-VL dataset. We will evaluate detectors pre-trained on any external datasets and fine-tuned on multi-modal (text and visual) 10-shot examples per class. Methods will be evaluated on a held-out set of images and will be ranked by mean average precision (mAP).

# Challenge Winners
**Team: BEATON**

Members: Kaijin Zhang, Xuezhen Tu, Qingpeng Nong, Xiugang Dong, Xurui Gao, Xiangsheng Zhou

[[Dowload Technical Report](https://neeharperi.com/files/beaton_techreport_cvprw25.pdf)]

# 2nd Place
**Team: FDUROILab Lenovo**

Members: Lingyi Hong, Mingxi Cheng, Keliang Yin, Runze Li, Xingdong Sheng, Wenqiang Zhang

[[Dowload Technical Report](https://neeharperi.com/files/fduroilab_techreport_cvprw25.pdf)]
[[Code](https://github.com/omnipotent13/FDUROILab_Lenovo_Roboflow-20VL)]

# 3rd Place
**Team: NJUST-KMG**

Members: Zhe Zhang, Lei Qi, Pengsong Niu, Yang Yang

[[Dowload Technical Report](https://neeharperi.com/files/njustkmg_techreport_cvprw25.pdf)]
[[Code](https://github.com/qianlanzz/Roboflow-20VL-Few-Shot-Object-Detection-Challenge-CVPR25)]

# Challenge Honorable Mentions
**Team: LEINAD**

Members: Sangbum Choi, Kyeongryeol Go

[[Dowload Technical Report](https://neeharperi.com/files/leinad_techreport_cvprw25.pdf)]

**Team: Intellindust-AI-Lab**

Members: Xuanlong Yu, Xi Shen

[[Dowload Technical Report](https://neeharperi.com/files/intellindust_ai_techreport_cvprw25.pdf)]
