# Project Overview
Use Machine Learning to predict the price of Bitcoin, whether it will go up or down. Utilizing data from various sources such as historical price data of Bitcoin, and data from Wikipedia on edits about Bitcoin. This also allows us to use sentiment analysis to analyse the trend according to the edits of Bitcoin in Wikipedia. We collect and clean the data before analyzing. We use the data to train a random forest model which will assist us in showing if Bitcoin prices will rise or fall tomorrow. Next, we use the XGBoost model along with more predictors to enhance and further improve our accuracy.

Backtesting system was also implemented while using a robust error metric to ensure and predict if the algorithm is performing well. 


# Project Steps
1. Load in data
2. Clean and merge the data
3. Create a machine learning model
4. Implement backtesting


# Project setup and installations
The things to install and is used for this project
* Jupyter Notebook
* Latest version of Python
* Python packages:
  * yfinance
  * pandas
  * scikit-learn
  * mwclient
  * xgboost
  * transformers
