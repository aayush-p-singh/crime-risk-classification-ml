# Crime Risk Classification Using Machine Learning

This project analyzes crime data from Indian states and classifies risk levels using population-normalized features and machine learning models.

## Overview
The project integrates crime statistics from the NCRB with population data. By normalizing crime counts per population, the analysis provides a fair comparison of crime risks across states. The project builds machine learning models to classify states into different risk categories.

## Objectives
- Transform raw NCRB data into structured, ML-ready datasets.
- Normalize crime data by population to ensure fair comparisons.
- Implement multiple classification models (Random Forest, SVM, Logistic Regression).
- Evaluate model performance and compare results.

## Methodology
1. Data Extraction: Crime data from NCRB reports combined with census population data.
2. Feature Engineering: Derived features like crime per population and women-related crime percentage.
3. Exploratory Data Analysis (EDA): Correlation heatmaps to understand feature relationships.
4. Model Training: Random Forest, SVM, and Logistic Regression models implemented.
5. Evaluation: Accuracy, confusion matrix, and model comparison.

## Results
- **Random Forest**: ~77.8% accuracy
- **SVM**: ~77.8% accuracy
- **Logistic Regression**: ~66.7% accuracy

## Key Insights
- Population normalization ensures fair state-level comparisons.
- Ensemble models perform better than linear models.
- Some high-risk states are harder to predict, indicating potential for improvement in recall.

## Limitations
- Data limited to state-level historical reports.
- Socio-economic factors not yet integrated.
- No real-time data included.

## Future Work
- Integrate socio-economic indicators (e.g., education, unemployment).
- Experiment with advanced models like XGBoost.
- Build an interactive dashboard for public safety insights.

## Tech Stack
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Author
Aayush Pratap Singh  
IILM University, Greater Noida

## Status
This work has been submitted to the International Conference on Advances in Computer Engineering and Communication Systems (ICACECS 2026).
