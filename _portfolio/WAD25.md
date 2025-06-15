---
title: "CVPR 2025 Scenario Mining Challenge"
excerpt: "<br/><img src='/images/av2.png'>"
permalink: "WAD25-Scenario-Mining-Challenge"
collection: portfolio
date: 2025-6-11
---

# Challenge Summary
Autonomous Vehicles (AVs) collect and pseudo-label terabytes of multi-modal data localized to HD maps during normal fleet tests. However, identifying interesting and safety critical scenarios from uncurated data streams is prohibitively time-consuming and error-prone. Although prior works have explored this problem in the context of structured queries and hand-crafted heuristics, we are hosting this challenge to solicit better end-to-end solutions to this important problem.

To this end, our benchmark includes 10,000 planning-centric natural language queries. Challenge participants can use all RGB frames, Lidar sweeps, HD Maps, and track annotations from the AV2 sensor dataset to find relevant actors in each log. Methods will be evaluated at three levels of spatial and temporal granularity. First, methods must determine if an action (defined by a natural language query) occurs in the log. Next, if the action occurs in the log, methods must temporally localize (e.g. find the start and end time) of the action. Lastly, methods must detect and track all objects relevant to the text description. Our primary evaluation metric is HOTA-temporal, a tracking metric that jointly considers detection and association accuracy for referred objects.

# Challenge Winners
**Team: Zeekr UMCV**

Members: Dubing Chen, Huan Zheng, Wencheng Han, Runzhou Tao, Zhongying Qiu, Jianfei Yang, Jianbing Shen

[[Dowload Technical Report](https://neeharperi.com/files/zeekr_umcv_techreport_cvprw25.pdf)]

# 2nd Place
**Team: Mi3 UCM**

Members: Yifei Chen, Ross Greer

[[Dowload Technical Report](https://neeharperi.com/files/mi3_ucm_techreport_cvprw25.pdf)]
[[Code](https://github.com/Chen1fly/Mi3_UCM_AV2_SM)]

# 3rd Place
**Team: ZXH**

Members: Xiaohong Zhang, Yuanqi Li, Xianfei Li, Peng Pai

[[Dowload Technical Report](https://neeharperi.com/files/zxh_techreport_cvprw25.pdf)]
[[Code](https://github.com/JiangXiaobai00/SML)]

# Honorable Mention
**Team: DGIST**

Members: Jin-Hee Lee, Jae-Keun Lee, Youngho Cheon, Soon Kwon

[[Dowload Technical Report](https://neeharperi.com/files/dgist_techreport_cvprw25.pdf)]
