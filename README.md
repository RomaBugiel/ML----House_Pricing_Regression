# House Pricing Dataset Analysis
A comprehensive analysis of the House Pricing dataset with various regression models and feature selection techniques.
Score on Kaggle: 0.15

## Data Science Workflow
* **Data cleaning** Handling missing values, outliers, and inconsistencies.
* **Exploratory Data Analysis** Understanding the data through summary statistics and visualizations.
  * bar plots, count plots, scatter plots, hexplot, probability plots, histograms
* **Feature Engineering** Creating new features or modifying existing ones to improve model performance, such as the "extraordinary" feature storing the information about extra add-ons in house.
* **Feature Selection:** Identifying and selecting the most important features for the model. Techniques used:
  * **VarianceThreshold:** Removes features with low variance.
  * Eliminating highly correlated features, 
  * **Correlation Matrix:** Identifies the most correlated features.
  * **RFE (Recursive Feature Elimination):** Selects features by recursively considering smaller sets of features.
  * **AIC Minimization Method:** Stepwise regression using the dmba library to select features based on the Akaike Information Criterion.
* **Regression Diagnostics:** Performing comprehensive diagnostics including:
  * **Coefficient Analysis:** Evaluating the significance and impact of each feature's coefficient.
  * **Multicollinearity Rejection Using VIF (Variance Inflation Factor):** Identifying and removing highly collinear features.
  * **Residual Analysis:** Checking the residuals to ensure they meet assumptions (e.g., normality, homoscedasticity).
  * **Partial Residual Analysis:** Understanding the relationship between each predictor and the response, adjusting for other predictors.
  * **Leverage and Influence:** Using the OLS method with the statsmodels library to identify influential data points.
  * **Outlier Handling:** Detecting and managing outliers.
  * **Cook's Distance:** Measuring the influence of each observation on the fitted model.
  * **Hat Values:** Identifying leverage points in the data.
  * **Studentized Residuals:** Identifying outliers based on standardized residuals.
* **Model Building:** Selecting and training regression models.
  * Standardization: StandardScaler
  * testing influence of various feature set on model performance
  * **Linear models** Linear Regression, Ridge, Lasso, ElasticNet
  * **Tree-based models** Random Forest
  * Cross-validation techniques & Hyperparameter: K-Fold Cross-Validation and Grid Search
* **Model Evaluation:** Assessing the performance of models using appropriate metrics.
  * RMSE, MAE, MAD, R^2
  * Feature Importance,  permutation importance to evaluate feature relevance.
* **Deployment:** Implementing the model in for Kaggle compatiion

## Technical - General
### Programming Languages and libiraries:
* Python: Pandas, NumPy, Scikit-learn, statsmod, Scipy, Matplotlib, Seaborn, dmba

### Environments
* Jupyter Notebooks
* Revision Control: Git


