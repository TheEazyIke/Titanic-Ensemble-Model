# Titanic Survival Prediction using Ensemble Model

Project Overview

This project employs an ensemble machine learning model to predict survival rates among passengers aboard the Titanic. The process involved comprehensive data exploration, cleaning, feature engineering, and evaluation to deliver accurate predictions.

Steps and Methodology

1. Data Preprocessing

- Loaded and inspected dataset for initial insights.
- Identified missing values and examined their impact.
- Addressed null values by either imputing or dropping based on significance.

2. Exploratory Data Analysis (EDA)

- Analyzed distribution and correlation among features.
- Explored survival rates relative to various passenger attributes (age, gender, class, fare).
- Visualized key insights to guide feature selection (histograms, correlation heatmap, bar charts, box & whisker plots, and pie charts).

3. Feature Engineering

- Created new meaningful features to enhance model performance.
- Converted categorical variables using encoding techniques, such as One Hot Encoding and Label Encoding.
- Normalized and scaled numerical data to optimize model accuracy.
- Implemented the oversampling technic SMOTE to address class imbalance.

4. Model Building
    
- Developed an ensemble model combining various classifiers (Gaussian Naive Bayes, Random Forest, and SVM) to leverage strengths of multiple algorithms.
- Utilized techniques such as cross-validation and hyperparameter tuning to refine model parameters.

5. Evaluation

- Assessed model performance using accuracy, precision, recall, and F1-score.
- Implemented cross-validation to validate robustness and generalizability of the model.

### Major Findings

- Passenger attributes such as gender, class, and age significantly impacted survival likelihood.

- Ensemble models provided superior predictive performance compared to individual classifiers.

### Final Results

The developed ensemble model achieved notable accuracy (~85%), demonstrating effectiveness in predicting passenger survival on the Titanic dataset.

Technologies Used:

- Python
- Pandas, NumPy
- scikit-learn (Ensemble algorithms)
- Matplotlib, Seaborn (Visualization)

Explore the detailed implementation, visualizations, and analyses in the provided Jupyter notebook.
