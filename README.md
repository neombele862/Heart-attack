
# Mortality Data Analysis Project 🧬📊

## Overview

This project analyzes mortality data to uncover trends, patterns, and actionable insights. By leveraging exploratory data analysis (EDA), advanced visualizations, and machine learning techniques, the study investigates how deaths are distributed across causes, regions, age groups, and time.

The goal is to provide critical insights to guide public health strategies, resource allocation, and policy decisions.

---

## Key Objectives

1. **Trend Analysis**: Examine temporal trends in mortality rates and identify seasonal or event-driven variations.
2. **Regional Insights**: Highlight disparities in death rates across counties and age groups.
3. **Cause Analysis**: Identify leading causes of death and their contributions to overall mortality.
4. **Machine Learning**: Predict or classify mortality outcomes using regression, clustering, and natural language processing (NLP).

---

## Methodology

### 1. Data Preparation
- Replaced suppressed or missing death counts with zero for consistency.
- Standardized date formats and handled invalid entries.
- Cleaned and normalized data for EDA and machine learning tasks.

### 2. Exploratory Data Analysis (EDA)
- **Temporal Trends**: Visualized monthly death rates from January 2023 to September 2024, identifying significant spikes and troughs.
- **Cause Analysis**: Ranked top causes of death (e.g., heart disease, cancer) to understand their prevalence.
- **Regional and Demographic Patterns**:
  - Heatmaps to explore age-group-specific mortality by region.
  - Bar charts highlighting high-mortality counties.

### 3. Machine Learning Models
- **Regression Analysis**:
  - Predicted death counts using year, month, and age group as features.
  - Evaluated model performance with Mean Squared Error (MSE) and R² metrics.
- **NLP Classification**:
  - Classified causes of death as high or low mortality using TF-IDF and Random Forest models.
  - Addressed class imbalance to improve minority class predictions.

---

## Results

### Key Findings:
- **Top Causes of Death**: Diseases of the heart and malignant neoplasms (cancer) are the leading contributors to mortality.
- **Regional Disparities**: Urban areas like Los Angeles County exhibit significantly higher death counts.
- **Age Trends**: Older age groups (85+ years) account for the majority of deaths, while younger age groups have much lower rates.
- **Seasonality**: Death spikes during winter months suggest seasonal factors like influenza may play a role.

### Visual Highlights:
- Line charts for temporal trends in overall and cause-specific deaths.
- Heatmaps for mortality distribution by age group and region.
- Bar charts for top causes of death and high-mortality counties.

---

## Tools and Technologies

| Tool/Library      | Purpose                                   |
|-------------------|-------------------------------------------|
| **Python**        | Core programming language                |
| **Pandas**        | Data cleaning and manipulation           |
| **Matplotlib/Seaborn** | Visualization of mortality trends       |
| **GeoPandas**     | Geospatial analysis                      |
| **Scikit-learn**  | Machine learning models                  |
| **TF-IDF**        | Text vectorization for NLP classification|

---

## Challenges and Solutions

1. **Imbalanced Data**: Addressed class imbalance in the NLP model using median-based thresholds and weighting techniques.
2. **Data Suppression**: Filled suppressed death counts with zero and handled missing values to maintain analytical consistency.
3. **Model Accuracy**: Expanded feature engineering for better regression performance, though results indicate scope for additional variables.

---

## Future Work

- Incorporate socioeconomic and environmental factors for a more comprehensive analysis.
- Utilize real-time mortality data for dynamic model updates.
- Develop dashboards for interactive visualization and public health communication.

---

## Contact

For inquiries or collaboration, please reach out to **Neo Mbele** at **neombele862@gmail.com**.
