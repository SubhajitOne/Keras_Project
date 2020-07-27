# Keras_Project

This Project is about predicting whether a person will be eligible to get loan or not.
There are 27 features which help us in predicting the eligibility.
Here 'loan_status' is the predicting feature.
Any null value if present was found out.
At first certain Exploratory Data Analysis were done to see how these features are correlated to the actual predicting feature.
Secondly Data Preprocessing was done where missing values are dealt with.
Then Categorical variables were  converted into Dummy variables.
At the end using Keras, neural network was formed to run the model and to predict whether a person will be eligible to get loan.
Here the neural network has 4 layers and the activation function used for the input layer and the 2 hidden layers is 'relu' Rectified Liner Unit 
and for the output layer it is a 'sgmoid' activation function.
20% Dropout layers are being used to prevent overfitting.
Evaluation of the model was done using Classification report and Confusion Matrix.
A new data was introduced and prediction was done on this model.
