---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Current Projects
=====
- ***LRSPDY: Low-Rank Decomposition with Speedup Guarantees:*** I am working on combining various low-rank decomposition techniques with [SPDY](https://arxiv.org/abs/2201.13096).
- ***Loseless Adaptive Gradient Compression:***
I am working on a real-time adaptive algorithm that determines the lossless compression based on a composite loss inspired by [AMC](https://arxiv.org/abs/1802.03494) paper which combines layer-wise compression errors and the number of parameters of the model. The problem that we are looking at is similar as the one in [ACCORDION](https://arxiv.org/abs/2010.16248) and [AdaComp](https://arxiv.org/abs/1712.02679).
- ***Understanding The Interplay between Privacy, Communication, and Utility in Federated Learning:*** I am exploring communication and privacy challenges inherent to federated learning as my undergrad thesis. My ultimate goal is to build upon the following fantastic papers:
[vqSGD](https://arxiv.org/abs/1911.07971),
[QSGD](https://arxiv.org/abs/1610.02132),
[cpSGD](https://arxiv.org/abs/1805.10559),
[Communication-Privacy-Accuracy Trilemma](https://arxiv.org/abs/2007.11707)

Previous Projects
=====
- ***L-GreCo: A Framework for Layerwise Adaptive Gradient Compression:*** I worked on an algorithm to obtain optimal compression of gradients for distributed neural networks regarding both training accuracy and compression criteria. For this purpose, we formulated the problem of finding optimal layerwise compression as a knapsack problem that a dynamic programming approach can solve. Our solution preserves baseline accuracy while increasing the compression ratio and speed for all different compression schemes (sparsification, low-rank, and quantization) on various tasks and model architectures. We are writing a paper on this which is going to be submitted to MlSys 2023.
- ***New Results on AVCs With Omniscient and Myopic Adversaries:*** I worked on communication channels in the presence of myopic adversaries. We extended the well-known Elias-Bassalygo upper bound to this regime, resulting in a paper accepted for presentation at ISIT 2022. You can find links to my presentation in the "Talks" section.
- ***Learning at The Edge:*** To make models runnable on edge devices with limited resources, I used low-rank representation techniques to reduce the neural network’s inference time and memory requirement.