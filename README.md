# Comparision-between-Linear-Regresssion-Logistic-Regression-Models

The notebook contains a comparison between Linear Regression and Logistic Regression on a given data sets

Data Source: CreditDataset.csv:
  - Comma-separated-value file provided which has 690 records in the data set. 
  - There are no missing values in the data. There are 13 attributes (columns in the data)
  - Final column representing the target class label (whether to allow the individual to have a credit card or to decline his or her application).
  - There are 6 numerical and 8 categorical attributes, The original character values have been changed to make them easy to use by an analytic algorithm.
  - For example, Column 4 originally had one of three character labels: ‘p’, ‘g’, or ‘gg’. These have been changed to the values 1, 2 or 3.
  - The last column (Column 14) is the target you are trying to predict. The value of ‘1’ indicates that your organization should allow this individual to have a credit card. The value of ‘0’ indicates that this individual’s application should be rejected.


Actions taken
- Load the “CreditData.csv”
- Create two subsets of data – one half for training data and the other half for test data.
- Train the linear regression model and logistic regression model
- Evaluate the performance of the models using Mean Squared Error
