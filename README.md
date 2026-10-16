# QBS 103 Final Project

Exploring gene expression in pregnancy and its relationship with maternal characteristics, using data from
[GEO GSE85307](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85307)
(paper: https://pubmed.ncbi.nlm.nih.gov/27841759/).

## Contents

| File | Description |
|---|---|
| `QBS103_FinalProject_Submission1.Rmd` | R Markdown source for Submission 1 (data wrangling and three ggplot2 figures) |
| `QBS103_FinalProject_Submission1.pdf` | Knitted PDF of Submission 1 |

## Submission 1

- Gene: *LYN*
- Continuous covariate: maternal vitamin D (ng/mL)
- Categorical covariates: pregnancy outcome (Normal vs. Preeclampsia) and obesity status (BMI < 30 vs. >= 30, derived from maternal BMI)
- Figures: histogram of gene expression, scatterplot of expression vs. vitamin D, boxplot of expression by outcome and obesity status

## Data

The data files are not stored in this repository. To reproduce the analysis, download the three original files
from Canvas and place them in the same folder as the `.Rmd`:

- `GSE85307_covar.csv`
- `GSE85307_geneExpression.csv`
- `GSE85307_geneNames.csv`

## Requirements

R with the `ggplot2` package (and `rmarkdown` plus a LaTeX installation to knit to PDF).

Author: Irene C
