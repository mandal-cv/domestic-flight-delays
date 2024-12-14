# Predicting Domestic Flight Delays

## Predict whether a flight will be delayed for more than 15 minutes

https://www.kaggle.com/competitions/flight-delays-fall-2018

- Ranked **first** on the leaderboard, achieving **ROC AUC of 0.959**, using a tuned **CatBoost** model.  
- Leveraged Random Forest to generate new features for **binary classification**, improving AUC in a highly imbalanced dataset by utilizing class weights and implementing a custom focal loss function.
