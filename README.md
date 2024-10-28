#The contribution of QB performance to winning - Part 2

An follow-up attempt to understand how predictive a QB's performance is towards the outcome of an NFL game. A Support vector machine (SVM) model will show the predictive significance of the features. 

Goal: Predict the outcome of NFL games (win or loss) based on specific features.
Key Features:
Difference between the two quarterbacks' QBR and EPA/pass.
Difference in average starting field position.
Turnover differential.


##Assessing Reliability of Results
###Cross-Validation: 
Performing k-fold cross-validation to ensure the model's robustness and reduce overfitting.
###Statistical Significance:
Conducting hypothesis tests to assess whether the features significantly predict game outcomes.
###Baseline Comparison:
Comparing the SVM model's performance with a logistic regression.
###Feature Importance Analysis: 
Identifying the most influential features.
