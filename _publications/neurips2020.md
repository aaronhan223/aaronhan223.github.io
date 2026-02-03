---
title: "Certified Monotonic Neural Networks"
date: 2020-09-25
id: neurips2020
selected: true
authors:
  - "Xingchao Liu"
  - "Xing Han"
  - "Na Zhang"
  - "Qiang Liu"
pub: "34th Conference on Neural Information Processing Systems (NeurIPS 2020)"
pub_post: "Spotlight"
abstract: "Learning monotonic models with respect to a subset of the inputs is a desirable feature to effectively address the fairness, interpretability, and generalization issues in practice. Existing methods for learning monotonic neural networks either require specifically designed model structures to ensure monotonicity, which can be too restrictive/complicated, or enforce monotonicity by adjusting the learning process, which cannot provably guarantee the learned model is monotonic on selected features. In this work, we propose to certify the monotonicity of the general piece-wise linear neural networks by solving a mixed integer linear programming problem. This provides a new general approach for learning monotonic neural networks with arbitrary model structures. Our method allows us to train neural networks with heuristic monotonicity regularizations, and we can gradually increase the regularization magnitude until the learned network is certified monotonic. Compared to prior work, our method does not require human-designed constraints on the weight space and also yields more accurate approximation. Empirical studies on various datasets demonstrate the efficiency of our approach over the state-of-the-art methods, such as Deep Lattice Networks."
links:
  Arxiv:
    url: "https://arxiv.org/pdf/2011.10219.pdf"
  Conference:
    url: "https://proceedings.neurips.cc/paper/2020/hash/b139aeda1c2914e3b579aafd3ceeb1bd-Abstract.html"
  Code:
    url: "https://github.com/gnobitab/CertifiedMonotonicNetwork"
---
