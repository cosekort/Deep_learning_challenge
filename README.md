# Deep_learning_challenge

Overview
The purpose of this activity is to create a neural-network model that will predict which applicants requesting funding for their ventures will be successful. An overview of the data is below!

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

Results: 
Data Preprocessing

Is successful was our target variable for this model. 
Application_type and Classification were used as features in this model. 
We removed the variables EIN and Name from the model prior to modeling. 

Compiling, Training, and Evaluating the Model

We used a total of three layers, two hidden and one output. For the hidden layers, the first layer was assigned 80 units and the second layer 40 units which was later changed in optimization. 
We were not able to achieve the target model performance of 75% for this model. With optimizations, we were only able to get to 73.65% accuracy. 
In order to increase my model performance I attempted to optimize using three different steps. 
  Reduce application type from 1800 to 1000. 
  Added additional epochs from 100 to 120. 
  Increased units in the second hidden layer 40 to 80. 
  

Summary: 
In conclusion, this model did not meet the minimum requirement for 75% accuracy. Despite efforts to optimize the model our accuracy score never surpassed 73.65. Seeing that this modeling did not work to provide us with the minimum accuracy my recommendation would be to run this as a logistic regression. We would pre-process the data, train and evaluate the model, and then analyze the model's coefficient to determine the probability of success. 


