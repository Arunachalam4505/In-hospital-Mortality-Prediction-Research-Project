**MORTALITY PREDICTION PROJECT**

The ability to predict in-hospital mortality of patients at the time of admission could improve clinical and operational outcomes. Various machine learning algorithms have been developed to predict in-hospital mortality and morbidity for all patients older than 45 years with non-cardiac-related surgeries. Machine learning algorithms include logistic regression with elastic net, decision trees, random forest, and XG Boost were primarily used. The Bayesian optimization method was developed to obtain the best parameters as part of hyperparameter tuning. Several re-sampling strategies, including SMOTE, Near Miss, Random Under Sampling, and Random Oversampling, were implemented to address class imbalance issues.

Additionally, a novel cluster based hierarchical DBSCAN method was implemented to oversample all the smaller clusters. Finally, a layered re-sampling approach was carried out to improve the model's overall performance. To enhance the performance of the imbalanced dataset, the F-1 threshold tuning technique is used to move the decision threshold. To evaluate the model's performance, several metrics like F1-score, AUCROC values, AUCPRC values, Precision, Recall, and confidence interval of the model were used. The performance of Logistic Regression and Random Forest improved consistently with all the re-sampling strategies. Random forest classifier had better scores with the novel clustered re-sampling method, whereas the logistic regression showed promising results with the layered re-sampling technique. An F-1 score of 0.227 was achieved using this method after threshold moving.

The dataset will include the record of patients older than 45 years with non-cardiac surgery at Nova Scotia Health Authority Queen Elizabeth II (QEII) hospitals (Victoria General and Halifax Infirmary) Halifax, Canada. The data set was collected of patients admitted from January 1, 2013, to December 1, 2017. Patients with cardiac surgery or deceased organ have been excluded. Also, patients without electronic anesthetic records during surgery have been excluded.

![image](https://user-images.githubusercontent.com/58626731/148839506-9081125c-0b05-4d11-8451-ada27c1a5ebc.png)


