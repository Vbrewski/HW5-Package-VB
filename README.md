
<!-- README.md is generated from README.Rmd. Please edit that file -->

# HW5VB

<!-- badges: start -->

<!-- badges: end -->

The goal of HW5VB is to load two functions: one that generates a random
sample from 4 different distributions, and another that generates a plot
of histograms from a random sample from 4 different distributions.

## Installation

You can install the released version of HW5VB from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("HW5VB")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Vbrewski/HW5-Package-VB")
```

## Usage

This is a basic example of the RDistribution() function which returns
the generated random samples from a selection of 4 different
distributions.

``` r
library(HW5VB)
RDistribution('normal', 10)
#>  [1]  1.2342407 -2.1890781  1.5339851  0.8036159 -0.7185504  0.7511472
#>  [7] -1.4721635  1.2825279 -0.9829344 -0.3792187
```

This is a basic example of the RDistributionPlot() function which
returns a histogram of the generated random samples from a selection of
4 different user selected distributions.

``` r
RDistributionPlot('normal', 10, bins = 5)
```
