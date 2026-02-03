---
title: "Designing Robust Transformers using Robust Kernel Density Estimation"
date: 2022-10-11
selected: true
authors:
  - "Xing Han"
  - "Tongzheng Ren"
  - "Tan Minh Nguyen"
  - "Khai Nguyen"
  - "Joydeep Ghosh"
  - "Nhat Ho"
pub: "37th Conference on Neural Information Processing Systems (NeurIPS 2023)"
abstract: "Recent advances in Transformer architecture have empowered its empirical success in various tasks across different domains. However, existing works mainly focus on improving the standard accuracy and computational cost, without considering the robustness of contaminated samples. Existing work has shown that the self-attention mechanism, which is the center of the Transformer architecture, can be viewed as a non-parametric estimator based on the well-known kernel density estimation (KDE). This motivates us to leverage the robust kernel density estimation (RKDE) in the self-attention mechanism, to alleviate the issue of the contamination of data by down-weighting the weight of bad samples in the estimation process. The modified self-attention mechanism can be incorporated into different Transformer variants. Empirical results on language modeling and image classification tasks demonstrate the effectiveness of this approach."
links:
  Arxiv:
    url: "https://arxiv.org/pdf/2210.05794.pdf"
---
