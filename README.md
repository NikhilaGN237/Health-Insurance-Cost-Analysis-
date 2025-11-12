# Insurance Data Analysis

## Project Overview

This project focuses on analyzing a structured health insurance dataset using **Python** and **Tableau** to uncover key factors influencing medical insurance charges. The objective is to provide data-driven insights into how demographic and lifestyle variables affect premium amounts, enabling smarter pricing strategies and risk segmentation.

---

## Problem Statement

An insurance provider seeks to:

- Understand how age, BMI, gender, children, smoking habits, and region influence medical charges
- Identify high-risk customer groups based on lifestyle and demographic factors
- Use insights to inform premium adjustments and future predictive modeling

Dataset Used:  
**insurance.csv** – Contains individual policyholder data with 7 key attributes

---

## Technologies Used

- **Python**  
  Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`  
- **Jupyter Notebook** – For data cleaning and exploratory analysis  
- **Tableau** – For building interactive visual dashboards  
- **Git & GitHub** – For version control and project documentation

---

## Data Preprocessing

Steps performed during data preparation:

- Verified structure and data types of all columns
- Checked for missing values and duplicates
- Identified and separated categorical vs numerical features
- Conducted outlier detection and normalization for key variables

---

## Exploratory Data Analysis (EDA)

The dataset was explored to answer the following questions:

**Demographic Insights**
- What is the distribution by gender and region?
- How common is smoking among policyholders?
- How many children are typically covered?

**Cost & Risk Drivers**
- What is the effect of age, BMI, and smoking on charges?
- Do smokers consistently pay higher premiums?
- Does obesity (BMI > 30) impact insurance costs?

**Visual Techniques Used**
- Scatter plots for age and BMI versus charges
- Count plots for categorical distributions
- Correlation heatmaps to identify strong relationships

---

## Tableau Dashboard Overview

The Tableau dashboard was designed to present clear, interactive insights:

- **Charges vs Age** with smoker-based segmentation
- **BMI vs Charges** to assess obesity-related impact
- **Charges by Number of Children**
- **Demographic breakdowns** for gender, region, and smoking status
- **Filters** to explore data by category

(Note: Dashboard not published for public view)

---

## Key Findings

- **Smoking status** is the strongest predictor of higher insurance charges  
- **BMI** and **age** are positively correlated with premiums  
- **Non-smokers** consistently pay lower rates across all age groups  
- **Number of children** has minimal effect on medical cost  

---

## Author

**Nikhila Gayathri Nalabolu**  
Data Analyst  
[LinkedIn Profile](https://www.linkedin.com/in/nikhila-gayathri-n-a7a633188/)  
Email: nikhilagayathrin@gmail.com

---

## Repository Contents

- `insurance.csv` – Raw dataset  
- `Insurance.ipynb` – Python notebook with full data analysis  
- `InsuranceDataAnalysis.twb` – Tableau workbook  
- `Dashboard.png` – Static screenshot of final dashboard

---

## License

This project is open for learning and personal use. For any commercial or academic application, please contact the author.
