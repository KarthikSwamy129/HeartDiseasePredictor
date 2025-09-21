A simple, end-to-end machine-learning project that tells you if a patient is likely to have heart disease based on 11 routine clinical measurements.

Inference:
- Trains a tuned XGBoost model on the classic UCI Heart-Disease dataset (303 patients)
- Achieves ≈ 94 % ROC-AUC and 88 % accuracy
- Explains predictions with SHAP
- Provides an interactive CLI—just run the script, answer the prompts, and get an instant risk score

| File | Purpose |
|------|---------|
|'Detect Heart Disease.pdf'| Descrption of parameters in the dataset |
| 'dataset.csv' | Raw data (age, sex, cholesterol, etc.) |
| 'HeartDisease.ipynb' | Full Colab workflow: EDA → cleaning → modelling → evaluation and prediction|
| 'HeartDiseaseModel.pkl' | Ready-to-use scikit-learn pipeline model(pre-processing + XGBoost) |


