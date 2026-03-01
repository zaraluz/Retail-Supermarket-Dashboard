# 🛒 Retail Supermarket BI Dashboard | Cloud Data Warehouse Project

## 📌 Project Overview

This project presents a complete Business Intelligence solution developed for a **Brazilian regional supermarket chain**.

⚠️ The dashboard is presented in **Portuguese**, as it was designed for Brazilian business stakeholders.

The solution was built on a cloud-based Data Warehouse architecture using AWS and follows a dimensional modeling approach to support operational and strategic decision-making.

---

## 🏗️ Data Architecture

Cloud Stack:

- AWS S3 → Data Lake storage  
- AWS Athena → SQL external tables  
- Star Schema dimensional modeling  
- Power BI → Visualization layer  

### Data Flow

ERP → ETL Process → AWS S3 → Athena → Power BI

---

## 📊 Dashboard Structure

The solution is divided into two strategic pages:

---

# 📊 Page 1 — Executive Overview (Visão Geral)

This page was designed for executive-level decision-making and fast performance monitoring.

<img width="2048" height="1174" alt="2" src="https://github.com/user-attachments/assets/e8f4d4ba-6c6c-4e4c-8694-0fa593e69d5e" />


## Main KPIs

- Total Revenue
- Gross Profit
- Gross Margin
- YoY Growth Comparison

### Strategic Visual Choices

The visual elements were intentionally selected to:

- Deliver immediate business health visibility  
- Highlight growth or decline trends  
- Support fast executive decisions  
- Simplify financial performance interpretation  

### Featured Analyses

- Profit comparison (Current Year vs Previous Year)
- Top 10 Most Sold Products
- Category YoY Performance
- Monthly Sales Comparison

### Operational Alerts

This section highlights:

- High sales + high loss products
- Low sales + high loss products

These alerts support:
- Waste reduction strategies  
- Pricing review  
- Operational optimization  

The design prioritizes clarity over complexity to ensure that managers, supervisors, and directors can understand insights without technical knowledge.

---

# 🏢 Page 2 — Supplier Strategic Analysis (Fornecedores)

This page focuses on supplier performance and operational risk analysis.

<img width="1791" height="1017" alt="3" src="https://github.com/user-attachments/assets/f6e498cb-c150-42c2-aacd-6d58d09fe269" />


## Key Indicators

- Active Suppliers
- Active SKUs
- Top 10 Revenue Concentration
- Supplier with Highest Volume
- Supplier with Highest Margin

---

## Supplier Performance Insights

### Profit by Supplier
Supports negotiation strategy and portfolio prioritization.

### Sales YoY by Supplier
Identifies growth or dependency risks.

### Supplier Distribution by Turnover Tier
Helps classify suppliers by operational relevance.

---

## Operational Risk Alerts

This section identifies:

- High stock + low sales suppliers  
- Low stock + high sales suppliers (rupture risk)

This allows:

- Inventory adjustment  
- Procurement optimization  
- Loss reduction  
- Margin protection  

---

## 🎨 Visual & Design Strategy

Because this is a **regional Brazilian retail company**, the dashboard was intentionally designed with:

- Clear Portuguese terminology
- Simple categorization (Alto, Médio, Baixo)
- Direct KPI communication
- Minimal visual noise
- Intuitive layout

The goal was not aesthetic complexity, but business clarity.

Every visual was chosen to answer a specific decision-making question.

---

## 🧠 PACE Framework

### 🟢 Plan
- Define retail KPIs
- Identify operational bottlenecks
- Structure dimensional model

### 🟡 Analyze
- Revenue vs Cost behavior
- Margin trends
- Loss patterns
- Supplier concentration risk

### 🔵 Construct
- Build ETL pipeline
- Implement Star Schema
- Create Athena external tables
- Develop Power BI dashboards

### 🔴 Execute
- Deliver executive-ready insights
- Support supplier negotiation
- Improve stock allocation
- Enable data-driven management

---

## 🔐 Data Confidentiality

All financial values have been anonymized.
