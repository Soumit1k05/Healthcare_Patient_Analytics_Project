# Healthcare & Patient Analytics Project 🏥

## Project Overview
This project was developed as part of the Data Science Certification with Thiranex. The goal is to apply data science techniques to healthcare data to improve patient risk assessment and financial planning.

## 🚀 Project Structure

### 1. Data Cleaning & Visualization
- **Objective:** Handle missing values and duplicates in patient records.
- **Key Actions:** Imputed missing Age (Mean), Cholesterol (Median), and Blood Pressure (Mode).
- **Visuals:** Diagnosis distribution and Age histograms.

### 2. Predictive Modeling (Machine Learning)
- **Objective:** Predict high-risk patients based on cholesterol levels.
- **Algorithm:** Random Forest Classifier.
- **Evaluation:** Used a Confusion Matrix to validate prediction accuracy.

### 3. Exploratory Data Analysis (EDA)
- **Objective:** Identify patterns and correlations between health metrics.
- **Key Actions:** Correlation heatmaps and Boxplots to analyze cholesterol variance across different diagnosis groups.

### 4. Health Domain Project (Financial Analysis)
- **Objective:** Estimate the financial impact of patient treatments.
- **Metric:** Developed a cost formula based on age and cholesterol to calculate average treatment costs per diagnosis.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## 📈 Key Findings
- The Random Forest model successfully identified high-risk patients.
- Patients marked as "Critical" consistently show higher treatment costs, correlating with higher cholesterol levels.
