# deep_learning_challenge￼
## Overview
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Within my knowledge of machine learning and neural networks, I've used specific features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results
- Training regimen results with 2 hidden layers produced a loss of 55.44% and accuracy of 72.62%
![alt text]https://github.com/abedasalsabil/deep_learning_challenge/blob/main/Model1.png)
- Training regimen results with three hidden layers produced a loss of 55.8% and accuracy of 72.5%
![alt text](https://github.com/abedasalsabil/deep_learning_challenge/blob/main/Model2.png)
- Training regimen results with different activations produced a loss of 55.5% and accuracy of 72.7%
![alt text](https://github.com/abedasalsabil/deep_learning_challenge/blob/main/Model3.png)


### Data Preprocessing
The target variable of the model is IS_SUCCESSFUL, which demonstrates if the money was used effectively. The feature variables of the model were APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT. The variables that were removed from the input data were EIN and NAME as they were used solely for identification purposes.

### Compiling, Training, and Evaluating the Model
The first model uses two hidden layers with "relu", the first layer having 80 neurons and the second layer having 30. This ran for 100 epochs and produced an accuracy of 72.6%. 

The second model was optimized using three hidden layers with "relu". the first layer has 30 neurons, the second layer has 40 neurons, and the third layer has 50 neurons. This ran for 100 epochs and produced accuracy of 72.5%.

The third model was optimized with two hidden layers with different activations which switched to "sigmoid". The ifrst layer had 80 neurons while the seonda layer had 30.The model running for 100 epochs produced results of 72.7% accuracy. 

## Summary
In conclusion, while the accuracies did not have significant varied change, the model with "sigmoid" activation produced higher accuracies than the rest. 
