
# Healthcare System Performance Dashboard

## Overview

This project presents a Power BI dashboard designed to analyse healthcare system performance using a real-world style patient dataset. The dashboard focuses on operational, demographic, financial, and hospital-level performance insights.

The report is structured to help stakeholders answer practical questions such as:

- How many patients are being handled across the system?
- What is the total revenue generated?
- What is the average length of stay?
- Which hospitals generate the most revenue?
- Which hospitals handle the highest patient volume?
- Which hospitals generate the highest revenue per patient?
- Are higher-revenue hospitals also less efficient or more efficient?

This project was built as a portfolio piece to demonstrate healthcare analytics, dashboard design, DAX, data modelling, and storytelling in Power BI.

---

## Dashboard Pages

### 1. Healthcare System Overview
This page provides a high-level view of the healthcare system, including:

- Total Patients
- Total Revenue
- Average Length of Stay
- Average Billing
- Patient admissions trend over time
- Patient volume by medical condition
- Gender distribution of patients
- Average billing vs age by condition

### 2. Hospital Performance Analysis
This page compares hospital-level performance using:

- Top revenue-generating hospitals
- Hospitals by patient volume
- Hospital efficiency using average LOS
- High-value hospitals using revenue per patient
- Revenue vs LOS vs patient volume comparison

---

## Business Problem

Healthcare organisations generate large volumes of operational and patient data, but raw data alone does not support effective decision-making. Leadership teams need clear, interactive reporting to identify:

- performance differences between hospitals
- bottlenecks in patient flow
- revenue concentration
- high-value facilities
- variations in efficiency and length of stay

This dashboard transforms raw healthcare data into an executive-style reporting tool that supports performance monitoring and strategic analysis.

---

## Data Source

This project uses a healthcare patient dataset sourced from Kaggle and imported into Power BI. The data includes fields such as:

- Name
- Age
- Gender
- Blood Type
- Medical Condition
- Date of Admission
- Discharge Date
- Admission Type
- Doctor
- Hospital
- Insurance Provider
- Billing Amount
- Room Number
- Medication
- Test Results
- Length_of_Stay

---

## Tools Used

- Power BI
- DAX
- Power Query
- GitHub
- CSV / tabular healthcare dataset

---

## Key Measures

The report uses the following main DAX measures:

```DAX
Total Patients = COUNT('Healthcare_dataset'[Name])

Total Revenue = SUM('Healthcare_dataset'[Billing Amount])

Average LOS = AVERAGE('Healthcare_dataset'[Length_of_Stay])

Average Billing = AVERAGE('Healthcare_dataset'[Billing Amount])

Revenue per Patient =
DIVIDE([Total Revenue], [Total Patients])

Key Insights

Revenue is concentrated among a small group of hospitals rather than evenly distributed across the system.

Hospitals with higher revenue do not always have higher average length of stay, suggesting performance differences across facilities.

Patient volume and financial value do not always move together, meaning high-volume hospitals are not automatically the highest-value hospitals.

Revenue per patient provides a more meaningful comparison than total revenue alone when assessing hospital value.

Length of stay is more useful when viewed as an average by hospital rather than a total.
