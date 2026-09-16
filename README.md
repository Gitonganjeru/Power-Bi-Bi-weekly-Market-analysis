# TalentCore Workforce Analytics

## Power BI | HR Analytics | People Analytics | Data Visualization

### Project Overview

TalentCore Workforce Analytics is a Power BI project developed as part of my Moringa School Data Analytics capstone.

The project analyzes employee workforce data to help HR and management understand **employee attrition, compensation, workforce composition, and overtime patterns**.

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
* Workforce age, tenure, and education characteristics
* How attrition changes over time
* Which workforce segments require management attention

Without this visibility, retention and workforce-planning decisions may be based on assumptions rather than evidence.

---

## Project Objectives

The analysis was designed to:

* Evaluate overall workforce health using key HR metrics
* Identify departments and offices with elevated attrition
* Investigate overtime and its potential relationship with employee turnover
* Analyze compensation across departments, roles, and gender
* Understand workforce age, tenure, and education characteristics
* Identify areas requiring management attention
* Develop data-driven recommendations for improving retention and workforce planning

---

# Methodology — CRISP-DM

The project followed the **CRISP-DM** framework.

### Business Understanding

The primary business challenge was employee attrition and the lack of visibility into the workforce segments contributing to employee turnover.

The analysis therefore focused on identifying attrition hotspots and workforce factors that could support better retention decisions.

### Data Understanding

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

### Data Preparation

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

### Analysis

The analysis focused on five major areas.

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

* Attrition tr
