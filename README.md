# Sentiment-Analysis-Model

The goal of the project is to analyze the relationship between world news headlines and stock price shifts using Natural Language Processing (NLP) techniques. The dataset used contains 25 columns of top news headlines for each day, spanning from 2008 to 2016. The labels are based on the Dow Jones Industrial Average stock index, where class 1 indicates an increase in stock price and class 0 indicates no change or a decrease in stock price.

The project begins by importing the necessary libraries, including Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and Scikit-learn for machine learning. The dataset is loaded into a Pandas DataFrame and the columns are inspected. The data is then visualized to gain insights into the data distribution and identify any trends.

The next step is to preprocess the data for NLP. The data is cleaned by removing punctuations and converting all text to lowercase to ensure consistency. A CountVectorizer is used to extract features from the text by converting the text into a matrix of token counts. The data is then split into training and testing datasets to train the machine learning model.

The RandomForestClassifier is used as a machine learning model for training. The model is trained on the training dataset, and its performance is evaluated on the testing dataset. The accuracy score is used to measure the performance of the model, which achieved an accuracy of 84.12% over the test data.

The results of the project show that there is a relationship between news headlines and stock price shifts. The machine learning model is able to predict the stock price changes based on the news headlines, which has implications for investors and financial analysts. The project can inform investment decisions and aid in risk management.

In conclusion, this project utilized NLP techniques to analyze the relationship between world news headlines and stock price shifts. The project highlights the importance of data preprocessing and feature extraction for NLP tasks. The machine learning model's performance shows that there is a relationship between news headlines and stock price shifts, which has practical implications for investors and financial analysts.
