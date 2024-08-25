# classification_challenge

 
## Data Import and Exploration

-Imported the dataset from the provided URL using pandas.
-Displayed the first few rows of the dataset to understand its structure.


##  Prediction:
- Made a prediction that the Random Forest model would perform better than the Logistic Regression model due to its ability to handle complex datasets and non-linear relationships.


## Data Preparation:
- Created the labels set (y) from the “spam” column.
- Created the features DataFrame (X) from the remaining columns.
- Used the value_counts function to check the balance of the labels (y).
- Split the data into training and testing sets using train_test_split.
- Tried to different test_train splits to find the best and settled on 25-75 percent respectively.
  

## Feature Scaling:
- Fit the StandardScaler with the training data.
- Scaled both the training and testing data using the transform function.


## Logistic Regression Model:
- Created a Logistic Regression model with random_state=1.
- Fitted the model to the scaled training data (X_train_scaled and y_train).
- Made predictions on the testing data (X_test_scaled) using the fitted model.
- Calculated the accuracy score of the Logistic Regression model (i.e., 92.79%)


## Random Forest Model:
- Created a Random Forest model with random_state=1.
- Fitted the model to the scaled training data (X_train_scaled and y_train).
- Made predictions on the testing data (X_test_scaled) using the fitted model.
- Calculated the accuracy score of the Random Forest model (i.e., 96.70%)


## Model Evaluation and Comparison:
- Compared the accuracy scores of the Logistic Regression and Random Forest models.
- Evaluated how the actual results compared to the initial prediction.
