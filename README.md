# Titanic Survival Prediction
A data analysis and machine learning project using the classic Titanic dataset to predict passenger survival. This project demonstrates data cleaning, visualization, feature engineering, and model comparison using Python.

📄 Overview
The Titanic dataset is a well-known beginner dataset for classification tasks. The goal is to analyze passenger data and build predictive models to determine which passengers survived the disaster.

💡 Objectives
Perform exploratory data analysis (EDA) to understand data distributions and relationships.

Clean data, handle outliers, and preprocess features.

Encode categorical variables for modeling.

Build and evaluate classification models:

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Visualize insights and model performance.

🧰 Tools & Libraries
Python

Pandas

NumPy

Matplotlib

Seaborn

scikit-learn

📊 Exploratory Data Analysis
Summary statistics: Data types, missing values, and descriptive stats.

Visualizations:

Count plots (e.g., gender distribution).

Histograms (age distribution).

Heatmaps (feature correlations).

Boxplots (Pclass vs. family aboard).

Pair plots colored by sex.

🧹 Data Cleaning & Preprocessing
Handled outliers in Siblings/Spouses Aboard using the IQR method.

Dropped non-informative columns like Name.

Label encoded categorical columns (e.g., Sex).

Split data into training and testing sets.

🤖 Model Building
K-Nearest Neighbors (KNN)
Used n_neighbors=3.

Evaluated using accuracy score.

Decision Tree Classifier
Used max_depth=3 for interpretability.

Evaluated with accuracy score, classification report, and confusion matrix.

