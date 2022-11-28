# Neural_Network_Charity_Analysis

## Overview of the Analysis
Deliverable 1: Preprocessing Data for a Neural Network Model
Deliverable 2: Compile, Train, and Evaluate the Model
Deliverable 3: Optimize the Model
Deliverable 4: A Written Report on the Neural Network Model 

## Data Preprocessing
- What variable(s) are considered the target(s) for your model? - "IS_SUCCESFUL" is the target in my model

- What variable(s) are considered to be the features for your model? - Application Type, affiliation, Classification, Use Case, Organization, Status, Income AMT, Special Considerations, Ask AMT. 

- What variable(s) are neither targets nor features, and should be removed from the input data? - EIN

## Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? - I used around 300 Neurons, 3 layers and RELU + SIGMOID activation functions

- Were you able to achieve the target model performance? - Unfortunately the accuracy fell below 75 on all 3 attempts, falling short of the goal of 75

- What steps did you take to try and increase model performance? - I increased the layers, the neurons and changed the activation function.

## Summary
Adding too many neurons/layers/epochs may not always be effective in the long run, and can in fact reduce the accuracy score.
