# TIvsTA-DAMA

This repository contains all code and data necessary to reproduce the analyses and figures for the manuscript:

*Clinical Performance of Tumor-Informed versus Tumor-Agnostic ctDNA Assays for Colorectal Cancer Recurrence: A Systematic Review and Diagnostic Accuracy Meta-Analysis*

## Requirements

This project uses renv for reproducible environments. You can restore the required packages by running:

```r
if (!requireNamespace("renv", quietly = TRUE)) {
  install.packages("renv")
}
library(renv)
renv::restore()
```

## Structure

The repository is structured as follows:

- `data/`: Contains the raw data files used in the analyses (QUADAS assessment and study statistics).
- `index.html`: Rendered HTML file from the Quarto document.
- `metaanalysis.qmd`: The Quarto document that performs the meta-analysis and generates the figures.
- `README.md`: This file.
- `renv.lock`: The lock file for the R environment, specifying package versions.
