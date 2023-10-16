# Almabetter_ML_Classification_project
Almabetter_ML_Classsification_project
**Health Insurance Cross sell**

The Health Insurance Cross Sell Prediction dataset encompasses the details of 3,81,109 customers who express interest in purchasing insurance, with 10 predictor variables and one target variable. Our initial steps involved data collection, thorough data cleaning to address null values, distribution analysis, and consideration of outliers. After this, we performed typecasting to ensure that the data is in the proper format for visualization.

Our analysis continued with an in-depth exploratory data analysis (EDA) phase, during which we crafted univariate, bivariate, and multivariate plots to unearth valuable insights. These insights informed our decisions regarding the subsequent steps in the machine learning (ML) model pipeline.

To prepare the data for modeling, we engaged in feature engineering and tackled multicollinearity among the independent variables by employing the Variance Inflation Factor (VIF). Notably, we chose not to address outliers, as their removal could lead to a loss of significant information and potentially introduce bias into the results.

We also recognized that certain features were categorical in nature and needed to be encoded into numerical values for machine learning algorithms. We accomplished this using Binary Label Encoding.

The dataset presented a challenge of high class imbalance in the target variable, Response. To mitigate this, we applied the Synthetic Minority Oversampling Technique (SMOTE) to create a balanced dataset.

With the data now well-prepared, we split it into train and test sets to ensure a stratified representation of both classes. Subsequently, we implemented a range of machine learning models, starting with the simple yet effective Logistic Regression, followed by Decision Trees, Random Forests, Naive Bayes, and XGBoost. We evaluated model performance using various classification metrics, including Precision, Recall, F1 Score, Accuracy, and AUC-ROC. Additionally, we assessed the model's effectiveness by examining the confusion matrix to determine the number of correctly and incorrectly classified patients.
