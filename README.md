# Graduate-Employment

## Overview
This repository contains a comprehensive analysis of factors influencing job placement outcomes for recent graduates. Using a dataset with academic, demographic, and institutional attributes, this project explores which characteristics best predict employment success after graduation.

## Research Question
What academic, demographic, and institutional characteristics best predict whether a graduate will be successfully placed in a job after completing their degree?

## Dataset
The analysis uses the Job Placement Dataset from Kaggle, containing:
- Demographic information (age, gender)
- Academic performance metrics (GPA)
- Educational background (degree, stream/specialization)
- Professional experience
- College/university information
- Placement outcomes and salary data (where applicable)

## Methodology
The project implements multiple predictive modeling approaches:

1. **Classification Models for Placement Prediction**
   - Logistic Regression
   - Linear Discriminant Analysis (LDA)
   - Multiple Linear Regression (MLR)

2. **Regression Models for Salary Estimation**
   - Multinomial Regression for salary categorization
   - Polynomial Regression for nonlinear salary relationships
   
3. **Feature Selection & Regularization**
   - Backward, forward, and stepwise selection
   - Analysis of feature importance
   - Cross-validation

## Key Findings
- Years of experience emerged as the strongest predictor of job placement
- College tier (institutional prestige) significantly impacts placement outcomes
- Electronics and Communication specialization shows a positive association with employment
- The GPA-salary relationship demonstrates nonlinear patterns
- Gender showed minimal impact on placement outcomes

## Repository Structure
- `data/`: Raw and processed datasets
- `scripts/`: R scripts for data processing and analysis
- `models/`: Model specifications and evaluation results
- `visualizations/`: Generated plots and visual analytics
- `docs/`: Additional documentation and findings report

## Requirements
- R (version 4.0+)
- Required packages:
  - tidyverse
  - tidymodels
  - MASS
  - caret
  - corrplot
  - ggplot2
  - pROC
  - nnet

## Usage
1. Clone the repository
2. Run the data preprocessing script
3. Execute model training and evaluation
4. Review results and visualizations
