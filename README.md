# Ensemble-methods--Classification

In this project, I have used the titanic dataset to study which features related to the passengers of the titanic determine whether they will survive or not. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others. Starting with some exploratory data analysis on the features, followed by creating a feature-engineering pipeline as a part of the data cleaning process, I have trained and tested several ensemble models including - Random forest classifer, XGBoost classifier, Adaboost, Gradient Boosting alongwith othet models like Linear SVC, Decision Tree, Logistic Regression and KNN classifier.

Also, I have encorporated grid search for fine-tuning the models to determine best parameters. The best performing model was chosen on the basis of highest mean cross-validation score, which is the XGBoost classifer (0.85), but it seems to overfit slightly.
