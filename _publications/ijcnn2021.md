---
title: "Model-Agnostic Explanations using Minimal Forcing Subsets"
collection: arxiv
permalink: mfs
excerpt: 
date: 2021-7-18
paperurl: 'https://arxiv.org/pdf/2011.00639.pdf'
paperconf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9533992'
code: 
authors: <b>Xing Han</b>, and Joydeep Ghosh
publisher: 2021 International Joint Conference on Neural Networks (IJCNN).

---
Learning monotonic models with respect to a subset of the inputs is a desirable feature to effectively address the fairness, interpretability, and generalization issues in practice. Existing methods for learning monotonic neural networks either require specifically designed model structures to ensure monotonicity, which can be too restrictive/complicated, or enforce monotonicity by adjusting the learning process, which cannot provably guarantee the learned model is monotonic on selected features. In this work, we propose to certify the monotonicity of the general piece-wise linear neural networks by solving a mixed integer linear programming problem. This provides a new general approach for learning monotonic neural networks with arbitrary model structures. Our method allows us to train neural networks with heuristic monotonicity regularizations, and we can gradually increase the regularization magnitude until the learned network is certified monotonic. Compared to prior work, our method does not require human-designed constraints on the weight space and also yields more accurate approximation. Empirical studies on various datasets demonstrate the efficiency of our approach over the state-of-the-art methods, such as Deep Lattice Networks.


[[Arxiv]](https://arxiv.org/pdf/2011.10219.pdf) [[Conference]](https://proceedings.neurips.cc/paper/2020/file/b139aeda1c2914e3b579aafd3ceeb1bd-Paper.pdf) [[Code]](https://github.com/gnobitab/CertifiedMonotonicNetwork)

Recommended citation:
<pre>
@article{liu2020certified,
  title={Certified monotonic neural networks},
  author={Liu, Xingchao and Han, Xing and Zhang, Na and Liu, Qiang},
  journal={Advances in Neural Information Processing Systems},
  volume={33},
  pages={15427--15438},
  year={2020}
}
</pre>