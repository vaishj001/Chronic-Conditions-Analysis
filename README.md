# 📊 Chronic Health Conditions Analysis & Prediction

## 📌 Project Overview
Chronic diseases such as **diabetes, cardiovascular conditions, and mental health disorders** pose significant public health and economic challenges. Healthcare providers, insurers, and policymakers need **data-driven strategies** to allocate resources, design intervention programs, and reduce long-term costs. 

This project builds a **decision-support framework** to identify **high-risk populations**, segment communities based on health risks, and predict disease prevalence. By integrating **predictive modeling, clustering, and geospatial analysis**, this project enables stakeholders to shift from **reactive healthcare spending to proactive risk mitigation**.

---

## 🎯 Objectives & Approach
This analysis delivers insights that drive healthcare strategy and resource allocation:

- **Predicting Chronic Disease Prevalence** → Machine learning models to forecast **high-risk populations**.
- **Segmentation & Risk Profiling** → Clustering techniques to categorize **population health risks**.
- **Regional Health Disparity Analysis** → Interactive **Tableau dashboards** to highlight **geographic gaps in healthcare**.
- **Benchmarking & Trend Comparisons** → Evaluating regional prevalence **against national standards**.

---

## 🔬 Data & Methodology

### **Dataset Overview**
- **Source:** [CDC's PLACES Dataset] (https://data.cdc.gov/d/swc5-untb)
- **Size:** 200,000+ records from **2021-2022**.
- **Key Features:** Demographics, medical history, chronic condition indicators, socioeconomic factors.

### **Methods & Technologies**
| Task | Tools & Methods |
|------|----------------|
| **Data Processing & Cleaning** | **Python (Pandas, NumPy)** |
| **Exploratory Data Analysis** | **Matplotlib, Seaborn** |
| **Predictive Modeling** | **Decision Trees, Random Forests** |
| **Segmentation & Clustering** | **KMeans, Hierarchical Clustering** |
| **Visualization & Insights** | **Tableau Dashboards (Heatmaps, Bar Charts, Geographic Trends)** |

---

## 📈 Key Insights & Findings

### **Predictive Modeling & Risk Identification**
- **Certain states exhibit prevalence rates exceeding national benchmarks by over 76.6%**, requiring targeted interventions.
- **Key risk factors include BMI, hypertension, smoking, and limited healthcare access**.
- **Random Forest model achieved 82% accuracy**, with **age, BMI, and healthcare access** as primary predictors.

### **Population Segmentation & Health Profiling**
- **Four major health risk clusters emerged**:
  - **Cluster 1 (42.09%)** → High-risk individuals with multiple chronic conditions.
  - **Cluster 2 & 3** → Mid-risk groups with mixed socioeconomic determinants.
  - **Cluster 4** → Low-risk populations benefiting from access to healthcare.
- **Cluster-based insights** support targeted policy design for public health agencies.

### **Geospatial Trends & Healthcare Accessibility Gaps**
- **Heatmaps reveal underutilization of preventive healthcare in certain regions**.
- **Regional deviation analysis highlights conditions with unexpected prevalence spikes**.
- **Population density vs. condition prevalence analysis** indicates **rural vs. urban disparities in healthcare access**.

---

## 📊 Data Visualization & Insights

### **Chronic Condition Risk Clusters**
- Identifies **vulnerable populations**, assisting **hospitals and policymakers in proactive resource allocation**.

### **Regional Prevalence & Benchmarking**
- Compares **chronic condition rates to national standards**, informing **public health investments**.

### **Geospatial Chronic Disease Mapping**
- Provides an **interactive tool for healthcare providers** to **optimize intervention strategies**.

### **Population Risk vs. Health Outcomes**
- Examines **the relationship between demographics, economic conditions, and chronic disease impact**.

🔗 **[Tableau Dashboard Link](https://public.tableau.com/views/chronic-condition-analysis/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 🚀 Applications & Future Enhancements
- **Healthcare Providers** → Use segmentation insights to **prioritize preventive care programs**.
- **Insurance Companies** → Apply risk stratification models to **refine premium structures**.
- **Public Health Agencies** → Allocate funding and resources **based on high-risk clusters**.

### Next Steps
- **Economic Impact Analysis** → Quantifying the financial burden of chronic conditions.
- **Real-Time Risk Monitoring** → Deploying **a live dashboard using Streamlit**.
- **Enhancing Predictive Models** → Incorporating **social determinants of health (SDOH)** to refine forecasts.

---

## 📂 Repository Structure
```
├── data/  # Processed datasets
├── notebooks/  # Jupyter Notebooks for modeling
├── tableau/  # Tableau Workbook & Dashboards
├── README.md  # Project Overview (this file)
```

---

## 🔧 Usage Instructions
1. Clone the repository: `git clone https://github.com/yourusernamevaishj001/Chronic-Conditions-Analysis.git`
2. Open the **Tableau workbook** to explore insights.
3. Run **Python script** for detailed data analysis.

---
