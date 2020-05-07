# Predicting-Insurance-Loss

This is my Olcademy Internship Assignment, wherein I have to predict insurance loss on a sample dataset. I decided against creating my own dataset. This is because I have no experience in the insurance claims department, and hence, my dataset features may have been irrelevant or unimportant. After some digging around, I came across this excellent dataset for the Allstate Claims Severity Kaggle competition.
Link: https://www.kaggle.com/c/allstate-claims-severity/data

Sadly, the features remain anonymized. With that being said however, I would much rather build a strong model that takes into consideration the vast amount and complexity of features involved in insurance claim analysis over a weak model trained on a dataset with finite features and limited examples.

Beyond the preprocessing and data pareparation steps, I had to decide on a model. Given the size of the dataset, my instinct reaction was to go for a neural network. However, due to time constraints, I used XGBoost regression, which delivered satisfactory results.


