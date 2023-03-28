---
permalink: /equationsandproofs/
title: "Equations & Proofs"
---

This is a neat list of some equations and proofs I encountered during my readings/learning. 
<br>
<br>
In a way, this is like catching pokemon haha.
<br>
<br>
<br>
<br>
## Neural Networks: A Crude Preceptron Objective Function (Single Layer)
<br>
Let training instance be of the form $(X,y)$. Note, sign is a step function. Let $\bar{X} = [x_1, . . . x_d]$ as inputs and $y \in (-1, +1)$ whilst, weights are denoted as $\bar{W} = [w_1, . . . w_d]$. Let $\hat{y}$ be the prediction, thus:

$$
  \hat{y} = sign(\bar{W} \times \bar{X}) = sign(\sum_{j=1}^d w_jx_j)
$$
