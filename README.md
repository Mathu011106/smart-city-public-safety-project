# Smart City Public Safety – Data Cleaning & Visualization

## Project Overview

This project focuses on analyzing public safety incidents in a smart city environment using Python. The dataset contains information about incidents, locations, emergency levels, weather conditions, crowd levels, severity scores, and police response time.

The main objective of this project is to clean the raw dataset, handle data quality issues, perform exploratory analysis, and create meaningful visualizations to identify patterns and trends in public safety incidents.

## Objectives

- Clean and preprocess the raw public safety dataset.
- Identify and handle missing values.
- Detect and remove duplicate records.
- Analyze numerical data and identify potential outliers.
- Explore relationships between different variables.
- Create meaningful visualizations.
- Extract useful insights from the dataset.

## Dataset

The dataset contains **10,200 records and 15 columns** related to smart city public safety incidents.

Important attributes include:

- Incident Type
- Area
- Emergency Level
- Weather
- Crowd Level
- Severity Score
- Police Response Time
- Other incident-related attributes

### Data Quality Issues

The raw dataset contained missing values and duplicate records.

- Missing values were identified in relevant columns.
- Missing categorical values were handled using the mode.
- Missing numerical values were handled using the median.
- Duplicate records were identified and removed.
- Numerical variables were analyzed for potential outliers.

## Data Cleaning Process

The following steps were performed:

1. Loaded the raw dataset using Pandas.
2. Inspected the dataset structure and data types.
3. Checked for missing values.
4. Handled missing values using appropriate methods.
5. Identified and removed duplicate records.
6. Performed numerical data analysis.
7. Checked for potential outliers using boxplots.
8. Saved the cleaned dataset for further analysis.

## Data Visualization

The following visualizations were created:

- Emergency Level Distribution
- Incident Type Distribution
- Incidents by Area
- Weather vs Emergency Level
- Crowd Level vs Emergency Level
- Correlation Heatmap

These visualizations help understand the distribution of incidents and relationships between important public safety factors.

## Key Findings

The analysis helps identify:

- Distribution of different emergency levels.
- Common types of public safety incidents.
- Areas with higher numbers of incidents.
- Relationship between weather conditions and emergency levels.
- Relationship between crowd levels and emergency situations.
- Correlations between numerical variables.

These insights can support better understanding of public safety patterns and help in making data-driven decisions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
SmartCity_PublicSafety_Project/
│
├── data/
│   ├── smart_city_public_safety_raw.csv
│   └── smart_city_thiranex_cleaned.csv
│
├── notebooks/
│   └── visualization.ipynb
│
├── visualizations/
│   ├── correlation_heatmap.png
│   ├── crowd_vs_emergency.png
│   ├── emergency_level_distribution.png
│   ├── incident_type_distribution.png
│   ├── incidents_by_area.png
│   └── weather_vs_emergency.png
│
├── report/
│   └── Task1_Data_Cleaning_Visualization_Report.pdf
│
└── README.md

# Conclusion

This project demonstrates the complete data cleaning and visualization workflow for a smart city public safety dataset. The cleaned data and visualizations provide useful insights into incident patterns, emergency levels, and factors that may influence public safety.

The project was developed as part of a Data Science Internship task at Thiranex.

# Author
Mathumitha P.

Data Science Intern
Thiranex