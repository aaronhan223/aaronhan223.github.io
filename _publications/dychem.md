---
title: "Dynamic Combination of Heterogeneous Models for Hierarchical Time Series"
collection: arxiv
permalink: mecats
excerpt: 
date: 2021-12-22
paperurl: 'https://arxiv.org/pdf/2112.11669.pdf'
paperconf: 'https://ieeexplore.ieee.org/abstract/document/10031198'
code: 'https://github.com/aaronhan223/htsf/tree/main/DYCHEM'
authors: <b>Xing Han</b>, Jing Hu and Joydeep Ghosh
publisher: ICDM 2022 Workshop

---
We introduce a framework to dynamically combine heterogeneous models called DYCHEM, which forecasts a set of time series that are related through an aggregation hierarchy. Different types of forecasting models can be employed as individual “experts” so that each model is tailored to the nature of the corresponding time series. DYCHEM learns hierarchical structures during the training stage to help generalize better across all the time series being modeled and also mitigates coherency issues that arise due to constraints imposed by the hierarchy. To improve the reliability of forecasts, we construct quantile estimations based on the point forecasts obtained from combined heterogeneous models. The resulting quantile forecasts are nearly coherent and independent of the choice of forecasting models. We conduct a comprehensive evaluation of both point and quantile forecasts for hierarchical time series (HTS), including public data and user records from a large financial software company. In general, our method is robust, adaptive to datasets with different properties, and highly configurable and efficient for large-scale forecasting pipelines.


[Arxiv](https://arxiv.org/pdf/2112.11669.pdf) [Conference](https://ieeexplore.ieee.org/abstract/document/10031198) [Code](https://github.com/aaronhan223/htsf/tree/main/DYCHEM)

Recommended citation:
<pre>
@article{han2021mecats,
  title={MECATS: Mixture-of-Experts for Quantile Forecasts of Aggregated Time Series},
  author={Han, Xing and Hu, Jing and Ghosh, Joydeep},
  journal={arXiv preprint arXiv:2112.11669},
  year={2021}
}
</pre>