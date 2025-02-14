Enhancing Smart Grid Security: Anomaly and Novelty Detection for Electricity Theft
Project Overview
Electricity theft is a significant challenge for modern smart grids, leading to financial losses and grid instability. This project focuses on applying machine learning techniques for anomaly and novelty detection in electricity consumption data. By leveraging models such as XGBoost, LSTM, Random Forest, and Local Outlier Factor (LOF), the study explores methods to detect electricity theft while handling class imbalance, contextual anomalies, and previously unseen patterns.

Features & Contributions
Anomaly Detection:
Implemented XGBoost for theft detection, achieving 80% accuracy and 66% recall after threshold adjustments.
Developed an LSTM-based approach for capturing temporal dependencies in electricity consumption data, improving accuracy to 91%.
Novelty Detection:
Applied Random Forest and LOF models to detect unseen and rare consumption patterns, achieving 90% accuracy in identifying novel anomalies.
Used synthetic novelty injection to improve model robustness.
Performance Analysis:
Evaluated models based on precision, recall, F1-score, confusion matrices, and AUROC curves to balance detection accuracy and false positive rates.
Technologies Used
Machine Learning Models: XGBoost, LSTM, Random Forest, Local Outlier Factor (LOF), Isolation Forest
Libraries & Tools: Python, NumPy, Pandas, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn
Data Handling: Time-series preprocessing, class balancing with SMOTE, feature scaling with StandardScaler
