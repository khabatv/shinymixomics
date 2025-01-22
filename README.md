# shinymixomics
A Shiny app for multi-omics analysis that allows users to upload and analyze different omics data types, including miRNA, mRNA, and proteomics.

# Multi-Omics Analysis Shiny App

## Overview
This Shiny app facilitates multi-omics analysis by allowing users to upload and analyze various omics data types, including miRNA, mRNA, and proteomics. It uses Partial Least Squares (PLS) and DIABLO methods for comprehensive data interpretation and visualization.

## Features
- Upload multiple omics datasets (miRNA, mRNA, proteomics).
- Interactive analysis with user-defined input for dataset names.
- Visual outputs including PLS plots and DIABLO results.
- Summary table of correlation analysis.

## Prerequisites
To run this app, you need to have the following R packages installed:
- `shiny`
- `mixOmics`
- `DT`

You can install these packages using the following commands:

```R
install.packages("shiny")
install.packages("mixOmics")
install.packages("DT")
