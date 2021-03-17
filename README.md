# Neural_Network_Charity_Analysis

## Project Overview
The goal of this project was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing
The target variable in the model is labeled IS_SUCCESSFUL, a binary notation of whether the recipient was effective. 

Variables considered features, or explanations of success, included: application type, affiliation, classification, use case, organization, status, income, ask amount, and other special considerations.

Applicant names and identification numbers were removed because they were neither targets nor features, and should be removed from the input data?

### Compiling, Training, and Evaluating the Model
Based on previous experience with models of the same size, a single neuron with two layers was chosen. The initial activation functions were 'relu' for the hidden layers and 'sigmoid' for the output layer. 

The models tested were not able to achieve the target performance of 75%. 

To increase model performance, the number of layers were increased, the hidden layer activation functions were changed top 'tanh' and model weights were saved every 5 epochs.

## Summary

At 73 percent, two of the models were close to the target performance. To achieve the project goal, further testing with respect to the number of neurons and more research into effective models for data of this size and makeup should be considered. In addition, another machine method approach may be considered.
