---
layout: page
title: DeepONet UQ
description: Uncertainty Quantification of Deep Learning Models using Operator Networks
img: assets/img/research/UQ2.png
importance: 2
category: research
---

## Uncertainty Quantification of Deep Learning Models using Operator Networks

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/research/DeepoUQ.png" title="DeepONet UQ" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The focus of this project is on uncertainty quantification, which is crucial in fields such as healthcare, autonomous vehicles, insurance, and transportation. While predictions based on statistical patterns can be insightful, they can also be flawed if overtrusted. Often, when models make inferences on less frequently seen or entirely new data, these inferences tend to be generalizations rather than reliable insights.

Ensuring that the models recognize their uncertainty with unfamiliar data points is vital to preventing incidents or damages caused by faulty predictions, especially in high-stakes situations involving life, death, or significant financial loss.

Currently, the framework is being tested using data from Caltrans' annual traffic dataset. The models are trained on multiple years of data to predict traffic counts during peak hours, while also providing uncertainty quantification for each prediction. This capability enables infrastructure developers to identify areas needing expansion to alleviate traffic congestion and critically assess the reliability of their data for more informed decision-making.

Preliminary results indicate that the new framework is significantly outperforming existing models in both prediction accuracy and uncertainty inference.
