# TalentCore Workforce Analytics

## Power BI | HR Analytics | People Analytics | Data Visualization

### Project Overview

TalentCore Workforce Analytics is a Power BI project developed as part of my Moringa School Data Analytics capstone.

The project analyzes employee workforce data to help HR and management understand **employee attrition, compensation, workforce composition and overtime patterns**.

Rather than simply reporting workforce numbers, the project focuses on using data to answer a business problem:

> **Where is employee attrition concentrated, what workforce factors may be associated with it, and where should management prioritize retention efforts?**

---

## Business Problem

TalentCore has 243 employees across six departments and six regional offices. While the company has an overall attrition rate of 16%, employee departures are not evenly distributed across the organization.

Leadership needs better visibility into:

* Which departments have the highest attrition
* Which offices are experiencing elevated employee turnover
* Whether overtime may be associated with attrition
* How compensation is distributed across departments and gender
* Workforce age, tenure and education characteristics
* How attrition changes over time
* Which workforce segments require management attention

Without this visibility, retention and workforce-planning decisions may be based on assumptions rather than evidence.

---

## Project Objectives

The analysis was designed to:

1. Evaluate overall workforce health using key HR metrics.
2. Identify departments and offices with elevated attrition.
3. Investigate overtime and its potential relationship with employee turnover.
4. Analyze compensation across departments, roles and gender.
5. Understand workforce age, tenure and education characteristics.
6. Identify areas requiring management attention.
7. Develop data-driven recommendations for improving retention and workforce planning.

---

## Methodology — CRISP-DM

The project followed the **CRISP-DM** framework.

### 1. Business Understanding

The primary business challenge was employee attrition and the lack of visibility into the workforce segments contributing to employee turnover.

The analysis therefore focused on identifying attrition hotspots and workforce factors that could support better retention decisions.

### 2. Data Understanding

The dataset contained **243 employee records** covering six departments and six offices, with hire dates spanning 2018–2025.

Key fields included:

* Employee ID
* Hire Date
* Exit Date
* Department
* Job Role
* Office Location
* Gender
* Age
* Education Level
* Monthly Salary
* Performance Rating
* Training Hours
* Overtime
* Attrition Status

### 3. Data Preparation

Data preparation was performed using **Power Query and Power BI**.

The preparation process included:

* Reviewing the dataset structure
* Validating data types
* Standardizing date fields
* Creating a dedicated Date table
* Building relationships between the employee data and dimension tables
* Creating calculated measures for workforce KPIs

Key measures included:

* Total Headcount
* Active Employees
* Employees Left
* Attrition Rate
* Average Age
* Average Tenure
* Average Monthly Salary

### 4. Analysis

The analysis focused on five major areas:

**Workforce Overview**

* Headcount
* Workforce composition
* Age
* Education
* Gender

**Departmental Performance**

* Attrition by department
* Active employees
* Employees who exited
* Salary distribution

**Attrition Analysis**

* Attrition trends over time
* Office-level attrition
* Overtime patterns
* High-risk workforce areas

**Compensation & Diversity**

* Salary distribution
* Department-level compensation
* Gender representation
* Compensation differences

### 5. Visualization

An interactive Power BI dashboard was developed with dedicated pages for:

* Executive Summary
* Workforce Overview
* Departmental Performance
* Attrition Analysis
* Compensation and Diversity Analysis

Slicers were incorporated to allow users to explore workforce segments.

### 6. Recommendations

The analysis was translated into practical recommendations focused on:

* Investigating non-compensation drivers of Finance attrition
* Improving retention in Customer Support
* Reviewing workforce conditions in Kisumu
* Monitoring and reducing excessive overtime
* Improving the measurement of compensation equity
* Using more stable measures for attrition trends

---

# Key Findings

### 1. Attrition is concentrated in specific departments

Finance recorded the highest departmental attrition rate at **22%**, followed by Customer Support at **20%**.

Operations had the lowest attrition rate at **8%**, making it a potential internal benchmark for retention practices.

### 2. Customer Support has the largest absolute loss

Customer Support had 41 active employees and 10 employees who had left.

Those 10 departures represented approximately **26% of all employee exits**, meaning that improving retention in this department could have a significant impact on total workforce turnover.

### 3. Kisumu is the main geographic attrition hotspot

Kisumu recorded an attrition rate of **23%**, compared with the company-wide rate of 16%.

This makes Kisumu the clearest geographic outlier in the available dashboard results.

### 4. High attrition is not necessarily explained by salary

Finance had the highest average monthly salary at approximately **KES 175,659**, while also recording a 22% attrition rate.

This suggests that salary alone may not explain employee turnover and that other factors such as workload, management, engagement or career development should be investigated.

### 5. Overtime is an important area for investigation

Approximately **40% of active employees regularly work overtime**.

The analysis identified overtime as a potentially important workforce factor and recommended a direct comparison of attrition rates between employees who work overtime and those who do not.

### 6. Attrition trends are highly volatile

Quarterly attrition varied substantially between 2018 and 2025.

Because the workforce is relatively small, individual employee exits can cause large changes in quarterly rates. A rolling four-quarter average or annualized reporting approach would therefore provide a more stable view of the trend.

---

# Business Recommendations

Based on the analysis, the project recommends:

* Investigating the underlying causes of Finance attrition through structured exit interviews.
* Prioritizing retention initiatives within Customer Support.
* Reviewing management, engagement and compensation competitiveness in Kisumu.
* Investigating workload and overtime in high-attrition departments.
* Using rolling or annualized attrition metrics instead of relying heavily on volatile quarterly rates.
* Correcting the compensation-by-gender calculation before making pay-equity conclusions.

---

# Areas for Improvement

This project also highlighted several areas where the dashboard and analytical process can be improved.

### 1. Improve visual storytelling

The dashboard can be organized into clearer analytical sections so that users can naturally move from:

**Workforce Overview → Attrition → Drivers → Recommendations**

A stronger visual hierarchy would make the story easier to follow.

### 2. Use specific visuals when presenting insights

When communicating an insight, the supporting chart should be presented alongside the conclusion rather than sharing an entire dashboard screenshot.

For example:

> **Insight:** Finance has the highest attrition rate among departments.

This should be accompanied by the **Departmental Attrition chart**, allowing the audience to immediately see the evidence behind the conclusion.

### 3. Improve dashboard layout

The dashboard can be refined by grouping related visuals and creating a more intentional flow.

Future iterations will prioritize:

* Clear section headers
* Consistent visual hierarchy
* Better spacing
* Reduced visual clutter
* Stronger alignment between charts and the business questions

### 4. Correct compensation measurement

The compensation-by-gender visual currently uses **Sum of Monthly Salary rather than Average Monthly Salary**.

Using the sum can make differences in workforce size appear to be pay differences.

The visual should therefore be rebuilt using average salary before making any conclusions about gender pay equity.

### 5. Improve data quality

The dataset contains inconsistent category labels, including variations of education and department names.

For example:

* `Customer Support`
* `Cust. Support`
* `Support`

These should be standardized in Power Query before final analysis.

### 6. Improve attrition trend analysis

The quarterly attrition chart is highly volatile.

A future version should include:

* Four-quarter rolling attrition
* Annualized attrition
* Possibly minimum-headcount thresholds for trend interpretation

This would reduce the risk of interpreting small-sample fluctuations as genuine business trends.

### 7. Add a direct overtime-vs-attrition analysis

The current dashboard identifies overtime as an important area for investigation, but a dedicated visual comparing:

**Attrition Rate — Overtime vs No Overtime**

would make the relationship easier to evaluate.

---

# Tools Used

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Visualization**
* **CRISP-DM**

---

# Dashboard Pages

1. Executive Summary
2. Workforce Overview
3. Departmental Performance
4. Attrition Analysis
5. Compensation & Diversity Analysis

---

# Project Outcome

This project demonstrates how Power BI can be used to move from raw workforce data to **business-focused insights and recommendations**.

The key lesson from the project was that effective analytics is not only about creating visually attractive dashboards. It also requires:

* Asking the right business questions
* Building reliable measures
* Choosing appropriate visualizations
* Connecting insights to evidence
* Communicating limitations
* Translating findings into actionable decisions

---

## Author

**Timothy Njeru**

Data Analytics | Power BI | SQL | Excel

Moringa School — Data Analytics
