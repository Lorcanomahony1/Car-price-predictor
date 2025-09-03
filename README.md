# Car-price-predictor
Software that uses machine learning algorithms to predict car prices using donedeal data


This repository contains the implementation of a machine learning model designed to predict the prices of used cars in Ireland. The model combines data from car listings on DoneDeal.ie with sentiment analysis of social media data from Reddit to enhance prediction accuracy. The project explores various machine learning algorithms, with the Random Forest Regressor achieving the highest performance (R² score of 0.897).

The goal of this project is to create a robust price prediction model for used cars in Ireland, addressing the inefficiencies of subjective pricing by car dealerships. By leveraging machine learning and sentiment analysis, the model provides fair and data-driven price predictions based on car attributes (e.g., make, model, mileage, year) and public sentiment from social media.


Model Performance
Random Forest Regressor: R² = 0.897 (testing set)
Support Vector Regressor: R² = 0.881
Linear Regression: R² = 0.778
Elastic Net Regression: R² = 0.772


Required Technologies

pandas for data manipulation
Programming Language: Python
scikit-learn for machine learning models
textblob for lexicon-based sentiment analysis
transformers for BERT-based sentiment analysis

