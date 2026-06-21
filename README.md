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

Before building the dashboard, I carefully reviewed and prepared the dataset to ensure the analysis was accurate, reliable, and ready for reporting. This step was essential in creating a solid foundation for meaningful insights and effective visualization.

During the data preparation process, I:

- Reviewed the dataset to understand its structure and identify potential data quality issues.
- Checked for missing, inconsistent, or inaccurate records and addressed them where necessary.
- Corrected data types to ensure fields were properly formatted for analysis.
- Standardized categorical values to maintain consistency across the dataset.
- Created calculated measures and key performance indicators (KPIs) using DAX.
- Structured and optimized the data model to support efficient reporting and dashboard performance.

By taking these steps, I ensured that the dashboard was built on clean, consistent, and well-structured data, enabling more accurate analysis of credit risk exposure, portfolio performance, and borrower risk trends.

---

## Data Analysis

I carried out these analysis in three key areas:

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

After analyzing the portfolio, I uncovered several interesting patterns and trends that helped paint a clearer picture of the loan portfolio and borrower behavior:

- **Grade B loans** make up the largest portion of the overall loan portfolio, indicating that a significant share of lending activity is concentrated within this risk category.
- Borrowers with **Grade A loans** contribute the highest total customer income, suggesting that higher-income customers tend to fall within the lowest-risk segment.
- **Education loans** emerged as the most common loan purpose, accounting for the largest share of loans in the portfolio.
- **Full-time employees** received the highest total loan amounts, highlighting their strong presence among approved borrowers.
- Loan allocation between **male and female borrowers** is fairly balanced, with no significant disparity in distribution.
- Among the cities analyzed, **Houston** recorded the highest total customer income, reflecting a strong concentration of high-earning borrowers.
- **Manchester, London, and Victoria** stand out as the cities with the highest loan volumes, making them key contributors to the overall portfolio.
- **Edinburgh** exhibited one of the highest Debt-to-Income (DTI) ratios, which may indicate a higher level of borrower financial strain and potential credit risk.

These insights provide valuable visibility into borrower demographics, lending patterns, geographic trends, and potential areas of risk within the portfolio.

---

## Recommendations

Based on the insights uncovered during the analysis, I identified several opportunities that could help improve portfolio performance and strengthen credit risk management:

### Strengthen Risk Monitoring

I recommend implementing closer monitoring for borrowers and locations with higher Debt-to-Income (DTI) ratios, as these segments may present a greater risk of default and potential credit losses.

### Refine Credit Assessment Processes

The analysis suggests that factors such as Debt-to-Income Ratio and Credit Utilization can provide valuable indicators of borrower risk. Giving these metrics greater consideration during the credit evaluation process could lead to more informed lending decisions.

### Prioritize Lower-Risk Borrower Segments

Expanding lending activities among financially stable borrowers may help improve overall portfolio quality while maintaining sustainable growth.

### Monitor Geographic Risk Trends

Regularly tracking loan performance across different cities can help identify emerging risk patterns early, allowing for more proactive portfolio management and risk mitigation.

### Maintain a Diversified Portfolio

Ensuring a balanced mix of loan grades, borrower profiles, and loan purposes can help reduce concentration risk and contribute to a more resilient and stable portfolio over time.

---

## Conclusion


Through this project, I developed an interactive Power BI dashboard that provides a comprehensive view of loan portfolio performance, borrower characteristics, and lending trends across different locations.

By analyzing key portfolio metrics, borrower profiles, and geographic patterns, I was able to uncover insights into lending behavior, portfolio composition, and potential areas of credit risk. The dashboard makes it easier to monitor performance, identify high-risk segments, and understand the factors influencing loan distribution across the portfolio.

Overall, this project demonstrates how data visualization and analytics can be used to transform raw lending data into actionable insights that support informed decision-making, stronger portfolio management, and more effective credit risk assessment.


