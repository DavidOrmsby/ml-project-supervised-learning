# machine_learning_project-supervised-learning

## Goals
- For this project I took the diabetes dataset from kaggle to see if I could make a binary classifaction model capable of predicting whether or not a patient has diabetes.  The dataset has 8 predictor columns and one target column.  Because the task is to diagnose disease, it's important to avoid any going undetected, therefore I will be  using recall score to evaulate the models.

## Files
### Supervised Leaning - Project.ipynb
- This is the notebook where everything is done
### Data/diabetes.csv
- This is a copy of the dataset I used

## Process
- There were many missing values that were recorded as zeroes instead of null
- There were also quite a few outliers that had to be identified and removed
- one column (insulin) was almost half nulls so it had to be dropped
- The data had to be standardized because the predictors were all on different scales
- Next I split the data into 80-20 train/test split and constructed the models.

## Conclusion
- The best model had an accuracy of .83 and a recall score of 0.68
- Glucose is the most important feature for predicting diabetes, and blood pressure is the least important
- However, all of the features were important for the model, as dropping the one with lowest feature score resulted in a decrease in accuracy
- The average age, BMI, glucose, skin thickness, blood pressure, and pregnancies were all higher in people with diabetes

