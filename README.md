# 🏥 Hospital Emergency Room Dashboard

## 📌 Project Overview

The **Hospital Emergency Room Dashboard** is an interactive, end-to-end Business Intelligence solution built using **Power BI Desktop** to monitor, analyze, and optimize Emergency Room (ER) operations. The dashboard provides healthcare administrators, operational managers, and decision-makers with actionable insights into patient flow, service efficiency, demographic trends, admission patterns, and departmental referrals.

By transforming raw hospital records into intuitive visual analytics, this solution enables stakeholders to identify bottlenecks, improve patient experience, optimize staffing allocation, and support data-driven decision-making.

---

## 🎯 Project Objectives

The primary objectives of this dashboard are:

* Monitor Emergency Room performance in real time.
* Track patient volumes and admission trends.
* Analyze average patient waiting times.
* Measure patient satisfaction levels.
* Identify peak operational hours and high-traffic days.
* Understand demographic and referral patterns.
* Improve hospital resource allocation and operational efficiency.

---

# 🚀 Dashboard Views

---

## 1️⃣ Monthly View

### Overview

The Monthly View provides a focused analysis of Emergency Room performance for a selected month and year. Users can dynamically filter the dashboard to evaluate short-term operational trends and service quality metrics.

### Key Features

#### 📊 Dynamic Time Intelligence

* Single Month Selector
* Year Filter
* Dynamic KPI calculations based on selected period

#### 📈 KPI Cards

The dashboard highlights critical performance indicators:

| KPI                        | Description                            |
| -------------------------- | -------------------------------------- |
| Total Patients             | Total ER visits during selected month  |
| Average Wait Time          | Average waiting time (minutes)         |
| Patient Satisfaction Score | Average satisfaction rating            |
| Total Referrals            | Patients referred to other departments |

#### 🔥 Patient Volume Heatmap

A comprehensive Day-Hour matrix visualizes patient traffic patterns.

**Rows:** Days of Week (Monday – Sunday)

**Columns:** Hourly Time Slots

Example:

| Time  | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
| ----- | --- | --- | --- | --- | --- | --- | --- |
| 00–02 | 45  | 38  | 40  | 41  | 48  | 52  | 46  |
| 10–12 | 85  | 78  | 80  | 83  | 90  | 92  | 79  |
| 18–20 | 95  | 88  | 90  | 91  | 96  | 101 | 89  |

This heatmap helps identify:

* Peak traffic hours
* Staff scheduling requirements
* Resource optimization opportunities

#### 👨‍⚕️ Admission Status Analysis

Visual representation of:

* Admitted Patients
* Non-Admitted Patients

#### 👩 Gender Distribution

Breakdown of:

* Male Patients
* Female Patients
* Other Categories

#### 🎂 Age Group Analysis

Patient segmentation across age brackets:

* 0–9
* 10–19
* 20–29
* 30–39
* 40–49
* 50–59
* 60+

#### 🏥 Department Referral Analysis

Tracks referrals to:

* General Practice
* Orthopedics
* Neurology
* Cardiology
* Gastroenterology
* Other Departments

#### 🌍 Racial Demographic Analysis

Provides insights into demographic composition of ER visitors.

---

## 2️⃣ Consolidated View

### Overview

The Consolidated View enables long-term trend analysis across multiple months or years.

Unlike the Monthly View, which focuses on short-term monitoring, this view supports strategic planning and performance evaluation over extended periods.

### Key Features

#### 📅 Interactive Date Range Filter

Users can:

* Select custom date ranges
* Compare periods
* Analyze seasonal trends

#### 📈 Historical Trend Analysis

Tracks:

* Patient Growth Trends
* Satisfaction Score Trends
* Wait Time Patterns
* Referral Trends
* Admission Rate Changes

#### 📊 Comparative Performance Monitoring

Supports:

* Month-over-Month Analysis
* Quarter-over-Quarter Analysis
* Year-over-Year Analysis

#### 🔍 Operational Insights

Helps answer questions such as:

* Are wait times improving?
* Is patient satisfaction increasing?
* Which departments receive the highest referrals?
* How has patient volume changed over time?

---

## 3️⃣ Patient Details View

### Overview

The Patient Details View provides detailed record-level information for auditing, validation, and operational investigations.

This page moves beyond aggregated visualizations and displays individual patient records.

### Patient Information Captured

| Field               | Description               |
| ------------------- | ------------------------- |
| Patient ID          | Unique Patient Identifier |
| Patient Name        | Full Patient Name         |
| Gender              | Patient Gender            |
| Age                 | Patient Age               |
| Admission Date      | Date of ER Visit          |
| Race                | Patient Demographic Group |
| Wait Time           | Waiting Time in Minutes   |
| Department Referral | Referred Department       |
| Admission Status    | Admitted / Not Admitted   |

### Benefits

* Detailed patient tracking
* Data validation
* Audit support
* Case investigation
* Operational transparency

---

# 📊 Descriptive Analysis & Key Findings

The dashboard includes a dedicated insights section that summarizes important findings from the Emergency Room dataset.

---

## 🏥 Referral Breakdown

### Key Observation

A significant proportion of patients do not require referral to another department after ER assessment.

Among referred cases:

🥇 General Practice

🥈 Orthopedics

🥉 Neurology

received the highest number of referrals.

### Business Impact

* Supports workforce planning
* Helps allocate specialist resources
* Improves referral management processes

---

## ⏰ Peak Performance Windows

### High-Volume Days

Analysis revealed:

* Monday
* Saturday

as the busiest Emergency Room days.

### Peak Traffic Hours

Patient traffic consistently spikes around:

* 11:00 AM
* 7:00 PM
* 11:00 PM

### Business Impact

These insights can help management:

* Schedule additional staff
* Improve shift planning
* Reduce patient wait times

---

## 👨‍👩‍👧‍👦 Demographic Composition

### Age Distribution

The largest patient segment falls within:

**30–39 Years Age Group**

### Demographic Trends

The dashboard highlights dominant racial and demographic groups utilizing Emergency Room services.

### Business Impact

* Targeted healthcare planning
* Better resource distribution
* Community health strategy support

---

# 🏗️ Data Architecture

## Data Model Design

The solution follows a structured data modeling approach using:

### Fact Table

#### Hospital ER Dataset

Contains:

* Patient Records
* Admissions
* Wait Times
* Satisfaction Scores
* Referral Data

### Dimension Tables

#### 📅 Calendar Table

Created specifically for:

* Date Filtering
* Time Intelligence
* Trend Analysis
* YTD Calculations
* MTD Calculations

### Model Benefits

✔ Improved Performance

✔ Faster Query Execution

✔ Better Scalability

✔ Accurate Time Intelligence

---

# ⚙️ Technologies Used

| Technology                  | Purpose                 |
| --------------------------- | ----------------------- |
| Power BI Desktop            | Dashboard Development   |
| Power Query                 | Data Transformation     |
| DAX                         | Measures & Calculations |
| Data Modeling               | Star Schema Design      |
| Excel / CSV                 | Source Data             |
| Time Intelligence Functions | Trend Analysis          |

---

# 🎨 User Experience (UX) Design

The dashboard incorporates a modern and intuitive user interface.

### Features

✔ Vertical Navigation Panel

✔ Sticky Sidebar Navigation

✔ Active Page Highlighting

✔ Consistent Color Theme

✔ Responsive Visual Layout

✔ Cross-Filtering Interactions

✔ Drill-Through Navigation

### Benefits

* Improved usability
* Faster report navigation
* Better stakeholder adoption
* Enhanced decision-making experience

---

# 📈 Business Value Delivered

The Hospital Emergency Room Dashboard enables healthcare organizations to:

* Monitor Emergency Room performance in real time.
* Improve patient experience through wait-time analysis.
* Optimize staffing and resource allocation.
* Identify operational bottlenecks.
* Understand patient demographics.
* Improve referral management.
* Support strategic and operational decision-making.

---

# 🏆 Conclusion

The Hospital Emergency Room Dashboard demonstrates how Business Intelligence can transform healthcare operations by converting raw patient records into meaningful insights. Through interactive reporting, advanced analytics, and intuitive visualizations, the solution empowers hospital management teams to improve efficiency, enhance patient care, and make informed operational decisions.

This project showcases expertise in:

✅ Power BI Development

✅ Data Modeling

✅ DAX Calculations

✅ Healthcare Analytics

✅ Dashboard Design

✅ Business Intelligence Reporting

✅ Data Visualization & Storytelling


Developed by VANSHIKA SHARMA 

