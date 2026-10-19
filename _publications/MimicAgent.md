---
title: 'MimicAgent: Quadruped Skills via Prompt-to-Trajectory Optimization'
collection: publications
permalink: /publications/MimicAgent
excerpt: ''
date: 2026-10-15
venue: 'Under Review'
paperurl: ''
citation: 'Nayak LK, Parameswaran NP, Peri N, Ramanan D. MimicAgent: Quadruped Skills via Prompt-to-Trajectory Generation. Under Review'

---

We present MimicAgent, a prompt-to-trajectory generation framework for learning dynamic quadruped skills. Although reward shaping is extensively used when training quadruped policies, navigating the resulting reward landscape is notoriously difficult, requiring hours of "graduate student descent". Eureka attempts to automate reward design with LLMs, but we find that it struggles to generalize across diverse skills and morphologies. Our key observation is that it is far easier for a human - and by association, an LLM - to generate reference motions than to shape reward functions. Our hypothesis is motivated by the success of example-guided RL for humanoids, which exploits large-scale motion capture datasets as references for training locomotion policies. Unlike humanoids, quadrupeds lack such reference motion data. Towards this end, we propose MimicAgent, an agentic harness that, given a skill prompt, generates quadruped reference trajectories with coding agents. These coarse reference trajectories are then used to train example-guided RL policies that are deployable in simulation and in the real-world. Notably, we find that when prompting Claude Fable 5.1 within our agentic harness, 87% of prompts yield semantically aligned reference trajectories.

[[Download Paper](https://neeharperi.com/files/MimicAgent.pdf)]
[[Project Page](https://luckykantnayak.github.io/mimic-agent/)]
