---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[CV in PDF Version](http://aaronhan223.github.io/files/Resume.pdf)

Education
======
* B.Eng. in Electronics and Electrical Engineering, The University of Edinburgh, 2017
* M.S. in Electrical and Computer Engineering, The University of Texas at Austin, 2019
* Ph.D. in Electrical and Computer Engineering, The University of Texas at Austin, 2023 (expected)

Professional Experience
======
* Summer 2022: Research Intern, Google
  * Built different forecasting models to improve workload prediction at machine and VM level
  * Developed effective reconciliation methods for time series with dynamically changing hierarchy

* Summer 2021: Research Intern, Intuit
  * Developed hierarchical time series forecasting models that improved forecasting accuracy
  * Improved efficiency of forecasting pipeline by writing concurrent and multi-GPU program

* Summer 2020: R&D Intern, Salesforce
  * Implemented state-of-the-art text style transfer models and designed a web-based UI for demo
  * Researched on text style transfer on small and unbalanced dataset. Implemented a Bayesian task adaptive meta learning algorithm to fine-tune pre-trained language models

* Summer 2018: Applied Scientist Intern, CognitiveScale
  * Implemented session-based recommendation algorithms and achieved state-of-the-art performance
  * Lead a team project of 5 interns to research ``Ethical AI'' and pitched a business idea to company

Skills
======
* Computer Skills: Python, R, LATEX, Shell Script (proficient); Java, Matlab, Verilog, C/C++, SQL (knowledge of)
* Tools: Tensorflow, PyTorch, TensorBoard, Scikit-Learn, Scipy, etc.
* Specialty: Time series, variational inference, generative models, transformers
* Languages: Mandarin (native), English, French

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
