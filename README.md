# Background Information
Companies lose revenue due to downtime it takes to hire a new employee and bring that employee up to speed. How can a company tackle this inevitable scenario in order to mitigate revenue loss.

# Problem Statement
As a data scientist you have been tasked with developing a model that efficiently predicts which employees are more likely to quit

# Data available
-https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

# Approach / Method used
Regression models were applied

# Results 
![Dataset_histogram](https://github.com/user-attachments/assets/301abc34-e839-4a6e-a155-796778c5ef49)

![Dataset_heatmap](https://github.com/user-attachments/assets/65a3f977-ebaf-4e0f-81f5-ae1dafb11415)

![JobeRole_MaritalStatus_JobInvolvement_JobLevel vs Attrition](https://github.com/user-attachments/assets/5b0531aa-0003-444a-b256-67d7a3c939be)


The accuracy of the logistic regression approach is                 : 85.03 %
The accuracy of the SVM approach is                                 : 83.84 %
The accuracy of the SVC approach is                                 : 83.50 %
The accuracy of the KNN approach is                                 : 83.50 %
The accuracy of the Naive Bayes approach is                         : 74.66 %
The accuracy of the Decision Tree approach is                       : 75.00 %
The accuracy of the Random Forest approach is                       : 83.67 %
The accuracy of the Cat-G Boost approach is                         : 84.01 %
The accuracy of the k-Fold Cross Val of Cat-G Boost approach is     : 85.39 %
The accuracy of the Meta_Model approach is                         : 85.03 %
The accuracy of the Deep Learning approach is                         : 84.86 %

The classification report for logistic regression approach is : 
              precision    recall  f1-score   support

           0       0.87      0.96      0.91       487
           1       0.63      0.32      0.42       101

    accuracy                           0.85       588
   macro avg       0.75      0.64      0.67       588
weighted avg       0.83      0.85      0.83       588

The classification report for SVM approach is : 
              precision    recall  f1-score   support

           0       0.86      0.96      0.91       487
           1       0.56      0.27      0.36       101

    accuracy                           0.84       588
   macro avg       0.71      0.61      0.63       588
weighted avg       0.81      0.84      0.81       588

The classification report for Kernel-SVM (or SVC) approach is : 
              precision    recall  f1-score   support

           0       0.84      0.99      0.91       487
           1       0.70      0.07      0.13       101

    accuracy                           0.84       588
   macro avg       0.77      0.53      0.52       588
weighted avg       0.81      0.84      0.77       588

The classification report for KNN approach is : 
              precision    recall  f1-score   support

           0       0.85      0.97      0.91       487
           1       0.56      0.18      0.27       101

    accuracy                           0.84       588
   macro avg       0.71      0.57      0.59       588
weighted avg       0.80      0.84      0.80       588

The classification report for Naive Bayes approach is : 
              precision    recall  f1-score   support

           0       0.88      0.80      0.84       487
           1       0.33      0.47      0.39       101

    accuracy                           0.75       588
   macro avg       0.60      0.64      0.61       588
weighted avg       0.78      0.75      0.76       588

The classification report for Decision Tree approach is : 
              precision    recall  f1-score   support

           0       0.85      0.85      0.85       487
           1       0.27      0.27      0.27       101

    accuracy                           0.75       588
   macro avg       0.56      0.56      0.56       588
weighted avg       0.75      0.75      0.75       588

The classification report for Random Forest approach is : 
              precision    recall  f1-score   support

           0       0.84      0.99      0.91       487
           1       0.67      0.10      0.17       101

    accuracy                           0.84       588
   macro avg       0.75      0.54      0.54       588
weighted avg       0.81      0.84      0.78       588

The classification report for Cat-G Boost approach is : 
              precision    recall  f1-score   support

           0       0.84      0.99      0.91       487
           1       0.73      0.11      0.19       101

    accuracy                           0.84       588
   macro avg       0.79      0.55      0.55       588
weighted avg       0.82      0.84      0.79       588

The classification report for Stacking Base Models (Logistic, SVM, SVC, Cat-G Boost) approach is : 
              precision    recall  f1-score   support

           0       0.85      0.92      0.88       501
           1       0.18      0.10      0.13        87

    accuracy                           0.80       588
   macro avg       0.52      0.51      0.51       588
weighted avg       0.75      0.80      0.77       588

The classification report for Deep Learning Model approach is : 
              precision    recall  f1-score   support

           0       0.88      0.94      0.91       487
           1       0.59      0.40      0.47       101

    accuracy                           0.85       588
   macro avg       0.74      0.67      0.69       588
weighted avg       0.83      0.85      0.84       588


Optimal number of features: 46

![ConfusionMatrix_DL](https://github.com/user-attachments/assets/b64dbfaf-5964-4ff1-89da-d570febd7ba8)

