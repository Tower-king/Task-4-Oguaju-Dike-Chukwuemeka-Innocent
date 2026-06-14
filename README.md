🏥 Healthcare Dashboard — Power BI Project

📋 Project Overview
This project presents an interactive Power BI dashboard built on a cleaned healthcare dataset.
The dashboard visualises key clinical and operational metrics — including patient demographics, billing trends, diagnosis distribution, and test result outcomes
— to support data-driven decision-making in a healthcare setting.

📁 Files

File
dashboard powerBI.pbix - PowerBi Dashboard

healthcare_dataset_cleaned.xlsx - Cleaned source dataset used for the dashboard

📊 Dashboard Overview

Title: HEALTHCARE DASHBOARD

Pages: 1

📈 Visualisations

1. No. of Admissions per Condition (Treemap)
   
Displays the volume of admissions broken down by medical condition. 
Conditions visible:

Arthritis
Diabetes
Hypertension
Obesity
Cancer
Asthma

Arthritis, Diabetes, and Hypertension dominate admissions — consistent with the chronic disease burden in the dataset.

2. Average of Billing Amount by Age (Line Chart)
   
Tracks how average billing amount varies across patient age groups (20–80+).

Billing peaks in younger age groups and fluctuates across the age spectrum, with a notable drop in older patients — possibly reflecting insurance coverage differences.

3. Admissions per Gender (Donut Chart)
   
Breaks down total admissions by gender with percentage labels:

Male
~9.28K
16.72%
Female
~9.47K
17.06%
Male
~9.11K
16.41%
Female
~9.37K
16.89%

Near-equal gender distribution confirms balanced patient demographics.

4. Test Results Findings (Bar Chart)
   
Counts of patients by test result category:

Test Result
Approximate Count
Abnormal
~18K
Normal
~18K
Inconclusive
~18K

Results are near-evenly distributed across all three categories — approximately 1 in 3 patients received abnormal results.

🔢 Key Metrics (KPI Cards)

Total Patients
55.50K

Average Age
51.54 years

Average Billing Amount
$25.54K

💡 Key Findings

Balanced patient demographics — near-equal male and female admissions across all groups

Obesity has the highest billing average (~$25.8K) — suggesting high resource utilisation and cost burden for obesity-related care

Arthritis, Diabetes, and Hypertension are the most common conditions — all chronic, preventable diseases

1 in 3 patients received abnormal test results — highlighting significant undetected or undertreated disease in the population

🎯 Insights & Recommendations

Preventive interventions targeting obesity are vital to reducing healthcare expenditure — it carries the highest average billing cost

Increased investment in chronic disease management programs for Arthritis, Diabetes, and Hypertension could reduce ER admissions and associated costs

The 1 in 3 abnormal test result rate calls for improved early diagnostic screening to catch conditions before they escalate to acute presentations

The even gender split suggests interventions should not be gender-targeted — a population-wide approach is appropriate

🩺 Clinical Context
As a medical officer, clinical expertise informed both the dashboard design and insight interpretation:

Recognising Obesity as a driver of high billing aligns with its role as a risk factor for Diabetes, Hypertension, and Heart Disease — all also present in the top diagnoses

The abnormal test result distribution is clinically significant — 1 in 3 is higher than expected in a healthy population and warrants investigation

Average age of 51.54 years places the patient population in the high-risk bracket for chronic non-communicable diseases

🔧 Tools Used

Microsoft Power BI — data modelling, DAX measures, interactive dashboard design

Microsoft Excel — source data preparation and cleaning

Part of the DecodeLabs Data Analytics Internship Portfolio
