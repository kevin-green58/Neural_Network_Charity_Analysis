# Neural_Network_Charity_Analysis

## Overview
The pupose of this analysis was to create a neural network which would predict whether a particular charity would be succcessful if funded by the non-profit, Alphabet Soup.

## Results
### Data Processing
- What variable(s) are considered the target(s) for your model?
The target for the model is whether or not the funding was successful

-What variable(s) are considered to be the features for your model?
The features for the model are application type, affiliation, classification use case, organization, status, income amount, special considerations, and ask amount

-What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and name are neither targets nor features.

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
Initially, I selected two hidden layers with 100 and 50 nodes respectively. This provided an accuracy of approx 66%. Unfortunately, further attempts to optimize the model resulted
in a lower accuracy score.

- Were you able to achieve the target model performance?
I was not able to achive the target performance of 75%. My 3rd attempt resulted in an accuracy of approx. 57%.

- What steps did you take to try and increase model performance?
My first idea was to remove the organization column as there was low variance between this column, but that did not work. My second attempt I added an additional hidden layer so
there were 150, 100, and 50 nodes respectively. This also gave a lower accuracy score. My third attempt I changed the activation function to "tanh" which gave me a lower accuracy
score as well. 

## Summary
I could not achieve the targeted accuracy score, and I don't believe with more fine tuning that 75% is possible with current model. With more descriptive data I believe that it could be
achieved. For further analysis a random forest classifier, or a logistic regression might be worth trying and then compare results.
