# Supervised Machine Learning-Predict Credict Risk

### Retrieve Data
From LendingClub output two CSVs:
* 2019loans.csv
* 2020Q1loans.csv
We will be using an entire year's worth of data (2019) to predict the credit risk of loans from the first quarter of the next year (2020).

### Preprocessing: Convert categorical data to numeric
Create a training set from the 2019 loans using pd.get_dummies() to convert the categorical data to numeric columns.
Similarly, create a testing set from the 2020 loans, also using pd.get_dummies(). Note! There are categories in the 2019 loans that do not exist in the testing set.

### Fit a LogisticRegression model and RandomForestClassifier model
