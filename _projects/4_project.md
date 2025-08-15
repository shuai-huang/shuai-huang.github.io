---
layout: page
title: Nonconvex Quadratic System
description: Convergence analysis around the global optimum of nonconvex quadratic system
img: assets/img/project_figure/nonconvex_opt_basin.png
importance: 4
category: work
related_publications: true
---

## 1. Global Convergence of Nonconvex Quadratic Systems

A basin of attraction exists around the global optimum of a nonconvex quadratic system {% cite nonconvex_quadratic %}. When the initialization is inside the basin of attraction, the gradient descent updates converge linearly toward the global optimum.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_figure/nonconvex_opt_basin.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    
</div>

## 2. Reconstructing Point Sets from Distance Distributions

A set of points on a line or a loop is reconstructed from their unlabelled pairwise distances via a nonconvex quadratic formulation {% cite uDGP_1D %}.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_figure/partial_digestion.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A DNA sequence (line) with 5 segmentation sites is reconstructed from its random segments.
</div>
