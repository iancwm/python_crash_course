# Implementation Plan: Enhance Project Notebooks with Rigorous EDA and ML Practices

## Phase 1: Project 1 - Pokemon EDA Notebook

- [x] Task: Restructure and Expand Pokemon EDA Notebook
    - [x] Write Tests: Add inline assert cells verifying data integrity, correlation calculations, and distribution statistics
    - [x] Implement Feature: Reorganize into modular sections — Data Loading & Understanding, Data Preparation, Enhanced EDA (distributions, correlations, type comparisons)
- [x] Task: Add ML Practices to Pokemon EDA
    - [x] Write Tests: Add assert cells verifying pipeline structure, cross-validation scores, and grid search results
    - [x] Implement Feature: Add Scikit-learn Pipeline for predicting a Pokemon stat, with cross-validation and GridSearchCV/RandomizedSearchCV for hyperparameter tuning
- [x] Task: Remove External Dependencies and Modernize
    - [x] Implement Feature: Remove all Google Drive references, ensure Python 3.12+ patterns, apply Google style guide
- [x] Task: Conductor - User Manual Verification 'Project 1 - Pokemon EDA' (Protocol in workflow.md)

## Phase 2: Project 2 - Cannabis Classification Notebook

- [ ] Task: Restructure and Expand Cannabis Classification Notebook
    - [ ] Write Tests: Add inline assert cells verifying class balance, feature distributions, and data quality checks
    - [ ] Implement Feature: Reorganize into modular sections — Data Loading & Understanding, Data Preparation, Enhanced EDA (class balance, feature correlations, strain type comparisons)
- [ ] Task: Add ML Pipeline and Hyperparameter Optimization
    - [ ] Write Tests: Add assert cells verifying pipeline fit/predict, CV score ranges, and best parameter extraction
    - [ ] Implement Feature: Replace ad-hoc modeling with Scikit-learn Pipeline, add cross-validation (StratifiedKFold), add GridSearchCV/RandomizedSearchCV
- [ ] Task: Add SHAP Values for Model Interpretation
    - [ ] Write Tests: Add assert cells verifying SHAP output shape, summary plot generation, and individual prediction explanation
    - [ ] Implement Feature: Add SHAP analysis — feature importance summary plot, dependence plots, and individual prediction force plots
- [ ] Task: Remove External Dependencies and Modernize
    - [ ] Implement Feature: Remove all Google Drive references, update code for current sklearn/pandas patterns, apply Google style guide
- [ ] Task: Conductor - User Manual Verification 'Project 2 - Cannabis Classification' (Protocol in workflow.md)

## Phase 3: Project 3 - Bank Churn Prediction Notebook

- [ ] Task: Restructure and Expand Bank Churn Prediction Notebook
    - [ ] Write Tests: Add inline assert cells verifying data integrity, class imbalance metrics, and feature engineering results
    - [ ] Implement Feature: Reorganize into modular sections — Data Loading & Understanding, Data Preparation (handling imbalance, feature engineering), Enhanced EDA (churn rate analysis, feature distributions by churn status)
- [ ] Task: Add ML Pipeline and Hyperparameter Optimization
    - [ ] Write Tests: Add assert cells verifying pipeline structure, CV scores, and hyperparameter search results
    - [ ] Implement Feature: Replace ad-hoc modeling with Scikit-learn Pipeline, add cross-validation, add GridSearchCV/RandomizedSearchCV, handle class imbalance (SMOTE or class weights)
- [ ] Task: Add SHAP Values for Model Interpretation
    - [ ] Write Tests: Add assert cells verifying SHAP summary plot, dependence plots, and individual prediction explanation
    - [ ] Implement Feature: Add SHAP analysis — feature importance, dependence plots for key features, individual prediction explanation
- [ ] Task: Remove External Dependencies and Modernize
    - [ ] Implement Feature: Remove all Google Drive references, update code for current sklearn/pandas patterns, apply Google style guide
- [ ] Task: Conductor - User Manual Verification 'Project 3 - Bank Churn Prediction' (Protocol in workflow.md)
