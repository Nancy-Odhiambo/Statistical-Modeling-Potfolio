Statistical Modeling Portfolio
Predicting Breast Cancer Diagnosis
Author: Nancy Odhiambo

Overview
This repository contains my STA 631 Statistical Modeling Portfolio, developed using the Breast Cancer Wisconsin Diagnostic Dataset. The project demonstrates a complete statistical modeling workflow, including data preprocessing, exploratory analysis, model development, regularization, classification, and performance evaluation.

The portfolio emphasizes reproducibility, model interpretability, and principled model comparison using the tidymodels framework in R.

View Portfolio
The full interactive HTML portfolio is available here:
https://nancy-odhiambo.github.io/Statistical-Modeling-Potfolio/

Repository Structure
File	Description
index.html	Published portfolio (GitHub Pages)
Statistical Modeling Portfolio.Rmd	Main R Markdown source
Breast_cancer_dataset.csv	Dataset used for modeling
LICENSE	MIT License
.Rproj	RStudio project file
README.md	Documentation


Modeling Workflow
This portfolio implements a structured and reproducible modeling pipeline:

Data Preparation
Variable inspection and cleaning

Feature engineering using recipes

Standardization and preprocessing

Train/test splitting

Models Implemented
Logistic Regression (full, reduced, polynomial, interaction)

Lasso Regression

Ridge Regression

Linear Discriminant Analysis (LDA)

Multinomial Logistic Regression

Evaluation and Validation
10‑fold cross‑validation

ROC curves and AUC

Confusion matrices

Accuracy, sensitivity, specificity

Comparative model assessment

The goal is to identify the most effective classification model for predicting malignant vs. benign tumors while balancing interpretability and predictive performance.

Tools and Technologies
R

tidyverse (data manipulation, visualization)

tidymodels (recipes, workflows, parsnip, yardstick)

glmnet (regularization models)

MASS, nnet (classical classification methods)

GGally, corrplot (EDA and correlation analysis)

kableExtra (formatted tables)

Purpose
This portfolio demonstrates my ability to:

Build reproducible and modular modeling workflows

Apply appropriate statistical learning methods to biomedical data

Evaluate and compare models using rigorous validation techniques

Interpret model results and communicate findings clearly

Produce a polished, professional analysis suitable for academic or industry review

License
MIT License.
