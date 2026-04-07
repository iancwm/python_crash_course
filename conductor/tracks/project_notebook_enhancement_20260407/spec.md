# Specification: Enhance Project Notebooks with Rigorous EDA and ML Practices

## 1. Overview

This track enhances the three Applied Project notebooks (Pokemon EDA, Cannabis Classification, Bank Churn Prediction) by incorporating rigorous EDA methodologies and production-grade machine learning practices. Each notebook will remain a single file but be reorganized into clear, independent modular sections. All existing datasets are retained; no new external data sources are introduced.

## 2. Goals

- Introduce CRISP-DM concepts (data understanding, data preparation, modeling, evaluation) into each notebook's structure
- Replace ad-hoc ML code with Scikit-learn Pipelines for reproducibility
- Add hyperparameter optimization using GridSearchCV and/or RandomizedSearchCV
- Incorporate cross-validation for robust model evaluation
- Add model interpretation using SHAP values for feature importance and individual predictions
- Maintain concise, practical prose with inline assert-based test cells throughout

## 3. Functional Requirements

1. **Each notebook must be organized into modular sections:**
   - Section 1: Data Loading and Understanding (Business + Data Understanding)
   - Section 2: Data Preparation and Cleaning (Data Preparation)
   - Section 3: Exploratory Data Analysis (Enhanced visualizations, correlations, distributions)
   - Section 4: Model Building with Pipelines (Scikit-learn Pipeline objects)
   - Section 5: Hyperparameter Optimization (GridSearchCV / RandomizedSearchCV)
   - Section 6: Model Evaluation and Interpretation (Cross-validation, SHAP values)

2. **Scikit-learn Pipelines must be used** for all preprocessing + modeling workflows to prevent data leakage and ensure reproducibility

3. **Cross-validation** (e.g., `cross_val_score`, `StratifiedKFold`) must replace or supplement simple train/test splits where appropriate

4. **Hyperparameter optimization** must use `GridSearchCV` or `RandomizedSearchCV` with clear parameter grids and scoring metrics

5. **SHAP values** must be used for at least one model per classification/regression project to demonstrate feature importance and individual prediction interpretation

6. **Inline assert-based test cells** must verify key concepts after each major section (e.g., pipeline structure, CV scores, SHAP output shape)

7. **All prose must be concise and practical** — minimal narrative, maximum executable code with clear expected outputs

## 4. Non-Functional Requirements

- All code must use Python 3.12+ compatible syntax
- All code must follow Google Python Style Guide
- No Google Drive references or external data authentication
- Notebooks must be self-contained and runnable from top to bottom without errors
- Each notebook must remain under a reasonable size (aim for clarity over comprehensiveness in any single section)

## 5. Acceptance Criteria

- All three notebooks run top-to-bottom without errors
- All inline assert-based test cells pass
- Scikit-learn Pipelines used for all modeling sections
- Cross-validation implemented alongside or replacing simple train/test splits
- Hyperparameter optimization demonstrated with GridSearchCV or RandomizedSearchCV
- SHAP values demonstrated for model interpretation in classification projects
- No deprecated API usage (e.g., no `.append` in pandas, no old sklearn patterns)
- No Google Drive references in any notebook
- Code style consistent with Google Python Style Guide

## 6. Out of Scope

- New datasets or data sources
- Splitting notebooks into multiple files
- Deep learning or neural network approaches
- Model deployment or productionization
- Changes to Session notebooks (1-8)
