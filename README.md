# Anomaly-Detection
This project focuses on detecting anomalies in digital meter data for MidAmerican Energy, aiming to improve response times and operational efficiency. The analysis includes data cleaning, exploratory data analysis (EDA), statistical analysis, and anomaly detection using various methodologies.


Key Features
Data Cleaning & Preprocessing: Handling missing values and preparing data for analysis.
Exploratory Data Analysis (EDA): Identifying trends, patterns, and anomalies in digital meter readings.
Statistical Analysis: Applying statistical tests to understand data distributions.
Anomaly Detection Methods:
Rolling Statistics: Identifies anomalies using a rolling window-based approach (Mean ± 2 × Std. Dev.).
Machine Learning-Based Anomaly Detection: Implements models such as Isolation Forest, DBSCAN, or Autoencoders to detect anomalies.
Threshold-Based Detection: Flags extreme values based on predefined operational thresholds.
Outcome
Anomalies Identified: 105,054 instances detected as anomalies.
Insights Derived: Helps optimize anomaly detection models for real-time monitoring and faster response.
Business Impact: Supports MidAmerican Energy in reducing operational disruptions and improving predictive maintenance strategies.
Technology Stack
Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
Jupyter Notebook for analysis and visualization

