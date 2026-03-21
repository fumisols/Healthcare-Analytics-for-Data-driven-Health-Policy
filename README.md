# Healthcare-Analytics-for-Data-driven-Health-Policy
The project's aim was to analyze &amp; visualize healthcare data to get insights that could support the government in making informed health policies for citizens.  The solution focused on transforming raw data into a clear, interactive dashboard that highlights trends in patient demographics, disease patterns, hospital performance, and healthcare use.

**Project Overview**

This project presents an interactive Healthcare Analytics Dashboard built using Power BI to analyze patient records across hospitals, doctors, and healthcare services.

The dashboard enables the stakeholders to:
Understand patient distribution and demographics
Identify high-burden medical conditions
Monitor hospital and doctor performance
Track admission trends over time
Evaluate billing and healthcare costs

**Problem Statement**

Healthcare data exists across multiple variables such as patients, hospitals, doctors, and treatments. However, decision-makers often lack a centralized system to answer key policy questions such as:
What are the most common health conditions affecting citizens?
Which hospitals and doctors are handling the highest patient load?
How do admissions change over time?
What demographic groups require more healthcare attention?
How does healthcare cost vary across patients and services?

Without proper visualization, it becomes difficult to identify trends, allocate resources efficiently, and design effective health policies, this project solves this problem.

**Dataset Description**
The dataset contained patient-level healthcare records with the following key fields:
Demographics: Name, Age, Gender, Blood Type
Medical Information: Medical Condition, Medication, Test Results
Hospital Data: Hospital, Doctor, Room Number
Admission Details: Admission Type, Date of Admission, Discharge Date
Financial Data: Billing Amount, Insurance Provider

**Methodology**
1. Data Cleaning
I removed inconsistencies and duplicates, standardized categorical values (e.g., gender, admission type), ensured correct data types (dates, numerical fields), handled missing or invalid records and verified billing and date accuracy

2. Data Transformation
I created calculated fields to calculate the Length of Stay = Discharge Date – Admission Date, categorised the Age Groups (Gen Z, Millennials, Gen X, Boomers) and Aggregated metrics for reporting Total patients, Total billing, Average billing and Patient distribution metrics

3. Data Modeling
I structured the dataset into key analytical dimensions to help enable flexible filtering and cross-analysis:
Patient Dimension: Gender, Age Group, Blood Type
Medical Dimension: Medical Conditions
Provider Dimension: Doctors and Hospitals
Financial Dimension: Billing Amount, Insurance Providers
Time Dimension: Admission Year

4. Dashboard Development
The dashboard was developed using Power BI with:
KPI Cards for key metrics
Bar Charts for comparisons (Doctors, Hospitals, Age Groups)
Pie/Donut Charts for distributions
Line Charts for trends
Slicers for interactive filtering

The design prioritizes clarity, usability, and insight discovery.

**Key Performance Indicators (KPIs)**
Total Patients
Total Billing Amount
Total Doctors
Average Billing Amount
Average Length of Stay
Top 5 Doctors by Patient Volume
Top 5 Hospitals by Patient Volume
Patients by Gender
Patients by Age Group
Patients by Blood Type
Patients by Medical Condition
Patients by Admission Type
Patients by Insurance Provider
Yearly Admission Trend

**Key Insights**
1. Patient Demographics
Gender distribution is nearly balanced as we have almost as many males as females.
Majority of patients fall within Gen X and Millennials, indicating high healthcare demand in working-age populations

2. Disease Burden
There was a high prevalence of Hypertension, Diabetes, and Cancer which suggests increasing burden of chronic, non-communicable diseases

3. Admission Patterns
We had a mix of Emergency, Urgent, and Elective admissions which indicates both reactive and planned healthcare usage

4. Hospital & Doctor Utilization
A small number of hospitals and doctors handle the highest patient volumes and this highlights resource concentration and potential overload

5. Financial Insights
High total billing indicates significant healthcare cost burden and Insurance providers play a key role in access to care

6. Trend Analysis
Admission trends fluctuated over time, showing changes in healthcare demand

**Impact**

This dashboard provides a data-driven foundation for policy and decision-making, enabling stakeholders to identify priority health issues, allocate healthcare resources effectively, improve hospital and workforce planning, monitor healthcare trends over time and support evidence-based health policy development.

**Recommendations**
1. Prioritize Chronic Disease Management: The Government should invest in preventive healthcare programs, early diagnosis initiatives and public awareness campaigns.

2. Improve Healthcare Resource Allocation by deploying more doctors and infrastructure to high-demand hospitals to balance workload across facilities.

3. Strengthen Preventive Healthcare by promoting routine health screenings, encourage healthier lifestyles and reduce long-term healthcare costs to reduce the rate of hypertension and obesity.

4. Enhance Data-Driven Policy Making: Use dashboards for continuous monitoring and integrate real-time healthcare data systems

5. Optimize Insurance Coverage: Improve access to affordable healthcare by strengthening the partnerships with insurance providers

**Tools Used**
Power BI – Data Visualization & Dashboarding
Microsoft Excel – Data Cleaning & Preparation
Data Modeling & Transformation
Data Analysis, Storytelling & Insights Communication
