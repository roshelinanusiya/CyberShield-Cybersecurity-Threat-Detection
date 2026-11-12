# CyberShield – Cybersecurity Threat Detection and Analytics Using Databricks

## Project Overview
CyberShield is a cybersecurity data analysis and machine learning project developed using Databricks. It analyzes network traffic records and classifies them as Normal or Attack using a Random Forest algorithm.

## Dataset
- Dataset: UNSW-NB15
- Source: University of New South Wales
- Contains normal network traffic and different types of cyberattacks.

## Technologies Used
- Python
- Databricks
- PySpark
- Machine Learning
- Random Forest
- MLflow
- Power BI

## Project Architecture
The project follows Medallion Architecture:

1. **Bronze Layer:** Stores the original network traffic data.
2. **Silver Layer:** Cleans the data and checks duplicate records.
3. **Gold Layer:** Performs feature engineering and prepares data for machine learning.

## Machine Learning
- Algorithm: Random Forest Classifier
- Target column: `label`
- 0 = Normal
- 1 = Attack

## Workflow
1. Data ingestion
2. Data cleaning
3. Feature engineering
4. Machine learning classification
5. MLflow experiment tracking
6. Dashboard visualization

## Dashboard
The dashboard presents:
- Security overview
- Threat analysis
- Network activity
- Machine learning information

## Future Scope
- Real-time network traffic monitoring
- Automatic model retraining
- Suspicious activity alerts
- Improved model deployment

## Project Limitation
This project analyzes the UNSW-NB15 dataset. It is not a live network monitoring or automatic attack-blocking system.

## Author
M.Sc Data Science Student
