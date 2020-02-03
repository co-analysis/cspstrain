
# cspstrain

<!-- badges: start -->
<!-- badges: end -->

The goal of {cspstrain} is to get people accustomed to working with Civil Service People Survey (CSPS) data with R.

## A note on the data

The data set used in this package is not a real data set. None of the rows are a real response from any actual respondent.

Instead, the data set is synthetic. This means that the distribution of results within any given variable is representative of the real data set, but none of the rows represent a real person's responses.

## Install

First you must have installed R. I recommend you install RStudio too.

Install the {remotes} package, which will then let you download {cspstrain} from GitHub.

```
install.packages("remotes")  # you only need to do this once
library(remotes)  # load the functions from the package

install_github("matt-dray/cspstrain")  # installs {cspstrain} to your machine
```

## Run tutorials

To run the tutorial you will first need to install the {learnr} package.

```
install.packages("learnr")  # you only need to do this once
library(learnr) # load the functions from the package
```

Then you can run the microdata tutorial with the following function:

```
run_tutorial("microdata", package = "cspstrain")
```

The tutorial will open in your browser.

## Note for admins

To add {learnr} tutorials, create a new subfolder in `inst/tutorials` that contains both the Rmd file and rendered HTML file for your tutorial. Give the tutorial a short, lowercase, snake_case name.
