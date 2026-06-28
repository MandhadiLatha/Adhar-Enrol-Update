### UIDAI Data Hackathon 2026 | Data Analytics • Machine Learning • Business Intelligence

## Project Overview

This project was developed as part of the **UIDAI Data Hackathon 2026**, which challenges participants to identify meaningful societal trends from Aadhaar enrolment and update data. The solution combines data analytics, statistical techniques, machine learning, and interactive dashboards to uncover demographic patterns, regional disparities, operational anomalies, and predictive indicators that support informed decision-making.

## Problem Statement

**Unlocking Societal Trends in Aadhaar Enrolment and Updates**

The objective is to:

* Identify meaningful patterns and demographic trends
* Detect operational anomalies
* Segment states based on Aadhaar service utilization
* Develop predictive indicators for future service demand
* Translate analytical findings into actionable policy recommendations

## Business Objectives

* Analyze Aadhaar enrolment behavior across India.
* Understand demographic trends by age group.
* Examine update activity across states and districts.
* Detect abnormal enrolment/update patterns.
* Segment states with similar operational characteristics.
* Develop indicators supporting resource planning.
* Build an executive dashboard for decision-makers.

## Dataset

The project uses two UIDAI datasets.
- Aadhaar Enrolment Dataset
Date
State
District
Pincode
Age 0–5
Age 5–17
Age 18+

- Aadhaar Update Dataset
Date
State
District
Pincode
Update Age 5–17
Update Age 18+

- Derived Features


## Project Workflow

```text
Raw Datasets
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Trend Analysis
      │
      ▼
Anomaly Detection
      │
      ▼
State Segmentation
      │
      ▼
Predictive Indicators
      │
      ▼
Tableau Executive Dashboard
```

## Data Cleaning

The datasets were cleaned using a reusable preprocessing pipeline.Activities included:

* Date conversion
* Missing value treatment
* Duplicate removal
* Data type correction
* Feature engineering
* Ratio calculations
* Month extraction

## Feature Engineering

| Feature                | Purpose                          |
| ---------------------- | -------------------------------- |
| Total Enrolments       | Total enrolments per record      |
| Total Updates          | Total update transactions        |
| Child Ratio            | Percentage of child enrolments   |
| Youth Ratio            | Percentage of youth enrolments   |
| Adult Ratio            | Percentage of adult enrolments   |
| Update Rate            | Updates relative to enrolments   |
| Update Burden          | Operational workload indicator   |
| Child Dependency Ratio | Future biometric update demand   |
| Aadhaar Demand Index   | Overall service demand indicator |


## Exploratory Data Analysis

The analysis focused on:
* Monthly enrolment trends
* Monthly update trends
* State-wise analysis
* District hotspots
* Age-wise distribution
* Geographic distribution


## Anomaly Detection

IQR Method - Used to detect statistical outliers in operational metrics.
Isolation Forest - Used for multivariate anomaly detection.

**Anomalous States
* Conduct operational reviews.
* Investigate unusual service demand.
* Improve monitoring mechanisms.

## State Segmentation using K-Means

| Cluster   | Business Name                    |
| --------- | -------------------------------- |
| Cluster 0 | Update-Dominant States           |
| Cluster 1 | Balanced Aadhaar Activity States |
| Cluster 2 | High Aadhaar Demand States       |


## Predictive Indicators

Several business indicators were developed.

# Update Rate - Measures update demand relative to enrolments.

Supports:
* Infrastructure planning
* Service capacity assessment

# Child Dependency Ratio - Estimates future biometric update requirements.

Supports:
* Long-term planning
* Resource forecasting

# Update Burden - Measures maintenance workload.

Supports:
* Workforce allocation
* Update centre planning

## Tableau Dashboards

# Executive Summary
* KPIs
* Monthly trends
* Age distribution
* Cluster overview


# State-wise Analysis

* Geographic distribution
* State rankings
* Demand analysis
* Cluster profiles


# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Isolation Forest
* K-Means Clustering
* Tableau
* Jupyter Notebook

# Key Outcomes

* Developed an end-to-end analytics solution for UIDAI operational data.
* Identified demographic and regional service trends.
* Detected operational anomalies using statistical and machine learning methods.
* Segmented states into actionable operational categories.
* Designed predictive indicators supporting strategic planning.
* Delivered an executive Tableau dashboard for data-driven decision-making.
