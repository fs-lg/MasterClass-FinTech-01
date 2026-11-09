🤖 Task 3: Modeling & Explainability

A) Model Implementation and Comparison

[ ] 3.1 Building a Baseline Model

Implement a simple, interpretable Decision Tree model, controlling its depth to prevent overfitting.

[ ] 3.2 Building an Advanced (Challenger) Model

Implement ensemble learning models (such as Random Forest or XGBoost).

[ ] 3.3 Hyperparameter Tuning

Optimize key parameters using cross-validation.

[ ] 🎯 Expected Outputs (Part A):

A table comparing model performance on the test dataset, including ROC-AUC and PR-AUC metrics (accounting for the imbalanced nature of the target class).

A confusion matrix for the final model based on a specific cut-off threshold, accompanied by an analysis of the trade-off between False Positives and False Negatives.

B) Explainable AI (XAI)

[ ] 3.4 Global Explanation (Required)

Extract and visualize SHAP values ​​using beeswarm and bar plots to identify features with the most significant positive and negative impacts on the model's decisions.

[ ] 3.5 Local Explanation (Required)

Analyze the model's behavior for at least two specific instances (e.g., an approved low-risk customer and a rejected high-risk customer) using SHAP waterfall or force plots.

[ ] 3.6 LIME Comparison (Optional)

Compare the output of LIME’s local approximation with the SHAP results for a specific case.