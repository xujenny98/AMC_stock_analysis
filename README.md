# AMC_stock_analysis
**Sklearn**
We are going to use sklearn as machine learning library; for logistic regression and text feature extraction

**Prepare Taining set**
To train the data, we’ll be using the AMC stock price data set AMC.csv and reddit API. 

**Prepare the test set**
collate the headlines data via an API and we will merge the daily headlines into a single string for each date with the AMC dataset from Yahoo finance. We will then create a new list, unique_dates, which contains the article dates with duplicates removed. As with the training set, we will use vectorizer to transform the text into our set of feature vectors, and set this variable to X_test.

**Fit the Model and Make Predictions**
We‘ll use the machine learning library sklearn to fit a logistic regression model to the training set and make conclusion. 
