# ELPI Analysis – MA Thesis

**Author:** María José Osimani  
**Purpose:** Master's thesis analysis of the *Encuesta Longitudinal de la Primera Infancia* (ELPI) dataset.  

## Overview
This project processes, merges, and analyzes multiple waves of ELPI data (2010, 2012, 2017) to study the relationship between **household composition** and **child development outcomes** in Chile.  

Main focus:
- Compare lone-mother households with two-parent households.
- Evaluate differences in income, parental involvement, and mother’s attitudes.
- Analyze child development scores (Battelle Developmental Inventory, Peabody Picture Vocabulary Test).
- Test potential mediators like family income and father-child interactions.

## Data
- **Survey Years:** 2010, 2012, 2017.
- **Files Used:** Household, interview, and child evaluation datasets from ELPI.
- **Main Variables:**
  - Household composition
  - Parental presence, visits, and economic support
  - Mother’s education, employment, and age
  - Child’s preschool attendance, premature birth
  - Development test scores (Battelle, PPVT)

## Methods
- Data cleaning, recoding, and merging across years.
- Descriptive statistics and t-tests/chi-squared tests for group comparisons.
- OLS and fixed-effects regressions for outcome analysis.
- Visualization of distribution and coefficient estimates.
- Mediation analysis linking household type → mediators → child outcomes.

## R Packages
`tidyverse`, `dplyr`, `haven`, `plm`, `ggplot2`, `gtsummary`, `descr`, `kableExtra`, `table1`, `lmtest`

## Output
- Cleaned datasets per year (`ELPI 2010.rds`, `ELPI 2012.rds`, `ELPI 2017.rds`)  
- Combined dataset (`ELPI Total.rds`)  
- Summary tables, regression outputs, coefficient plots.

## License
MIT License – see `LICENSE` file.
