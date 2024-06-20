---
title: "CVPR 2024 Foundational Few-Shot Object Detection Challenge"
excerpt: "<br/><img src='/images/fsod.png'>"
permalink: "VPLOW24-Foundational-FSOD-Challenge"
collection: portfolio
date: 2024-6-18
---

# Challenge Summary
Can foundation models replace human annotators for 2D data annotation? Vision-Language Models (VLMs) like GroundingDINO have demonstrated remarkable zero-shot 2D detection performance on standard benchmarks like COCO. However, such foundational models may still be sub-optimal for specific target applications like autonomous vehicle perception. Indeed, this well-known observation has created the ad-hoc practice of prompt engineering, where users actively search for a textual prompt that elicits the desired zero-shot behavior. Instead, we argue that one can principally address the challenge of aligning foundational models to target concepts through the lens of few-shot recognition by presenting VLMs with a few visual examples of the target concept. Crucially, such examples can be multi-modal, using both text and visual cues, mimicking the natural few-shot multi-modal instructions that are often given to human annotators when defining a target concept of interest. Concretely, we formalize the problem of learning from multi-modal annotator instructions using the nuImages dataset. We will evaluate detectors pre-trained on any external datasets (except nuImages and nuScenes) and fine-tuned on multi-modal (text and visual) 10-shot examples per nuImages class. Methods will be evaluated on a held-out set of images and will be ranked by mean average precision (mAP).

# Challenge Winners
**Team: NJUST KMG**

Members: Hongpeng Pan, Jinkai Li, Shifeng Yi, Bing Hu, Shouwei Yang, Yi Xu, Yang Yang
k

[[Dowload Technical Report](https://neeharperi.com/files/njustkmg_techreport_cvprw24.pdf)]

# Challenge Honorable Mentions
**Team: ZJYD CXY Vision**

Members: Qibo Chen, Jianyue Ge, Weizhong Jin, Li Yu

[[Dowload Technical Report](https://neeharperi.com/files/zjydcxyvision_techreport_cvprw24.pdf)]
