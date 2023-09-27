---
title: "A Novel Control-Variates Approach for Performative Gradient-Based Learners with Missing Data"
collection: arxiv
permalink: cvige
excerpt: 
date: 2023-6-18
paperurl: 'https://arxiv.org/pdf/2011.00639.pdf'
paperconf: 'https://ieeexplore.ieee.org/abstract/document/10191415'
code: 
authors: <b>Xing Han</b>, Jing Hu and Joydeep Ghosh
publisher: 2023 International Joint Conference on Neural Networks (IJCNN).

---
We propose a new, principled approach to tackling missing data problems that can reduce both bias and variance of any (stochastic) gradient descent-based predictive model that is learned on such data. The proposed method can use an arbitrary (and potentially biased) imputation model to fill in the missing values, as it corrects the biases introduced by imputation with a control variates method, leading to an unbiased estimation for gradient updates. Theoretically, we prove that our control variates approach improves the convergence of stochastic gradient descent under common missing data settings. Empirically, we show that our method yields superior performance as compared to the results obtained using competing imputation methods, on various applications, across different missing data patterns.


[Conference](https://ieeexplore.ieee.org/abstract/document/10191415)

Recommended citation:
<pre>
@inproceedings{han2023novel,
  title={A Novel Control-Variates Approach for Performative Gradient-Based Learners with Missing Data},
  author={Han, Xing and Hu, Jing and Ghosh, Joydeep},
  booktitle={2023 International Joint Conference on Neural Networks (IJCNN)},
  pages={1--8},
  year={2023},
  organization={IEEE}
}
</pre>