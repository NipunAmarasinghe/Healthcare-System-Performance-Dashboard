# Healthcare System Performance Dashboard

## Overview

This project presents a multi-page Power BI dashboard designed to analyse healthcare system performance using the **Health_Care Real-World Data: 55K Patients** dataset.

The dashboard focuses on operational, demographic, financial, and hospital-level performance insights. It was built to demonstrate practical healthcare analytics skills in Power BI, including KPI design, DAX measures, interactive filtering, and dashboard storytelling.

This project demonstrates an end-to-end analytics workflow, starting from dataset exploration and progressing to an interactive Power BI dashboard for business insights.

---

## Project Context

This project is based on the Kaggle dataset:

**Health_Care Real-World Data: 55K Patients**  
Source: `https://www.kaggle.com/datasets/prashantkumaryt/health-care-real-world-data-55k-patients`

The dataset contains **55,500 healthcare patient records** and is designed to simulate real-world hospital and healthcare system data. It is distributed as **1 CSV file**. This makes it suitable for exploratory analysis, SQL practice, and business intelligence reporting.

---

## Business Problem

Healthcare organisations generate large volumes of structured patient and operational data, but raw records alone do not support decision-making.

This project transforms healthcare data into an interactive Power BI dashboard that allows stakeholders to:

- monitor patient volumes
- compare hospital performance
- evaluate revenue concentration
- assess average length of stay
- identify high-value hospitals using revenue per patient
- explore patient demographics and medical condition patterns

The goal is to convert tabular healthcare data into a clear executive-style reporting tool.

---

## Dashboard Pages

### 1. Healthcare System Overview
This page provides a system-level view of healthcare activity, including:

- Total Patients
- Total Revenue
- Average Length of Stay
- Average Billing
- Patient admissions trend over time
- Patient volume by medical condition
- Gender distribution
- Average billing vs age by condition

### 2. Hospital Performance Analysis
This page focuses on comparing hospitals using:

- Top revenue-generating hospitals
- Hospitals by patient volume
- Hospital efficiency using average LOS
- High-value hospitals using revenue per patient
- Revenue vs LOS vs patient volume comparison

---

## Data Source

This project uses the following dataset:

**Health_Care Real-World Data: 55K Patients**  
Kaggle: `https://www.kaggle.com/datasets/prashantkumaryt/health-care-real-world-data-55k-patients`

According to the dataset page, it contains **55,500 healthcare patient records** designed to simulate real-world hospital and healthcare system data.

The dataset supports analysis of fields such as:

- patient demographics
- hospital admissions
- discharge details
- medical conditions
- billing amounts
- doctors and hospitals
- operational and financial metrics

---

## Tools Used

- Power BI
- DAX
- Power Query
- GitHub
- CSV dataset

---

## Key Measures

```DAX
Total Patients = COUNT('Healthcare_dataset'[Name])
