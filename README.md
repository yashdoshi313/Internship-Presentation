# Co-op Final Presentation – Slavin Raphael (Winter 2025)

This repository documents my internship progress at **Slavin Raphael**, a Toronto-based multi-brand fashion sales agency specializing in premium footwear and apparel distribution across North America.  

The work involved applying **data analytics, forecasting, and dashboarding techniques** to solve real-world business problems in financial planning, sales returns, and export compliance. [📄 View Full Presentation (PDF)](Internship-Presentation/Co-op%20Final%20Presentation%20-%2021st%20April%202025.pdf)


---

## 📌 Projects

### **Project 1 – Purchase Forecasting for Tiger of Sweden**
- **Problem**: Lack of clear visibility into purchasing patterns, requiring reliable monthly forecasts to support Q2 2025 cash flow planning.  
- **Approach**:
  - Extracted raw invoice data from Visual ERP (`TOS_Stmt.csv`, Nov 2019–Feb 2025).  
  - Cleaned and pre-processed data in Excel & Python (Pandas, Statsmodels-ARIMA).  
  - Analyzed historical purchase trends and built ARIMA forecasting models.  
- **Insights**:
  - September = peak spend; May & December = low spend.  
  - 86% invoices paid; 14% unpaid flagged as credit risk.  
  - Forecast: Baseline reserve €528K for Q2 2025, with flexibility up to €1.45M.  

---

### **Project 2 – Sales Return Audit for a Major Client**
- **Problem**: High return rates eroding margins; no visibility into return-heavy SKUs and regions.  
- **Approach**:
  - Cleaned Visual ERP datasets (Python + Excel), merged transaction & overview tables.  
  - Designed **Power BI dashboard** with star schema (FactReturns + DimProduct/Store/Date/Division).  
  - DAX calculations for top returned SKUs and regional analysis.  
- **Insights**:
  - Top Returned Product: *Mix & Match Trouser* (fit/quality issues).  
  - High Return Stores: Vancouver Store (366) & Yorkdale Store (311).  
  - Seasonal Trend: Q4 spikes (Oct–Nov) linked to fall collection & promos.  
  - Ontario & BC drove ~70–80% of return dollars.  
- **Recommendations**: Audit sizing/quality, improve size guides, refine promo return policies.  

---

### **Project 3 – Export & Duty Audit**
- **Problem**: No centralized visibility on export duties, invoice duplication, and brand-level efficiency.  
- **Approach**:
  - Merged brand-level export tables in **SQL Server Management Studio**.  
  - Analyzed monthly duties, per-unit brand costs, and duplicate invoices.  
- **Insights**:
  - December 2024 = highest duty payments (year-end surge).  
  - **Tiger Brand** had highest duty per unit (€18.16 vs. €10–12 for others).  
  - Duplicate invoices (e.g., SI-1054410 repeated 7x) posed audit risks.  
- **Recommendations**: Duty structure review, tariff optimization, enforce invoice uniqueness rules.  

---

### **Project 4 – Account Reconciliation (Dec 2024 – Mar 2025)**
- **Problem**: Reconciliation with a major client (cannot name) during creditor protection filing.  
- **Approach**:
  - Extracted invoice/credit/payment data from Visual ERP & client’s 852 statement.  
  - Created pivot tables to detect anomalies at store/transaction-date level.  
  - Pinpointed discrepancies (e.g., Yorkdale store 29/01/25, $130.96 misreport).  
- **Outcome**: Delivered accurate reconciliation, minimizing financial exposure and ensuring reporting compliance.  

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, Matplotlib, Statsmodels/ARIMA)  
- **Excel** (data cleaning, pivoting)  
- **Power BI** (dashboard modeling, DAX)  
- **SQL Server (SSMS)** (data merging & audits)  
- **Visual ERP** (data extraction & reconciliation)  

---

## 📊 Key Skills Applied
- Forecasting & Time Series Modeling  
- Financial Reconciliation  
- Power BI Dashboarding (Star Schema + DAX)  
- SQL Querying & Data Audits  
- Data Cleaning & Preprocessing  

---

## 🔗 Presentation
This summary is based on my **Co-op Final Presentation (April 21, 2025)**.  
