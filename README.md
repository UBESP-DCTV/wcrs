
<!-- README.md is generated from README.Rmd. Please edit that file -->

<!-- badges: start -->

[![R build
status](https://github.com/UBESP-DCTV/wcrs/workflows/R-CMD-check/badge.svg)](https://github.com/UBESP-DCTV/wcrs/actions)
[![Coverage
status](https://codecov.io/gh/UBESP-DCTV/wcrs/branch/master/graph/badge.svg)](https://codecov.io/gh/UBESP-DCTV/wcrs)

[![CRAN
status](https://www.r-pkg.org/badges/version/wcrs)](https://cran.r-project.org/package=wcrs)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
<!-- badges: end -->

# wcrs

The goal of *wcrs* is to provide a series of tools to implement a
Weighted Competing Risks analysis in a unified framework.

The package is designed to estimate weighted cumulative incidence
functions in a competing risks setting, plot them and return useful
statistical summaries, such as 1-year cumulative incidence of cardiac
death in subjects who had heart failure. Furthermore, functions to fit
weighted cause-specific hazard models are also available.

The functions are targeted for Propensity Score Inverse Probability
Weighting (PS-IPW) analyses, where weights derived from estimated PS are
used to approximate a randomized study.

## Installation

You can install the development version from
[GitHub](https://github.com/) with the following procedure:

``` r
# install.packages("devtools")
remotes::install_github("UBESP-DCTV/wcrs")
```

## Feature request

If you need some more features, please open an issue on
[github](https://github.com/UBESP-DCTV/wcrs/issues).

## Bug reports

If you encounter a bug, please file a
[reprex](https://github.com/tidyverse/reprex) (minimal reproducible
example) on [github](https://github.com/UBESP-DCTV/wcrs/issues).

## Code of Conduct

Please note that the ‘wcrs’ project is released with a [Contributor Code
of Conduct](.github/CODE_OF_CONDUCT.md). By contributing to this
project, you agree to abide by its terms.

## Warnings

The package is currently under active development. The functions are not
stable yet and the users should consider their usage for experimental
purposes only.
