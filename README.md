# House Pricing Dataset Analysis
A comprehensive analysis of the House Pricing dataset with various regression models and feature selection techniques.
Score on Kaggle: 1.12

## Data Science Workflow
* <span style="color: green; font-weight: bold;">Data Cleaning:</span> Handling missing values, outliers, and inconsistencies.
* <span style="color: green; font-weight: bold;">Exploratory Data Analysis (EDA):</span> Understanding the data through summary statistics and visualizations.
* <span style="color: green; font-weight: bold;">Feature Engineering:</span> Creating new features or modifying existing ones to improve model performance.
* <span style="color: green; font-weight: bold;">Feature Selection:</span> Identifying and selecting the most important features for the models
* <span style="color: green; font-weight: bold;">Model Building:</span> Selecting and training regression models.
* <span style="color: green; font-weight: bold;">Model Evaluation:</span> Assessing the performance of models using appropriate metrics.
* <span style="color: green; font-weight: bold;">Deployment:</span> Implementing the model in a production environment.
* <span style="color: green; font-weight: bold;">Feature Importance Testing:</span> Using techniques like feature importance and permutation importance to evaluate feature relevance.

## Technical - General
### Programming Languages
* Python: Widely used for its simplicity and extensive libraries (<span style="color: green; font-weight: bold;">Pandas</span>, <span style="color: green; font-weight: bold;">NumPy</span>, <span style="color: green; font-weight: bold;">Scikit-learn</span>, <span style="color: green; font-weight: bold;">Scipy</span>)

### Environments
* Jupyter Notebooks
* Revision Control: Git

## Data Manipulation and Cleaning
* Data manipulation: <span style="color: green; font-weight: bold;">Pandas</span> for handling missing values using imputation techniques such as mean and mode (<span style="color: green; font-weight: bold;">SimpleImputer</span>), data standarization (<span style="color: green; font-weight: bold;">StandardScaler</span>)
* Data Visualization: <span style="color: green; font-weight: bold;">Matplotlib</span> and <span style="color: green; font-weight: bold;">Seaborn</span>: creating histograms, box plots, correlation plots, scatter plots, and probability plots.
* Feature Selection: <span style="color: green; font-weight: bold;">eliminated highly correlated features, low-variance features</span>, Recursive Feature Elimination (<span style="color: green; font-weight: bold;">RFE</span>) technique, finding the most target correlated features

## Technical - Machine Learning

### Supervised Learning

> Dataset contains a wide set of features, thus the analysis cover esspecialy

* Linear models (<span style="color: green; font-weight: bold;">Linear Regression, Ridge, Lasso, ElasticNet</span>).
* Tree-based models (<span style="color: green; font-weight: bold;">Random Forest</span>).
* Cross-validation techniques & Hyperparameter tuning: <span style="color: green; font-weight: bold;">K-Fold Cross-Validation and Grid Search</span>
* Metrics: Root Mean Squared Error (<span style="color: green; font-weight: bold;">RMSE</span>), Mean Absolute Error (<span style="color: green; font-weight: bold;">MAE</span>), <span style="color: green; font-weight: bold;">R^2</span> score.
