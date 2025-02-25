# 📊 Chronic Health Conditions Analysis & Prediction

## 📌 Project Overview
Chronic diseases such as **diabetes, cardiovascular conditions, and mental health disorders** pose significant public health and economic challenges. Healthcare providers, insurers, and policymakers need **data-driven strategies** to allocate resources, design intervention programs, and reduce long-term costs. 

This project builds a **decision-support framework** to identify **high-risk populations**, segment communities based on health risks, and predict disease prevalence. By performing **classification, predictive modeling, and clustering**, this project enables stakeholders to shift from **reactive healthcare spending to proactive risk mitigation**.

---

## 🎯 Objectives & Approach
This analysis delivers insights that drive healthcare strategy and resource allocation:

- **Predicting Chronic Disease Prevalence** → Machine learning models to forecast **high-risk populations**.
- **Segmentation & Risk Profiling** → Clustering techniques to categorize **population health risks**.
- **Regional Health Disparity Analysis** → Interactive **Tableau dashboards** to highlight **geographic gaps in healthcare**.
- **Benchmarking & Trend Comparisons** → Evaluating regional prevalence **against national standards** in **Tableau**.

---

## 🔬 Data & Methodology

### **Dataset Overview**
- **Source:** [CDC's PLACES Dataset](https://data.cdc.gov/d/swc5-untb)
- **Size:** 200,000+ records from **2021-2022**.
- **Key Features:** Demographics, medical history, chronic condition indicators, socioeconomic factors.

### **Methods & Technologies**
| Task | Tools & Methods |
|------|----------------|
| **Data Processing & Cleaning** | **Python (Pandas, NumPy)** |
| **Exploratory Data Analysis** | **Matplotlib, Seaborn** |
| **Classification & Predictive Modeling** | **Logistic Regression, Random Forests, XGBoost** |
| **Segmentation & Clustering** | **KMeans** |
| **Visualization & Insights** | **Tableau Dashboards (Heatmaps, Bar Charts, Geographic Trends)** |

---

## 📈 Key Insights & Findings

### **1️⃣ Predictive Modeling & Risk Identification**
- Certain states exhibit **chronic disease prevalence rates exceeding national benchmarks by over 76.6%**, indicating **urgent need for targeted interventions**.  
- **Key risk factors identified** include **total population, socio-economic factors, and healthcare access disparities**.  
- **XGBoost improved model accuracy** to **97.6% R²**, compared to Random Forest Model with **93.63% R²**, with **population size, condition prevalence, and state-level healthcare indicators** as the primary predictors.  

### **2️⃣ Population Segmentation & Health Profiling**
- The dataset was segmented into **four major health risk clusters**, derived from **population size and chronic disease prevalence**:  
  - **Cluster 1 (41.7%)** → **High-risk populations** with multiple chronic conditions.  
  - **Cluster 2 & 3** → **Moderate-risk groups** influenced by socioeconomic factors.  
  - **Cluster 4 (Low-risk)** → Populations benefiting from **better healthcare access & lower prevalence rates**.  
- **Clustering insights aid public health planning**, supporting **resource allocation and preventive care strategies**.

### **3️⃣ Trends & Visualizations**
- **State-level heatmaps reveal healthcare disparities**, particularly in **rural vs. urban populations**.  
- **Regional deviation analysis** identified **unexpected spikes** in chronic conditions, **suggesting potential underreporting or localized health crises**.  
- **Analysis of population density vs. prevalence** highlights **healthcare access gaps**, where high-density areas may not equate to adequate medical support.

---

## 📊 Data Visualization & Insights

#### **1. Chronic Condition Risk Clusters**
- Identifies **vulnerable populations**, assisting **hospitals and policymakers in proactive resource allocation**.

#### **2. Regional Prevalence & Benchmarking**
- Compares **chronic condition rates to national standards**, informing **public health investments**.

#### **3. Geospatial Chronic Disease Mapping**
- Provides an **interactive tool for healthcare providers** to **optimize intervention strategies**.

#### **4. Population Risk vs. Health Outcomes**
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
├── .ipynb/  # Jupyter Notebooks for modeling
├── README.md  # Project Overview (this file)
```

---

## 🔧 Usage Instructions
1. Clone the repository: `git clone https://github.com/vaishj001/Chronic-Conditions-Analysis.git`
2. Open the **Tableau workbook** to explore insights.
3. Run **Python script** for detailed data analysis.
