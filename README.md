# Heart-Disease-Analysis-Kaggle-

This study leverages machine learning techniques to develop predictive models for heart disease using epidemiological data from the CDC's Behavioral Risk Factor Surveillance System (BRFSS). The dataset encompasses 319,795 records across 169 variables related to demographics, lifestyle factors, and medical history. After pre-processing the raw data, two algorithms - Logistic Regression and Random Forest - are employed to construct classification models with the binary target variable of heart disease presence. The study maintains key assumptions underlying these methods regarding relationships, variable independence, model robustness, and feature relevance. Data analysis is conducted, including exploratory analysis and quadratic/interaction term generation, to capture potential non-linearities. The anticipated results exceed 90\% accuracy, with Random Forest likely outperforming Logistic Regression. By unraveling the risk profile of heart disease, this research aims to equip healthcare practitioners with personalized assessment tools to curb the incidence and burden of cardiovascular mortality. The methodology and large-scale real-world dataset offer insights for improving preventive strategies.

We trained Support Vector Machine, Logistic Regression, Random Forest, and XGBoost on the data. Our results are shown as follow:

1. **Table 1: Comparative Overview of Confusion Matrices for Various Classifier Models**

   ```markdown
   | Model               | TN    | FP  | FN   | TP  |
   |---------------------|-------|-----|------|-----|
   | SVM                 | 87649 | 0   | 8290 | 0   |
   | Logistic Regression | 86936 | 713 | 7515 | 775 |
   | Random Forest       | 87389 | 260 | 7927 | 363 |
   | XGBoost             | 87081 | 568 | 7610 | 680 |
   ```
   *Detailing True Negative (TN), False Positive (FP), False Negative (FN), and True Positive (TP) Counts*

2. **Table 2: Comparative Analysis of Classifier Performance Metrics**

   ```markdown
   | Metric     | SVM     | Logistic Reg. | RF     | XGBoost |
   |------------|---------|---------------|--------|---------|
   | Accuracy   | 0.9136  | 0.9142        | 0.9147 | 0.9148  |
   | Precision  | 0.0000  | 0.5208        | 0.5827 | 0.5449  |
   | Recall     | 0.0000  | 0.0935        | 0.0438 | 0.0820  |
   | Specificity | 1.0000 | 0.9919        | 0.9970 | 0.9935  |
   | F1 Score   | 0.0000  | 0.1585        | 0.0815 | 0.1426  |
   ```
   *'Logistic Reg.' denotes Logistic Regression and 'RF' refers to Random Forest.*
