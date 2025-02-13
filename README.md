# House-Price-Prediction
This project aims to predict house prices using Support Vector Regression (SVR). The dataset has been preprocessed, cleaned, 
and normalized before training the model. After testing multiple machine learning algorithms, SVR with RBF kernel was selected due to its superior performance.

##Dataset
- From "Boston Housing Dataset"

## Preprocessing Steps
- Handling missing values by filling with median values.
- Outlier detection & removal using IQR method.
- Feature scaling using MinMaxScaler to normalize data.
- Train-test split: 80% training, 20% testing.

##Model Training
- Linear Regression
- Support Vector Regression
- Random Forest Regressor
  After evaluation, SVR was chosen for final training due to its best performance.
