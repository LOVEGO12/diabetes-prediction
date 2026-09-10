   # Diabetes Prediction from Medical Data

   Predicts diabetes likelihood using the Pima Indians Diabetes dataset.
   Compares Logistic Regression and Random Forest classifiers.

   ## Results
   | Model | Accuracy | Precision | Recall | F1 Score |
   |---|---|---|---|---|
   | Logistic Regression | 0.71 | 0.60 | 0.50 | 0.55 |
   | Random Forest (balanced) | 0.76 | 0.65 | 0.69 | 0.67 |

   Random Forest was tuned with `class_weight='balanced'` to improve recall 
   on the diabetic class, since missing true diabetic cases is costlier than 
   false alarms in a screening context.

   - Notebook: `Disease_Prediction_Diabetes.ipynb`
   - Dataset: `diabetes.csv`
