# Statistical Modeling Portfolio  
Predicting Breast Cancer Diagnosis  
Author: Nancy Odhiambo  

## Overview  
This repository contains a Statistical Modeling Portfolio, developed using the Breast Cancer Wisconsin Diagnostic Dataset. The project demonstrates a complete statistical modeling workflow, including data preprocessing, exploratory analysis, model development, regularization, classification, and performance evaluation.  

The portfolio emphasizes reproducibility, model interpretability, and principled model comparison using the tidymodels framework in R.

## View Portfolio  
The full interactive HTML portfolio is available here:  
https://nancy-odhiambo.github.io/Statistical-Modeling-Potfolio/

## Repository Structure  
| File | Description |
|------|-------------|
| `index.html` | Published portfolio (GitHub Pages) |
| `Statistical Modeling Portfolio.Rmd` | Main R Markdown source |
| `Breast_cancer_dataset.csv` | Modeling dataset |

## Modeling Workflow  
This portfolio implements a structured and reproducible modeling pipeline.

### Data Preparation  
- Variable inspection and cleaning  
- Feature engineering using recipes  
- Standardization and preprocessing  
- Train/test splitting  

### Models Implemented  
- Logistic Regression (full, reduced, polynomial, interaction)  
- Lasso Regression  
- Ridge Regression  
- Linear Discriminant Analysis (LDA)  
- Multinomial Logistic Regression  

### Evaluation and Validation  
- 10‑fold cross‑validation  
- ROC curves and AUC  
- Confusion matrices  
- Accuracy, sensitivity, specificity  
- Comparative model assessment  

## Tools and Technologies  
- Rmarkdown 
- tidyverse  
- tidymodels (recipes, workflows, parsnip, yardstick)  
- glmnet  
- MASS, nnet  
- GGally, corrplot  
- kableExtra  

## Purpose  
This portfolio demonstrates the ability to:  
- Build reproducible and modular modeling workflows  
- Apply appropriate statistical learning methods to biomedical data  
- Evaluate and compare models using rigorous validation techniques  
- Interpret model results and communicate findings clearly  
- Produce a polished, professional analysis suitable for academic or industry review  

## License  
MIT License.
