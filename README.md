
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ohwhaley <img src="man/figures/imgfile.png" align="right" alt="" width="120" />

<!-- badges: start -->

[![](https://img.shields.io/badge/devel%20version-0.0.0.9000-blue.svg)](https://github.com/fontikar/ohwhaley)
[![](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/yangsophieee/ohwhaley/workflows/R-CMD-check/badge.svg)](https://github.com/yangsophieee/ohwhaley/actions)
[![codecov](https://codecov.io/gh/yangsophieee/ohwhaley/branch/master/graph/badge.svg?token=XN4PEEZU12)](https://codecov.io/gh/yangsophieee/ohwhaley)
<!-- badges: end -->

Whale-come! This R package was inspired by
[cowsay](https://github.com/sckott/cowsay) and
[praise](https://github.com/rladies/praise). I hope this package made
you smile today!!!

## First things first

`ohwhaley` is a toy project and is still under development. You can
install the latest version from [GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("fontikar/ohwhaley")
```

## Take it for a spin

`ohwhaley` contains one function only. `say()` will echo a randomly
chosen whale-themed phrase for your enjoyment.

``` r
library(ohwhaley)
 
say() 
#> 
#>             ------ 
#>            I'm having a whale of a time! 
#>             ------ 
#>                \   
#>                 \  
#>                  \
#>      .-'
#> '--./ /     _.---.
#> '-,  (__..-`       \
#>    \          .     |
#>     `,.__.   ,__.--/
#>      '._/_.'___.-`
```

Alternatively, you can supply your own phrase

``` r
say("I'm beached as bro!!!")
#> 
#>             ------ 
#>            I'm beached as bro!!! 
#>             ------ 
#>                \   
#>                 \  
#>                  \
#>      .-'
#> '--./ /     _.---.
#> '-,  (__..-`       \
#>    \          .     |
#>     `,.__.   ,__.--/
#>      '._/_.'___.-`
```
