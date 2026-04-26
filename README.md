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
| **Generalized Linear Model** | different types of models in one big framework (linear predictor + link function + distribution) | Linear / Parametric |
| **K-Nearest Neighbors (KNN)** | finds K neighbours and bases off majority wins (classification) or average (regression) | Instance-Based / Non-Parametric |
| **Decision Trees** | splits data into branches like a flowchart | Tree-Based / Non-Parametric |
| **Bagging** | trains many models on bootstrapped samples and majority wins (classification) or average (regression) | Ensemble (Variance Reduction) / Parallel Learning |
| **Random Forest** | bagging but randomizes features per split, final output based on majority wins (classification) or average (regression) | Ensemble (Tree-Based) / Parallel Learning |
| **AdaBoost** | Improves on the misclassifications of previous models, learns from weak learners | Ensemble (Boosting) / Sequential Learning |
| **Gradient Boosting** | improves on the residual errors of previous models | Ensemble (Boosting) / Sequential Learning |
| **XGBoost** | ... | ... |
| **Ridge Regression** | L2 regularization that shrinks coefficients to reduce overfitting | Regularization |
| **Lasso Regression** | L1 regularization that shrink non-important coefficients to zero (feature selection) | Regularization |
| **Elastic Net** | Combines L1 (Lasso) and L2 (Ridge) penalties | Regularization |

---

## Unsupervised Machine Learning Models

> Models I've learned about.

| Model | Notes | Type |
|-------|-------|------|
| **K-Means Clustering** | Minimizes within-cluster sum of squares using centroids (mean) | Clustering |
| **DBSCAN** | Clustering based on density | Clustering |

---

## Schedule

| 📆 Date (MM/DD/YY) | 📚 Lesson | 
|:------------------:|-----------|
| **02/27/26** | **Understanding Classification Metrics**<br>• Define each metric Accuracy, Precision, Recall, F1, ROC-AUC<br>• Explore their mathematical approaches |
| **03/03/26** | **F1 Dilema and Quick Review of Performance Metrics**<br>• What cases does higher or lower F1 is better<br>• Quickly review $R^2$, Log-Likelihood, AIC, BIC |
| **03/04/26** | **Model Analysis (LPM, LOGIT, KNN, DT)**<br>• Explore the math, logic, interpretations, and code of the following models: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Linear Probability Model<br>&nbsp;&nbsp;&nbsp;&nbsp;• Logistics Regression<br>&nbsp;&nbsp;&nbsp;&nbsp;• K-Nearest Neighbours<br>&nbsp;&nbsp;&nbsp;&nbsp;• Decision Tree |
| **03/09/26** | **Model Analysis (Bagging, RF, AdaB, GradB, XGB)**<br>• Explore the math, logic, interpretations, and code of the following models: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Bagging<br>&nbsp;&nbsp;&nbsp;&nbsp;• Random Forest<br>&nbsp;&nbsp;&nbsp;&nbsp;• AdaBoost<br>&nbsp;&nbsp;&nbsp;&nbsp;• Gradient Boost<br>&nbsp;&nbsp;&nbsp;&nbsp;• XGBoost |
| **03/30/26** | **Full Power Gradient Boost**<br>• Create a fully powered Gradient Boost with the following hyperparameter tuning: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Cross-Validation<br>&nbsp;&nbsp;&nbsp;&nbsp;• Grid Search|
| **04/03/26** | **Feature Transformation on Linear Probability Model**<br>• Create a Linear Probability Model the following feature transformations: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Log<br>&nbsp;&nbsp;&nbsp;&nbsp;• Polynomial |
| **04/17/26** | **Notebook Reworks**<br>• Rework the following notebooks: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Feature Transformation on Linear Probability Model |
| **04/29/26** | **Feature Selection Selection**<br>• What are the use cases of the following feature selection modes: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Decision Tree<br>&nbsp;&nbsp;&nbsp;&nbsp;• Bagging<br>&nbsp;&nbsp;&nbsp;&nbsp;• Random Forest |
| **04/30/26** | **XGBoost**<br>• Explore and study XGBoost |
| **05/01/26** | **Notebook Reworks**<br>• Rework the following notebooks: <br>&nbsp;&nbsp;&nbsp;&nbsp;• ... |
| **05/08/26** | **Unsupervised Learning**<br>• Work on the following models: <br>&nbsp;&nbsp;&nbsp;&nbsp;• K-Means Clustering <br>&nbsp;&nbsp;&nbsp;&nbsp;• DBSCAN |\

**Note to Self:** Make sure to backup what you say in the notebooks with graphs and numbers.
