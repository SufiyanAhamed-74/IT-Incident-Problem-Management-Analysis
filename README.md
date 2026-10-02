# IT Incident & Problem Management Analysis

## 📌 Project Overview

This project analyzes IT incident records to understand incident trends, recurring issues, priority and severity patterns, resolution performance, SLA compliance, and potential problem areas.

An interactive Power BI dashboard was developed to monitor incident KPIs, resolution performance, backlog, recurring incidents, major incidents, and assignment group performance.

The project demonstrates practical understanding of IT Service Management (ITSM) concepts such as Incident Management, Problem Management, SLA Management, performance monitoring, root-cause investigation, and continuous service improvement.

---

## 🎯 Objectives

- Monitor overall IT incident volume and trends
- Analyze incidents by priority and severity
- Track open, closed, and in-progress incidents
- Measure SLA compliance and SLA breaches
- Evaluate incident resolution time
- Identify recurring incidents and potential problem areas
- Analyze performance across assignment groups
- Monitor major incidents and customer impact
- Identify areas for continuous service improvement

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **CSV Dataset**

---

## 📊 Dataset

The dataset contains **3,500 IT incident records**.

### Key Fields

| Field | Description |
|---|---|
| Incident_ID | Unique incident identifier |
| Incident_Date | Date when the incident was reported |
| Incident_Category | Category of the incident |
| Priority | Incident priority level |
| Severity | Severity of the incident |
| Affected_Service | IT service affected by the incident |
| Department | Affected department |
| Assignment_Group | Team responsible for resolving the incident |
| Channel | Incident reporting channel |
| Status | Current incident status |
| Major_Incident | Indicates whether the incident is a major incident |
| Recurring_Incident | Indicates whether the incident is recurring |
| Reopened | Indicates whether the incident was reopened |
| Customer_Impact | Level of customer impact |
| SLA_Target_Hours | Target resolution time |
| Resolution_Date | Date when the incident was resolved |
| Resolution_Time_Hours | Time taken to resolve the incident |
| Incident_Age_Hours | Age of the incident |
| SLA_Status | Whether the SLA was met or breached |
| Root_Cause | Recorded or identified root cause |

---

## 🔄 Data Preparation

Data preparation was performed using **Power Query**.

### Steps performed:

- Reviewed dataset structure and data types
- Converted date and numeric fields appropriately
- Checked missing and inconsistent values
- Prepared incident and SLA-related fields
- Created a clean dataset for Power BI analysis

---

## 📈 Dashboard KPIs

The dashboard focuses on important incident management metrics:

- Total Incidents
- Open Incidents
- Closed Incidents
- In-Progress Incidents
- Major Incidents
- Recurring Incidents
- Reopened Incidents
- SLA Compliance %
- SLA Breach Count
- Average Resolution Time
- Customer Impact

---

## 📊 Dashboard Analysis

### 1. Incident Overview

Provides an overall view of incident performance.

Key analysis includes:

- Total incident volume
- Incident status
- Monthly incident trends
- Priority distribution
- Severity distribution
- Incident categories
- Affected services

### 2. Incident Performance

Focuses on operational and resolution performance.

Key analysis includes:

- Incidents by priority
- Incidents by severity
- Resolution time by assignment group
- Resolution time by category
- SLA compliance
- SLA breaches
- Incident backlog
- Reopened incidents

### 3. Problem Management Analysis

Focuses on recurring incidents and potential underlying problem areas.

Key analysis includes:

- Recurring incident categories
- Frequently affected services
- Repeated incidents
- Major incident patterns
- Root-cause distribution
- Assignment groups handling recurring issues
- Areas requiring further investigation

---

## 🧮 DAX Measures

Example measures created for the dashboard include:

```DAX
Total Incidents =
COUNTROWS('IT Incidents')
