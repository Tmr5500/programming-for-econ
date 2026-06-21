# Housing Affordability in the Netherlands (2021–2024)

## Project Overview

This project examines whether growth in median disposable household income kept pace with growth in housing values across Dutch provinces between 2021 and 2024.

The analysis combines housing value data and household income data from Statistics Netherlands (CBS) and investigates:

- Temporal variation
- Spatial variation across provinces
- Differences across ownership categories
- Housing affordability before and after ECB monetary tightening

## Data Sources

### Income Dataset

Statistics Netherlands (CBS)

https://opendata.cbs.nl/#/CBS/nl/dataset/86161NED/table

### Housing Value Dataset

Statistics Netherlands (CBS)

https://www.cbs.nl/nl-nl/cijfers/detail/85036NED

## Repository Structure

```text
data/
    income_data.csv
    housing_data.csv

Dutch_Housing_Affordability_Report.Rmd

README.md
```

## Required Packages

The project uses the following R packages:

- tidyverse
- dplyr
- ggplot2
- sf
- tmap
- cbsodataR
- knitr
- rmarkdown

## Reproducing the Analysis

1. Clone the repository.
2. Open the R project or RMarkdown file.
3. Install required packages.
4. Knit the RMarkdown file to HTML or PDF.

The report can be reproduced directly from the RMarkdown file using the included code.
