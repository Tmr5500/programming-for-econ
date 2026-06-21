# Housing Affordability in the Netherlands (2021–2024)

## Project Overview

This project investigates whether growth in median disposable household income kept pace with growth in housing values across Dutch provinces between 2021 and 2024.

Using data from Statistics Netherlands (CBS), the analysis examines housing affordability through temporal, spatial, sub-population, and event-based perspectives. Housing affordability is measured using an affordability ratio calculated as average housing value divided by median disposable household income.

## Research Question

Did income growth keep pace with housing value growth across Dutch provinces between 2021 and 2024?

## Data Sources

### Income Dataset

Statistics Netherlands (CBS)

https://opendata.cbs.nl/#/CBS/nl/dataset/86161NED/table

### Housing Value Dataset

Statistics Netherlands (CBS)

https://www.cbs.nl/nl-nl/cijfers/detail/85036NED

## Repository Structure

```text
programming-for-econ/
│
├── databases untouched/
├── Updated_Template_Assignment.Rmd
├── run_all.R
├── README.md
├── renv.lock
└── renv/
```

## Required Packages

The analysis uses the following R packages:

* dplyr
* ggplot2
* sf
* tmap
* rnaturalearth
* cbsodataR
* tidyr
* knitr
* rmarkdown

## Reproducing the Analysis

1. Clone or download the repository.
2. Open the project in RStudio.
3. Restore the project environment using:

```r
renv::restore()
```

4. Run:

```r
source("run_all.R")
```

or knit the RMarkdown file directly.

The report and all figures should be reproduced automatically from the included code and data.
