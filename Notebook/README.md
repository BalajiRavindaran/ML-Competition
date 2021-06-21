# Notebook description

This notebook contains all the steps including understanding the data,data visualization,data pre-processing,correlation grouping,crosstab visualization.<br />

The models Logistic regression,KNN,Decision tree,Random forest are individually predicted and roc curve is observed,later ensemble technique is used across models by Random forest and logistic regression,Random forest and KNN,Random forest and decision tree to get better accuracy.

The accuracy of different models and ensemble models is as followed :<br />
0.9473684210526315 -- Logistic regression<br />
0.8947368421052632 -- KNN<br />
0.9342105263157895 -- Decision tree<br />
0.9736842105263158 -- Random forest<br />
0.9736842105263158 -- Ensemble model with Random forest and logistic regression<br />
0.9736842105263158 -- Ensemble model with Random forest and KNN<br />
0.8421052631578947 -- Ensemble model with Random forest and Decision tree<br />

Since, The models Random forest,Ensemble model with Random forest and logistic regression,Ensemble model with Random forest and KNN have the same accuracy,random forest is used for prediction and the output .csv file containing two columns ID,Target is generated.
