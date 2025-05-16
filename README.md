# ML-Exam_IoT_MultiClassPrediction

This project explores machine learning techniques for classifying cyberattacks in Internet of Things networks. Previous studies have for the most part either classified attacks into larger groups or used neural networks. However, this project seeks to answer how effectively lightweight machine learning models can classify 33 types of cyberattacks in IoT networks using a balanced version of the CIC-IoT2023 dataset. This project addresses a multiclass classification problem, which will be tackled using lightweight ensemble learning models. All in a transparent, fair and explainable fashion, following the concepts of Responsible AI. To address this, thorough data preprocessing, stratified sampling, SMOTE, and feature selection based on both multicollinearity (VIF) and feature importance was conducted. 

A Logistic Regression model was used as a baseline, with three tree-based models, Decision Tree, Random Forest, and XGBoost, tested. Hyper parameter tuning was carried out on these three test models with RandomizedSearchCV to optimize parameters. Among them, XGBoost achieved the best overall performance with a macro average F1-score of 0.71, despite persistent challenges with minority classes. The results show that, with careful tuning and preprocessing, lightweight models can offer strong performance in multiclass intrusion detection tasks on resource-constrained IoT systems—while adhering to principles of fairness, interpretability, and Responsible AI.

Github link: https://github.com/CarlVDFristam/ML-Exam_IoT_MultiClassPrediction

Keywords: Cyber security, Internet of things, Intrusion detection system, Random Forest, XGBoost, Attack type classification
