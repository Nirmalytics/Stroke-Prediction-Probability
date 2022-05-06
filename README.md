# Stroke-Prediction-Probability
Predicting the probability of stroke occurrence of a dataset which has  several health, demographic and lifestyle details about its patients.

## Final Model
We select features using 
SelectKBest and F_Classif.

I used Logistic Regression with manual class weights since the dataset is imbalanced

Later tuned model by selecting variables with high coefficient >  0.3

Age, Hypertension, heart disease, Avg glucose level, age category are the features obtained

I again tuned this with  Ridge Regression with C = 0.001

I used StratifiedKFold with CV= 10 for cross validation and we got an roc_auc of
0.82562800




