# 📊 UK Data Job Market Analysis 2025

[![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi&style=flat-square)](https://powerbi.microsoft.com/) 
[![Python](https://img.shields.io/badge/Language-Python-blue?logo=python&style=flat-square)](https://www.python.org/) 
[![SQL](https://img.shields.io/badge/Database-SQL-lightgrey?logo=sqlite&style=flat-square)](https://www.sql.org/)

---

## 🚀 Project Summary

This project explores the **UK data job market (2025)** by analyzing over **6,300 job listings** extracted from **Reed.co.uk** during March 2025.  
Using a custom **Python pipeline** (Reed API + Selenium), combined with advanced **Power BI visualization**, the project identifies:

- The **most in-demand technical and analytical skills**
- **Job role trends** in Data Analytics & Data Science
- Salary patterns across roles, industries, and locations
- Emerging insights for **job seekers**, **educators**, and **employers**

---

## 🎯 Business Problem

With rapid growth in **data-centric roles**, there is an urgent need for actionable insights into the **UK data job market**:

- **Which skills are truly in demand?**
- **How do job roles evolve across the market?**
- **What are realistic salary expectations?**
- **How can job seekers better align their upskilling to market demand?**

This project addresses these questions through a **real-time, data-driven approach**.

---

## 🗂️ Data Collection & Processing

| Stage | Tools / Techniques |
|-------|--------------------|
| Data Extraction | Reed API + Selenium (Python) |
| Raw Data Volume | ~6,300 job listings (March 2025) |
| Data Fields | Job Title, Company, Location, Salary, Job Description, etc. |
| Skill Extraction | Keyword-based extraction (custom curated list) |
| Salary Standardization | Advanced normalization to annual salary for comparison |
| Location Cleaning | Standardized to major UK cities |

---

## 🛠️ Tools & Technologies

- **Python**: Pandas, Selenium, Requests, Matplotlib
- **Power BI**: Advanced dashboards, Network Analysis, Text Analysis
- **SQL**: Data querying & transformation
- **Excel**: Supporting analysis
- **Git**: Version control

---

## 🔍 Key Results

- Identified **top 15 most in-demand skills** for Data Analysts and Data Scientists in the UK
- Mapped **role–skill relationships** using Network Graphs
- Revealed **salary trends** by role and location
- Produced an interactive **Power BI Dashboard** for **real-time insights**

---

## 📊 Project Artifacts

### 🚀 Interactive Dashboard

| Artifact | Link / Location |
|----------|-----------------|
| Power BI Dashboard (.pbix) | [`/powerbi_dashboard/UK_Data_Job_Insights.pbix`](./powerbi_dashboard/UK_Data_Job_Insights.pbix) |
| Dashboard Screenshots | [`/powerbi_dashboard/dashboard_screenshots/`](./powerbi_dashboard/dashboard_screenshots/) |

### 📈 Notebooks

| Notebook | Purpose |
|----------|---------|
| `data_extraction.ipynb` | Job scraping: Reed API + Selenium |
| `data_cleaning.ipynb` | Cleaning + transformation |
| `skill_extraction.ipynb` | Skill extraction logic |
| `exploratory_analysis.ipynb` | EDA & Visualization |

---

## 🏆 How to Use

1️⃣ Clone the repository:  
```bash
git clone https://github.com/KiranCorreya93/UK-Data-Job-Insights-2025.git
