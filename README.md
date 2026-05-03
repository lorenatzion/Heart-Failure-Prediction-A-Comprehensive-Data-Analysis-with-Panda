# Heart Failure Prediction: Comprehensive Data Analysis with Pandas 🩺

## Project Description
This repository contains an Exploratory Data Analysis (EDA) of the "Heart Failure Prediction Dataset." The goal is to analyze clinical features and identify significant patterns that distinguish healthy individuals from those with heart disease.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Seaborn, Matplotlib, NumPy.

---

## Visual Analysis & Key Insights

### 1. Patient Status Distribution
![Patient status distribution](visuals/Patient%20status%20distribution.png)
This chart shows a nearly balanced dataset, with 52.28% of patients diagnosed with heart disease and 47.72% remaining healthy.

### 2. Age Distribution
![Age distribution](visuals/Age%20distribution.png)
The histogram reveals that heart disease cases tend to increase and concentrate in patients aged between 50 and 65 years.

### 3. Chest Pain Type Analysis
![Chest Paintype](visuals/Chest%20Paintype.png)
Asymptomatic (ASY) chest pain is identified as the most critical symptom, showing a significantly higher frequency of heart disease compared to other pain types.

### 4. Cholesterol Trends
![Cholesterol trends](visuals/Cholesterol%20trends.png)
Average cholesterol levels fluctuate by age, with women showing sharper increases in specific age groups compared to the more stable trend in men.

### 5. Correlation Matrix
![Correlation matrix](visuals/Correlation%20matrix.png)
The heatmap indicates that **'Oldpeak'** (ST depression induced by exercise relative to rest) has the strongest positive correlation with heart disease, while **'MaxHR'** shows a negative relationship with the condition.

---

## Dataset Structure
The dataset includes 918 observations with 12 clinical features such as:
- Age, Sex, ChestPainType, RestingBP, Cholesterol, MaxHR, and HeartDisease (Target).
