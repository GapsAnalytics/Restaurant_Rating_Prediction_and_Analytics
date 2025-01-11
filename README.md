# Restaurant Rating Prediction and Analytics
### Project Overview
This repository contains a machine learning model that predicts the aggregate rating of a restaurant based on its features. The target variable is Aggregate rating, which is predicted using various restaurant attributes like cost, location, votes, and other metadata.
The project demonstrates the complete workflow of data preprocessing, model training, evaluation, and deployment using Python.
### Tools
- MS Excel -Data Cleaning
- Python Programming Language- EDA and visualization
### Libraries
- Jupyter notebook
- Pandas
- Numpy
- SckitLearn
- Seaborne and Martplotlib
### Data Cleaning and Sorting
It involves cleaning data to remove null/missing values or using an imputer class to compute the mean, median or mode where data are missing/null.
### Data Processing
1. Label Encoding
2. Feature Engineering:  It involve separating the input variable from the target variable.
3. Data Visualization: It involve displaying the target class in a scatterplot to determine the best model to use based on the data points distribution.
4. Adjusting imbalanced dataset- This is achieved using undersampling or oversampling method with the smote class or resampling method
### Data Splitting
If the data set are not splitted originally, a test_train_split class from sklearn is used to achieve this. But if the data is seperated into train and test data on differnt spreadsheet. Then it is necessary you tag them as X_train, X_test, Y_train, Y_test.
### Data Rescaling
The StandardScaler is used to fit and Transform the X_train, then transform the X_test to have mean value of 0 and standard deviation of 1.
### Model Training
Based on the distribution of data points, a logistic regression classifier algorithm was used to train the model.
### Evaluation
Evaluate models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R².
The r2 score was found to be 95.9%.
### Recommendation
Hyperparameter tuning can be employed to iterate through all other supervised machine learning algorithm to geth the best performer. This involve using GridSearchCV class.

