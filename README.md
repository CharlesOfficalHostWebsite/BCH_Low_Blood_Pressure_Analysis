<h1 align="center">Boston Children Hospital (BCH) Blood Pressure Analysis Project</h1>

## 📌 Introduction
During pediatric surgeries, every moment is critical. Monitoring patient vital signs, especially **blood pressure**, can mean the difference between life and death. This project analyzes blood pressure data to identify cases where **systolic BP dropped below safe thresholds for at least 14 minutes**, helping medical teams assess and mitigate risks.


## ⚠️ Problem Statement
Boston Children's Hospital (BCH) medical team  face a complex challenge:

- They had two separate datasets: patient demographics and minute-by-minute blood pressure readings
  
- identifying prolonged periods of low blood pressure across different pediatric age groups (as different age groups have different blood pressure thresholds), using data from multiple sources.
  
- They needed to find continuous periods of low blood pressure lasting 14 minutes or more

## 🎯 Objective
Our project aimed to:
- Develop an automated system to detect low blood pressure events
- Create age-specific thresholds for identifying critical BP drops lasting for  14+ minutes or more
- Generate actionable insights for medical professionals
- Generate a **report listing affected patients and duration of low BP events**.
- Provide **insights through visualizations** to help doctors analyze trends.
  
## 📌 Why This Project?
- **Increased focus on patient safety** in surgeries.
- **Large datasets make it difficult to track prolonged low BP cases manually**.
- **Improving real-time monitoring systems** can help prevent serious complications.

## 🛠️ Data & Methodology
1. **Data Collection** – Extracted patient demographics and blood pressure readings.
2. **Data Cleaning** – Removed errors, missing values, and inconsistencies.
3. Developed a Python-powered ETL (Extract, Transform, Load) solution that:
4. Reads patient demographic and blood pressure data
5. Dynamically calculates age-specific blood pressure thresholds
6. **Analysis** – Identified low BP events lasting **14+ consecutive minutes**.
7. **Visualization** – Created **bar charts and timelines** to analyze trends.
8. **Reporting** – Generated a **final report and PowerPoint presentation**.

## 📊 Key Results & Visual Insights
From our analysis, we discovered:
- 5 unique patients with prolonged low blood pressure events
- Periods ranging from 14 to 24 continuous minutes of low BP
- Potential critical moments that might have gone unnoticed without this analysis
- Patient 456: Youngest patient (39 months), 20 minutes of low BP
- Patient 987: Longest low BP period of 24 minutes
- Multiple patients across different ages showed concerning BP patterns
