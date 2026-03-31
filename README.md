Credit Card Risk Analytics & Fraud Detection

Problem Statement:
Detect high-risk financial transactions in a highly imbalanced dataset.

Tools Used:
Python (Pandas, Scikit-learn)
Power BI
VS Code

Key Challenges:
Large dataset (19M+ rows)
Severe class imbalance (~1.6% risky transactions)

Proposed Solution:
Stratified sampling (1% subset)
SMOTE + class weighting
Behavioral feature engineering
Risk scoring model

Results:
Recall improved 4x
Built a risk scoring system
Identified key drivers:
Transaction frequency
Average spend behavior

Key Insights:
Behavioral patterns outperform time-based features
High-frequency users show distinct risk patterns
Multi-error transactions indicate high anomaly probability
