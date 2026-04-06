# 👋 Welcome to My ML/AI Learning Repository

Hi! This repository is my personal **learning repository** where I document new and additional insights about Machine Learning and AI. I experiment with curious topics, dig deeper into interesting concepts, and try to answer the "why" behind everything.

> 💡 **Why this exists:** I want to learn more and understand the levels of ML/AI whilst answering my curious questions about some things related to them

---

## 🧠 Models I've Explored So Far

Here are the ML models I've learned about so far.

| 🤖 Model | 📝 Notes | ⌨️ Type |
|----------|----------|------------------|
| **Linear Regression (OLS)** | Predicts continuous values using ordinary least squares | Linear / Parametric |
| **Linear Probability Model (LPM)** | Simple linear model for binary outcomes but can predict probabilities outside 0–1 | Linear / Parametric (Binary) |
| **Logistic Regression** | Uses the sigmoid function to keep predicted probabilities between 0 and 1 | Linear / Parametric (Binary) |
| **Generalized Linear Model (Binomial)** | A GLM with binomial distribution and logit link; equivalent to logistic regression | Linear / Parametric (Binary) |
| **K-Nearest Neighbors (KNN)** | Classifies using the majority label among the k closest observations; final output based on majority wins | Instance-Based / Non-Parametric |
| **Decision Trees** | Splits data into branches based on feature values like a flowchart | Tree-Based / Non-Parametric |
| **Bagging** | Bootstrap Aggregating: trains many models on bootstrapped samples and averages results | Ensemble (Variance Reduction) |
| **Random Forest** | Bagging + KNN  + random feature selection to build many diverse decision trees; final output based on majority wins | Ensemble (Tree-Based) |
| **AdaBoost** | Sequential boosting that focuses more on previously misclassified observations; uses sample weight | Ensemble (Boosting) |
| **Gradient Boosting** | Sequentially builds trees that correct the residual errors of previous models | Ensemble (Boosting) |
| **XGBoost** | (Did Not Finish) | (Did Not Finish) |
| **Ridge Regression** | L2 regularization that shrinks coefficients to reduce overfitting | Regularization |
| **Lasso Regression** | L1 regularization that shrink non-important coefficients to zero (feature selection) | Regularization |
| **Elastic Net** | Combines L1 (Lasso) and L2 (Ridge) penalties | Regularization |

---

## 📅 Learning Schedule

Curious about what I'm studying next? Check out my schedule to see what topics I'm exploring!

| 📆 Date | 📚 Lesson | 
|:-------:|-----------|
| **Feb 27, 2026** | **Understanding Classification Metrics**<br>• Define each metric Accuracy, Precision, Recall, F1, ROC-AUC<br>• Explore their mathematical approaches |
| **Mar 3, 2026** | **F1 Dilema and Quick Review of Performance Metrics**<br>• What cases does higher or lower F1 is better<br>• Quickly review $R^2$, Log-Likelihood, AIC, BIC |
| **Mar 4, 2026** | **Model Analysis (LPM, LOGIT, KNN, DT)**<br>• Explore the math, logic, interpretations, and code of the following models: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Linear Probability Model<br>&nbsp;&nbsp;&nbsp;&nbsp;• Logistics Regression<br>&nbsp;&nbsp;&nbsp;&nbsp;• K-Nearest Neighbours<br>&nbsp;&nbsp;&nbsp;&nbsp;• Decision Tree |
| **Mar 9, 2026** | **Model Analysis (Bagging, RF, AdaB, GradB, XGB)**<br>• Explore the math, logic, interpretations, and code of the following models: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Bagging<br>&nbsp;&nbsp;&nbsp;&nbsp;• Random Forest<br>&nbsp;&nbsp;&nbsp;&nbsp;• AdaBoost<br>&nbsp;&nbsp;&nbsp;&nbsp;• Gradient Boost<br>&nbsp;&nbsp;&nbsp;&nbsp;• XGBoost |
| **Mar 30, 2026** | **Full Power Gradient Boost**<br>• Create a fully powered Gradient Boost with the following hyperparameter tuning: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Cross-Validation<br>&nbsp;&nbsp;&nbsp;&nbsp;• Grid Search|
| **Apr 3, 2026** | **Feature Transformation on Linear Probability Model**<br>• Create a Linear Probability Model the following feature transformations: <br>&nbsp;&nbsp;&nbsp;&nbsp;• Log<br>&nbsp;&nbsp;&nbsp;&nbsp;• Polynomial |
| **Apr 6, 2026** | **XGBoost**<br>• Explore and study XGBoost |
| **Apr 9, 2026** | **Notebook Reworks**<br>• Rework the following notebooks: ... |
| **Apr 10, 2026** | **Feature Selection Selection**<br>• Difference of DT, Bagging, RF Importance and their use cases  |
| **?** | **?**<br>• What happens if you add more neighbors in knn, how much depth for dt, bagging, rf?  |
| **?** | **?**<br>• why is decision tree importance better than random forest importance on boosting methods (Adaboost, Gradient Boost, XGBoost)  |
| **?** | **?**<br>• Create complete models of each i've learned so like pushed to its best performance (use US Census Dataset)  |

**Note to Self:** <u>Make sure to backup what you say in the notebooks with graphs or numbers.</u>


*P.S. This is a living document - I'm constantly adding new things as I learn them. Check back every Mondays, Wednesdays, and Fridays!* ✨
