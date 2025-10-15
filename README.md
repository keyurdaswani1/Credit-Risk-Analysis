# Credit-Risk-Analysis
Performed credit risk analysis by cleaning and merging datasets, removing nulls, and conducting Chi-Square tests to identify variable relationships. Built and tuned Decision Tree, Random Forest, and XGBoost models using GridSearchCV to classify borrowers into credit risk categories with high accuracy.


Key Steps & Methodology

1. Data Cleaning & Preprocessing
Imported and merged multiple datasets while eliminating null values and redundant features.
Handled categorical variables using Label Encoding and addressed multicollinearity with Variance Inflation Factor (VIF) analysis.

2. Exploratory Data Analysis (EDA)
Performed detailed statistical exploration to understand feature distributions and correlations.
Conducted Chi-Square tests to identify dependencies between categorical variables such as loan status, income group, and employment type.
Visualized key trends using Matplotlib and Seaborn.

3. Model Development:
Built and compared multiple classification algorithms, including:
Random Forest Classifier
XGBoost Classifier
Decision Tree Classifier
Split data into training (80%) and testing (20%) sets for model validation.

4. Model Optimization
Tuned XGBoost hyperparameters using GridSearchCV to enhance performance.
Evaluated models using Accuracy, Precision, Recall, and F1-score metrics.

5. Performance Insights
The optimized XGBoost model achieved the highest accuracy and provided reliable credit risk segmentation.
Helped interpret key predictors influencing loan default probability.

Tech Stack
Languages: Python
Libraries: Pandas, NumPy, Scikit-learn, Statsmodels, XGBoost, Matplotlib, Seaborn
Techniques: Feature Engineering, Chi-Square Test, VIF, GridSearchCV, Classification Modeling, Model Evaluation

Outcome

Delivered a robust predictive model capable of classifying customers into low, medium, and high-risk credit segments. This solution demonstrates how machine learning can enhance credit risk assessment and decision automation in the financial sector.
