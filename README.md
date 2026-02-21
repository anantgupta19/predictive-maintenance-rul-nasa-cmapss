# Predictive Maintenance using Machine Learning on NASA CMAPSS Dataset

## Overview

This project implements a machine learning–based predictive maintenance system to estimate the **Remaining Useful Life (RUL)** of turbofan engines using the NASA CMAPSS dataset. The objective is to predict equipment failure before it occurs, enabling proactive maintenance and reducing downtime, operational cost, and risk.

This project focuses on:

* Predictive Maintenance using Machine Learning
* Remaining Useful Life (RUL) Prediction
* Feature Engineering for performance improvement
* Comparative analysis of regression models

This work was presented at the **CFRTM 2025 Conference at IIT Bhubaneswar**, highlighting its research significance and real-world applicability.

---

## Conference Presentation

This project was presented at:

**CFRTM 2025**
Centre for Future Research in Technology and Management
**Indian Institute of Technology (IIT) Bhubaneswar**

The presentation covered:

* Problem statement and industrial relevance
* NASA CMAPSS dataset analysis
* Feature engineering techniques
* Machine learning model comparison
* Performance evaluation and results
* Real-world predictive maintenance applications

This conference presentation validated the research quality and practical impact of this work.

---

## Problem Statement

Industrial systems such as aircraft engines experience gradual degradation over time. Traditional maintenance approaches include:

* Reactive Maintenance (after failure)
* Preventive Maintenance (scheduled maintenance)

Both approaches are inefficient and costly.

Predictive Maintenance uses machine learning to:

* Monitor system condition
* Predict future failures
* Optimize maintenance timing

This project predicts Remaining Useful Life (RUL) using sensor data.

---

## Dataset

Dataset used: **NASA CMAPSS (Commercial Modular Aero-Propulsion System Simulation)**

Contains:

* Multiple engine units
* Sensor readings over operational cycles
* Engine degradation simulation
* Failure progression data

Dataset includes:

* Engine ID
* Cycle number
* Operational settings
* 21 sensor measurements

---

## Methodology

### Step 1: Data Preprocessing

* Load dataset
* Assign column names
* Calculate Remaining Useful Life (RUL)
* Merge datasets
* Clean and prepare features

---

### Step 2: Feature Engineering

Feature engineering techniques applied:

* Rolling mean
* Rolling standard deviation
* Trend-based features
* Statistical aggregation
* Degradation pattern extraction

Feature engineering significantly improved model performance.

---

### Step 3: Machine Learning Models

Models used:

### Linear Regression

* Baseline model
* Simple and interpretable
* Used for comparison

### Random Forest Regression

* Ensemble learning method
* Handles nonlinear relationships
* Provides better prediction accuracy

---

### Step 4: Model Evaluation

Evaluation metrics:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Prediction vs Actual visualization

Random Forest performed better due to ability to model nonlinear degradation patterns.

---

## Results

Key outcomes:

* Feature engineering improved prediction performance
* Random Forest outperformed Linear Regression
* Accurate RUL prediction achieved
* Clear degradation patterns identified

This demonstrates the effectiveness of machine learning in predictive maintenance applications.

---

## Project Structure

```
predictive-maintenance-rul-nasa-cmapss/

│
├── data/
│   ├── train_FD001.txt
│   ├── test_FD001.txt
│   ├── RUL_FD001.txt
│
├── notebooks/
│   └── Feature_eng_research_paper.ipynb
│
├── results/
│   ├── plots/
│   └── model_outputs/
│
├── README.md
├── requirements.txt
└── presentation/
    └── CFRTM_IIT_Bhubaneswar_2025_Presentation.pdf
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Applications

This system can be applied in:

* Aviation Industry
* Manufacturing
* Automotive Industry
* Power Plants
* Industrial IoT Systems

---

## Key Contributions

* Implemented complete predictive maintenance pipeline
* Applied feature engineering to improve performance
* Compared multiple ML models
* Generated degradation and prediction visualizations
* Presented research at IIT Bhubaneswar

---

## Future Improvements

Possible extensions:

* Deep Learning models (LSTM, GRU)
* Real-time prediction using IoT data
* Deployment using Flask or FastAPI
* Integration with industrial monitoring systems

---

## Author

Ad
Mechanical Engineering, ZHCET AMU
BS Data Science, IIT Madras

Research Interests:

* Machine Learning
* Predictive Maintenance
* AI in Healthcare
* Industrial AI Systems

---

## License

This project is open-source and available under the MIT License.
