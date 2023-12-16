# Predicting-Car-Prices-Using-KNN
In this project, I'll predict a car's market price using its attributes using machine learning workflow. The data set I will be working with contains information on various cars. For each car we have information about the technical aspects of the vehicle such as the motor's displacement, the weight of the car, the miles per gallon, how fast the car accelerates, and more. You can read more about the data set [here](https://archive.ics.uci.edu/dataset/10/automobile) and can download it directly from [here](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data).


Summary of the steps I took in this project:
1. Cleaned the data.
2. Trained two univariate k nearest neighbors models and experimented with different numbers of neighbors. We then used the data obtained from our univariate model to determine which columns to feed into our multivariate model.
3. Trained two multivariate models and used hyperparameter tuning to find the optimal number of neighbors to consider. I suggested that to minimise the RMSE we should consider a model with hyperparameter value of 3 and top 4 predictor columns as the predictor columns in the KNN model.
