# ApplyAIGroupProject
Utilizing machine learning in order to predict the amount of energy consumed by buildings

Note: There are 4 csv files in our project.
original_train.csv: Raw training data from kaggle.
original_test.csv: Raw test data from kaggle. This one is discarded from testing process because it misses "site_eui" factor.
cleaned_train.csv: Cleaned training set that randomly seperated from the cleaned original_train.csv (weights 90%).
cleaned_test.csv: Cleaned test set that randomly seperated from the cleaned original_train.csv (weighs 10%).
(The cleaned_csv split is accomplished using Data_Cleansing.ipynb. It can be opened using Juypter Notebook.)
