# Airbnb-Price-Prediction
Predicting and optimizing Airbnb listing prices using machine learning

## Project Overview
This project aims to predict Airbnb listing prices in Chicago based on various features such as number of bedrooms, bathrooms, location, host status, and other factors. The goal is to provide insights into pricing optimization for Airbnb hosts.

## Repository Structure

├── data/                 
├── notebooks/            
├── reports/           
├── .gitignore        
├── LICENSE           
├── README.md            

## Tools & Technologies
Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
Machine Learning Models: Random Forest, XGBoost
Data Visualization: Seaborn, Matplotlib


## Exploratory Data Analysis (EDA):
Visualized price distribution
<img width="1172" alt="Screen Shot 2025-03-14 at 1 43 55 AM" src="https://github.com/user-attachments/assets/12a47c17-f860-44d2-87ba-b7dedb9c6c3d" />

Geographic price distribution using latitude/longitude
<img width="1172" alt="Screen Shot 2025-03-14 at 1 44 34 AM" src="https://github.com/user-attachments/assets/b6553a9a-8627-4703-9dbc-811de73dc831" />

## Feature Engineering:
Converted categorical variables
Handled missing values
Scaled numerical features
Model Training & Evaluation:

Used Random Forest Regressor and XGBoost
Hyperparameter tuning using RandomizedSearchCV
Model performance evaluation using RMSE and R² Score

## Findings & Insights:
Higher-priced listings tend to have more rooms and higher host ratings.
Listings in specific areas have significantly higher prices.
Future improvements include A/B testing for pricing strategy optimization.

## Results
### Model	            RMSE   R²Score
Random Forest (tuned)	151.47	0.68
XGBoost	              176.29	0.57
