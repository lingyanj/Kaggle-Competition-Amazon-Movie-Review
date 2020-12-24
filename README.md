# Kaggle-Competition-Amazon-Movie-Review
Kaggle Competition in Amazon Movie Review Data Analysis and Prediction

The goal of this competition is to predict star rating associated with user reviews from Amazon Movie Reviews using the available features. For the predictions, I used classical machine learning algorithms, like random forests, regression trees, etc. Using deep learning models, or any other related technique, that lies far from the syllabus of class CS506 is prohibited. What we mainly seek from this competition - besides performance- is smart ways to make sense of the data, construct new features from the available metadata, and understand my thought procedure.

## Data descriptions:
1. train.csv - 1,697,533 unique reviews from Amazon Movie Reviews, with their associated star ratings and metadata. It is not necessary to use all reviews, or metadata for training. Some reviews will be missing a value in the 'Score' column. That is because, these are the scores you want to predict.
2. test.csv - Contains a table with 300,000 unique reviews. The format of the table has two columns; i) 'Id': contains an id that corresponds to a review in train.csv for which you predict a score ii) 'Score': the values for this column are missing since it will include the score predictions. You are required to predict the star ratings of these Id using the metadata in train.csv.
3. sample.csv - a sample submission file. The 'Id' field is populated with values from test.csv. Kaggle will only evaluate submission files in this exact same format.

## Data fields:
ProductId - unique identifier for the product
UserId - unique identifier for the user
HelpfulnessNumerator - number of users who found the review helpful
HelpfulnessDenominator - number of users who indicated whether they found the review helpful
Score - rating between 1 and 5
Time - timestamp for the review
Summary - brief summary of the review
Text - text of the review
Id - a unique identifier associated with a review

## Data link:
[Kaggle](https://www.kaggle.com/c/cs506-fall-2020/data)
