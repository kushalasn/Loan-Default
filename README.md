Performance Analysis of Machine Learning Classifiers for Loan Default

In this analysis, we analysed the performance of 3 major machine learning classifiers.
Each classifier's hyperparameters were optimized using GridSearchCV.Evaluation metrcs such as accuracy,auc_score, recall were calculated on the test set.


Decision Tree Classifier
The decision tree classifer achieved decent accuracy of 75%.Decision tree model has good balance between precision and recall, offering alternative for the classification task.

K Nearest Neihgbor
The KNN achieved lower accuracy of 68%.  Decision tree model has good balance between precision and recall, offering alternative for the classification task. Recall has good rate of 35%, it makes it appropriate for prioritising sensitivity over specificity.

XGBoost Classifier 

XGBoost performed best overall. The best overall combination of precison, recall and ROC AUC. It has the highest F1 score. 

Summary recommendation

After evaluating 3 models , XGBoost performed the best, provided strong performance across muultiple metrics. We can choose any model based on metric priority and application requirements. 
