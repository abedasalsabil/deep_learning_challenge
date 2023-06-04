# deep_learning_challenge￼
## Overview
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Within my knowledge of machine learning and neural networks, I've used specific features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results
- Training regimen results with epochs = 100 produced a loss of 55.44% and accuracy of 72.62%
![alt text](https://github.com/abedasalsabil/deep_learning_challenge/blob/main/epoch100.png)
- Training regimen results with epochs = 70 produced a loss of 55.98% and accuracy of 72.61%
![alt text](https://github.com/abedasalsabil/deep_learning_challenge/blob/main/epoch70.png)
- Training regimen results with epochs = 120 produced a loss of 56.90% and accuracy of 72.54%
![alt text](https://github.com/abedasalsabil/deep_learning_challenge/blob/main/epoch120.png)


### Data Preprocessing
The target variable of the model is IS_SUCCESSFUL, which demonstrates if the money was used effectively. The feature variables of the model were APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT. The variables that were removed from the input data were EIN and NAME as they were used solely for identification purposes.

### Compiling, Training, and Evaluating the Model
For all the models, two hidden layers were used. "Relu" was used for both hidden layers because the values cound be an infinite amount. "Sigmoid" was used for the outer layer as the last output would be either 0 or 1. For each model, the following epochs were used: 100, 70, and 120. 

## Summary
In conclusion, a model using 100 epochs is the most effective as it produced higher accuracy scores. However, the differences are very slight when compared to the other models. 
