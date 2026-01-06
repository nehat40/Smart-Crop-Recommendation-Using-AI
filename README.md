# Smart-Crop-Recommendation-Using-AI

This project uses AI and machine learning to analyze soil, weather, and environmental conditions and recommend the most suitable crop for be

![img](https://github.com/nehat40/Smart-Crop-Recommendation-Using-AI/blob/52ea7fe0bda2f55f13e56656147a85a9bff313a5/Presentation1.jpg)

Crop selection depends on soil type, climate, temperature, rainfall, nutrient levels, and market conditions. Incorrect crop choices can result in low yield, financial loss, and resource wastage. To support smarter, data-driven farming decisions, I built an AI-powered Smart Crop Recommendation System that recommends the best crop based on environmental and soil parameters.

Objective:

The main objective of this project is to help farmers, students, and agricultural researchers identify the most suitable crop to cultivate for a given set of conditions. This project uses machine learning to analyze input features such as:

Nitrogen (N) level

Phosphorus (P) level

Potassium (K) level

Temperature

Humidity

Rainfall

Soil pH

Based on these factors, the model predicts the most suitable crop from a predefined list.

Why This Project Matters:

Choosing the right crop is essential for:

Higher crop yield

Reduced fertilizer and resource usage

Sustainable farming practices

Increased profitability for farmers

Improved food security

This solution aligns with the mission of AI for Good, helping communities make better agricultural decisions.

Dataset:

The dataset includes soil nutrient values and climate conditions for multiple crops such as rice, maize, chickpea, kidney beans, pigeon peas, banana, mango, grapes, watermelon, muskmelon, orange, apple, cotton, lentil, and more. Each row in the dataset has the following attributes:

Feature Description N Nitrogen content in soil P Phosphorus content in soil K Potassium content in soil temperature Average temperature humidity Average humidity (%) ph Soil pH level rainfall Rainfall (mm) label Recommended crop Machine Learning Approach:

To build this project, I used the following steps:

Data pre processing: cleaned the data, handled missing values if any, and normalized numerical features.

Exploratory Data Analysis (EDA): visualized soil nutrients, rainfall patterns, and correlations.

Model selection: tested different ML models such as

KNN
Random Forest
Decision Tree
XG Boost
ADA Boost
GaussianNB
SVM

Model training: split the dataset into training and testing sets.

Model evaluation: measured accuracy, precision, recall, and confusion matrix.

The Random Forest Classifier performed best due to its robustness and ability to handle diverse agricultural conditions.

Model Performance:

The model achieved a high accuracy (often above 99% depending on hyperparameters), which shows it can reliably recommend crops. The confusion matrix showed strong classification accuracy across most crops.

Conclusion:

The Smart Crop Recommendation using AI project demonstrates how machine learning can support agriculture through intelligent decision-making. By analyzing soil nutrients and climate conditions, the model recommends the best crop, helping farmers increase productivity and reduce risks. This system can be expanded into a full-scale agritech solution, promoting a future where farming becomes more efficient, sustainable, and profitable.


