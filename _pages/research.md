---
permalink: /research/
title: Research
---
## Work in Progress

**A Pairwise Differencing Distribution Regression Approach for Network Models**. 2025. &bull; <small>[Download paper](http://gabrielaszini.github.io/files/GabrielaSzini_JMP.pdf)</small>

<details>
  <summary>
    <small>Abstract</small>
  </summary>
  <small>
This paper proposes a novel estimation method for distribution regressions in a network setting, considering the effects of covariates on the entire outcome distribution rather than just on the mean. I adopt a semiparametric approach, taking into account two-way unit-specific effects that are treated as fixed parameters to be estimated. Thus, I extend the standard distribution regression approach to a network setting by estimating multiple binary choice models with twoway fixed effects for different thresholds of the distribution. Instead of using bias-correction methods to address the incidental parameter problem, as previously proposed in the literature, I propose to employ a conditional maximum-likelihood approach (Charbonneau (2017), Jochmans (2018)) that differentiates out the unit-specific effects. This method yields consistent point estimates that converge at a parametric rate and remain asymptotically unbiased in the tails of the outcome distribution, where the underlying network can be seen as sparse. Monte Carlo simulations validate these findings for both single cut-offs and the overall outcome distribution. The empirical application focuses on gravity equations for bilateral trade, demonstrating the effectiveness of the proposed approach in cases where the outcome variable is bounded below at zero.
  </small>
</details><br>

**Bounds on Average Effects in Network Formation Models** (with [Cavit Pakel](https://cavitpakel.github.io/)). 

## Working papers

**On the Use of the Synthetic Difference-in-Differences Approach with(-out) Covariates: The Case Study of the Brexit Referendum** (with Artūras Juodis and Esther de Brabander). 2023. *R&R Econometric Reviews* &bull; <small>[Download paper](http://gabrielaszini.github.io/files/deBrabanderJuodisSzini_Brexit_2023.pdf)</small> &bull; <small>[Download supplementary appendix](http://gabrielaszini.github.io/files/deBrabanderJuodisSzini_Brexit_appendix_2023.pdf)</small> &bull; <small>[Video of online seminar](https://www.youtube.com/watch?v=ukQQ7CLO6bI)</small>
<details>
  <summary>
    <small>Abstract</small>
  </summary> 
  <small>
The Synthetic Control (SC) method has been a popular and dominant method to evaluate treatment and intervention effects in the last two decades. The method is powerful yet very intuitive to use both for empirical researchers and policy experts, but is not without shortcomings. As a response to this, the new Demeaned SC (DSC) and Synthetic Differencein-differences (SDID) approaches were introduced in the literature. In this paper, we evaluate the relative benefits of using DSC and SDID using in-sample placebo analysis on the real data on the Brexit referendum, as well as an extensive Monte Carlo study. Overall, using the SDID methodology, we find that the estimated effect of the Brexit referendum on UK GDP at the end of 2018 and 2019 is higher than previously documented in the literature.
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

