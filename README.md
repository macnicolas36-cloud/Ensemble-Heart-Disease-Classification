Heart Disease Classification
Predicts heart disease presence from clinical data using the Cleveland UCI dataset (303 samples, 14 features).
Data
Place heart-disease.csv in the project directory. No missing values. Binary target: 1 = disease, 0 = no disease.
Requirements
pip install scikit-learn pandas numpy matplotlib seaborn
Models compared

Logistic Regression (~88.5% accuracy)
Random Forest (~86.9%)
KNN (~72.1%)

Usage
Run all cells top to bottom:

EDA — distributions, correlations, class balance
Modeling — 80/20 train/test split, model comparison
Hyperparameter tuning (in progress)
Evaluation

Notes

ConvergenceWarning on Logistic Regression is expected — increase max_iter to suppress
