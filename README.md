# deep-learning-challenge
Module 21 Assignment

Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis is to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the features in the dataset.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model? 
- "IS SUCCESSFUL" is the target
What variable(s) are the features for your model?
- The remaining columns, minus the EIN & NAME are the features
What variable(s) should be removed from the input data because they are neither targets nor features?
- the EIN & NAME Variables
- 
Compiling, Training, and Evaluating the Model

For the initial Training Model:
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Number of Input Features: The input layer of the model has an input dimension of 43. This suggests that the dataset being used to train the model has 43 features.

- Number of Neurons (Units) in Hidden Layers:

- First Hidden Layer: 80 neurons with ReLU activation function.
- Second Hidden Layer: 30 neurons with ReLU activation function.

Were you able to achieve the target model performance?
No, I was only able to achieve in the low 70% range

What steps did you take in your attempts to increase model performance?
I adjusted model types, number of neurons and epochs.

In summary, the model was reasonable in it's results. Other things I can try in the future are preprocessing the data differently and limiting other variables out to see if any difference is made.  
