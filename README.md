# Seecom-Dataset-classification_all-machine-Learning-techniques+EDA
 
The objective of the project is to build and deploy a parsimonious predictive model to detect the faulty wafers using CRISP-DM model. CRISP-DM comprises of six phases: Business understanding, Data understanding, Data Modelling, Model Evaluation and Deployment. The SECOM dataset is used for the purpose of modelling. Thorough exploration of the model is done and the data is prepared. For data preparation purposes, feature selection is done by Boruta, missing value imputation by MICE and imbalance treatment by SMOTEENN. Four models are produced using Decision Tree, Random Forest, XGBoost and AdaBoost. Finally, the model evaluation and final decision is made using the confusion matrix, balanced accuracy, recall and cost.

![image](https://user-images.githubusercontent.com/67371172/159318047-66fc781f-4e39-4ede-ac29-15370a85d6c1.png)

![image](https://user-images.githubusercontent.com/67371172/159318282-9f336891-01a4-4b75-879e-61463616e6f7.png)


Summary: Based on the evaluation metrics and goodness of fit of all models, Random Forest (RF) has the highest accuracy, highest recall, highest AUC, and least cost. The model was produced by transforming the raw data using MICE imputation technique, Boruta feature selection technique and SMOTEENN imbalance treatment. RF is able predict 15 of 19 fail labels and 226 out of 295 pass labels accurately i.e., it can correctly predict more than 75% of each label. Therefore, Random Forest best aligns with the business goal.

Thanks
