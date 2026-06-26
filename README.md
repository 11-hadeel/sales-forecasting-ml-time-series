# Sales Forecasting Using Time Series and Machine Learning

## Overview
This project was developed as part of my Erasmus+ Traineeship at the University of Bucharest, Faculty of Mathematics and Computer Science.  
The project focuses on product-level sales forecasting using statistical and machine learning models.

The goal was to analyze historical sales data, create forecasting features, compare different models, and evaluate their performance using standard regression and forecasting metrics.

## Project Objective
The main objective of this project is to predict future product sales using time series forecasting techniques and machine learning models.  
This type of forecasting can support business decision-making, revenue planning, inventory management, and operational efficiency.

## Dataset
The project used a monthly product-level sales dataset containing features such as:

- Date
- Year
- Month
- Product ID
- Product Status
- Price
- Next Month Price
- Total Quantity
- Return
- Out-of-Stock Events
- Pandemic Indicator

> Note: The original dataset is not publicly shared due to privacy and confidentiality reasons.

## Methods Used

### Data Preprocessing
- Missing value handling
- Outlier detection and capping using IQR
- Scaling using RobustScaler
- Log transformation of the target variable
- Train-test split with the last 12 months used for testing

### Feature Engineering
The following time series features were created:

- Lag features: lag_1, lag_2, lag_3, lag_6, lag_12
- Rolling mean and rolling standard deviation
- Exponential weighted moving averages
- Month and quarter seasonality features
- Year trend feature
- Difference features

## Models
Several statistical and machine learning models were trained and compared:

- ETS
- SARIMA
- Prophet
- XGBoost
- LightGBM
- LSTM

## Evaluation Metrics
The models were evaluated using:

- MAE
- RMSE
- MAPE
- R² Score
- Correlation

## Results
The best-performing models showed strong forecasting capability, especially after handling outliers and excluding highly irregular product behavior.

LightGBM and XGBoost achieved the strongest overall performance among the tested models, while ETS and LSTM also showed competitive results in specific cases.

## Skills Demonstrated
- Time Series Forecasting
- Data Analysis
- Machine Learning
- Feature Engineering
- Model Evaluation
- Python
- Pandas
- Scikit-learn
- XGBoost
- LightGBM
- Prophet
- LSTM
- Data Visualization

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Prophet
- XGBoost
- LightGBM
- TensorFlow / Keras
- Matplotlib
- Seaborn

## Project Context
This project was completed during my Erasmus+ Traineeship at the University of Bucharest under the topic:

**Time Series for Real-World Applications**
