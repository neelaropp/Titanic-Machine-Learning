COMP4432 Machine Learning - Assignment 3

Titanic Survival Prediction

This project explores predicting the survival of passengers on the Titanic using machine learning techniques. The dataset, sourced from Seaborn, contains information about passengers, including demographic details, travel class, fare price, and survival status. The project follows a structured workflow, beginning with data cleaning and feature engineering, followed by initial model training and evaluation, and concluding with model tuning and optimization.

The first phase involves data exploration and preparation. The dataset is assessed for missing values, with appropriate imputation or removal strategies applied. Redundant features are identified and eliminated, while useful new features, such as adult_male, are engineered. Exploratory Data Analysis (EDA) is performed to understand data distributions and relationships between variables.

In the second phase, three machine learning models are trained: Logistic Regression, Support Vector Classifier (SVC), and Decision Tree. Cross-validation is employed to generate probability predictions, and the models are evaluated using classification reports, confusion matrices, and ROC-AUC scores. The results provide insights into how well each model differentiates between passengers who survived and those who did not.

The third phase focuses on model tuning. StandardScaler is applied to standardize the training and testing datasets, ensuring that models perform optimally. The Support Vector Classifier is re-evaluated using scaled data to assess improvements in predictive performance. A hyperparameter search is conducted using GridSearchCV to optimize the SVC model, exploring different values for kernel type, regularization parameter (C), and gamma. The best model is identified based on the highest ROC-AUC score and is evaluated on the test dataset.

Key findings from this project highlight the importance of feature engineering, data preprocessing, and hyperparameter tuning in improving model performance. The results demonstrate that standardization significantly enhances the performance of the Support Vector Classifier, while hyperparameter tuning further refines its predictive ability. The final model selection is based on comparing ROC-AUC scores to determine the most effective classifier.

This project underscores the necessity of a structured approach to machine learning, where data cleaning, exploratory analysis, and iterative model tuning are crucial for building a reliable predictive model. The implementation showcases how various machine learning techniques can be leveraged to gain meaningful insights and improve classification performance in real-world datasets.
