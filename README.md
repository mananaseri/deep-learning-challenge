# deep-learning-challenge

Alphabet Soup Deep Learning Model Report


we used neural networks to predict whether applicants will be successful if funded by Alphabet Soup. our goal is to achieve a target predictive accuracy higher than 75%.


In Data Preprocessing

First read in the charity_data.csv to a Pandas DataFrame, 

We removed the 'EIN', 'NAME' columns from the input data as they were neither targets nor features and had no contribution to predict power of the model.

The target variable for our model indicates whether the funding provided by Alphabet Soup was successful (1) or not (0).

Features variable include various columns such as 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and others.

Moreover we did Compiling, Training, and Evaluating the Model


How many neurons, layers, and activation functions did you select for your neural network model, and why?

We selected a deep neural network architecture with three hidden layers consisting of 80 and 30 neurons, respectively. we used ReLU as activation function in each hidden layer

Were you able to achieve the target model performance?

No, we were not able to achieve the target model performance with an accuracy higher than 75%.


Steps Taken to Increase Model Performance:
1) we dropped non-beneficial columns, scaling features, and encoding categorical variables.
2) Experimentation with different architectures and hyperparameters.

Summary

In summary, the deep learning model that was developed could not achieve the target predictive accuracy of over 75% and we got the 72 % accuracy. To  achieve the predictive accuracy of over 75% We should consider perform feature engineering and use more advanced techniques such as transfer learning .
