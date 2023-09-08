# voting_outcomes_predictions
This notebook focuses on predicting the outcomes of voting events using a model ensemble approach. 
The goal is to employ multiple machine learning models to create an ensemble that combines their predictions in order to achieve more accurate results.

## Dataset

The dataset used for this task was collected using Show of Hands, an informal polling platform for use on mobile devices and the web, to see what aspects and characteristics of people's lives predict how they will be voting for the presidential election.

Show of Hands has been downloaded over 300,000 times across Apple and Android app stores, and users have cast more than 75 million votes. In this problem, we'll use data from thousands of users and one hundred different questions to see which responses predict voting outcomes.
## Models

To improve the prediction accuracy, an ensemble of machine learning models is employed. The following models are used in the ensemble:

- Gradient Boosting Classifier
- Logistic Regression
- Multi-layer Perceptron Classifier

Each model is trained and tuned independently using appropriate techniques such as cross-validation, hyperparameter tuning, and feature engineering. The idea is to leverage the unique strengths of each model and combine their predictions to make more robust predictions.
