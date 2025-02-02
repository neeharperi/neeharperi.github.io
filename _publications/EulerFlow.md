---
title: 'Neural Eulerian Scene Flow Fields'
collection: publications
permalink: /publications/EulerFlow
excerpt: ''
date: 2025-01-01
venue: 'ICLR'
paperurl: ''
citation: 'Vedder K, Peri N, Khatri I, S Li, E Eaton, M Kocamaz, Y Wang, Ramanan D, J Pehserl. Neural Eulerian Scene Flow Fields In: International Conference on Learning Representations, ICLR 2025'

---

We reframe scene flow as the task of estimating a continuous space-time ordinary differential equation (ODE) that describes motion for an entire observation sequence, represented with a neural prior. Our method, EulerFlow, optimizes this neural prior estimate against several multi-observation reconstruction objectives, enabling high quality scene flow estimation via self-supervision on real-world data. EulerFlow works out-of-the-box without tuning across multiple domains, including large-scale autonomous driving scenes and dynamic tabletop settings. Remarkably, EulerFlow produces high quality flow estimates on small, fast moving objects like birds and tennis balls, and exhibits emergent 3D point tracking behavior by solving its estimated ODE over long-time horizons. On the Argoverse 2 2024 Scene Flow Challenge, EulerFlow outperforms all prior art, surpassing the next-best unsupervised method by more than 2.5×, and even exceeding the next-best supervised method by over 10%.

[[Download Paper](https://neeharperi.com/files/EulerFlow.pdf)]
[[Project Page](https://vedder.io/eulerflow)]
[[Code](https://github.com/kylevedder/SceneFlowZoo)]
