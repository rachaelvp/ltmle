# ltmle 

Development version of forked repository for Longitudinal Targeted Maximum 
Likelihood Estimation `R` package.

-----

## Description

The development branch ("rvp-devel") of this forked `ltmle` repository forces 
the following:
- Stratified cross-validation for binary outcomes. 
- Adaptive selection of the number of V cross-validation folds that is based on 
  the effective sample size.

A more general development might (1) allow flexibility in terms of overriding 
these new behaviors; and (2) be incorporated as a default when
`SL.cvControl = NULL`, or when relevant elements in `SL.cvControl` list (`V` 
and/or `stratifyCV`) are `NULL`. 

-----

## Installation

``` r
devtools::install_github("rachaelvp/ltmle@rvp-devel")
```
-----

This development is brought on by an on-going project with the U.S. Food and 
Drug Administration (FDA Contract 75F40119C10155), led by [Susan Gruber, 
PhD, MPH, MS](https://www.putnamds.com).