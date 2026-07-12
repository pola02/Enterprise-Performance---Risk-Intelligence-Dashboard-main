# 📊 Enterprise Performance & Risk Analytics Dashboard

## 🏢 Project Overview
This project delivers an **end-to-end Business Intelligence solution** focused on **enterprise financial performance and operational risk analytics**.  
It is designed to support **executive-level decision-making** by integrating revenue, cost, margin, and risk indicators into a unified Power BI reporting experience.

The dashboard simulates a real-world **consulting-style use case** similar to projects delivered by firms like PwC, EY, and KPMG.

---

## 🎯 Business Objectives
- Monitor **Revenue vs Budget** performance across time, regions, and categories
- Analyze **cost structure** and gross margin drivers
- Identify **high-risk regions** based on operational KPIs
- Quantify **cost and revenue at risk**
- Provide clear, actionable **executive insights**

---

## 🧠 Key Analytics Domains
- Business Intelligence (BI)
- Enterprise Performance Management (EPM)
- Financial Analytics
- Operational & Risk Analytics

---

## 📐 Data Model
The model follows a **Star Schema** design.

### Fact Tables
- Fact_Sales – Revenue, Cost, Gross Profit
- Fact_Budget – Budgeted Revenue and Cost
- Fact_Operations – Incidents, Exceptions, Downtime, Ops Impact Cost

### Dimension Tables
- Dim_Date
- Dim_Month
- Dim_Region
- Dim_Category
- Dim_Product

All relationships are **single-direction, one-to-many** where applicable to ensure accurate filter propagation.

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview
**Purpose:** 30-second executive snapshot

**KPIs:**
- Total Revenue
- Budget Revenue
- Revenue Variance %
- Gross Margin %
- Risk Score

**Visuals:**
- Revenue vs Budget Trend
- Regions at Risk (Revenue Variance)
- Dynamic Insight Box (measure-driven)

---

### 2️⃣ Financial Performance
**Purpose:** Deep dive into revenue, cost, and margin drivers

**KPIs:**
- Revenue
- Cost
- Gross Profit
- Gross Margin %

**Visuals:**
- Revenue by Category
- Gross Margin % by Category
- Revenue & Cost Trend
- Cost Breakdown by Category
- Financial Insight Box

---

### 3️⃣ Risk & Operations
**Purpose:** Identify and quantify operational risk exposure

**KPIs:**
- Risk Score
- High Risk Regions
- Cost at Risk
- Revenue at Risk %

**Visuals:**
- Risk Score by Region (conditional formatting)
- Revenue Impact by Region
- Risk Trend Over Time
- Risk Insight Box (measure-driven)

---

## 🧮 Key Measures (Examples)
- Total Revenue
- Budget Revenue (Adjusted)
- Revenue Variance %
- Gross Margin %
- Risk Score
- Risk Score Index
- Cost at Risk
- Revenue at Risk %

All insights are generated dynamically using **DAX measures**, not static text.

---

## 🎨 Design Principles
- Executive-friendly layout
- Consistent color theme across pages
- Conditional formatting for risk levels
- Minimal clutter, maximum clarity
- Reset Filters button for usability

---

## 🛠 Tools & Technologies
- Power BI Desktop
- DAX for advanced calculations
- Power Query for data transformation
- Star Schema Modeling

---

## 🚀 Use Cases
- Executive reporting
- Finance & FP&A analysis
- Risk management dashboards
- Consulting portfolio project
- BI & Data Analytics portfolio

---

## 📌 Notes
- All data is **simulated for training and portfolio purposes**
- Project focuses on **logic, modeling, and insight generation**, not raw data realism

---

## 👤 Author
**Mohamed Heta**  
Business Intelligence & Data Analytics

---

## 🔗 Portfolio Usage
This project is suitable for:
- GitHub portfolio
- LinkedIn project showcase
- Consulting interviews
- BI / Data Analyst roles

#MAKE_DATA_TALK  
#معلومة_في_السكة
