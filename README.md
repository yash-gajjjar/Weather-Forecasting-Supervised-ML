# Whether Forecasting System Using Supervised Machine learning 

## Predict next-day rain in Australia

![Alt text](https://i.imgur.com/KWfcpcO.png)

### Problem Statement
Predict next-day rain by training classification models on the target variable RainTomorrow.

### Content
The [Rain in Australia dataset](https://kaggle.com/jsphyg/weather-dataset-rattle-package) contains about 10 years of daily weather observations from numerous Australian weather stations. Here's a small sample from the dataset:

![](https://i.imgur.com/5QNJvir.png)

RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or No? 

##### Source & Acknowledgements
Observations were drawn from numerous weather stations. The daily observations are available from http://www.bom.gov.au/climate/data.

An example of the latest weather observations in Canberra: http://www.bom.gov.au/climate/dwo/IDCJDW2801.latest.shtml

##### Data source: 
http://www.bom.gov.au/climate/dwo/ and http://www.bom.gov.au/climate/data

## To extract as much accuracy as possible, we have used several supervised machine learning models shown below.
1. Logistic Regression
2. Decision Tree
3. Random Forest Model

### The following topics are used in this project:

- Exploratory data analysis and visualization
- Splitting a dataset into training, validation & test sets
- Filling/imputing missing values in numeric columns
- Scaling numeric features to a (0,1) range
- Encoding categorical columns as one-hot vectors
- Training a logistic regression model using Scikit-learn
- Evaluating a model using a validation set and test set
- Training and interpreting decision trees
- Training and interpreting random forests
- Overfitting & hyperparameter tuning

