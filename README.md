# PremierLeaguePredictor
This project aims to predict the results of the English Premier League. It considers previous data and compares it to actual results to see how accurate the model was.

#Project Walkthrough
Grabbing the match data by parsing the CSV file with pandas and cleaning the data.
Created predictors like rolling averages, shots, goals attempted, etc. as predictors to plug into the model.
Used the sklearn library for the RandomForestClassifier machine learning model to train the predictors.
