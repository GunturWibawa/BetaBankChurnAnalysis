# BetaBankChurnAnalysis

Churn Analysis in Beta Bank

The project assigned to me during the eighth sprint involves Supervised Learning.

Throughout this sprint, I engaged in the refinement of machine learning models, the development of evaluative metrics, and the manipulation of imbalanced data sets.

# **Project Insight**

Beta Bank is grappling with the gradual attrition of customers on a monthly basis. Such as, the employees have expressed a desire to prioritize the retention of their steadfast client. As a Data Scientist, it became my responsibility to architect a predictive model to ensure the likelihood of a customer severing ties with the bank in the imminent future. This determination would be based on an analysis of historical behavioral patterns and previous contract termination records. The designed model was mandated to achieve an F1 score exceeding 0.59 and to be evaluated using the AUC-ROC metric.

Upon a deep analysis and construction of the model, I am able to provide the following summary of the project:

This initiative culminated in the creation of a imperfect Machine Learning model that equalized positive and negative data through the employment of three distinct techniques: class_weight, upsampling, and downsampling. Through a series of experimental trials, I see that the class_weight method has the most favorable outcomes. Furthermore, I ensure that the RandomForest model achieved the most highest F1 score, with DecisionTree trailing closely, while the LogisticRegression model languished at the bottom in terms of F1 scoring.
