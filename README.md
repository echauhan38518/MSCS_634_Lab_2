Wine Classification Using K-Nearest Neighbors and Radius Neighbors

Objective of the Laboratory Exercise

This laboratory exercise investigates distance-based classification methods using the Wine dataset from scikit-learn.
Two classification models were implemented:

• K-Nearest Neighbors (KNN)
• Radius Neighbors (RNN)

The objective was to evaluate the impact of parameter selection, specifically k and radius, on model accuracy.
accuracy.

Key Findings

KNN Results:
Analysis indicated that moderate values of k produced stable and reliable classification performance.
In contrast, very small k values increased the risk of overfitting.

RNN Results:
Model performance was highly sensitive to the selection of the radius parameter.
Inappropriate radius values resulted in unstable predictions or reduced accuracy.

Comparison:
K-Nearest Neighbors produced more consistent results, whereas Radius Neighbors required more precise parameter tuning.

Challenges and Decisions

Feature scaling was essential to prevent features with large values from dominating the classification process.
Outlier handling was necessary for the Radius Neighbors model.
Multiple parameter values were tested to analyze performance trends.

Technologies Utilized

• Python
• Scikit-learn
• Matplotlib
• Pandas