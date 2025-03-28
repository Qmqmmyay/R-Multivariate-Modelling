
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Graduation-Thesis-Multivariate-Frequency-Severity

This is a project applying Actuarial Modelling to Social Health
Insurance in Ho Chi Minh City, 2014, where each visit has multiple
expenses.

## Overview

The goal of this project is to analyze multivariate frequency and
severity models using R.

## Installation

You can install the required packages using:

``` r
install.packages(c("tidyverse", "actuar", "ggplot2", "MASS"))
#> Error in install.packages : Updating loaded packages
```

## Example Analysis

``` r
data(cars)
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

## Visualizations

![](README_files/figure-gfm/pressure_plot-1.png)<!-- -->

Make sure to render `README.Rmd` to update `README.md` using:

``` r
rmarkdown::render("README.Rmd")
```

## License

This project is licensed under the MIT License - see the LICENSE file
for details.
