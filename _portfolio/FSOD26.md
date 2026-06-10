---
title: "CVPR 2026 Foundational Few-Shot Object Detection Challenge"
excerpt: "<br/><img src='/images/fsod.png'>"
permalink: "VPLOW26-Foundational-FSOD-Challenge"
collection: portfolio
date: 2026-6-1
---

# Challenge Summary
Can foundation models replace human annotators for 2D data annotation? Vision-Language Models (VLMs) like GroundingDINO have demonstrated remarkable zero-shot 2D detection performance on standard benchmarks like COCO. However, such foundational models may still be sub-optimal for specific target applications like medical and aerial image analysis Indeed, this well-known observation has created the ad-hoc practice of prompt engineering, where users actively search for a textual prompt that elicits the desired zero-shot behavior. Instead, we argue that one can principally address the challenge of aligning foundational models to target concepts through the lens of few-shot recognition by presenting VLMs with a few visual examples of the target concept. Crucially, such examples can be multi-modal, using both text and visual cues, mimicking the natural few-shot multi-modal instructions that are often given to human annotators when defining a target concept of interest. Concretely, we evaluate how well foundation models can learn from multi-modal annotator instructions using the Roboflow-VL dataset. We will evaluate detectors pre-trained on any external datasets and fine-tuned on multi-modal (text and visual) 10-shot examples per class. Methods will be evaluated on a held-out set of images and will be ranked by mean average precision (mAP).

# Overall Track Challenge Winner
**Team: Superb AI**

Members: Kyeongryeol Go, Hyundong Jin, Taewoong Jang, Wooseong Choi

[[Dowload Technical Report](https://neeharperi.com/files/superb_ai_techreport_cvprw26.pdf)]
[[Code](https://github.com/gokyeongryeol/zero-fsod)]

# Overall Track Runner Up
**Team: FDUROILab Lenovo**

Members: Lingyi Hong, Mingxi Cheng, Xingqi He, Runze Li, Xingdong Sheng, Wenqiang Zhang

[[Dowload Technical Report](https://neeharperi.com/files/fduroilab_techreport_cvprw26.pdf)]
[[Code](https://github.com/omnipotent13/FDUROILab_Lenovo_Roboflow-20VL-2026)]

# Other Teams

**Team: Aliz**

Members: Ali Alavi

[[Dowload Technical Report](https://neeharperi.com/files/aliz_techreport_cvprw26.pdf)]
[[Code](https://github.com/saliAlavi/roboflow-20vl_few-shot_object_detection_cvpr_competition_26)]

**Team: ANMSPro**

Members: Abu Noman Md Sakib

[[Dowload Technical Report](https://neeharperi.com/files/anmspro_techreport_cvprw26.pdf)]
[[Code](https://github.com/anmspro/cvpr-rf20vl)]

# In-Context Prompting Track Winner
**Team: Lababa**

Members: Pu Luo, Cong Xu, Yumei Li, Licheng Jiao, Puha Chen, Dan Zhang

[[Dowload Technical Report](https://neeharperi.com/files/lababa_techreport_cvprw26.pdf)]
[[Code](https://github.com/lapuuu-810/Roboflow-20VL-Few-Shot-lababa)]

# In-Context Prompting Track Runner Up
**Team: MR UCAS**

Members: Chenhao Zhou, Qianqian Xu, Minye Lei, Yihang Huang, Peisong Wen, Siran Dai, Yang Liu, Qingming Huang

[[Dowload Technical Report](https://neeharperi.com/files/mr_ucas_techreport_cvprw26.pdf)]
[[Code](https://github.com/Chou2021/training-free-fsod)]

# Other Teams
**Team: HUST-ORP**

Members: Qile Miao, Wencan Pei, Zerui Xi, Ruijie Ma, Jianxin Lin, Yiping Gao

[[Dowload Technical Report](https://neeharperi.com/files/hust_orp_techreport_cvprw26.pdf)]

**Team: XMU MAC**

Members: Zhigang Chen, Xiawu Zheng, Rongrong Ji

[[Dowload Technical Report](https://neeharperi.com/files/xmu_mac_techreport_cvprw26.pdf)]

**Team: TAHAKOM**

Members: Norah Alshammari, Dalal Alayban, Reema Alsugair

[[Dowload Technical Report](https://neeharperi.com/files/tahakom_techreport_cvprw26.pdf)]

**Team: ANMSPro**

Members: Abu Noman Md Sakib

[[Dowload Technical Report](https://neeharperi.com/files/anmspro2_techreport_cvprw26.pdf)]
[[Code](https://github.com/anmspro/cvpr-rf20vl)]
