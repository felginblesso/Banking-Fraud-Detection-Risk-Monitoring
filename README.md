# Banking-Fraud-Detection-Risk-Monitoring
Banking fraud detection, transaction risk assessment, and fraud alert monitoring using MySQL and Power BI.


## 📌 Project Overview

This project focuses on analysing banking transactions to identify suspicious activities, assess transaction risks, and monitor potential fraudulent activities.

A relational database was designed using MySQL, incorporating transaction details, fraud detection rules, transaction risk assessments, and fraud alerts.

An interactive Power BI dashboard was developed to visualize fraud trends, alert severity, detection patterns, and investigation statuses, providing meaningful insights into banking fraud monitoring.

---

## 🎯 Objectives

- Analyse banking transactions to identify suspicious activities and potential fraud patterns.
- Implement rule-based fraud detection mechanisms.
- Assess transaction risks using risk scores and risk classifications.
- Monitor fraud alerts based on severity and investigation status.
- Identify frequently triggered fraud detection rules.
- Develop an interactive Power BI dashboard for fraud monitoring and risk analysis.

---

## 🗄️ Database Structure

The MySQL database consists of four interconnected tables:

- **Transactions** – Banking transaction details and related attributes.
- **Fraud_Rules** – Fraud detection rules used to identify suspicious activities.
- **Transaction_Risk** – Transaction-level risk scores and risk classifications.
- **Fraud_Alerts** – Fraud alert details, detection rules, severity, and investigation status.

---

## 🛠️ Tools & Technologies

- MySQL
- SQL Data Analysis
- Microsoft Power BI
- Data Visualization
- Dashboard Development

---

## 🔄 Project Workflow

Database Design → Data Generation → SQL Analysis → Fraud Rule Analysis → Transaction Risk Assessment → Power BI Dashboard Development → Business Insights

---

## 🔍 Fraud Detection Rules

The following detection rules are considered for identifying suspicious transaction activities:

1. **Blacklisted IP** – Identifies transactions originating from blacklisted IP addresses.
2. **Rapid Transactions** – Detects unusually frequent transactions within a short period.
3. **Shared IP** – Identifies multiple users performing transactions from the same IP address.
4. **Unregistered Device** – Flags transactions associated with unregistered devices.
5. **High-Value International Transaction** – Identifies high-value international transactions for further risk assessment.

---

## 📈 Key KPIs

| **KPI**            | **Value** |
| ------------------ | --------- |
| Total Transactions | 10K       |
| Fraud Alerts       | 2.731K    |
| Open Alerts        | 635       |
| Detection Rules    | 5         |

---

## 🔍 Key Analysis

### Fraud Alerts & Severity

- Monitored fraud alerts across Critical, High, Medium, and Low severity levels.
- Analysed alert distribution based on investigation status.
- Identified the distribution of fraud alerts across different detection rules.

### Transaction Risk & Monitoring

- Analysed transaction risk scores and risk classifications.
- Monitored suspicious transaction activities using multiple detection rules.
- Evaluated fraud alert trends over time.
- Tracked open, closed, in-review, and confirmed-fraud alerts.

---

## 💡 Business Value

1. Enables better visibility into suspicious banking transaction activities.
2. Supports prioritization of fraud alerts based on severity and risk levels.
3. Helps identify frequently triggered fraud detection patterns.
4. Improves monitoring of fraud investigation statuses.
5. Supports data-driven decision-making in banking fraud risk management.

---

## 📊 Dashboard

[Banking Fraud Detection Dashboard](Screenshots/Dashboard.png) ([image](Screenshots/Dashboard.png))

---

## 📂 Project Files

- `SQL/` – Database creation and data generation.
- `PowerBI/` – Interactive Power BI dashboard.
- `Screenshots/` – Dashboard preview.
