# ADHD-ASD-gender-bias--ML
Machine Learning project to investigate gender bias in ADHD and ASD diagnosis. Includes EDA, interpretable ML models, and fairness-focused evaluation using open healthcare datasets.


This project applies machine learning and fairness-aware evaluation to investigate gender bias in the diagnosis of Attention Deficit Hyperactivity Disorder (ADHD) and Autism Spectrum Disorder (ASD).

Research consistently shows that females are underdiagnosed or diagnosed later due to symptom presentation differences and male-centric diagnostic criteria. This project evaluates whether machine learning models can improve diagnostic equity and accuracy by incorporating demographic and behavioural features.

The work was completed as part of an MSc in Digital Business & Data Analytics at Henley Business School.

Key Skills Demonstrated:
Data Cleaning & Feature Engineering
Exploratory Data Analysis (EDA)
Supervised Machine Learning
Model Evaluation & Fairness Analysis
Healthcare & Ethical AI Applications
Python (pandas, scikit-learn, XGBoost)

📊Datasets Used: 
ASD Dataset: Autism Spectrum Quotient (AQ-10) survey data (Kaggle)
ADHD Dataset: ADHD-200 phenotypic dataset (Nolan Nichols)

Raw datasets are not included to comply with ethical and licensing constraints. Dataset sources are fully cited within the dissertation.

Machine Learning Models
The following models were trained and evaluated:
ASD
Logistic Regression
K-Nearest Neighbours
Support Vector Machine
Decision Tree
Random Forest
XGBoost

ADHD
Logistic Regression
Random Forest
Support Vector Machine
K-Nearest Neighbours
Gaussian Naive Bayes
Gradient Boosting

In addition to standard performance metrics, this project explicitly evaluates fairness across gender groups, recognising the ethical importance of unbiased healthcare decision-making.
Metrics Used
Accuracy: Overall correctness of predictions
Precision & Recall: To assess false positives and false negatives
F1-Score: Balance between precision and recall
ROC–AUC: Ability to distinguish between diagnostic classes

Fairness-Oriented Evaluation:
Group-wise performance comparison
Model performance was analysed separately for male and female participants to detect disparities in predictive behaviour.

Disparate Impact Awareness
Differences in recall and false negative rates across genders were examined to identify whether one group was systematically disadvantaged.

Interpretability-first approach
Models such as Logistic Regression and Random Forest were prioritised to allow transparent inspection of feature importance and decision logic.

Key Fairness Findings
ADHD models showed evidence of gender imbalance, reflecting known underdiagnosis of females. ASD models were more strongly influenced by age than gender in the selected dataset, highlighting the importance of dataset composition.
Random Forest models offered the best balance between accuracy and fairness, making them more suitable for healthcare contexts.

NOTE: This study does not claim to eliminate bias entirely.
Instead, it demonstrates how bias can be measured, monitored, and reduced through careful model selection and evaluation.
Models were evaluated using train–test splits, hyperparameter tuning, and robust performance metrics.
