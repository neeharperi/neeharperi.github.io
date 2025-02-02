---
title: 'Planning with Adaptive World Models for Autonomous Driving'
collection: publications
permalink: /publications/AdaptiveDriver
excerpt: ''
date: 2025-01-01
venue: 'ICRA'
paperurl: ''
citation: 'AB Vasudevan, Peri N, J Schneider, Ramanan D. Planning with Adaptive World Models for Autonomous Driving In: International Conference on Robotics and Automation, ICRA 2025'

---

Motion planning is crucial for safe navigation in complex urban environments. Historically, motion planners (MPs) have been evaluated with procedurally-generated simulators like CARLA. However, such synthetic benchmarks do not capture real-world multi-agent interactions. nuPlan, a recently released MP benchmark, addresses this limitation by augmenting real-world driving logs with closed-loop simulation logic, effectively turning the fixed dataset into a reactive simulator. We analyze the characteristics of nuPlan’s recorded logs and find that each city has its own unique driving behaviors, suggesting that robust planners must adapt to different environments. We learn to model such unique behaviors with BehaviorNet, a graph convolutional neural network (GCNN) that predicts reactive agent behaviors using features derived from recentlyobserved agent histories; intuitively, some aggressive agents may tailgate lead vehicles, while others may not. To model such phenomena, BehaviorNet predicts the parameters of an agent’s motion controller rather than directly predicting its spacetime trajectory (as most forecasters do). Finally, we present AdaptiveDriver, a model-predictive control (MPC) based planner that unrolls different world models conditioned on BehaviorNet’s predictions. Our extensive experiments demonstrate that AdaptiveDriver achieves state-of-the-art results on the nuPlan closed-loop planning benchmark, improving over prior work by 2% on Test-14 Hard R-CLS, and  generalizes even when evaluated on never-before-seen cities.

[[Download Paper](https://neeharperi.com/files/AdaptiveDriver.pdf)]
[[Project Page](https://arunbalajeev.github.io/world_models_planning/world_model_paper.html)]
