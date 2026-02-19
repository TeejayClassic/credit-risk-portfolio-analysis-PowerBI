# Credit Risk Portfolio Analysis & Risk Segmentation

## 1. Business Context

Financial institutions must continuously evaluate borrower risk exposure to maintain portfolio stability and minimize credit losses. 

This project presents a portfolio-level credit risk assessment focused on borrower leverage, income strength, and grade-based risk segmentation. The analysis evaluates whether deteriorating credit grades align with increasing financial stress indicators and identifies areas of potential portfolio vulnerability.

---

## 2. Project Objective

The primary objectives of this analysis were to:

- Assess overall loan portfolio exposure
- Evaluate borrower leverage using financial risk ratios
- Analyze income distribution across credit grades
- Identify risk concentration in lower-grade segments
- Validate the effectiveness of the loan grading framework

---

## 3. Dataset Overview

The dataset contains borrower-level financial and loan attributes, including:

- `loan_grade`
- `Person_income`
- `loan_interest_rate`
- `loan_to_income_ratio`
- `debt_to_income_ratio`
- `credit_utilization_ratio`
- demographic attributes (marital status, gender, home ownership)
- loan intent and geographic indicators

The data was cleaned and structured for analytical modeling in Power BI.

---

## 4. Methodology

### Step 1 – Data Preparation
- Validated ratio formats and standardized percentage fields
- Ensured consistent loan grade categorization
- Verified aggregation logic for exposure calculations

### Step 2 – Portfolio Exposure Analysis
- Total Loan Exposure
- Total Income
- Total Other Debt

This provided a high-level view of borrower financial strength relative to outstanding obligations.

### Step 3 – Risk Metric Calculation
Key financial ratios were evaluated:

- Average Debt-to-Income Ratio (DTI)
- Average Credit Utilization Ratio
- Average Loan-to-Income Ratio (LTI)
- Average Interest Rate

These metrics serve as indicators of borrower leverage, liquidity pressure, and risk-based pricing.

### Step 4 – Risk Segmentation by Grade
Risk metrics were segmented across loan grades (A–G) to evaluate structural differences in borrower risk profiles.

The analysis compared:
- Loan exposure by grade
- Income distribution by grade
- Average DTI by grade
- Average Interest rate by grade

---

## 5. Key Findings

### Portfolio Composition
Loan exposure is primarily concentrated within Grade A and B borrowers, indicating a relatively strong portfolio structure with limited high-risk concentration.

### Leverage Trend by Grade
Debt-to-income ratios increase progressively as loan grades deteriorate, reaching peak levels within lower-grade segments. This confirms elevated repayment pressure among weaker credit tiers.

### Income Strength Distribution
Higher income concentration is observed within Grade A and B borrowers, while lower grades exhibit weaker income profiles combined with higher leverage levels.

### Credit Utilization Risk
An average credit utilization ratio of approximately 50% suggests moderate borrower leverage across the portfolio, indicating potential liquidity pressure in certain segments.

### Underwriting Discipline
The average loan-to-income ratio remains conservative, suggesting disciplined lending relative to borrower income capacity.

---

## 6. Primary Risk Insight

The most significant observation from this analysis is the consistent increase in borrower leverage as loan grades deteriorate, combined with declining income strength across lower-grade segments.

Specifically:

- Debt-to-income ratios rise progressively from Grade A to Grade G.
- Lower-grade borrowers exhibit weaker aggregate income profiles.
- Higher leverage levels are structurally concentrated within weaker credit tiers.

This confirms that financial stress is not randomly distributed across the portfolio but is systematically concentrated within deteriorating credit grades. 

The alignment between rising leverage metrics and declining credit grades validates the effectiveness of the grading framework while highlighting structurally vulnerable borrower segments requiring closer monitoring.

---

## 7. Tools Used

- Power BI (Data Modeling & Visualization)
- DAX (KPI Calculations)
- Excel (Data Cleaning & Preparation)

---

## 8. Repository Structure

```
data/          → Raw and cleaned dataset  
dashboard/     → Power BI (.pbix) file  
report/        → Exported PDF version of dashboard  
images/        → Dashboard preview images  
```

---

## 9. Author

Tijani Ibrahim Olawale  
Aspiring Credit Risk Analyst | Power BI | SQL | Financial Analytics  

Open to opportunities in fintech, banking, and risk analytics.
