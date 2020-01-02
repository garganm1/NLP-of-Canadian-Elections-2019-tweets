# NLP-of-Canadian-Elections-2019-tweets

The aim of this notebook is to predict how and what public opinion can signify/signal the current condition of the political landscape of a country (Canada in this case) especially during the time of elections. It is a Sentiment Analysis problem to be analysed using NLP (Natural Language Processing) in the form of text.

We have two datasets in this exercise. One is "generic_tweets" and the other is "Canadian_elections_2019.csv". The model will be fitted over generic tweets and predicted over Canadian elections. Please go through the files to better understand the data.

We will broadly bifurcate the notebook into following parts:

1. Data Cleaning (To prepare the data for analysis - Bag of Words & TF-IDF)
2. Exploratory Data Analysis (To seek out preliminary assumptions/inferences)
3. Model Preparation (To fit several models on generic tweets post the two types of cleaning procedures applied)
4. Model Implementation (To implement the best type of cleaning and model on our Canadian elections dataset)
5. Results (To make inferences and conclusions based on the aim of this exercise as well as confirm any preliminary assumptions/inferences taken during EDA phase)

As a Bonus exercise, we will try word-embedding and N-grams as a basis of data-cleaning to see if there is any improvement in the model
