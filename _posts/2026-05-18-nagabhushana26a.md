---
title: 'CATFormer: When Continual Learning Meets Spiking Transformers With Dynamic
  Thresholds'
abstract: Although deep neural networks perform extremely well in controlled environments,
  they fail in real-world scenarios where the data isn’t available all at once, and
  the model requires an update to adapt itself to the new data distribution, which
  might or might not follow the initial distribution. Previously acquired knowledge
  is lost during such subsequent updates from new data. a phenomenon commonly known
  as catastrophic forgetting. In contrast, the brain can learn without such catastrophic
  forgetting, irrespective of the number of tasks it encounters. Existing spiking
  neural networks (SNNs) for class-incremental learning (CIL) suffer a sharp performance
  drop as tasks accumulate. We here introduce CATFormer (Context Adaptive Threshold
  Transformer), a scalable framework that overcomes this limitation. We observe that
  the key to preventing forgetting in SNNs lies not only in synaptic plasticity, but
  in modulating neuronal excitability too. At the core of CATFormer is the Dynamic
  Threshold Leaky Integrate-and-Fire (DTLIF) neuron model, which leverages context-adaptive
  thresholds as the primary mechanism for knowledge retention. This is paired with
  a Gated Dynamic Head Selection (G-DHS) mechanism for task-agnostic inference. Extensive
  evaluation on both static (CIFAR-10/100/Tiny-ImageNet) and neuromorphic (CIFAR10-DVS/SHD)
  datasets reveals that CATFormer outperforms existing rehearsal-free CIL algorithms
  across various task splits, establishing it as an ideal architecture for energy-efficient
  and true class incremental learning.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nagabhushana26a
month: 0
tex_title: 'CATFormer: When Continual Learning Meets Spiking Transformers With Dynamic
  Thresholds'
firstpage: 84
lastpage: 92
page: 84-92
order: 84
cycles: false
bibtex_author: Nagabhushana, Vaishnavi and Agrawal, Kartikay and Borthakur, Ayon
author:
- given: Vaishnavi
  family: Nagabhushana
- given: Kartikay
  family: Agrawal
- given: Ayon
  family: Borthakur
date: 2026-05-18
address:
container-title: Proceedings of the First Workshop on NeuroAI Multimodal Intelligence
  @ AAAI 2026
volume: '308'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 5
  - 18
pdf: https://raw.githubusercontent.com/mlresearch/v308/main/assets/nagabhushana26a/nagabhushana26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
