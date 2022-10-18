# Neural_Network_Charity_Analysis

## Overview of the analysis: 

Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special consideration for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively

**The purpose of this analysis is using determine which applicants will be successful if funded by Alphabet Soup by using machine learning to create a binary classification.**

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing

What variable(s) are considered the target(s) for your model?
  - IS_SUCCESSFUL
  
What variable(s) are considered to be the features for your model?
  - APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
  
What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN and Name

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

  - Hidden layer 1 nodes = 80
  - Hidden layer 2 nodes = 30
  - Three layers (Two hidden & output)
  - Activation functions used - ReLu (hidden layers) and Sigmoid (output)

What steps did you take to try and increase model performance?

- Increased neurons in hidden layer 1
- Increased neurons in hidden layer 2
- Changing number of epochs

## Summary:

The results were my machine learning model was 47% accurate and loss score of 72% which is high and thus does not meet the target. Additional layers and potentially more data that is clean would likely increase accuracy. 
