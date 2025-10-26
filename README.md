Description: heart_data.csv contains patient clinical and demographic data aimed at predicting cardiovascular disease. The dataset includes age (converted from days to years), gender, height, weight, blood pressure, cholesterol, glucose, lifestyle factors, and a calculated BMI.

Key Features:

	•	age (in years), gender, height, weight
  
	•	ap_hi, ap_lo, cholesterol, gluc
  
	•	smoke, alco, active, BMI (calculated), cardio (target)
  
Project Highlights:

	•	Dropped unnecessary columns (index, id) and normalized numeric data.
  
	•	Train-test split with StandardScaler applied to numeric features.
  
	•	Classification models: SVM, KNN, Decision Tree, Random Forest.
  
	•	Comprehensive evaluation: Accuracy, Precision, Recall, F1-score, ROC-AUC.
  
	•	Visualization: Confusion matrices, ROC curves, feature importance plots.
  
	•	Interactive Gradio interface for real-time CVD prediction based on patient inputs.
