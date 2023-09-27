---
title: Designing Robust Transformers using Robust Kernel Density Estimation"
collection: arxiv
permalink: rkde
excerpt: 
date: 2022-10-11
paperurl: 'https://arxiv.org/pdf/2210.05794.pdf'
paperconf: 
code: 
authors: <b>Xing Han</b>, Tongzheng Ren, Tan Minh Nguyen, Khai Nguyen, Joydeep Ghosh and Nhat Ho
publisher: 37th Conference on Neural Information Processing Systems (NeurIPS 2023).

---
Recent advances in Transformer architecture have empowered its empirical success in various tasks across different domains. However, existing works mainly focus on improving the standard accuracy and computational cost, without considering the robustness of contaminated samples. Existing work has shown that the self-attention mechanism, which is the center of the Transformer architecture, can be viewed as a non-parametric estimator based on the well-known kernel density estimation (KDE). This motivates us to leverage the robust kernel density estimation (RKDE) in the self-attention mechanism, to alleviate the issue of the contamination of data by down-weighting the weight of bad samples in the estimation process. The modified self-attention mechanism can be incorporated into different Transformer variants. Empirical results on language modeling and image classification tasks demonstrate the effectiveness of this approach.


[Arxiv](https://arxiv.org/pdf/2210.05794.pdf) 

Recommended citation:
<pre>
@article{han2022robustify,
  title={Robustify Transformers with Robust Kernel Density Estimation},
  author={Han, Xing and Ren, Tongzheng and Nguyen, Tan Minh and Nguyen, Khai and Ghosh, Joydeep and Ho, Nhat},
  journal={arXiv preprint arXiv:2210.05794},
  year={2022}
}
</pre>