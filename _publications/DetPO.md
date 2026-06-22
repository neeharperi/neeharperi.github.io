---
title: 'DetPO: In-Context Learning with Multi-Modal LLMs for Few-Shot Object Detection'
collection: publications
permalink: /publications/DetPO
excerpt: ''
date: 2026-06-15
venue: 'ECCV'
paperurl: ''
citation: 'Gare GR, Peri N, Popov M, Jain S, Galeotti J, Ramanan D. DetPO: In-Context Learning with Multi-Modal LLMs for Few-Shot Object Detection In: European Conference on Computer Vision, ECCV 2026'

---

Multi-Modal LLMs (MLLMs) demonstrate strong visual grounding capabilities on popular object detection benchmarks like OdinW-13 and RefCOCO. However, state-of-the-art models still struggle to generalize to out-of-distribution classes, tasks and imaging modalities not typically found in their pre-training. While in-context prompting is a common strategy to improve performance across diverse tasks, we find that it often yields lower detection accuracy than prompting with class names alone. This suggests that current MLLMs cannot yet effectively leverage few-shot visual examples and rich textual descriptions for object detection. Since frontier MLLMs are typically only accessible via APIs, and state-of-the-art open-weights models are prohibitively expensive to fine-tune on consumer-grade hardware, we instead explore black-box prompt optimization for few-shot object detection. To this end, we propose Detection Prompt Optimization (DetPO), a gradient-free test-time optimization approach that refines text-only prompts by maximizing detection accuracy on few-shot visual training examples while calibrating prediction confidence. Our proposed approach yields consistent improvements across generalist MLLMs on Roboflow20-VL and LVIS, outperforming prior black-box approaches by up to 9.7%.

[[Download Paper](https://neeharperi.com/files/DetPO.pdf)]
[[Project Page](https://ggare-cmu.github.io/DetPO/)]
[[Code](https://github.com/ggare-cmu/DetPO)]
