---
permalink: /research/
title: Research
---
## Publications

**On the Use of the Synthetic Difference-in-Differences Approach with(-out) Covariates: The Case Study of the Brexit Referendum** (with Artūras Juodis and Esther de Brabander). 2025. *Econometric Reviews* &bull; <small>[Video of online seminar](https://www.youtube.com/watch?v=ukQQ7CLO6bI)</small>
<details>
  <summary>
    <small>Abstract</small>
  </summary> 
  <small>
The Synthetic Control (SC) method has been a popular and dominant method to evaluate treatment and intervention effects in the last two decades. The method is powerful yet very intuitive to use both for empirical researchers and policy experts, but is not without shortcomings. As a response to this, the new Demeaned SC (DSC) and Synthetic Differencein-differences (SDID) approaches were introduced in the literature. In this paper, we evaluate the relative benefits of using DSC and SDID using in-sample placebo analysis on the real data on the Brexit referendum, as well as an extensive Monte Carlo study. Overall, using the SDID methodology, we find that the estimated effect of the Brexit referendum on UK GDP at the end of 2018 and 2019 is higher than previously documented in the literature.
  </small>
</details><br>

## Work in Progress

**Bounds on Average Effects in Network Formation Models** (with [Cavit Pakel](https://cavitpakel.github.io/)). 

## Working papers

**A Pairwise Differencing Distribution Regression Approach for Network Models**. 2026. (submitted) &bull; <small>[Download paper](http://gabrielaszini.github.io/files/GabrielaSzini_PD_Aug2026.pdf)</small> &bull; <small>[Supplemental Appendix](http://gabrielaszini.github.io/files/GabrielaSzini_PD_Aug2026_Supplemental.pdf)</small>

<details>
  <summary>
    <small>Abstract</small>
  </summary>
  <small>
I develop an estimation and inference framework for distribution regression in dyadic network settings with two-way fixed effects that vary across thresholds of the outcome. I show that identification of the structural parameters is achieved through binarization of the outcome at each threshold, and estimate the model by conditional maximum likelihood, which "differences out" the fixed effects and circumvents the incidental parameter problem. The estimator remains asymptotically unbiased under sparsity, whether from the network structure or binarization at extreme thresholds. The second novelty is to establish the joint asymptotic distribution of the estimators across multiple thresholds with different convergence rates, and to develop simultaneous confidence bands and tests for equality of coefficients across thresholds. Monte Carlo simulations confirm small bias, valid inference, and correct simultaneous coverage under sparsity. An application to bilateral trade finds that coefficients vary substantially across the distribution, with equality rejected for key trade barriers.
  </small>
</details><br>

**On the Use of U-statistics for linear dyadic interaction models**. 2023. &bull; <small>[arXiv](https://arxiv.org/abs/2309.02089)</small>
<details>
  <summary>
    <small>Abstract</small>
  </summary> 
  <small>
Even though dyadic regressions are widely used in empirical applications, the (asymptotic) properties of estimation methods only began to be studied recently in the literature. This paper aims to provide in a step-by-step manner how U-statistics tools can be applied to obtain the asymptotic properties of pairwise differences estimators for a two-way fixed effects model of dyadic interactions. More specifically, we first propose an estimator for the model that relies on pairwise differencing such that the fixed effects are differenced out. As a result, the summands of the influence function will not be independent anymore, showing dependence on the individual level and translating to the fact that the usual law of large numbers and central limit theorems do not straightforwardly apply. To overcome such obstacles, we show how to generalize tools of U-statistics for single-index variables to the double-indices context of dyadic datasets. A key result is that there can be different ways of defining the Hajek projection for a directed dyadic structure, which will lead to distinct, but equivalent, consistent estimators for the asymptotic variances. The results presented in this paper are easily extended to non-linear models.
  </small>
</details>





[//]: This java script is the button to show abstract
<script>
  function visib(id) {
    var x = document.getElementById(id);
    var triangle = x.previousElementSibling.firstElementChild;

    if (x.style.display === "block") {
      x.style.display = "none";
      triangle.style.transform = "rotate(0deg)";  /* Rotate back to 0 degrees */
    } else {
      x.style.display = "block";
      triangle.style.transform = "rotate(90deg)";  /* Rotate to 90 degrees */
    }
  }
</script>

<style>
  .triangle {
    width: 0;
    height: 0;
    border-top: 5px solid transparent;  /* Change to border-top */
    border-bottom: 5px solid transparent;  /* Change to border-bottom */
    border-left: 10px solid black;  /* Change to border-left */
    display: inline-block;
    margin-right: 5px;
    transition: transform 0.3s ease;
  }
  details[open] .triangle {
    transform: rotate(90deg);
  }
</style>

