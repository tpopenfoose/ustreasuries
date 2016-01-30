<!-- README.md is generated from README.Rmd. Please edit that file -->
ustreasuries
============

The *ustreasuries* package downloads daily Constant-Maturity Treasury (CMT) yields and provides visualizations & analytics that use that data (all the 'greeks' for derivative analysis will be included in the next release).

### Vignettes

-   **cmt-rates** a description of Constant Maturity and Annualized Percentage rates
-   **yield-curves** examples of downloading the data and printing yield curves for interesting periods in recent financial history
-   **plot-10year** a plot of the 10-year from 1962 to present

### Functions

-   **USTreasuryRates** downloads a data.frame with daily data from 1962
-   **PrintYieldCurves** prints one or more yield curves
-   **APY** converts Constant-Maturity Treasury (CMT) yields to Annualized Percentage Yields (APY)

Installation
------------

We're not on CRAN yet; get the development version from GitHub:

``` r
# see https://github.com/hadley/devtools for the
# best procedure to install *devtools* on your
# system; Windows in particular has unexpected
# requirements

devtools::install_github("grfiv/treasuries")

# Notes: 
#    1. Add 'build_vignettes=TRUE' parameter to include vignettes 
#       (recommended but a current version of pandoc is required)
#    2. add 'auth_token="..."' if you get a 404
#       contact the author for this
#    3. if you receive a message about corrupt databases or fetch(key), 
#       restarting R will fix the problem;
#       these appear to be issues with devtools 1.10.0.9000
```
