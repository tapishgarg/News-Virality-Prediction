# News-Virality-Prediction

Using Machine Learning technique to deteremine the virality of news article from "The Times of India"

The dataset we use is the UCI's Online News Popularity dataset - https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity

First I used newspaper3k library of python to get top world news from https://timesofindia.indiatimes.com
Splitted the UCI dataset in 80/20 ratio (train/test)
Here I used RandomForestRegressor to fit my model on the above Dataset.
Used SelectFromModel to identify important features and trained the model on that.

Final step is to convert the dataset that I took from times of India website is to make features like UCI dataset which I didn't show in this repo.
