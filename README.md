# Final Year Project: Intracerebral Hemorrhage Data Analysis

This repository contains the Python implementation for my undergraduate Final Year Project on **hematoma expansion, perihematomal edema (PHE), and treatment effects in intracerebral hemorrhage (ICH)**.

## Project Overview

The project focuses on analyzing longitudinal clinical and CT imaging data from patients with intracerebral hemorrhage. The main tasks include:

- Identification of **hematoma expansion within 48 hours**
- Integration and preprocessing of clinical and imaging features
- Prediction of hematoma expansion using statistical and machine-learning models
- Analysis of longitudinal **perihematomal edema trajectories**
- Investigation of associations between treatment strategies and patient trajectory patterns

## Methods

The analysis pipeline includes:

- Data cleaning and integration using `pandas` and `NumPy`
- Feature engineering from clinical and imaging variables
- L1-regularized Logistic Regression
- Generalized Additive Models (GAM)
- Tree-based and ensemble learning methods
- Cross-validation and model evaluation
- Bootstrap-based stability and uncertainty assessment
- Longitudinal trajectory modelling and treatment-effect analysis

## Code

The main analysis is contained in:

`final.ipynb`

The notebook includes the full workflow from data preprocessing and feature construction to predictive modelling, trajectory analysis, treatment-effect evaluation, and visualization.

## Tools

Python, pandas, NumPy, scikit-learn, statsmodels, pyGAM, LightGBM, CatBoost, matplotlib

## Note

The original clinical and medical imaging datasets are not included in this public repository due to data privacy and confidentiality requirements.
