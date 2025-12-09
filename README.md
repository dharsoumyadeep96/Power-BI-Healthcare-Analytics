# Power-BI-Healthcare-Analytics (Patient Wait List Analysis)

<img width="978" height="894" alt="Healthcare Analytics Pic" src="https://github.com/user-attachments/assets/d76485ce-7057-4147-b63e-fd67f045de55" />

An entire Power BI healthcare analytics solution for monitoring and evaluating patient data in various settings (day case, inpatient, and outpatient).


### 🎥 Video Presentation

https://youtu.be/_dhMRm-NsTM?si=5LA3xPYmAjLURbxu


### 🚀 Interactive Dashboard

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

#### Home Page

![Home Page](https://github.com/user-attachments/assets/da31260d-2acb-479e-a4ce-0b12f7a6a675)


####  Summary Page - Executive Overview

![Summary](https://github.com/user-attachments/assets/34ce28a8-c2a5-4804-ad98-fe8d47afa8bf)


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

#### Key Indicators

##### Average & Median Patient Wait List metrics
##### Toggle between statistical views

#### Detailed View - Drill-Down Analysis

![Detailed View](https://github.com/user-attachments/assets/07321eb2-046d-4339-ada5-809b3b85ed82)

#### Interactive Filters Panel

- [x] 📅 Archive_Date: Date range slider (1/31/2018 - 3/31/2021)
- [x] 🏷️ Case_Type: Multi-select dropdown
- [x] 🏥 Specialty_Name: Comprehensive specialty filter
- [x] 👥 Age_Profile: Age group segmentation
- [x] ⏱️ Time_Bands: Wait time categorization

#### Hierarchical Data Grid

- [x]   Multi-level expansion: Archive_Date → Specialty → Age Profile → Time Bands
- [x]  Real-time aggregations across dimensions

#### Example breakdown for Anaesthetics specialty:
- [x] Age 0-15: 18 patients across various time bands
- [x] Age 16-64: 1,458 patients with detailed time segmentation
- [x] Age 65+: 473 patients

#### Column totals: Day Case, Inpatient, Outpatient, Grand Total

#### Sample Data Insights

##### Wednesday, January 31, 2018: 582,686 total patients

- [x] Day Case: 57,267
- [x] Inpatient: 22,937
- [x] Outpatient: 502,482

### 🎯 Key Performance Indicators (KPIs)

#### Volume Metrics
- [x] Total patient count by case type
- [x] Specialty-wise patient distribution
- [x] Age profile segmentation

#### Wait Time Analysis
- [x] Time band distribution
- [x] Average vs Median wait times
- [x] Trend analysis over 3.5 years


#### Operational Efficiency

- [x] Case type bifurcation percentages
- [x] Month-over-month growth trends
- [x] Specialty performance benchmarking

#### Strategic Insights

- [x] High-demand specialties identification
- [x] Patient demographic patterns
- [x] Resource allocation opportunities

### 💡 Business Value

- [x] Operational Excellence: Identify bottlenecks in patient flow
- [x] Resource Optimization: Allocate staff and facilities based on demand patterns
- [x] Patient Experience: Reduce wait times through data-driven interventions
- [x] Strategic Planning: Forecast capacity needs and specialty requirements
- [x] Compliance: Monitor and report on healthcare service delivery standards

### 🎨 Design Highlights

- [x] Modern dark theme with purple/pink accent colors
- [x] Intuitive navigation between Summary and Detailed views
- [x] Interactive visualizations (donut charts, stacked bars, area charts, heat maps)
- [x] Professional healthcare-focused aesthetics
- [x] Responsive layout optimized for executive presentations
- [x] Adopted a color palette for consistency throughout the dashboard (https://coolors.co/palette/139a43-66d17f-0dab76-d19c1d-fe5f55)


### 📈 Data Coverage
- [x] Timeline: January 2018 - March 2021 (39+ months)
- [x] Total Records: 24.6+ million patient interactions
- [x] Specialties Tracked: 15+ medical specialties
- [x] Age Segments: 4 distinct age profiles (0-15, 16-64, 65+)

### 🚀 Use Cases

- [x]  Hospital administration performance monitoring
- [x]  Healthcare policy impact assessment
- [x]  Capacity planning and forecasting
- [x]  Wait list reduction initiatives
- [x]  Specialty service expansion decisions
- [x]  Patient satisfaction improvement programs

### Presented by: Soumyadeep Dhar
### Tool: Microsoft Power BI Desktop
### Analysis Type: Descriptive, Diagnostic, and Predictive Analytics

###  🔗 Connect & Collaborate
- [x] Analyst: Soumyadeep Dhar
- [x] 📧 Email: soumyadeepdhar433@gmail.com
- [x] 💼 LinkedIn: www.linkedin.com/in/soumyadeep-dhar-785724333


### 🌟 Star this repository if you found it helpful!
- [x]  Keywords: data-analytics, business-intelligence, power bi-dashboard, Healthcare, kpi-analysis, data-visualization, Treatment ,Business-insights, Doctor,Patient
