# Smart City Public Safety Analytics

## 📌 Project Overview

Smart City Public Safety Analytics is a Data Science and Machine Learning project designed to analyze emergency incidents in a smart city environment.

The project uses historical public safety incident data to understand emergency patterns, identify high-risk situations, analyze response times, and predict the emergency level of new incidents.

The project covers the complete Data Science workflow:

- Data Cleaning
- Data Visualization
- Exploratory Data Analysis (EDA)
- Predictive Modeling
- Real-World Public Safety Analytics
- Model Evaluation
- Risk Analysis
- Feature Importance
- Business Recommendations

This project was developed as part of a **Data Science Internship at Thiranex**.

---

## 🎯 Problem Statement

In a smart city, emergency incidents such as accidents, fires, medical emergencies, and security incidents can occur at different locations and times.

Emergency response teams need to understand:

- What types of incidents occur most frequently?
- Which areas have higher emergency risk?
- How do weather and crowd levels affect emergencies?
- How severe are incidents?
- How quickly do emergency services respond?
- Can the emergency level of an incident be predicted using Machine Learning?

This project analyzes these factors and builds a Machine Learning model to classify incidents into:

- Low
- Medium
- High

emergency levels.

---

## 🎯 Objectives

The main objectives of this project are:

1. Clean and preprocess smart city public safety data.
2. Identify and handle missing values and duplicate records.
3. Perform data visualization to understand emergency patterns.
4. Perform Exploratory Data Analysis (EDA).
5. Analyze relationships between incident characteristics and emergency levels.
6. Analyze emergency response times.
7. Build Machine Learning models for emergency-level prediction.
8. Evaluate model performance using classification metrics.
9. Identify important features affecting emergency levels.
10. Provide useful insights and recommendations for public safety management.

---

## 📊 Dataset

The dataset contains simulated smart city public safety incident records.

### Dataset Size

- Original records: **10,200**
- Records after cleaning: **9,800**
- Number of features: **15**

### Dataset Features

| Feature | Description |
|---|---|
| Incident_ID | Unique identifier for each incident |
| Incident_Type | Type of emergency incident |
| Area | Location/area where the incident occurred |
| Time_of_Day | Time period of the incident |
| Day_of_Week | Day on which the incident occurred |
| Weather | Weather condition during the incident |
| Crowd_Level | Crowd level in the incident area |
| CCTV_Available | Whether CCTV is available |
| Police_Response_Time | Police response time |
| Ambulance_Response_Time | Ambulance response time |
| Fire_Response_Time | Fire service response time |
| Number_of_People | Number of people involved |
| Severity_Score | Severity score of the incident |
| Previous_Incidents | Number of previous incidents |
| Emergency_Level | Target variable: Low, Medium, or High |

---

## 🧹 Task 1 – Data Cleaning & Visualization

The first stage of the project focuses on preparing the dataset for analysis and Machine Learning.

### Data Cleaning

The following data-cleaning operations were performed:

- Checked dataset shape and structure.
- Identified missing values.
- Removed duplicate records.
- Verified data types.
- Checked numerical features.
- Prepared a cleaned dataset for further analysis.

After cleaning:

- Rows: **9,800**
- Columns: **15**
- Missing values: **0**
- Duplicate records: **0**

### Visualizations

The following visualizations were created:

- Emergency Level Distribution
- Incident Type Distribution
- Incidents by Area
- Weather vs Emergency Level
- Crowd Level vs Emergency Level
- Correlation Heatmap

These visualizations help understand the overall structure and patterns in the public safety dataset.

---

## 🔎 Task 2 – Predictive Modeling Using Machine Learning

The second stage focuses on predicting the emergency level of an incident.

### Machine Learning Algorithms

The following classification algorithms were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### Data Preparation

Categorical features were converted into numerical values using Label Encoding.

The dataset was divided into:

- Training data: 80%
- Testing data: 20%

Feature scaling was performed using StandardScaler where required.

### Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

A Random Forest model was also used for feature importance analysis.

---

## 📈 Task 3 – Exploratory Data Analysis

The third stage performs detailed Exploratory Data Analysis to identify meaningful patterns in the public safety data.

### EDA Areas

The analysis includes:

- Emergency level distribution
- Incident type analysis
- Area-wise incident analysis
- Emergency level by incident type
- Emergency level by area
- Weather vs emergency level
- Crowd level vs emergency level
- Time of day vs emergency level
- Numerical feature distributions
- Severity score analysis
- Emergency response time analysis
- Correlation analysis
- Percentage-based emergency analysis

### Key EDA Questions

The analysis attempts to answer:

1. Which emergency level occurs most frequently?
2. Which incident types are associated with higher emergency levels?
3. Which areas experience more incidents?
4. Does crowd level influence emergency severity?
5. Does weather condition affect emergency patterns?
6. How does severity score vary across emergency levels?
7. How do response times differ between emergency levels?
8. Which numerical features are correlated?

---

## 🌆 Task 4 – Real-World Data Project

The fourth stage applies the complete Data Science workflow to a real-world public safety scenario.

The project demonstrates how public safety data can support emergency management and decision-making.

### Real-World Use Case

The system can assist public safety teams in:

- Identifying high-risk incidents
- Prioritizing emergency situations
- Understanding risky locations
- Monitoring incident patterns
- Analyzing emergency response performance
- Supporting emergency resource allocation
- Predicting emergency levels

### Risk Analysis

The project analyzes risk based on:

- Incident Type
- Area
- Severity Score
- Crowd Level
- Weather
- Time of Day
- Previous Incidents
- Emergency Response Time

### Feature Importance

Random Forest feature importance is used to identify which features contribute most to predicting emergency levels.

This helps understand the factors that have a stronger influence on emergency classification.

### Model Evaluation

The Task 4 Machine Learning workflow includes:

- Train/Test Split
- Random Forest Classification
- Accuracy
- Classification Report
- Confusion Matrix
- Feature Importance

---

## 📁 Project Structure

```text
SmartCity_PublicSafety_Project/
│
├── data/
│   ├── smart_city_public_safety_raw.csv
│   └── smart_city_thiranex_cleaned.csv
│
├── notebooks/
│   ├── visualization.ipynb
│   ├── ml.ipynb
│   ├── Task2_Predictive_Modeling.ipynb
│   ├── Task3_EDA.ipynb
│   ├── Task4_Real_World_Project.ipynb
│   └── smart_city_model.pkl
│
├── visualizations/
│   ├── task4_emergency_overview.png
│   ├── task4_incident_risk.png
│   ├── task4_area_risk.png
│   ├── task4_severity_analysis.png
│   ├── task4_response_time.png
│   ├── task4_crowd_risk.png
│   ├── task4_time_risk.png
│   ├── task4_feature_importance.png
│   └── task4_confusion_matrix.png
│
├── report/
│   ├── Task1_Data_Cleaning_Visualization_Report.pdf
│   ├── Task2_Predictive_Modeling.pdf
│   ├── Task3_EDA_Report.pdf
│   └── Task4_Real_World_Project_Report.pdf
│
└── README.md

🛠️ Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
Development Tools
Jupyter Notebook
VS Code
Git
GitHub

Key Insights

The project provides insights into:

Distribution of emergency levels.
Frequently occurring incident types.
Areas with higher numbers of incidents.
Relationship between incident type and emergency severity.
Relationship between crowd level and emergency level.
Relationship between weather and emergency situations.
Variation in severity scores.
Emergency response-time patterns.
Important features used by the prediction model.

🚨 Real-World Applications

This project can be extended for use in:
  Smart City Emergency Management
  Authorities can analyze incident patterns and prioritize emergency response.
  Police Response Planning
  Historical incident data can help identify areas requiring increased police presence.
  Ambulance Resource Planning
  Emergency patterns can support better ambulance allocation.
  Fire Emergency Management
  Fire-related incidents can be analyzed based on location, severity, crowd level, and response time.
  CCTV-Based Public Safety
  CCTV availability can be combined with incident data to support faster detection and response.
  Emergency Risk Prediction
  Machine Learning can help classify new incidents into Low, Medium, or High emergency levels.

🔮 Future Enhancements

The project can be further improved by adding:
  Real-time emergency data
  Live CCTV integration
  Real-time GPS tracking
  Real-time traffic information
  Real-time weather APIs
  Interactive dashboards
  Deep Learning models
  Natural Language Processing
  Generative AI
  Agentic AI
  Automated emergency alerts
  Emergency route optimization
  Mobile application
  Real-time prediction system

⚠️ Limitations
  The current dataset is simulated/historical data.
  Real-time emergency data is not connected.
  CCTV feeds are not directly integrated.
  External weather and traffic APIs are not connected.
  The Machine Learning model is trained on the available dataset.
  Model performance may change when applied to real-world data.
  Real-world deployment would require continuous monitoring and validation.

📌 Project Outcome

This project demonstrates an end-to-end Data Science workflow for a Smart City Public Safety use case.

It combines:
  Data Cleaning → Visualization → EDA → Machine Learning → Model Evaluation → Risk Analysis → Real-World Insights
  The project demonstrates how Data Science and Machine Learning can support public safety decision-making by analyzing emergency patterns and predicting emergency levels.
