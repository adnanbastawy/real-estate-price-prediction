Real Estate Market Analysis & Price Prediction
Overview

This project analyzes real estate listings in Egypt to understand property price patterns and build machine learning models for price prediction.

The project covers both property sales and residential rentals, starting from data cleaning and exploratory data analysis and ending with machine learning model evaluation.

Objectives
Analyze real estate prices across different property types and locations.
Understand the factors that affect property prices.
Explore relationships between property features and prices.
Compare different machine learning models.
Evaluate model performance using regression metrics.
Build models that can estimate real estate prices.
Dataset

The dataset contains real estate listings with information such as:

Property type
Location
Area
Number of bedrooms
Number of bathrooms
Furnishing status
Price
Other property-related features

The dataset was cleaned and prepared before performing the analysis and modeling.

Project Workflow

The project follows this workflow:

Data Collection
Data Cleaning
Exploratory Data Analysis
Feature Engineering
Data Preprocessing
Train / Validation / Test Split
Model Training
Hyperparameter Tuning
Model Evaluation
Results Analysis
Exploratory Data Analysis

The analysis investigates:

Property price distributions
Price differences between locations
Relationship between area and price
Effect of bedrooms and bathrooms on price
Differences between property types
Differences between sales and rental markets
Machine Learning Models

Several regression models were evaluated, including:

Linear Regression
Random Forest
Gradient Boosting
CatBoost

The models were compared using regression evaluation metrics.

Evaluation Metrics

The models were evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score

These metrics were used to compare prediction errors and how well the models explained the variation in property prices.

Results

The final analysis showed that machine learning models can capture important relationships between property characteristics and prices.

The best-performing model was selected based on the evaluation results from the test data.

Sales Market
R²: 0.83
MAE: 2.50M EGP
RMSE: 3.98M EGP
Rental Market
R²: 0.84
MAE: 11.24K EGP
RMSE: 18.4K EGP
Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
CatBoost
Jupyter Notebook

Key Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
Feature Engineering
Data Preprocessing
Regression
Model Selection
Hyperparameter Tuning
Model Evaluation
Data Visualization
Machine Learning

Future Improvements
Add more recent real estate listings.
Include additional property features.
Experiment with additional machine learning algorithms.
Deploy the final model as a web application or API.
Build an interactive interface for real estate price prediction.

Author

Adnan Bastawy

Data & AI Engineer Intern | Samsung Innovation Campus
