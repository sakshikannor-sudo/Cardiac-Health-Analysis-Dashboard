# ❤️ Cardiac Health Analysis Dashboard

**Made with Plotly | Created using Plotly Studio**

---
<img width="1867" height="642" alt="image" src="https://github.com/user-attachments/assets/9531ca51-6d11-428d-9bf8-ff2987fd8d14" />


## 📌 Project Overview

The **Cardiac Health Analysis Dashboard** provides a comprehensive visual and statistical exploration of cardiac health indicators and heart disease risk factors. The dashboard is built on a dataset of **1,025 patient records** and focuses on identifying relationships between physiological measurements, lifestyle-related variables, and the presence of heart disease.

This interactive dashboard enables users to explore trends, compare subgroups, and identify high-risk patients using dynamic filters and intuitive visualizations.

Link: https://232c62b9-e393-4fbf-9e15-c406b2861cd4.plotly.app/
---

## 📊 Dataset Summary

- **Total Patients:** 1,025  
- **Average Age:** 54.4 years  
- **Heart Disease Rate:** 51.3%  
- **Average Cholesterol:** 246 mg/dL  
- **Average Maximum Heart Rate:** 149 bpm  
- **Last Updated:** 2026-01-14 (UTC)

<img width="1901" height="592" alt="image" src="https://github.com/user-attachments/assets/cd1ac2f8-4744-4eb8-8933-a900a36ef062" />


### 🔑 Key Variables

- Age  
- Sex (0 = Female, 1 = Male)  
- Chest Pain Type (0–3)  
- Resting Blood Pressure  
- Cholesterol Level  
- Fasting Blood Sugar  
- Resting ECG Results  
- Maximum Heart Rate  
- Exercise-Induced Angina  
- ST Depression (Oldpeak)  
- Target (1 = Heart Disease Present)

---

## 🎛️ Interactive Filters

The dashboard includes global filters that dynamically update all visualizations:

- **Age Range**  
- **Sex**  
- **Chest Pain Type**  
- **Fasting Blood Sugar**

These filters allow users to drill down into specific patient subgroups and perform focused analysis.

---

## 📈 Visualizations & Descriptions

### 1️⃣ Heart Disease Prevalence by Age Group

**Chart Type:** Bar Chart  

**Description:**  
Displays the **percentage of patients with heart disease** across different age groups. Ages are grouped into fixed-width bins (default: 5-year intervals).

**Insights:**
- Heart disease prevalence generally increases with age  
- Middle-aged and elderly groups show higher risk  
- Supports early screening and preventive planning  

<img width="1855" height="905" alt="image" src="https://github.com/user-attachments/assets/5abe71df-689b-4069-a540-234690d6ccb6" />

---

### 2️⃣ Maximum Heart Rate by Sex Comparison

**Chart Type:** Grouped Bar Chart  

**Description:**  
Compares the **average maximum heart rate** across chest pain types, segmented by sex (Male vs Female).

**Insights:**
- Males generally exhibit higher maximum heart rates  
- Chest pain type influences cardiovascular response  
- Highlights sex-based physiological differences  

<img width="1843" height="952" alt="image" src="https://github.com/user-attachments/assets/47ed59d2-016f-470c-bc27-e8b75d9fbd83" />

---

### 3️⃣ High-Risk Cardiac Patients Table

**Chart Type:** Interactive Data Table  

**Description:**  
Displays patients diagnosed with heart disease (**target = 1**) sorted by **ST depression (oldpeak)**, a strong indicator of myocardial ischemia.

**Displayed Attributes:**
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Maximum Heart Rate  
- Exercise-Induced Angina  
- ST Depression  

**Insights:**
- Higher ST depression correlates with increased cardiac risk  
- Enables identification of patients requiring urgent attention  

<img width="1788" height="975" alt="image" src="https://github.com/user-attachments/assets/fea1d274-70a5-4c6c-974c-965343ca9d38" />

---

### 4️⃣ Heart Disease Prevalence by Sex and Chest Pain Type

**Chart Type:** Pivot Table with Conditional Formatting  

**Description:**  
Shows the **count of heart disease cases** segmented by sex and chest pain type.

**Insights:**
- Males show higher disease prevalence across all chest pain types  
- Chest pain types 0 and 2 are strongly associated with disease  
- Helps understand symptom-based risk distribution  

<img width="1841" height="522" alt="image" src="https://github.com/user-attachments/assets/f40e8a3e-1c2e-4b09-aee6-790a38c72048" />

---

### 5️⃣ Top Age Groups by Heart Disease Prevalence

**Chart Type:** Horizontal Bar Chart  

**Description:**  
Ranks the **top age groups** with the highest number of heart disease cases.

**Insights:**
- Identifies age groups with the highest disease burden  
- Useful for targeted healthcare interventions  

<img width="1841" height="690" alt="image" src="https://github.com/user-attachments/assets/615467da-2480-4912-a380-a23c682e5cfa" />

---

### 6️⃣ Resting Blood Pressure vs Resting ECG

**Chart Type:** Distribution / Box Plot  

**Description:**  
Visualizes the distribution of **resting blood pressure** across different resting ECG results.

**Insights:**
- Certain ECG abnormalities align with higher blood pressure  
- Helps correlate electrical heart activity with hypertension risk  

<img width="1846" height="952" alt="image" src="https://github.com/user-attachments/assets/11890d41-4fa7-4bf6-b269-64e0d828c206" />

---

## 🧠 Key Analytical Insights

- Age, chest pain type, and ST depression are strong predictors of heart disease  
- Male patients show higher prevalence across most risk categories  
- Elevated cholesterol and abnormal ECG patterns frequently co-occur with disease  
- Interactive filters support personalized and subgroup-specific analysis  

---

## 🛠️ Tools & Technologies

- **Plotly & Plotly Studio** – Interactive visual analytics  
- **Python** – Data preparation and analysis  
- **Dashboard-Driven Exploratory Data Analysis (EDA)**  

---

## 🎯 Use Cases

- Clinical decision support  
- Public health risk assessment  
- Healthcare analytics portfolios  
- Educational and academic demonstrations  

---

## 📌 Conclusion

The **Cardiac Health Analysis Dashboard** transforms complex medical data into actionable insights using interactive and visually rich analytics. It supports early risk detection, comparative analysis, and informed decision-making in cardiac healthcare.

---

📷 **Logo:** Plotly  
📊 **Data Source:** Cardiac Health Analysis Dashboard Dataset
