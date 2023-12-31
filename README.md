
<!-- README.md is generated from README.Rmd. Please edit that file -->

# targetthis <img src="man/figures/logo.png" align="right" height="139" alt="" />

<!-- badges: start -->

[![status](https://www.repostatus.org/badges/latest/concept.svg)](https://www.repostatus.org/#concept)
[![R-CMD-check](https://github.com/PatrickCoyle/targetthis/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/PatrickCoyle/targetthis/actions/workflows/R-CMD-check.yaml)
[![lint](https://github.com/PatrickCoyle/targetthis/actions/workflows/lint.yaml/badge.svg)](https://github.com/PatrickCoyle/targetthis/actions/workflows/lint.yaml)
<!-- badges: end -->

The `targetthis` package extends RStudio to assist in building and
documenting `targets` pipelines. The `targets` package is documented in
[The {targets} R package user
manual](https://books.ropensci.org/targets/)

## Installation

You can install the development version of `targetthis` from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("PatrickCoyle/targetthis")
```

## Feature 1: Shiny gadget to build a new target from available inputs

<figure>
<img src="misc/img1.png"
alt="Using targetthis gadgets in the RStudio IDE" />
<figcaption aria-hidden="true">Using targetthis gadgets in the RStudio
IDE</figcaption>
</figure>

## Feature 2: RStudio addin to load a highlighted target into the global environment

![](misc/img2.png)

It is recommended to bind this addin to a [keyboard
shortcut](https://support.posit.co/hc/en-us/articles/206382178-Customizing-Keyboard-Shortcuts-in-the-RStudio-IDE).

![](misc/img3.png)

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-landau" class="csl-entry">

Landau, William Michael. 2021. “The Targets r Package: A Dynamic
Make-Like Function-Oriented Pipeline Toolkit for Reproducibility and
High-Performance Computing.” *Journal of Open Source Software* 6 (57):
2959. <https://doi.org/10.21105/joss.02959>.

</div>

<div id="ref-R-base" class="csl-entry">

R Core Team. 2019. *R: A Language and Environment for Statistical
Computing*. Vienna, Austria: R Foundation for Statistical Computing.
<https://www.R-project.org>.

</div>

</div>
