# fars

The `fars` package provides a series of functions to read, summarize and visualize [data](https://www-fars.nhtsa.dot.gov/Main/index.aspx) from the U.S. National Highway Traffic Safety Administration's Fatality Analysis Reporting System (FARS).  

Building this package was an assignment of the Coursera course "Building R Packages", offered by Johns Hopkins University as part of their Specialization "Mastering Software Development in R". The functions in the package were provided as input for the assignment and have only been slightly altered. At this point, they are only able to access data provided in the `extdata` folder existing inside the installation directory of the `fars` package. Work in progress. Or not.  

## Installation

You can install fars from github with

``` r
# install.packages("devtools")
devtools::install_github("DulceC/fars")
```

but why would you do that?

[![](https://travis-ci.org/DulceC/fars.svg?branch=master)](https://travis-ci.org/DulceC/fars)
