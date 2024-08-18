---
layout: page
title: Quantitative MRI
description: 
img: assets/img/project_figure/bayesian_r2star.png
importance: 1
category: work
related_publications: true
---

## 1. Robust Quantitative Susceptibility Mapping (QSM)

A bespoke Gaussian-mixture distribution is used to model the long-tailed noise distribution in cases of brain hemorrhage and/or calcification in QSM {% cite robust_qsm %}.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_figure/robust_qsm.png" title="example image" class="img-fluid rounded z-depth-1" %}{:style="margin:auto; display:block;"}
    </div>
</div>
<div class="caption">
    Comparison of the recovered quantitative susceptibility maps using MEDI and the proposed AMP-PE approaches.
</div>

## 2. Bayesian R2* Mapping with Mono-Exponential Decay Model

The mono-exponential decay model of MR signal is incorporated into a Bayesian approach to recover the R2* map via compressive sensing {% cite Bayesian_r2star %}.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_figure/bayesian_r2star.png" title="example image" class="img-fluid rounded z-depth-1" %}{:style="margin:auto; display:block;"}
    </div>
</div>
<div class="caption">
    Comparison of the recovered R2* maps using the conventional L1-norm minimization and the proposed AMP-PE approaches.
</div>


