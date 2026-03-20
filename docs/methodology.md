# Methodology

## Objective

The objective of this project was to build a healthcare performance dashboard in Power BI using the **Health_Care Real-World Data: 55K Patients** dataset.

The aim was to convert patient-level healthcare data into a dashboard that supports system-level and hospital-level performance analysis.

---

## Dataset

Source dataset:

**Health_Care Real-World Data: 55K Patients**  
Kaggle: `https://www.kaggle.com/datasets/prashantkumaryt/health-care-real-world-data-55k-patients`

The dataset page states that it contains **55,500 healthcare patient records** in **1 CSV file**.

---

## Workflow

### 1. Data Loading
The dataset was imported into Power BI Desktop from CSV format.

### 2. Data Validation
Columns were reviewed for correct data types, including:

- Date of Admission → Date
- Discharge Date → Date
- Age → Whole Number
- Billing Amount → Decimal / Currency
- Length_of_Stay → Whole Number

### 3. Measure Creation
Core business measures were created using DAX:

- Total Patients
- Total Revenue
- Average LOS
- Average Billing
- Revenue per Patient

### 4. Dashboard Design
The report was structured into two pages:

- Healthcare System Overview
- Hospital Performance Analysis

### 5. Visual Selection
Visual types were selected according to the question being answered:

- KPI Cards → headline metrics
- Line Chart → admissions trend
- Bar / Column Charts → hospital and condition comparisons
- Donut Chart → gender split
- Scatter Chart → performance comparison

### 6. Filtering Strategy
Dropdown slicers were added for:

- Medical Condition
- Gender
- Admission Type
- Doctor

### 7. Interpretation
Hospital-level performance was analysed using:

- total revenue
- patient volume
- average LOS
- revenue per patient

---

## Design Principles

The report followed five main design principles:

1. clarity
2. consistency
3. visual hierarchy
4. minimal clutter
5. analyst-oriented storytelling

---

## Limitation

The dataset is intended for analysis practice and simulation of healthcare reporting scenarios, so findings should be treated as portfolio-style analytical outputs rather than real clinical conclusions.

---

## Outcome

The final output is a structured Power BI dashboard suitable for:

- analytics portfolio presentation
- interview discussion
- demonstration of healthcare BI capability
