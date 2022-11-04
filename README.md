# BreastCancerPrediction
A Machine learning project that predicts breast cancer in patients upon analyzing the dataset using various ML algorithms.
The dataset upon correlation is split into two parts named X and Y consisting or the dependent and non-independent values respectively.
Upon this, the dataset is split into two part i.e the training and the testing part namely X_train, x_test , Y_train and Y_test .

Feature Scaling of the data is done before the training phase.

Function 'model' consists of three training algorithms that the training data goes through in order to create trained models.

Random Forest algorithm turns out to be the most accurate training algorithms in this particular case and hence a 'BCMP.joblib' model 
is dumped that predicts data using the Random forest algorithm.
