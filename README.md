# Estimating the Causal Effect of Smoking Cessation on Weight Gain  

This project estimates the causal effect of quitting smoking on body weight using observational data from the NHEFS dataset. It applies causal inference techniques to isolate the impact of smoking cessation while controlling for demographic and health-related confounders.

---

## Overview
- Evaluates whether smoking cessation leads to weight gain.  
- Uses causal inference methods such as propensity score matching and regression adjustment.  
- Conducted in R with the NHEFS (National Health and Nutrition Examination Follow-up Study) dataset.  
- Includes a reproducible R Markdown report and dataset documentation.  

---

## Methodology
1. Data cleaning and variable selection.  
2. Estimation of treatment effects between quitters and non-quitters.  
3. Propensity score estimation and matching.  
4. Model evaluation and sensitivity analysis.  

---

## Tools
Language: R  
Libraries: `causaldata`, `MatchIt`, `dplyr`, `ggplot2`, `causalimpact`  

---

## Repository Structure
| File | Description |
|------|--------------|
| Code.Rmd | R Markdown file with the full analysis |
| Data.csv | NHEFS dataset used for the study |
| Dataset_dscripton.csv | Codebook and variable descriptions |
| Html_Report.html | Rendered report with results and visualizations |
| README.md | Project documentation |

---
