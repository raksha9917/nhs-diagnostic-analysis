# NHS Diagnostic Analysis — Missed Appointments & Capacity Utilisation (2020–2022)
Diagnostic analysis of NHS appointment data (2020–2022): trends, missed appointments, capacity utilisation, and sentiment analysis.

**Author:** Raksha Nama  
**Role:** Junior Data Analyst  
**Institution:** London School of Economics – Data Analytics Career Accelerator  
**Tools:** Python (Pandas, NumPy, Matplotlib, Seaborn, TextBlob), Power BI, Excel  
**Period Analysed:** January 2020 – June 2022 

---

## 🧩 Project Overview

This diagnostic analysis investigates NHS appointment data to identify patterns in **missed appointments (DNAs)**, assess **capacity utilisation**, and capture **public sentiment** towards healthcare services during the COVID-19 pandemic.

The goal was to uncover actionable insights to help the NHS improve operational efficiency, reduce DNA rates, and enhance resource allocation across service settings.

---

## 🎯 Objectives

1. Quantify the volume and trend of **missed appointments (DNAs)**.  
2. Examine **capacity utilisation** across NHS service types and time periods.  
3. Analyse how **appointment mode** (face-to-face, telephone, video) affected DNA rates.  
4. Evaluate **public sentiment** on NHS services using Twitter data.  
5. Recommend strategic interventions to reduce DNAs and improve patient outcomes.

---

## 🧠 Analytical Approach

| Phase | Description | Tools Used |
|:------|:-------------|:-----------|
| **1. Data Cleaning & Preparation** | Imported CSV data, formatted dates, removed duplicates, handled nulls, and standardised column types. | Python (Pandas, NumPy) |
| **2. Exploratory Data Analysis (EDA)** | Analysed time trends, regional differences, and service utilisation patterns. Visualised appointment volumes, DNA counts, and seasonal variations. | Matplotlib, Seaborn |
| **3. DNA Trend Analysis** | Explored relationship between appointment mode, booking lead time, and DNA rate. Calculated overall DNA percentage. | Pandas, Plotting Libraries |
| **4. Capacity Utilisation** | Evaluated service capacity relative to total appointments and benchmarked utilisation rates across periods. | Python, Power BI |
| **5. Sentiment Analysis** | Scraped and analysed NHS-related tweets. Classified text sentiment (positive/negative/neutral). | Tweepy, TextBlob, WordCloud |

---

## 📊 Key Findings

| Insight | Description |
|----------|--------------|
| **Overall DNA Rate** | 4.2% of all NHS appointments were missed between Jan 2020 – Jun 2022. |
| **GP Appointments** | Accounted for ~91.5% of all appointments. |
| **Mode Impact** | Telephone appointments had the lowest DNA rate. |
| **Capacity Utilisation** | Average utilisation ~75–80%, indicating sufficient staffing but regional disparities. |
| **Regional Hotspots** | Higher DNA rates observed in Greater Manchester region. |
| **Public Sentiment** | Shift from negative to positive sentiment during the pandemic recovery phase. |

---

## 💡 Recommendations

1. **Automate SMS/Email Reminders:** Nudge patients before appointments to reduce DNAs.  
2. **Encourage Hybrid Care Models:** Maintain flexible appointment types (phone/video).  
3. **Target Regional DNAs:** Use postcode-level insights to focus outreach.  
4. **Adopt Predictive Analytics:** Build models to forecast likely no-shows.  
5. **Monitor Public Sentiment:** Track online engagement to inform service strategy.

---

## ⚙️ Tools & Libraries

| Category | Libraries / Tools |
|-----------|-------------------|
| **Data Analysis** | Python, Pandas, NumPy |
| **Visualisation** | Matplotlib, Seaborn, Power BI |
| **Text Analysis** | , TextBlob, WordCloud |
| **Reporting** | Jupyter Notebook, PowerPoint, PDF |
| **Environment** | JupyterLab / VS Code |

---

## 🗂 Repository Contents
📁 Jupyter Notebook →  NHS Diagnostic Analysis Notebook
📁 Outputs →  NHS Diagnostic Analysis Technical Report and Presentation Slides
📄 README.md → This document
📄 requirements.txt → Python dependencies
📄 LICENSE → MIT License
