# Power-BI-Healthcare-Analytics

<img width="978" height="894" alt="Healthcare Analytics Pic" src="https://github.com/user-attachments/assets/d76485ce-7057-4147-b63e-fd67f045de55" />

An entire Power BI healthcare analytics solution for monitoring and evaluating patient data in various settings (day case, inpatient, and outpatient).


### 🚀 Interative Dashboard

https://app.powerbi.com/view?r=eyJrIjoiYzM2ZWRlZGYtOTU5MS00ZTk0LWFiZDQtZDQ1ZGZmMjE3OWNjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

A intensive end-to-end Power BI analysis of healthcare patient wait list management and hospital operations. This project transforms raw patient data into actionable insights about wait times, patient demographics, specialty performance, case type distribution, and operational efficiency trends.

### 📌 Project Synopsis

This healthcare analytics solution provides hospital administrators and healthcare managers with real-time visibility into patient wait lists across different care settings, enabling data-driven decisions to optimize patient flow and resource allocation.

###  🏥 Dataset & Data Model

<img width="1300" height="573" alt="Data Model" src="https://github.com/user-attachments/assets/3935034a-b4bd-48d5-bb5d-17e85d057439" />

####  Source Tables

- [x] Inpatient: Patients admitted to hospital for more than one day
- [x] Outpatient: Patients receiving medical treatment without hospital admission
- [x] Day Case: Patients admitted to hospital for one day
- [x] All_Data: Consolidated patient records

####  Dimension Tables

- [x] Calculated Method: Custom calculation methodologies
- [x] Key Measures: DAX measures for analytics
- [x] Mapping_Specialty: Medical specialty categorization


### ⚜️ Key Fields

- [x] Patient classification (Adult_Child, Age_Profile)
- [x] Temporal data (Archive_Date, Time_Bands)
- [x] Care attributes (Case_Type, Specialty_Name, Specialty_HIPE)
- [x] Reference data (Source_Name)


###  📊 Dashboard Features
####  Summary Page - Executive Overview

<img width="966" height="544" alt="Summary Page" src="https://github.com/user-attachments/assets/6027520d-e2e7-42dd-ba0b-23bab3db63b7" />

####  Total Wait List Metrics

- [x] Current Year: 709K patients
- [x] Previous Year: 640K patients
- [x] YoY Growth Analysis

####  Wait List Bifurcation by Case Type

- [x] Outpatient: 72.49% (80 patients)
- [x] Day Case: 16.89% (19 patients)
- [x] Inpatient: 10.62% (12 patients)
- [x] Overall Case Count: 54

#### Key Visualizations

#####  🔄 Monthly Trend Analysis: 3.5-year trend (Jul 2018 - Jan 2021) comparing Day Case/Inpatient vs Outpatient volumes
#####  📊 Wait List Analysis: Time Band vs Age Profile matrix with color-coded severity
##### 🏆 Top 5 Specialties by Wait List:
- [x] Otolaryngology (ENT) - 159
- [x] Paed Orthopaedic - 264
- [x] Paediatric Dermatology - 233
- [x] Paediatric ENT - 272
- [x] Paediatric Surgery - 163
