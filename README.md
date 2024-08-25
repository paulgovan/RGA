
<!-- README.md is generated from README.Rmd. Please edit that file -->

# WeibullR.rga

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/WeibullR.rga)](https://CRAN.R-project.org/package=WeibullR.rga)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

Reliability Growth Analysis in R.

## Installation

You can install the development version of WeibullR.rga like so:

``` r
devtools::install_github('paulgovan/weibullr.rga')
```

## Example

Here is a basic example of Reliability Growth Analysis:

``` r
library(WeibullR.rga)
times <- c(100, 200, 300, 400, 500)
failures <- c(1, 2, 1, 3, 2)
result <- rga(times, failures)
plot_rga(times, failures, result)
```

<img src="man/figures/README-example-1.png" width="100%" />

## Code of Conduct

Please note that the WeibullR.rga project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
