# Collecting and Analysing Big Data - Class Code
 Code from my assignment of Collecting and Analysing Big Data from KU Leuven.
 The assignment was devided in two parts
 
## 1. Connect to an API and retrieve 500 lines of data
The aim is to collect daily currency exchanges from a free API: https://exchangerate.host/#/.
However, the API has a call limit 365 days. Thus, the aim of the script is to allow the users to fetch more years of data with one function and then concatenating the separate calls into one DataFrame.
The function works for multiples of 365 days, however this allows to have API calls for multiple years.

## 2. Classifier of Movie Genre Prediction based on NLP text analysis of their description
The aim is to build different classfiers which leverage NLP methods in order to obtain a prediction of the movie genre based on the text description. Several attempts are made to improve the original Logistic Regression model. Firsly, by implementing a Grid Search to look for better performing parameters, adding stop words and lemmatizing the text.

Afterwards, two new competing models are offered: an XGBoost classifier and a Support Vector Machine. The latter delivers the best validation accuracy, however the Grid Search was limited due to a limited computational power. Deploying the model on a server could allow the search of better performing parameters for the SVM.
 
