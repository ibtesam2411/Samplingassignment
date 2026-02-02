Credit Card Fraud Sampling Analysis
 Objective

The objective of this assignment is to understand the importance of sampling techniques in handling imbalanced datasets and to analyze how different sampling strategies affect the performance of multiple machine learning models.

We use a highly imbalanced Credit Card Fraud dataset, balance it, apply different sampling techniques, and compare model performance.

 Dataset

Dataset used: Creditcard_data.csv

Target variable: Class

0 → Non-fraud transaction

1 → Fraud transaction

The dataset was originally highly imbalanced, so resampling techniques were applied.

 Handling Imbalance

The dataset was balanced using:

SMOTE (Synthetic Minority Over-sampling Technique)

Feature scaling using StandardScaler

 Sampling Techniques Used

Five different sampling techniques were applied:

Sampling1 – Random UnderSampling

Sampling2 – Random OverSampling

Sampling3 – SMOTE

Sampling4 – NearMiss

Sampling5 – Cluster Centroids

 Machine Learning Models Used

Five different ML models were trained:

Model ID	Model
M1	Logistic Regression
M2	Decision Tree
M3	Random Forest
M4	Support Vector Machine (SVM)
M5	Naive Bayes
 Final Accuracy Results
Model	Sampling1	Sampling2	Sampling3	Sampling4	Sampling5
<img width="628" height="130" alt="image" src="https://github.com/user-attachments/assets/1c5dd344-31b9-4073-8dd7-52f0c539be2b" />

 Best Sampling Technique per Model
Model	Best Sampling Technique
M1	Sampling4
M2	Sampling2
M3	Sampling5
M4	Sampling1
M5	Sampling1
 Conclusion

No single sampling technique works best for all models.

Performance varies significantly based on the model and sampling strategy.

Proper handling of imbalance is crucial for reliable fraud detection.
