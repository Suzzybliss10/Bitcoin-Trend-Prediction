# Bitcoin-Trend-Prediction
A group project performed for a course module in the University of Strathclyde


This repository contains Python code for analyzing Bitcoin price trends and predicting price movements using machine learning techniques. Below is a description of the main components and functionalities of the code:

Libraries Used:
Pandas: Data manipulation and analysis.
Scikit-learn: Machine learning models and tools.
Matplotlib and Seaborn: Data visualization.
NumPy: Mathematical operations.
Data Loading and Preprocessing:
Bitcoin price data is loaded from a CSV file.
The data is sorted by date.
Various preprocessing steps include converting dates to datetime objects, handling missing values, and creating new features such as next day's closing price and price trends.

Exploratory Data Analysis (EDA):
Price trend analysis through line charts and bar charts.
Volume distribution analysis using pie charts.
Correlation analysis between features.

Feature Engineering:
Creation of new features such as price change, moving averages, and volatility indicators (e.g., Bollinger Bands).
Machine Learning Models:
Utilization of several classification algorithms including Logistic Regression, Random Forest, Bagging Classifier, AdaBoost, and Gradient Boosting.
Cross-validation for model evaluation and tuning.
Model training and testing on both Bitcoin data and combined Bitcoin-Gold data.

Model Evaluation:
Evaluation metrics include precision score, accuracy score, and confusion matrix.
Visualization of results through scatter plots and regression lines.
Integration with Gold Data:
Integration of Bitcoin data with gold price data for comparative analysis.
Feature selection and model training on combined datasets.

Conclusion:
The code provides a comprehensive framework for analyzing Bitcoin price trends and making predictions using machine learning techniques.
It offers flexibility for further experimentation and model improvement.
Feel free to explore the code and adapt it to your specific needs. If you have any questions or suggestions, please don't hesitate to reach out.

(Note: Ensure that necessary data files are available and paths are correctly specified before running the code.)
