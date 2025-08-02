
# 📊 Loan Default Analysis Dashboard using Power BI

This Power BI report presents a comprehensive analysis of **loan default trends**, combining borrower demographics, financial profiles, credit scoring, and temporal trends. It aims to support data-driven decision-making in lending risk and loan portfolio management.

---

## 📁 Dataset Overview

- **Total Records:** 255,347
- **Features:** 19
- **Key Columns:**
  - `LoanAmount`
  - `Income`
  - `CreditScore`
  - `Default` (Target)
  - `EmploymentType`, `Education`, `MaritalStatus`, `Age`, `LoanDate`

---

## 📌 Report Pages & Visuals

### 📍 Page 1: Loan Default & Overview

![Loan Default & Overview]

**Key Visuals:**
- 🔹 Loan Amount by Purpose
- 🔹 Average Income by Employment Type
- 🔹 Default Rate by Employment Type
- 🔹 Average Loan Amount by Age Group
- 🔹 Default Rate by Year (%)

**Insights:**
- Highest loan amount issued for **home and business purposes**
- **Full-time employees** have the highest income and lowest default rates
- **Unemployed individuals** have the highest default rate (3.4%)
- **Adults (26–45)** take the largest loans on average

---

### 📍 Page 2: Applicant Demographics & Financial Profile

![Applicant Demographics & Financial Profile]

**Key Visuals:**
- 🔸 Median Loan by Credit Score Category
- 🔸 Loan Amount by Age Group & Marital Status
- 🔸 Total Loan by Credit Score Bins
- 🔸 Number of Loans by Education Type
- 🔸 Loan Amount by Dependents/Mortgage Status

**Insights:**
- Higher credit scores result in lower median loan amounts
- **Bachelor's degree holders** take the most loans
- Having **dependents or mortgage** has minimal impact on middle-aged adults’ loan volumes

---

### 📍 Page 3: Financial Risk Metrics

![Financial Risk Metrics]

**Key Visuals:**
- 🟣 YOY Loan Amount Change
- ⚪ YOY Default Loan Change
- 🔁 YTD Loan by Credit Score & Marital Status
- 🌐 Loan Distribution by Income Bracket & Employment Type

**Insights:**
- Significant growth in loan amounts observed in **2015 and 2018**
- YOY default trends fluctuate—spike observed in **2015** and **2018**
- **High-income full-time employees** contribute the highest loan volumes

---

## 💡 Business Takeaways

- **Default rates are closely tied to employment status and income level**
- **Education and credit score categories** reveal loan preference and approval trends
- **Monitoring YOY trends** helps anticipate credit risk and plan for future loan policies

---

## 🛠 Tools & Technologies Used

| Tool/Platform        | Purpose & Description                                                                 |
|----------------------|----------------------------------------------------------------------------------------|
| **Excel**            | Used to prepare and organize raw data before processing                               |
| **SQL**              | Employed for data transformation, cleaning,                                           |
| **Power BI Desktop** | Used to build visualizations and dashboards                                           |
| **Power BI Dataflows** | Workspaces created for data modeling and transformation in the cloud environment   |
| **Power Query (M)**  | Applied to clean and reshape the data in Power BI                                    |
| **DAX**              | Used to create calculated columns, measures, KPIs, and advanced metrics              |


---

## 📂 Project Structure

