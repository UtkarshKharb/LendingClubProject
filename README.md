# Lending_Club_Project
In this project, I have analysed a subset of the lending club data available from Kaggle [link](https://www.kaggle.com/wordsforthewise/lending-club).
The dataset I have used(lending_club_loan_two.csv -which is the data and lending_club_info.csv -which is information about the columns) is a subset of the dataset in the above link and has additional information added to make it more usable.

## Data Preparation
1. I have done lots of cleaning and feature engineering i.e removing null values, irrelevant features, converting categorical features to dummy variables and extracting useful features from the available features.
2. Have done many visualisations using Matplotlib and Seaborn to understand the data and the features
3. Data has been normalised using MinMaxScaler since it is being used for a Deep Learning Model

## Deep Learning Model
1. Created a Deep Learning Model using Keras API of Tensorflow
2. Added dropout layers to avoid overfitting

## Model performance is evaluated using sklearn metrics
