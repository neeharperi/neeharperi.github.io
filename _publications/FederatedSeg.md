---
title: "Semi-Supervised Federated Multi-Organ Segmentation with Partial Labels"
collection: publications
permalink: /publications/FederatedSeg
excerpt: ''
date: 2024-06-01
venue: 'AAPM'
paperurl: ''
citation: 'Pemmaraju R, Peri N. Semi-Supervised Federated Multi-Organ Segmentation with Partial Labels. In: American Association of Physicists in Medicine, AAPM 2024'

---
Purpose: Federated learning enables the decentralized training of machine learning models without sharing sensitive data, making it well-suited for medical image analysis tasks where patient privacy is of major concern. Current federated multi-organ segmentation solutions require label consistency across participating centers, which may be burdensome in clinical settings with varying data annotation protocols. In this work, we develop a federated learning framework for decentralized training of neural networks for multi-organ segmentation from partially-labeled datasets.

Methods: To address the issue of incomplete contour sets, we introduce an implicit multi-encoder UNet (IME-UNet) that decomposes the multi-organ segmentation task into individual organ tasks. This allows for extraction of organ-specific features from expert centers with low computational cost. We also utilize a pseudo-labeling strategy to create complete multi-organ segmentation maps from partial labels. We train our model with a standard supervised loss on ground-truth labels and a consistency loss on pseudo-labels.

Results: Our models segment 12 organs from a set of 4 public abdominal CT datasets (AMOS, LITS, TCIA, and WORD) with partial organ labels. Results on BTCV, an out-of-federation dataset of 30 images, indicates that IME-UNet significantly improves over our baseline UNet model (0.773 ± 0.16 vs 0.526 ± 0.12 average DICE). While our federated model shows modest improvements over the baseline for large organs in all datasets, performance gains are most notable for small organs with few examples (e.g. Adrenal glands). We posit that this improvement can be primarily attributed to the pseudo-label consistency loss.

Conclusion: In this work, we introduce a framework for training multi-organ segmentation models using datasets with partial labels. We demonstrate that naively training federated UNets with partial labels yields sub-optimal performance, and show that IME-UNet significantly improves over the baseline, particularly for small organs with few labeled examples
