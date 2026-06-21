# 📊 Credit Risk Portfolio Analysis Using Power BI

## Table of Contents

* [Project Overview](#project-overview)
* [Business Problem](#business-problem)
* [Project Objectives](#project-objectives)
* [Dataset Description](#dataset-description)
* [Tools Used](#tools-used)
* [Data Cleaning & Preparation](#data-cleaning--preparation)
* [Data Analysis](#data-analysis)
* [Dashboard Pages](#dashboard-pages)
* [Key Insights & Findings](#key-insights--findings)
* [Recommendations](#recommendations)
* [Conclusion](#conclusion)

---

## Project Overview

This project focuses on analyzing a credit risk portfolio to understand lending patterns, borrower characteristics, and potential risk factors within the loan portfolio.

Using Power BI, I developed an interactive dashboard that provides insights into portfolio performance, borrower demographics, and geographic lending trends. The analysis was designed to help stakeholders identify areas of risk, understand borrower behavior, and support more informed lending decisions.

---

## Business Problem

Financial institutions must strike a balance between growing their loan portfolio and managing credit risk. Poor lending decisions can lead to higher default rates, increased financial losses, and reduced profitability.

The challenge is to identify patterns within the portfolio that can help lenders better understand who they are lending to, where risk is concentrated, and which segments contribute most to overall portfolio performance.

This analysis was conducted to provide visibility into key lending metrics and uncover insights that can support effective credit risk management.

---

## Project Objectives

The primary objectives of this project were to:

* Evaluate overall loan portfolio performance.
* Analyze borrower demographics and borrowing behavior.
* Assess key credit risk indicators across loan grades.
* Identify geographic trends in lending activities.
* Highlight areas of potential risk exposure.
* Provide recommendations to support data-driven lending decisions.

---

## Dataset Description

The dataset contains information on loan applicants and approved loans, including borrower demographics, financial indicators, and loan characteristics.

### Key Fields

* Customer Income
* Loan Amount
* Loan Grade
* Interest Rate
* Debt-to-Income Ratio (DTI)
* Credit Utilization
* Education Level
* Employment Type
* Gender
* Marital Status
* Loan Purpose
* Country
* State
* City

---

## Tools Used

| Tool            | Purpose                               |
| --------------- | ------------------------------------- |
| Power BI        | Dashboard Development & Visualization |
| Power Query     | Data Cleaning & Transformation        |
| DAX             | KPI Creation & Calculated Measures    |
| Microsoft Excel | Source Data Management                |

---

## Data Cleaning & Preparation

Before building the dashboard, the dataset was reviewed and prepared to ensure accuracy and consistency.

The preparation process included:

* Validating data quality and completeness
* Reviewing records for inconsistencies
* Correcting data types where necessary
* Standardizing categorical fields
* Creating calculated measures and KPIs using DAX
* Structuring the dataset for efficient reporting and analysis

---

## Data Analysis

The analysis was carried out across three key areas:

### Portfolio Performance Analysis

This section focused on evaluating the overall health of the loan portfolio using metrics such as:

* Total Customer Income
* Total Loan Amount
* Average Interest Rate
* Average Credit Utilization
* Average Debt-to-Income Ratio

### Borrower Analysis

This section examined borrower demographics and borrowing behavior, including:

* Education Level
* Employment Type
* Gender Distribution
* Marital Status
* Average Income per Borrower
* Average Loan per Borrower

### Geographic Analysis

This section explored lending activity across different locations to identify regional trends and risk exposure.

Key areas analyzed include:

* Loan Distribution by City
* Income Distribution by City
* Geographic Coverage
* Debt-to-Income Ratio by City

---

## Dashboard Pages

### Executive Dashboard

The Executive Dashboard provides a high-level overview of portfolio performance and risk indicators.

<img width="100%" alt="Executive Dashboard" src="Image/Executive Dashboard.png">

#### Key Metrics

* Total Customer Income
* Total Loan Amount
* Average Debt-to-Income Ratio
* Average Credit Utilization
* Average Interest Rate

#### Visualizations

* Loan Distribution by Grade
* Income Distribution by Grade
* Loan Distribution by Purpose
* Interest Rate Analysis by Loan Grade

---

### Borrowers Analysis

The Borrowers Analysis page focuses on understanding the composition of the borrower base.

<img width="100%" alt="Borrowers Analysis" src="Image/Borrowers analysis.png">

#### Visualizations

* Loan Distribution by Education Level
* Loan Distribution by Gender
* Loan Distribution by Marital Status
* Loan Distribution by Employment Type

#### KPIs

* Total Borrowers
* Average Loan per Borrower
* Average Income per Borrower
* Average Credit Utilization

---

### Geographic Analysis

The Geographic Analysis page provides insights into regional lending activities and risk concentration.

<img width="100%" alt="Geographic Analysis" src="Image/Geographic analysis.png">

#### Visualizations

* Geographic Loan Distribution Map
* Top Cities by Loan Amount
* Top Cities by Customer Income
* Top Cities by Debt-to-Income Ratio

#### KPIs

* Total Countries
* Total States
* Total Cities
* Average Interest Rate

---

## Key Insights & Findings

Several notable insights emerged from the analysis:

* Grade B loans account for the largest share of the overall loan portfolio.
* Grade A borrowers generate the highest total customer income.
* Education-related loans represent the largest loan category within the portfolio.
* Full-time employees receive the highest share of total loan amounts.
* Loan distribution between male and female borrowers is relatively balanced.
* Houston records the highest customer income among the cities analyzed.
* Manchester, London, and Victoria rank among the cities with the highest loan volumes.
* Edinburgh shows one of the highest Debt-to-Income ratios, indicating elevated borrower risk.

---

## Recommendations

### Strengthen Risk Monitoring

Borrowers and locations with higher Debt-to-Income ratios should be monitored more closely to reduce potential credit losses.

### Enhance Credit Assessment Criteria

Debt-to-Income Ratio and Credit Utilization should play a more significant role in lending decisions and risk evaluation.

### Focus on Lower-Risk Borrower Segments

Expanding lending activities within financially stable borrower groups may help improve overall portfolio quality.

### Implement Geographic Risk Monitoring

Regular monitoring of city-level performance can help identify emerging risk patterns and support proactive decision-making.

### Maintain Portfolio Diversification

A balanced distribution of loan grades and borrower segments can help reduce concentration risk and improve long-term portfolio stability.

---

## Conclusion

This project provides a comprehensive view of loan portfolio performance, borrower characteristics, and geographic lending patterns through an interactive Power BI dashboard.

By combining portfolio metrics, borrower analysis, and geographic insights, the dashboard helps identify key drivers of performance and areas of potential risk. The findings can support better lending decisions, improved portfolio management, and more effective credit risk monitoring.


