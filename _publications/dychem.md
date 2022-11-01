---
title: "MECATS: Mixture-of-Experts for Quantile Forecasts of Aggregated Time Series"
collection: arxiv
permalink: mecats
excerpt: 
date: 2021-12-22
paperurl: 'https://arxiv.org/pdf/2112.11669.pdf'
paperconf: 
code: 'https://github.com/aaronhan223/htsf/tree/main/DYCHEM'
authors: <b>Xing Han</b>, Jing Hu and Joydeep Ghosh
publisher: Arxiv, under review.

---
We introduce a mixture of heterogeneous experts framework called MECATS, which simultaneously forecasts the values of a set of time series that are related through an aggregation hierarchy. Different types of forecasting models can be employed as individual experts so that the form of each model can be tailored to the nature of the corresponding time series. MECATS learns hierarchical relationships during the training stage to help generalize better across all the time series being modeled and also mitigates coherency issues that arise due to constraints imposed by the hierarchy. We further build multiple quantile estimators on top of the point forecasts. The resulting probabilistic forecasts are nearly coherent, distribution-free, and independent of the choice of forecasting models. We conduct a comprehensive evaluation on both point and probabilistic forecasts and also formulate an extension for situations where change points exist in sequential data. In general, our method is robust, adaptive to datasets with different properties, and highly configurable and efficient for large-scale forecasting pipelines.


[Arxiv](https://arxiv.org/pdf/2112.11669.pdf) [Code](https://github.com/aaronhan223/htsf/tree/main/DYCHEM)

Recommended citation:
<pre>
@article{han2021mecats,
  title={MECATS: Mixture-of-Experts for Quantile Forecasts of Aggregated Time Series},
  author={Han, Xing and Hu, Jing and Ghosh, Joydeep},
  journal={arXiv preprint arXiv:2112.11669},
  year={2021}
}
</pre>