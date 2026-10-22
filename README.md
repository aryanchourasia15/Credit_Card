\# Credit Card Fraud Detection System



\## Project Overview

This project focuses on building a machine learning model to identify fraudulent credit card transactions from high-volume financial data. Using imbalanced classification techniques, feature engineering, and model evaluation metrics (Recall, Precision, ROC-AUC), the model minimizes false negatives to detect fraud effectively while maintaining operational precision\[cite: 4].



\---



\## Key Technical Highlights

\* \*\*Imbalanced Data Handling:\*\* Applied techniques like SMOTE (Synthetic Minority Over-sampling Technique) to balance class distribution across 250,000+ transaction records\[cite: 4].

\* \*\*Model Evaluation \& Recall Optimization:\*\* Prioritized high Recall (92%) on the fraud class to capture malicious transactions without overwhelming manual review queues\[cite: 4].

\* \*\*Feature Engineering \& SQL Preprocessing:\*\* Cleaned, transformed, and queried raw transaction logs using SQL and Pandas to extract behavioral aggregation features\[cite: 4].



\---



\## Repository Structure

```text

├── data/                                 # Transaction log datasets

├── notebooks/                             # Jupyter notebooks for EDA and model development

├── src/                                   # Python scripts for data processing \& model training

└── README.md                              # Project documentation

