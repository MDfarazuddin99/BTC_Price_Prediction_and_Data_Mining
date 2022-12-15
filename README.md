![Python](https://img.shields.io/badge/Python-3.x-red) ![ML](https://img.shields.io/badge/Machine-Learning-blue) ![LSTM](https://img.shields.io/badge/Model-LSTM-lightgrey) ![TF](https://img.shields.io/badge/TensorFlow-2.x-orange) ![Status](https://img.shields.io/badge/Status-Completed-success) ![DS](https://img.shields.io/badge/Data-Science-ff69b4)

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

**Project Report :**

# Contributions 

<img width="624" alt="Screen Shot 2022-12-14 at 5 33 20 PM" src="https://user-images.githubusercontent.com/99928364/207751621-709b1270-34b1-4c73-a05b-d34a316e6bcd.png">

<img width="617" alt="Screen Shot 2022-12-14 at 5 31 09 PM" src="https://user-images.githubusercontent.com/99928364/207751346-52b3e72a-199b-44cd-982c-3cea501c8fc7.png">

<img width="617" alt="Screen Shot 2022-12-14 at 5 32 11 PM" src="https://user-images.githubusercontent.com/99928364/207751485-d522bbea-49df-43c4-b3d8-e280470da497.png">



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

# LSTM Model Architecture 

<img width="1015" alt="Screen Shot 2022-12-14 at 5 38 18 PM" src="https://user-images.githubusercontent.com/99928364/207752191-4a660f3f-b20b-464a-851a-3009fa6012cd.png">


# Model Implementation
<img width="412" alt="image" src="https://user-images.githubusercontent.com/99928364/207747757-0702800c-acda-4186-9146-b534e0d2687f.png">


# Statistical Models Comparison

<img width="1015" alt="Screen Shot 2022-12-14 at 5 37 00 PM" src="https://user-images.githubusercontent.com/99928364/207752044-f6a1c9b7-b891-4238-b315-bfe97c59bcce.png">

# Stock Price of BTC for this year start

<img width="1046" alt="Screen Shot 2022-12-14 at 5 42 47 PM" src="https://user-images.githubusercontent.com/99928364/207752744-cf84ce49-ed11-4f3a-a221-307d65d74e81.png">

# Bitcoin prices high and low for year 2021

<img width="1013" alt="Screen Shot 2022-12-14 at 5 54 24 PM" src="https://user-images.githubusercontent.com/99928364/207754073-d9deb72e-3e42-4138-9810-73b4ddd71ad7.png">

# BTC Prediction Using Trends from other Cryptocurrencies

<img width="969" alt="Screen Shot 2022-12-14 at 5 56 56 PM" src="https://user-images.githubusercontent.com/99928364/207754373-c8310a0b-5089-4644-98f2-603dc2340669.png">

# Correlation Matrix Plot

<img width="406" alt="image" src="https://user-images.githubusercontent.com/99928364/207754465-0e6233c4-301f-47d1-9ead-4040ab8c9a55.png">

# Feature wise Scatter Plot

<img width="407" alt="image" src="https://user-images.githubusercontent.com/99928364/207754556-ca500263-37be-4997-b4ca-2acb19f751b5.png">

# Models Tested to predict Clos BTC

<img width="374" alt="image" src="https://user-images.githubusercontent.com/99928364/207754633-bdf2e7c6-76d4-4366-a56a-db72eff47bc5.png">

# Random Forest Regressor

<img width="468" alt="image" src="https://user-images.githubusercontent.com/99928364/207754686-a16bf363-49b1-48e1-9414-be7ccc2376f0.png">

# Model Explainability Using SHAP (plot-1)

<img width="593" alt="image" src="https://user-images.githubusercontent.com/99928364/207754723-47af723c-6040-4387-95b7-4d9dce28ad8c.png">


<img width="569" alt="image" src="https://user-images.githubusercontent.com/99928364/207754749-907678f3-53e8-4dfa-a717-b6459e45428f.png">


<img width="526" alt="image" src="https://user-images.githubusercontent.com/99928364/207754800-e6f9de18-45b3-4f61-b53d-7a1d501e8dec.png">

# Lag plots and Histogram

<img width="1217" alt="Screen Shot 2022-12-14 at 6 06 17 PM" src="https://user-images.githubusercontent.com/99928364/207755531-3c7cfc19-00fe-4513-ab9f-912330fb5ba7.png">

<img width="1038" alt="Screen Shot 2022-12-14 at 6 01 08 PM" src="https://user-images.githubusercontent.com/99928364/207754948-ce8d0b30-9eac-4711-873b-f5e97107a9d8.png">

# Making Data ready for LSTM Model

<img width="703" alt="Screen Shot 2022-12-14 at 6 02 03 PM" src="https://user-images.githubusercontent.com/99928364/207755040-fae6cf69-fbe3-47c1-b4b2-232d8ad25769.png">

# Train LSTM Model

<img width="1033" alt="Screen Shot 2022-12-14 at 6 02 40 PM" src="https://user-images.githubusercontent.com/99928364/207755099-14f6b6c2-a2e5-4757-aa3e-a0fc556f4e2a.png">

<img width="923" alt="Screen Shot 2022-12-14 at 6 03 11 PM" src="https://user-images.githubusercontent.com/99928364/207755178-60a2ee9d-b83b-43fd-a3c6-0bc5b6411355.png">

# LSTM Predictions using testX and plotting line graph against Actual testY

<img width="954" alt="Screen Shot 2022-12-14 at 6 04 16 PM" src="https://user-images.githubusercontent.com/99928364/207755308-a6f28b8f-4143-4379-b055-8d0b8397c4eb.png">

<img width="1053" alt="Screen Shot 2022-12-14 at 6 04 34 PM" src="https://user-images.githubusercontent.com/99928364/207755342-67ac89bc-f139-4129-971e-fb5e46af37cb.png">


# Future Price Predictions - For 5 Days beyond the actual trading days where there is no idea for realtime data

![image](https://user-images.githubusercontent.com/99928364/207755408-cfb6f11a-ce39-4e53-a108-c6bb4184888f.png)


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






