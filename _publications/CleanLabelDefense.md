---
title: "Deep K-NN Defense against Clean-Label Data Poisoning Attacks"
collection: publications
permalink: /publications/CleanLabelDefense
excerpt: ''
date: 2020-01-01
venue: 'ECCVW - Adversarial Robustness in the Real World'
paperurl: ''
citation: 'Peri N, Gupta N, Huang WR, Fowl L, Zhu C, Feizi S, Goldstein T, Dickerson JP. Deep k-NN Defense
against Clean-Label Data Poisoning Attacks. In: European Conference on Computer Vision Workshops, ECCVW (2020)'

---
Targeted clean-label data poisoning is a type of adversarial attack on machine learning systems in which an adversary injects a few correctly-labeled, minimally-perturbed samples into the training data, causing a model to misclassify a particular test sample during inference. Although defenses have been proposed for general poisoning attacks, no reliable defense for clean-label attacks has been demonstrated, despite the attacks' effectiveness and realistic applications. In this work, we propose a simple, yet highly-effective Deep k-NN defense against both feature collision and convex polytope clean-label attacks on the CIFAR-10 dataset. We demonstrate that our proposed strategy is able to detect over 99% of poisoned examples in both attacks and remove them without compromising model performance. Additionally, through ablation studies, we discover simple guidelines for selecting the value of k as well as for implementing the Deep k-NN defense on real-world datasets with class imbalance. Our proposed defense shows that current clean-label poisoning attack strategies can be annulled, and serves as a strong yet simple-to-implement baseline defense to test future clean-label poisoning attacks. Our code is available on [GitHub](https://github.com/neeharperi/DeepKNNDefense)

[[Video](https://youtu.be/x9VYZCVevAM)]
[[Download Paper](http://neeharperi.com/files/CleanLabelDefense.pdf)]
