# ApplyAIGroupProject
Utilizing machine learning in order to predict the amount of energy consumed by buildings

Note: There are 4 csv files in our project.
original_train.csv: Raw training data from kaggle.
original_test.csv: Raw test data from kaggle. This one is discarded from testing process because it misses "site_eui" factor.
new_train.csv: New training set that randomly seperated from the original_train.csv (weights 90%).
new_test.csv: New test set that randomly seperated from the original_train.csv (weighs 10%).
(The csv split is accomplished using CSV_Split.ipynb. It can be opened using Juypter Notebook.)
