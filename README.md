# BTC_Price_Prediction_and_Data_Mining [ Algorithm Track ]

# Team Members

Prerna Garsole (016015831)

Farazuddin Mohammad (016176836)

Pranav Chandra Kallepalli (016587064)

# Details and Project Documents


Kaggele Dataset : https://www.kaggle.com/datasets/team-ai/bitcoin-price-prediction

Colab notebook for Prerna Garsole  Contribution : https://github.com/MDfarazuddin99/BTC_Price_Prediction_and_Data_Mining/blob/main/Prerna_Garsole_255FinalProject.ipynb

Colab notebook for Farazuddin Mohammad Contribution :https://github.com/MDfarazuddin99/BTC_Price_Prediction_and_Data_Mining/blob/main/BTC_LSTM.ipynb

Colab notebook for Pranav Chandra Kallepalli Contribution : 

**Presentation :** https://github.com/MDfarazuddin99/BTC_Price_Prediction_and_Data_Mining/blob/main/Group18-BitcoinPricePrediction.pptx

**Video Demo :**

**Project Report : **

# Contributions 

# Introduction 

The main goal of this project is to forecast the price of Bitcoin, the most popular cryptocurrency in the world right now.By compiling information from coin market cap and taking into account numerous hyper-parameters that have affected bitcoin prices in the past, we are able to provide reliable price predictions.

# Objective 
Bitcoin(BTC) is a decentralized digital currency that can be transferred on the peer-to-peer bitcoin network. BTC transactions are verified by network nodes through cryptography and recorded in public distributed ledger called blockchain.
The accurate prediction of bitcoin price can not only provide decision support for investors but also provide reference for the government to formulate regulatory policies.
Our aim is to perform Exploratory Data Analysis on the Bitcoin Prices Data and build, develop and test models to perform price prediction.

# About Dataset

Date: date of the record (Sequential Data) (Feature Variable).

Open: the opening price, the price at which an asset, in this case, Bitcoin, trades at the beginning of the day. (USD) (Feature Variable).

High: the maximum price of the day, the highest price reached by Bitcoin on that day, (USD) (Feature Variable).

Low: the minimum price of the day, the lowest price reached by the Bitcoin on that day, (USD) (Feature Variable).

Close: the closing price, the price at which Bitcoin trades at the end of the day, (USD) (Target Variable).

Volume: the sum of actual trades made during the day, (USD)(Feature Variable).

Market Cap: market capitalization, the total value of all shares of a company(Feature Variable).

<img width="1104" alt="Screen Shot 2022-12-14 at 4 55 55 PM" src="https://user-images.githubusercontent.com/99928364/207747197-00116655-6a3a-4171-892e-57368ba0e292.png">

# Architecture Diagram

<img width="719" alt="Screen Shot 2022-12-14 at 4 59 23 PM" src="https://user-images.githubusercontent.com/99928364/207747561-ed2a72d1-363d-4cb6-b68e-bfc8e2ad3418.png">


# Models Tested

1. Statistical Models

      a. Auto Regressive Model Time Series data set
  
      b. Moving Average Model Time Series data set
  
      c. Auto Regressive Integrated Moving Average Time series data set
  
2. KNN Model to predict the closing price using the Trends from other Major Cryptocurrency

3. Random Forest to predict the closing price using the Trends from other Major Cryptocurrency

4. Gradient Boosting to predict the closing price using the Trends from other Major Cryptocurrency

5. LSTM(Long Short Term Memory)

# Model Implementation
<img width="412" alt="image" src="https://user-images.githubusercontent.com/99928364/207747757-0702800c-acda-4186-9146-b534e0d2687f.png">


# Steps to run

1. git clone gh repo clone MDfarazuddin99/BTC_Price_Prediction_and_Data_Mining

2. cd BTC_Price_Prediction_and_Data_Mining

3. Install python libraries using command **pip install -r requirements.txt**

4. Run the application now by typing flask run or python app.py

# Conclusion

Performed EDA to Observe Trends in features used int BTC Price Prediction.

Built and Tested the following models

      1. Statistical Models: Auto Regression, Moving Average and ARIMA
      
      2. KNN

      3. Gradient Boosting Regression

      4. Decision Tree Regressor

      5. Random Forest Regression

      6. LSTM
      
Added Model Explainability using Shap API.


# Future Work

1. Doing Hyperparameter tuning on the ensemble models to get better performance.

2. Adding confidence data based on the expert suggestion to tweak the model in live conditions can be useful.

3. Adding Acceleration component for faster training and performance Boost.

# References

[1] Shengao Zhang, Mengze Li, Chunxiao Yan, "The Empirical Analysis of Bitcoin Price Prediction Based on Deep Learning Integration Method", Computational Intelligence and Neuroscience, vol. 2022, Article ID 1265837, 9 pages, 2022. https://doi.org/10.1155/2022/1265837

[2] Statistical models: https://towardsdatascience.com/bitcoin-price-prediction-using-time-series-forecasting-9f468f7174d3

[3] https://medium.com/geekculture/lstm-for-bitcoin-prediction-in-python-6e2ea7b1e4e4






