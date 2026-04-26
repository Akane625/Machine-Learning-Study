# My ML/AI Learning Repository

Hi, this repository is my **learning repository** where I document new and additional insights about Machine Learning and AI. I experiment with topics, dig deeper into interesting concepts, and try to answer the "why" behind everything.

> **Why this exists:** I want to learn more and understand ML/AI further

---

## Supervised Machine Learning Models

> Models I've learned about.

| Model | Notes | Type |
|-------|-------|------|
| **Linear Regression (OLS)** | find best fit line using ordinary least squares | Linear / Parametric |
| **Linear Probability Model (LPM)** | predict binary outcome | Linear / Parametric (Binary) |
| **Logistic Regression** | It predicts probabilities between 0 and 1 | Linear / Parametric (Binary) |
| **Generalized Linear Model (GLM)** | different types of models in one big framework (linear predictor + link function + distribution) | Linear / Parametric |
| **K-Nearest Neighbors (KNN)** | finds K neighbours and bases off majority wins (classification) or average (regression) | Instance-Based / Non-Parametric |
| **Decision Trees (DT)** | splits data into branches like a flowchart | Tree-Based / Non-Parametric |
| **Bagging** | trains many models on bootstrapped samples and majority wins (classification) or average (regression) | Ensemble (Variance Reduction) / Parallel Learning |
| **Random Forest (RF)** | bagging but randomizes features per split, final output based on majority wins (classification) or average (regression) | Ensemble (Tree-Based) / Parallel Learning |
| **AdaBoost** | Improves on the misclassifications of previous models, learns from weak learners | Ensemble (Boosting) / Sequential Learning |
| **Gradient Boosting** | improves on the residual errors of previous models | Ensemble (Boosting) / Sequential Learning |
| **XGBoost** | ... | ... |
| **Ridge Regression (L2)** | Shrinks coefficients to reduce overfitting | Regularization |
| **Lasso Regression (L1)** | Shrink non-important coefficients to zero (feature selection) | Regularization |
| **Elastic Net** | Combines L1 (Lasso) and L2 (Ridge) penalties | Regularization |

---

## Unsupervised Machine Learning Models

> Models I've learned about.

| Model | Notes | Type |
|-------|-------|------|
| **K-Means Clustering** | Minimizes within-cluster sum of squares using centroids (mean) | Clustering |
| **Density-Based Spatial Clustering of Applications with Noise (DBSCAN)** | Clustering based on density | Clustering |

---

## Schedule

| Date (MM/DD/YY) | Title | Details |
|:---------------:|--------|--------|
| **02/27/26** | **Understanding Classification Metrics** | • Accuracy, Precision, Recall, F1, ROC-AUC <br> • Additionally explore their mathematical approaches |
| **03/03/26** | **F1 Dilemma + Metrics Review** | • When higher/lower F1 is better <br> • Review: $R^2$, Log-Likelihood, AIC, BIC |
| **03/04/26** | **Model Analysis I** | • Explore the math, logic, interpretations, and code of each <br> • LPM, Logistic Regression, KNN, DT |
| **03/09/26** | **Model Analysis II** | • Explore the math, logic, interpretations, and code of each <br> • Bagging, RF, AdaBoost, Gradient Boosting |
| **03/30/26** | **Full Gradient Boosting** | • Cross-validation + Grid search tuning |
| **04/03/26** | **Feature Transformation (LPM)** | • Log transformation, Polynomial features |
| **04/17/26** | **Notebook Rework I** | • Feature Transformation (LPM) |
| **04/27/26 - 05/01/26** | **XGBoost Deep Dive** | • Theory + implementation |
| **?** | **Unsupervised Learning (Clustering)** | • K-Means, DBSCAN |

---

## Notes
- **Self:** make sure to backup the things I write in the notebooks with graphs and numbers
- **Starting 04/26/2026:** make one big notebook with a one week deadline, instead of small ones in a day
- **About Notebook Reworks:** if a notebook gets reworked, make sure to place the updates on the last cell

---


