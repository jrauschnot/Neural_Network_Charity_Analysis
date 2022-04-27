# Neural_Network_Charity_Analysis

# Project Overview:
An analysis of charities using neural networks

## Resources:

* Data Sources: charity_data.csv

* Software: Jupyter notebooks, sk learn, tensorflow

## Results:

* Data Preprocessing

1. What variable(s) are considered the target(s) for your model?
- Target was "IS_SUCCESSFUL" column

2. What variable(s) are considered to be the features for your model?
- Features were remaining columns.

3. What variable(s) are neither targets nor features, and should be removed from the input data?
- Columns "EIN", "NAME" were removed from the input data. 

* Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Attempt 1: 8 neurons, 5 neurons; 2 layers; "relu" activation and "relu" activation
- Attempt 2: 5 neurons; 1 layer; "Sigmoid" activation
- Attempt 3: 8 neurons, 5 neurons, 3 neurons; 3 layers; "relu" activation, "relu" activation, "sigmoid" activation

2. Were you able to achieve the target model performance?
- No, the target model was not achieved

3. What steps did you take to try and increase model performance?
- Various steps included:
    - additional epoch training 
    - additional hidden layers
    - alternative activation functions


## Summary: 
- None of the deep learning models were able to achieve the target of 75% accuracry.  Perhaps a linear regression model would be more appropriate for this data set. 

<img width="647" alt="Screen Shot 2022-04-26 at 8 35 38 PM" src="https://user-images.githubusercontent.com/93015602/165434818-c5cff164-be50-4374-9855-70db3ecd2605.png">

