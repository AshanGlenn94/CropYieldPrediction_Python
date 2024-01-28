# CropYieldPrediction_Python

**Description:**

This project focuses on predicting crop yields based on various agricultural factors. The dataset used in this project was sourced from Kaggle and contains valuable information related to crop production and environmental conditions. The goal of this project was to develop and evaluate machine learning models to predict crop yields, helping farmers and agricultural stakeholders make informed decisions.

**Key Features:**

**Data Exploration:** The project begins with EDA to gain insights into the dataset's structure and identify patterns and correlations between different variables.

**Data Preprocessing:** Data preprocessing techniques, including data cleaning, handling missing values, and feature engineering, were employed to prepare the dataset for modeling.

**Model Selection:** Several regression models were implemented and evaluated for their predictive accuracy, including Linear Regression, Random Forest, Gradient Boosting, XGBoost, K-Nearest Neighbors (KNN), Decision Trees, and Bagging Regressor.

**Model Evaluation:** Each model's performance was assessed using various metrics such as R-squared score, Mean Squared Error (MSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE).

**Cross-Validation:** K-fold cross-validation was used to ensure robust model evaluation and mitigate overfitting.

**Visualization:** Data visualization techniques, including heat maps, histograms, pairplots, scatter plots, box/bar plots, were used to visualize the relationships between actual and predicted crop yields.

**Outcome:**

The project's outcome revealed that ensemble methods such as "Random Forest" and "Bagging Regressor" achieve the highest accuracy (R-squared score) among all the models, with approximately 98.56% accuracy. These models can be valuable tools for farmers and agricultural experts to optimize crop production and resource allocation. 

The "Gradient Boost" and "XGBoost" models also demonstrate good performance, with R-squared scores of approximately 83.11% and 97.33%, respectively.

The "Decision Tree" model also performs well, with an R-squared score of approximately 97.62%.

The "Linear Regression" model performs the least effectively among the models, with an R-squared score of only approximately 7.37%. Linear regression may not be suitable for capturing non-linear relationships in the data.

The "KNN" (K-Nearest Neighbors) model exhibits lower accuracy compared to the other models, with an R-squared score of approximately 28.90%. KNN may not be well-suited for this dataset.

![image](https://github.com/AshanGlenn94/CropYieldPrediction_Python/assets/72578388/66b01158-b0bd-4c80-a344-3df9c2f27fa8)


**Impact:**

By accurately predicting crop yields, this project can assist in making data-driven decisions in agriculture, leading to increased productivity and reduced resource wastage. It provides a valuable tool for farmers and stakeholders in the agricultural sector to make informed choices and optimize crop production.
