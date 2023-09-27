---
title: "Split Localized Conformal Prediction"
collection: arxiv
permalink: slcp
excerpt: 
date: 2022-6-27
paperurl: 'https://arxiv.org/pdf/2206.13092.pdf'
paperconf: 
code: 'https://github.com/aaronhan223/SLCP'
authors: <b>Xing Han</b>, Ziyang Tang, Joydeep Ghosh and Qiang Liu
publisher: ICML 2021 DFUQ Workshop

---
Conformal prediction is a simple and powerful tool that can quantify uncertainty without any distributional assumptions. However, existing methods can only provide an average coverage guarantee, which is not ideal compared to the stronger conditional coverage guarantee. Although achieving exact conditional coverage is proven to be impossible, approximating conditional coverage is still an important research direction. In this paper, we propose a modified non-conformity score by leveraging local approximation of the conditional distribution. The modified score inherits the spirit of split conformal methods, which is simple and efficient compared with full conformal methods but better approximates conditional coverage guarantee. Empirical results on various datasets, including a high dimension age regression on image, demonstrate that our method provides tighter intervals compared to existing methods.


[Arxiv](https://arxiv.org/pdf/2206.13092.pdf) [Code](https://github.com/aaronhan223/SLCP)

Recommended citation:
<pre>
@article{han2022split,
  title={Split Localized Conformal Prediction},
  author={Han, Xing and Tang, Ziyang and Ghosh, Joydeep and Liu, Qiang},
  journal={arXiv preprint arXiv:2206.13092},
  year={2022}
}
</pre>