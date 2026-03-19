# Methodology

## Objective

The objective of this project was to build a healthcare performance dashboard in Power BI that provides both system-level and hospital-level insights using a patient dataset.

---

## Workflow

### 1. Data Loading
The healthcare dataset was imported into Power BI Desktop and reviewed in Data View and Model View.

### 2. Data Validation
Columns were checked for appropriate data types, including:

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
The dashboard was structured into two pages:

- Healthcare System Overview
- Hospital Performance Analysis

A consistent theme was applied using:

- light grey page background
- white card-style visual containers
- dark blue KPI values
- aligned slicer row
- grouped chart sections

### 5. Visual Selection
Visuals were chosen based on the business question being answered:

- KPI Cards → headline metrics
- Line Chart → admissions trend
- Bar / Column Charts → ranking and comparison
- Donut Chart → gender split
- Scatter Chart → performance comparison

### 6. Filtering Strategy
Dropdown slicers were added for:

- Medical Condition
- Gender
- Admission Type
- Doctor

These were placed consistently across the page to improve usability.

### 7. Performance Interpretation
The second page focused on hospital-level comparisons using:

- total revenue
- patient volume
- average LOS
- revenue per patient

This allowed the dashboard to move beyond descriptive reporting into comparative performance analysis.

---

## Design Principles

The report followed five main design principles:

1. Clarity  
2. Consistency  
3. Visual hierarchy  
4. Minimal clutter  
5. Analyst-oriented storytelling

---

## Limitations

This dataset appears to be synthetic or simulated, which means some distributions are more balanced than real hospital data. As a result:

- some categories may appear evenly distributed
- some averages may be closer together than in real-world systems
- insights should be interpreted as portfolio-style analysis rather than clinical decision support

---

## Outcome

The final output is a structured Power BI dashboard suitable for:

- portfolio presentation
- interview discussion
- demonstration of healthcare analytics capability
