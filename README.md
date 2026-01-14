# Project Name
> RNN project: Stock Price prediction

## Table of Contents
* [General Info](#general-information)
* [conclusion](#conclusion)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem statement: Given the stock prices of Amazon, Google, IBM, and Microsoft for a set number of days, predict the stock price of these companies after that window.
- Objective: The objective of this assignment is to try and predict the stock 
prices using historical data from four companies IBM (IBM), 
Google (GOOGL), Amazon (AMZN), and Microsoft (MSFT).
​
​
- There are four CSV files corresponding to four stocks: AMZN, GOOGL, IBM, and MSFT. The files contain historical data that were gathered from the websites of the stock markets where these companies are listed: NYSE and NASDAQ.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## conclusion
- Sequential modeling works well for stock data: Recurrent Neural Networks (RNNs) effectively capture temporal patterns in historical stock prices.
- Multi-stock modeling captures market correlations: 
Using data from multiple technology companies (AMZN, GOOGL, IBM, MSFT) improves prediction by leveraging broader market trends.

- Advanced RNNs outperform simple RNNs: 
GRU/LSTM networks handle long-term dependencies better, producing lower validation and test errors than simple RNNs.

- Data preprocessing is critical: 
Proper windowing, scaling, and handling missing values prevent NaNs and ensure stable model training.

- Predictions are reasonably accurate but not perfect: 
While the models can track trends and approximate stock movements, stock markets remain inherently volatile and influenced by external factors beyond historical prices.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used​
- Programming Language: Python 3.x​
- Libraries & Frameworks:​
pandas → data loading & manipulation​
- - numpy → numerical computations​
- - matplotlib & seaborn → data visualization​
- - scikit-learn → data scaling and preprocessing​
- - tensorflow.keras → building and training RNN, GRU, LSTM models​
- Environment: Google Colab 
- Data Sources: Historical stock data CSVs (AMZN, GOOGL, IBM, MSFT)​
- Machine Learning Concepts:​
- - Recurrent Neural Networks (Simple RNN, GRU, LSTM)​
- - Windowing & sequence modeling for time series​
- - Hyperparameter tuning & early stopping​
​
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by IIITB for the online course of ML and AI
- References: upgrad online learning portal


## Contact
Created by [@nooptioncoding] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
