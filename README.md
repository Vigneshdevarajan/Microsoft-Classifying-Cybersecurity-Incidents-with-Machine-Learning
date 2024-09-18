Microsoft Cybersecurity Incident Classification

Project Overview
The Microsoft Cybersecurity Incident Classification project aims to enhance the efficiency of Security Operation Centers (SOCs) by developing a machine learning model that accurately predicts the triage grade of cybersecurity incidents. The model classifies incidents into three categories: True Positive (TP), Benign Positive (BP), or False Positive (FP). This classification aids SOC analysts in prioritizing incidents and responding to threats more effectively.

Data Exploration and Understanding
Purpose: To understand the dataset's structure, feature types, target variable distribution, and patterns.
Key Steps:
Loaded and inspected the dataset (train.csv).
Conducted Exploratory Data Analysis (EDA) to identify patterns, correlations, and anomalies.
Data Preprocessing and Feature Engineering
Purpose: Prepare the dataset for modeling by addressing missing values and enhancing feature sets.
Key Steps:
Handled missing data through imputation or row removal.
Engineered new features and encoded categorical variables.
Data Splitting
Purpose: Split the dataset into training and validation sets for model performance evaluation.
Key Steps:
Performed an 80/20 train-validation split.
Applied stratified sampling to maintain class distribution.
Model Selection and Training
Purpose: Identify and train suitable machine learning models.
Models Used:
Baseline Models: Logistic Regression, Decision Trees.
Advanced Models: Random Forests.
Key Steps:
Implemented k-fold cross-validation.
Model Evaluation and Tuning
Purpose: Evaluate and fine-tune models using appropriate metrics.
Key Metrics:
Macro-F1 Score, Precision, Recall.
Key Steps:
Evaluated performance on the validation set.
Model Interpretation and Feature Importance
Purpose: Understand feature impact on model predictions.
Error Analysis
Final Evaluation on Test Set
Purpose: Assess model generalizability and robustness.
Key Steps:
Evaluated the model on a separate test set and compared results to the baseline.
Reporting
Purpose: Document the entire process and provide recommendations.
Sections:
Model Documentation: Rationale for model choices, challenges, and optimizations.
