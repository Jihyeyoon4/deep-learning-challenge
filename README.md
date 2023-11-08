# deep-learning-challenge

# Report on the Neural Network Model

## Data Preprocessing

### Target Variable
The target variable for our model is the binary outcome indicating the success of a given instance, denoted as `IS_SUCCESSFUL`.

### Features
The features for our model include the following variables:
- `APPLICATION_TYPE`
- `AFFILIATION`
- `CLASSIFICATION`
- `USE_CASE`
- `ORGANIZATION`
- `STATUS`
- `INCOME_AMT`
- `SPECIAL_CONSIDERATIONS`
- `ASK_AMT`

### Variables to Remove
The variables `EIN` and `NAME` were removed from the input data as they do not contribute to the predictive power of the model.

## Compiling, Training, and Evaluating the Model
<img width="1241" alt="Screenshot 2023-11-08 at 3 45 20 PM" src="https://github.com/Jihyeyoon4/deep-learning-challenge/assets/135522656/5d83f8ff-b0f1-4a54-8f95-a246e141414f">
<img width="629" alt="Screenshot 2023-11-08 at 3 45 37 PM" src="https://github.com/Jihyeyoon4/deep-learning-challenge/assets/135522656/9ccc9f4d-da4c-4203-8a09-8393078b6525">


### Neural Network Architecture
My neural network model consists of an input layer, two hidden layers, and an output layer. The first hidden layer has 7 neurons with ReLU activation, and the second hidden layer has 7 neurons with ReLU activation. The output layer has a single neuron with a sigmoid activation function.


### Model Performance
The model was able to achieve an accuracy of approximately 69.43% on the test data. 

### Steps for Performance Improvement
I tried training for more epochs and experimenting with different hidden layers, number of nodes, activation functions, etc., in order to find the optimal model structure and incresing learning rate to improve performance. 

## Summary

The neural network model achieved an accuracy of 69.43%, indicating some predictive capability. However, there is room for improvement.


