# Neural_Network_Charity_Analysis

## Overview
The goal of this project was to predict whether applicants will be successful if funded by Alphabet Soup.

## Results
- The IS_SUCCESSFUL column was the target for the model
- The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT columns were considered the features of the model
- The EIN and NAME columns were neither targets nor features were removed
### Compiling and Training
- For the first model I used four hidden layers and got an accuracy score of 53.3%
- For the second layer I used three hidden layers and got an accuracy score of 72.3%
- For the third model I tried it without hidden layers and used a random forest classifier model to determine the accuracy and got a score of 70.6%
- The SPECIAL_CONSIDERATIONS column was dropped for the second and third attempts

## Summary
For future training, I would remove the USE_CASE and AFFILIATION columns in an effort to use less data for the model.
