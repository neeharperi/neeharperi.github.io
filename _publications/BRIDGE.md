---
title: 'Bridging Handheld and Teleoperated Supervision for Contact-Rich Manipulation via State-Gated Experts'
collection: publications
permalink: /publications/BRIDGE
excerpt: ''
date: 2026-10-15
venue: 'Under Review'
paperurl: ''
citation: 'Surendran V, Peri N, Watkins D. Bridging Handheld and Teleoperated Supervision for Contact-Rich Manipulation via State-Gated Experts. Under Review'

---

Handheld data collection systems, such as the Universal Manipulation Interface (UMI), enable scalable data collection across diverse environments but only capture observed actions rather than the desired actions executed by a robot controller. In contrast, teleoperation captures desired actions directly, but is prohibitively time-consuming to collect. We revisit this trade-off through the lens of label validity across task phases. We observe that handheld trajectories provide valid supervision in tolerant, free-space phases, but lack dynamic feasibility in contact-sensitive phases, where tracking observed trajectories at high stiffness produces large, unsafe contact forces. We study the interaction between these two supervision types for contact-rich manipulation and find that training policies that combine handheld data with a small number of targeted teleoperated demonstrations provides an efficient hybrid strategy. Specifically, rather than teleoperating the entire task, we only collect partial teleoperated demonstrations for task segments where base handheld policies fail. However, naively mixing handheld and teleoperated phase-specific data yields worse performance than training on handheld data alone. To address this mismatch between observed and desired supervision, we propose Bi-modal Routing for Imitation Data via Gated Experts (BRIDGE), a mixture of diffusion policy experts that routes between specialist task phase heads conditioned on the current robot state. Notably, our approach produces measurably lower end-effector forces under contact and improves success rates over handheld-only baselines by up to 36.7% across three contact-rich manipulation tasks.

[[Download Paper](https://neeharperi.com/files/BRIDGE.pdf)]
[[Project Page](https://nperi-rai.github.io/bridge-project/)]
