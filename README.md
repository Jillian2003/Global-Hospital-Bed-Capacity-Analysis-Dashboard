# Global Hospital Bed Capacity Analysis Dashboard
_A comprehensive pre-pandemic global analysis of healthcare bed capacity_

---

## Introduction

### **Objective**
Analyze global hospital bed distribution to assess healthcare infrastructure across countries and identify gaps in resource availability.

### **Dataset**
Utilizes a global healthcare capacity dataset, including hospital beds per country over time, categorized by type.

### Focus Areas

- Population vs. bed availability  
- Bed type trends  
- Temporal trends in healthcare resources  

---

## The Dataset and Key Metrics

### **Key Variables**
- `Country`
- `Population`
- `Year`
- `Bed Type` (e.g., ICU, General, Psychiatric, etc.)
- `Number of Beds`

### **Core KPIs Tracked**
- **Average Beds per 1,000 People (Global):** `1.780`
- **Total Countries Included:** `200`
- **Average Country Population:** `1.6 million`
- **Distinct Bed Types Tracked:** `5`

---

## 🧹 Data Acquisition and Cleaning

- Data sourced from a public [Kaggle dataset](#) and imported into **Excel** and **Tableau**
- Duplicates were checked by `Country-Year-Bed Type` combination
- Missing values in `Population` or `Bed Counts` were handled via:
  - External references for imputation
  - Exclusion in analysis when appropriate
- Data was cleaned and grouped to standardize bed type definitions and population metrics
  
<img width="970" height="251" alt="Screenshot 2025-07-15 182131" src="https://github.com/user-attachments/assets/58a4bc5c-1e84-463f-bacc-1464cb73b907" />

---

## 📈 Preliminary Analysis

- **Average Beds per 1,000 People:** `1.8`
- **Countries Analyzed:** `200`
- **Average Population per Country:** `1.62 million`
- **Distinct Bed Types:**
  - ICU
  - TOTAL
  - Psychiatric
  - ACUTE
  - OTHER (merged from: SPECIAL, CHRONIC DISEASE, CHILDREN, LONG TERM CARE, REHABILITATION, WOMEN, MILITARY)

> These figures reveal substantial variation in healthcare infrastructure, especially in low-income countries.

---

## 📉 Metrics Analyzed

### **1. Country-wise Population Overview**
- Largest Populations: India, USA, China, Mexico, Brazil
- Small-population countries (e.g., Iceland, Malta) still included but with limited infrastructure data
- Contextualizes healthcare needs vs. capacity

---

### **2. Top 10 Countries by Bed Count & Type**
- USA leads in hospital beds per capita
- Developed countries show higher ICU bed concentration
- Emerging economies often lack ICU and psychiatric facilities

---

### **3. Beds Tracked Over Time (Yearly Trend)**
- Steady global bed numbers from 2011–2017
- Sharp spike in 2018 followed by steep decline
- Varied national trends:
  - U.S. shows consistent increase
  - Jamaica exhibits stagnation
- Reflects healthcare policy and investment shifts

---

## 💡 Key Insights

### **Global Disparities in Healthcare Capacity**
- Some countries have 10+ beds/1,000 people; others have <1
- Psychiatric and "other" beds significantly underrepresented
- High-income nations consistently perform better across all metrics

### **Temporal Trends**
- Post-2011 stagnation/decline in many developed countries (possibly due to digital healthcare rise)
- Several middle-income countries are expanding infrastructure

---

## 📌 Recommendations

### **For Global Health Policy Makers**
- **Prioritize expansion** in low-resource countries, especially for ICU and psychiatric care
- **Invest in scalable infrastructure** to meet growing population needs
- **Benchmark and monitor** bed distribution annually
- **Promote data transparency** for global collaboration

### **For Researchers & NGOs**
- Use bed availability as a **proxy for healthcare readiness**
- Target aid based on **per capita bed access**, not just GDP or total population

---

## 📊 Dashboard

<img width="1454" height="988" alt="Screenshot 2025-07-15 181123" src="https://github.com/user-attachments/assets/b966898d-9dbf-4e87-b522-34e412ae89fc" />

<img width="1495" height="1014" alt="Screenshot 2025-07-15 181138" src="https://github.com/user-attachments/assets/e31f9885-90bf-43e1-98a7-e2451cb86d30" />

> 📍 **Explore the Dashboard**: https://public.tableau.com/app/profile/jillian.ireland/viz/GlobalHospitalBedCapacityAnalysisDashboard/Overview

The dashboard provides interactive views into bed availability by country, bed type, and over time — enabling evidence-based decisions and global comparisons.
