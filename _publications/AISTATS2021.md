---
title: "Simultaneously Reconciled Quantile Forecasting of Hierarchically Related Time Series"
collection: arxiv
permalink: sharq
excerpt: 
date: 2021-1-21
paperurl: 'https://arxiv.org/pdf/2102.12612.pdf'
paperconf: 'https://proceedings.mlr.press/v130/han21a.html'
code: 'https://github.com/aaronhan223/htsf/tree/main/SHARQ'
authors: <b>Xing Han</b>, Sambarta Dasgupta and Joydeep Ghosh
publisher: Proceedings of the 24th International Conference on Artificial Intelligence and Statistics (AISTATS) 2021

---
Many real-life applications involve simultaneously forecasting multiple time series that are hierarchically related via aggregation or disaggregation operations. For instance, commercial organizations often want to forecast inventories simultaneously at store, city, and state levels for resource planning purposes. In such applications, it is important that the forecasts, in addition to being reasonably accurate, are also consistent w.r.t one another. Although forecasting such hierarchical time series has been pursued by economists and data scientists, the current state-of-the-art models use strong assumptions, e.g., all forecasts being unbiased estimates, noise distribution being Gaussian. Besides, state-of-the-art models have not harnessed the power of modern nonlinear models, especially ones based on deep learning. In this paper, we propose using a flexible nonlinear model that optimizes quantile regression loss coupled with suitable regularization terms to maintain the consistency of forecasts across hierarchies. The theoretical framework introduced herein can be applied to any forecasting model with an underlying differentiable loss function. A proof of optimality of our proposed method is also provided. Simulation studies over a range of datasets highlight the efficacy of our approach.


[[Arxiv]] [[Conference]] [[Code]]

Recommended citation:
<pre>
@inproceedings{han2021simultaneously,
  title={Simultaneously reconciled quantile forecasting of hierarchically related time series},
  author={Han, Xing and Dasgupta, Sambarta and Ghosh, Joydeep},
  booktitle={International Conference on Artificial Intelligence and Statistics},
  pages={190--198},
  year={2021},
  organization={PMLR}
}
</pre>