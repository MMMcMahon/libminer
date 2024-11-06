
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

[![R-CMD-check](https://github.com/MMMcMahon/libminer/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/MMMcMahon/libminer/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of libminer is to provide an overview of your R library setup.
It is a toy package created as a part of a workshop and not meant for
serious use.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_GitHub("MMMcMahon/libminer")
```

## Example usage

To get a count of installed packages in each of your library locations,
use the `lib_summary()` function:

``` r
library(libminer)
lib_summary()
#>                                                                      Library
#> 1                                         C:/Program Files/R/R-4.4.1/library
#> 2                          C:/Users/mcmahonm/AppData/Local/R/win-library/4.4
#> 3 C:/Users/mcmahonm/AppData/Local/Temp/1/RtmpEPi4pF/temp_libpath65bc34db4ccf
#>   n_packages
#> 1         29
#> 2        153
#> 3          1
```

you can also run lib() to list all of your packages:

``` r
lib()
```
