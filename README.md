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
* The Random Forest model is the better classifier. It had an accuracy score for:

Training Score: 0.7029009304871374

Testing Score: 0.6978653530377669

* LogisticRegression model unscaled gave me an accuracy score for:

Training Data Score: 0.6522167487684729

Testing Data Score: 0.6472906403940887

* While the scale data logistic Regression had an accuracy score for:

Training Score: 1.0

Testing Score: 0.7113300492610838

this result might be an instant of overfiting


