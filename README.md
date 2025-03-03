# Gold-Price-Prediction-Using-Python-Machine-Learning

## Table of Contents

1. [Introduction](#introduction)

2. [Data Collection and Preprocessing](#data-collection-and-preprocessing)

3. [Exploratory Data Analysis](#exploratory-data-analysis)

4. [Feature Engineering](#feature-engineering)

5. [Model Training](#model-training)

6. [Model Evaluation](#model-evaluation)

7. [Results and Visualization](#results-and-visualization)

8. [Conclusion](#conclusion)

## 1. Introduction

This project aims to predict gold prices using Python and machine learning techniques. By leveraging historical gold price data and key financial indicators, we develop a predictive model using a Random Forest Regressor. This project is useful for financial analysts and traders who want to make data-driven decisions in the commodities market.

## 2. Data Collection and Preprocessing

- The dataset is loaded from a CSV file (gold_price_data.csv).

- Key financial indicators such as SPX (S&P 500 index), GLD (Gold Price), USO (Oil Price), SLV (Silver Price), and EUR/USD exchange rate are included.

- Missing values are checked, and necessary data cleaning steps are performed.

- The Date column is converted to a datetime format.

## 3. Exploratory Data Analysis

- Summary statistics of the dataset are examined.

- A heatmap is generated to analyze correlations between variables.

- A distribution plot of gold prices is visualized.

## Heatmap displaying the correlation of Gold prices and other variables

![image_alt]()



## Distribution of Plot of Gold prices

![image_alt]()


## 4. Feature Engineering

- The dataset is split into features (SPX, USO, SLV, EUR/USD) and the target variable (GLD).

- Data is split into training and testing sets using an 80-20 ratio.

## 5. Model Training

- The Random Forest Regressor model is chosen for training.

- The model is trained on the training data.

## 6. Model Evaluation

- The trained model is used to make predictions on the test set.

- The performance of the model is evaluated using the R-squared (R²) metric, which measures how well the predictions match the actual values.

- The model achieves an impressive R² score of 0.9888, indicating strong predictive performance.

## 7. Results and Visualization

- A comparison between actual and predicted gold prices is plotted.

- The model shows a high level of accuracy, as evidenced by the close alignment of actual and predicted values.

## 8. Conclusion

- This project successfully demonstrates how machine learning can be applied to financial market prediction. The Random Forest Regressor model achieves a high accuracy in forecasting gold prices. Future work could explore additional features, alternative machine learning models, and real-time price prediction.

- This project provides a solid foundation for leveraging data science in financial analytics and predictive modeling.

## Acuatl vPrices vs Predicted values of Gold Price plot

![image_alt]()
