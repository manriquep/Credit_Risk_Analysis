# **Credit\_Risk\_Analysis**

**Overview**

Apply machine learning to solve a real-world challenge: credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques are used to train and evaluate models with unbalanced classes.

**Results**

**Oversampling**

- Naive Random Oversampling

![image](https://user-images.githubusercontent.com/74743437/121091446-fea37580-c7b7-11eb-9a55-ced3fc325023.png)

- SMOTE

![image](https://user-images.githubusercontent.com/74743437/121091518-1bd84400-c7b8-11eb-809c-bd63579eb010.png)

**Undersampling**

- Cluster Centroids

![image](https://user-images.githubusercontent.com/74743437/121091645-52ae5a00-c7b8-11eb-9c77-dfdb34053ae5.png)

**Combination (Over and Under) Sampling**

- SMOTEENN

![image](https://user-images.githubusercontent.com/74743437/121091850-a620a800-c7b8-11eb-9503-1039a00dfc33.png)

**Ensemble Learners**

- Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/74743437/121091947-cb151b00-c7b8-11eb-9efc-2f3aef2340ec.png)

- Easy Ensemble AdaBoost

![image](https://user-images.githubusercontent.com/74743437/121091981-dec08180-c7b8-11eb-883c-bf1b2379a76d.png)

**Summary**

Easy Ensemble AdaBoost Classifier is the most effective ML model providing the best f1 score which balances accuracy and precision to consider the score. Precision is found to be low for all the models.

Recommendation would be to use the Easy Ensemble AdaBoost Classifier as it classified the most true positives.
