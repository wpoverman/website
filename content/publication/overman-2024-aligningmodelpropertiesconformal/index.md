---
title: Aligning Model Properties via Conformal Risk Control
authors:
  - William Overman
  - Jacqueline Jil Vallon
  - Mohsen Bayati
date: '2024-12-10'
publishDate: '2024-12-10'
abstract: >
  AI model alignment is crucial due to inadvertent biases in training data and the
  underspecified pipeline in modern machine learning, where numerous models with
  excellent test set metrics can be produced, yet they may not meet end-user requirements.
  Recent advances demonstrate that post-training model alignment via human feedback
  can address some of these challenges. However, these methods are often confined
  to settings (such as generative AI) where humans can interpret model outputs and
  provide feedback. In traditional non-generative settings, where model outputs are
  numerical values or classes, detecting misalignment through single-sample outputs is
  highly challenging. In this paper we consider an alternative strategy. We propose interpreting model
  alignment through property testing, defining an aligned model f as one belonging to a
  subset P of functions that exhibit specific desired behaviors. We focus on post-processing
  a pre-trained model f to better align with P using conformal risk control. Specifically,
  we develop a general procedure for converting queries for a given property P to a
  collection of loss functions suitable for use in a conformal risk control algorithm. We
  prove a probabilistic guarantee that the resulting conformal interval around f contains
  a function approximately satisfying P.
publication_types:
- paper-conference
publication: '*Advances in neural information processing systems 37 (NeurIPS 2024)*'
featured: true
links:
  - name: arXiv
    url: https://arxiv.org/abs/2406.18777
image:
  caption: 'Univariate Partial Dependence plot highlighting the main theorem, which shows that we can find a function satisfying the desired property of monotonicity within the conformal band.'
focal_point: ''
preview_only: false
---

---
title: Global Convergence of Multi-Agent Policy Gradient in Markov Potential Games
authors:
- Stefanos Leonardos
- Will Overman
- Ioannis Panageas
- Georgios Piliouras
date: '2022-04-25'
publishDate: '2022-04-25'
publication_types:
- paper-conference
publication: '*International Conference on Learning Representations*'
featured: true
links:
- name: URL
  url: https://openreview.net/forum?id=gfwON7rAm4
image:
  caption: '2-state MDP congestion game considered in the experiments section'
focal_point: ''
preview_only: false
---
