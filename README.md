# ML_DHPR
Dataset dhpr (Dihydrofolate Reductase Inhibitors Data) contains values for 325 compounds potent (or not) against cancer cells. For each compound,  115 molecular descriptors have been calculated. Additionally, each sample is designated as "active" (1) or "inactive" (0).The data frame dhfr contains a column called Y with the outcome of binary classification. The remainder of the columns are molecular descriptor (D) values.
Jupyter notebook presents short EDA analysis of  dhpr dataset and 5 ML algorithms ( RF, AdaBoost, ExtraTreesClassifier, LGBM, SVM) with the evaluation and feature importance.
The best model due to quality metrics is AdaBoost Classifier. ( Accuracy: 0.95,  ROC-AUC: 0.98).
