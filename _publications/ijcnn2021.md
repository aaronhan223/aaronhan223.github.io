---
title: "Model-Agnostic Explanations using Minimal Forcing Subsets"
collection: arxiv
permalink: mfs
excerpt: 
date: 2021-7-18
paperurl: 'https://arxiv.org/pdf/2011.00639.pdf'
paperconf: 'https://ieeexplore.ieee.org/document/9533992'
code: 
authors: <b>Xing Han</b> and Joydeep Ghosh
publisher: 2021 International Joint Conference on Neural Networks (IJCNN).

---
How can we find a subset of training samples that are most responsible for a specific prediction made by a complex black-box machine learning model? More generally, how can we explain the model's decisions to end-users in a transparent way? We propose a new model-agnostic algorithm to identify a minimal set of training samples that are indispensable for a given model's decision at a particular test point, i.e., the model's decision would have changed upon the removal of this subset from the training dataset. Our algorithm identifies such a set of ``indispensable'' samples iteratively by solving a constrained optimization problem. Further, we speed up the algorithm through efficient approximations and provide theoretical justification for its performance. To demonstrate the applicability and effectiveness of our approach, we apply it to a variety of tasks including data poisoning detection, training set debugging and understanding loan decisions. The results show that our algorithm is an effective and easy-to-comprehend tool that helps to better understand local model behavior, and therefore facilitates the adoption of machine learning in domains where such understanding is a requisite. 


[Arxiv](https://arxiv.org/pdf/2011.00639.pdf) [Conference](https://ieeexplore.ieee.org/document/9533992)

Recommended citation:
<pre>
@inproceedings{han2021model,
  title={Model-agnostic explanations using minimal forcing subsets},
  author={Han, Xing and Ghosh, Joydeep},
  booktitle={2021 International Joint Conference on Neural Networks (IJCNN)},
  pages={1--8},
  year={2021},
  organization={IEEE}
}
</pre>