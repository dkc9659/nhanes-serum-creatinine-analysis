# regression-project
# Factors Associated with Serum Creatinine in U.S. Adults

### Multiple Linear Regression Analysis | NHANES 2021–2023

**Status:** In Progress  
**Tools:** R, tidyverse, ggplot2, Quarto  
**Institution:** New York University, MS in Biostatistics

## Project Overview

This project investigates the relationship between demographic, physical, and health-related factors and serum creatinine levels among U.S. adults using data from the National Health and Nutrition Examination Survey (NHANES), August 2021–August 2023.

Serum creatinine is a biomarker commonly used in evaluating kidney function. Understanding its associations with demographic and health characteristics can provide insight into variation in kidney-related laboratory measurements.

The analysis uses multiple linear regression to examine associations between selected predictors and serum creatinine concentrations.

## Research Question

Which demographic, physical, and health-related factors are associated with serum creatinine levels among U.S. adults?

## Dataset

**Source:** [CDC National Health and Nutrition Examination Survey (NHANES)](https://wwwn.cdc.gov/nchs/nhanes/)

**Survey period:** August 2021–August 2023

**Population:** U.S. adults aged 18 years and older

**Outcome:** Serum creatinine (mg/dL), a continuous variable

The project combines NHANES demographic, laboratory, examination, and questionnaire datasets using the unique participant identifier (`SEQN`).

## Variables

| Variable | Description |
|---|---|
| Serum creatinine | Continuous outcome measured in mg/dL |
| Age | Participant age in years |
| Sex | Participant sex |
| BMI | Body mass index (kg/m²) |
| Systolic blood pressure | Blood pressure measured in mmHg |
| Diabetes status | Self-reported diabetes diagnosis |
| Physical activity | Moderate leisure-time activity, minutes per week |

## Exploratory Data Analysis

Preliminary exploratory analysis included:

- Examining variable distributions and descriptive statistics.
- Assessing missing data across variables.
- Visualizing relationships between serum creatinine and candidate predictors.
- Identifying skewness and potentially influential observations.

Among 8,153 adult participants in the preliminary merged dataset, 5,658 had available serum creatinine measurements.

Serum creatinine showed a right-skewed distribution, with a median of approximately 0.85 mg/dL.

## Statistical Methods

The analysis is being developed using multiple linear regression.

Planned and ongoing steps include:

1. Data cleaning and variable preparation.
2. Exploratory data analysis and missingness assessment.
3. Fitting multiple linear regression models.
4. Comparing candidate models and assessing multicollinearity.
5. Evaluating residual diagnostics, including linearity, constant variance, normality, and influential observations.
6. Interpreting estimated associations and their uncertainty.

Potential transformations of serum creatinine will be considered if supported by model diagnostics.

## Results

Final regression results, model comparisons, diagnostic plots, and interpretations will be added after the analysis is complete.

## Reproducibility

The analysis is conducted in R using Quarto for reproducible reporting.

Project files include R/Quarto analysis scripts, data preparation steps, and exploratory analysis outputs.


## Data Source

Centers for Disease Control and Prevention, National Center for Health Statistics. National Health and Nutrition Examination Survey, August 2021–August 2023.
