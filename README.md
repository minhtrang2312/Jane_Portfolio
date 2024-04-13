# Jane_Portfolio
## Project: Predictive model for hospital readmissions

### Background
Hospital readmission for diabetic patients is a significant concern in the United States due to the increasing prevalence of diabetes and its associated complications. There's an urgent need for effective interventions and strategies to reduce hospital readmissions and improve the quality of care for diabetic patients in the U.S. healthcare system. Additionally, reducing readmission rates for diabetic patients has a great potential to reduce medical cost significantly.

This project aims to help a group of hospitals to better understand diabetic patient readmissions. The hospitals gave access to ten years of information on diabetic patients readmitted to the hospital after being discharged. The doctors want to assess if initial diagnoses, number of procedures, or other variables could help them better understand the probability of readmissions

#### Business questions: 
How to identify patients with high probability of readmission based on initial diagnoses, number of procedures, and other variables?

### Data questions:
Does diabetes play a central role in readmission?
On what groups of patients should the hospital focus their follow-up efforts to better monitor patients with a high probability of readmission?
Dataset Description
Collected from 130 hospitals in the U.S. during 10 years(1999-2008)
Contains 101,766 observations and 50 features
The following table shows a quick overview of the features' name, types, discription and percentage of missing values

### Proposed solution, evaluation metrics and current benchmark
We propose logistic regression, decision tree, and random forest models for predicting hospital readmission risk in diabetic patients using the Diabetes 130-US hospitals dataset.

Reasons for Model Selection:

-Logistic Regression: Widely used for binary classification tasks, interpretable, efficient, and provides probability estimates.
-Decision Tree: Captures complex relationships, interpretable, handles mixed data types.
-Random Forest: Combines multiple decision trees, robust, handles high-dimensional datasets and noisy data, provides feature importance measures.

Evaluation Metrics:Accuracy, Precision, Recall, AUC-ROC.

Benchmark: Common benchmarks for hospital readmission risk prediction include an accuracy of 70-80%, precision and recall of 60-70%, and an AUC-ROC score of 0.64 or higher (Lu & Uddin, 2022). These benchmarks guide the evaluation of model performance on the Diabetes 130-US hospitals dataset.
