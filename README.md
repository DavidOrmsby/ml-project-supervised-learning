# machine_learning_project-supervised-learning

## Goals
- For this project I took the diabetes dataset from kaggle to see if I could make a binary classifaction model capable of predicting whether or not a patient has diabetes.


## Process
- There were many missing values that were recorded as zeroes instead of null
- There were also quite a few outliers that had to be identified and removed
- The data had to be standardized because the predictors were all on different scales
- Next I split the data into 80-20 train/test split and constructed the models.

## Conclusion
- A logistic regression model could predict diabetes with 78% accuracy
- the random forest model could predict diabetes 83% accuracy
- Glucose is the most important feature for predicting diabetes, and blood pressure is the least important
- However, all of the features were important for the model, as dropping the one with lowest feature score resulted in a 10% decrease in accuracy
- The average age, BMI, glucose, skin thickness, blood pressure, and pregnancies were all higher in people with diabetes

