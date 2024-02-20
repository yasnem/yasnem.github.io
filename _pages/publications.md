---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* **Estimation Beyond Data Reweighting: Kernel Method of Moments**\
Heiner Kremer, Yassine Nemmour, Bernhard Schölkopf, Jia-Jie Zhu\
International Conference on Machine Learning (**ICML**) 2023\
[arXiv](https://arxiv.org/abs/2305.10898)

* **Maximum Mean Discrepancy Distributionally Robust Nonlinear Chance-Constrained Optimization with Finite-Sample Guarantee**\
Yassine Nemmour, Heiner Kremer, Bernhard Schölkopf, Jia-Jie Zhu\
IEEE Conference on Decision and Control (**CDC**) 2022\
[arXiv](https://arxiv.org/abs/2204.11564)

* **Distributionally robust chance constrained programs using maximum mean discrepancy**\
Yassine Nemmour, Heiner Kremer, Bernhard Schölkopf, Jia-Jie Zhu\
*NeurIPS 2021, Safe and Robust Control of Uncertain Systems Workshop*

* **Adversarially Robust Kernel Smoothing**\
Jia-Jie Zhu, Christina Kouridi, Yassine Nemmour, Bernhard Schölkopf\
International Conference on Artificial Intelligence and Statistics **AISTATS** 2022, **Oral**\
[arXiv](https://arxiv.org/abs/2102.08474)
* **Shallow Representation is Deep: Learning Uncertainty-aware and Worst-case Random Feature Dynamics**\
Diego Agudelo-España, Yassine Nemmour, Bernhard Schölkopf, Jia-Jie Zhu\
IEEE Conference on Decision and Control **CDC** 2022\
[arXiv](https://arxiv.org/abs/2106.13066)
* **Distributional Robustness Regularized Scenario Optimization with Application to Model Predictive Control**\
Yassine Nemmour, Bernhard Schölkopf, Jia-Jie Zhu\
Learning for Dynamics and Control **L4DC** 2021\
[arXiv](https://arxiv.org/abs/2110.13588)
* **Reliable real-time ball tracking for robot table tennis**\
Sebastian Gomez-Gonzalez, Yassine Nemmour, Bernhard Schölkopf, Jan Peters\
**Robotics** 2019\
[mdpi](https://www.mdpi.com/2218-6581/8/4/90)
