# Customer Service Request Analysis Dashboard
Service Request Trends & Performance (2021-2025)

# Introduction & Background
The goal of this analysis project is to gain insights into customer service requests by analyzing the running totals of closed and open cases per year. This will help end users better understand unresolved issues and identify trends in service requests. Additionally, this project serves as a demonstration of my skills and expertise in **Data Science and Power BI.**

I hope that this analysis provides valuable insights and potential opportunities for further improvements in customer service management.


# Business Ojbectives
This dashboard aims to answer the following key business questions:

- How many service requests were received this year compared to last year?
- What is the trend of service requests over time (by year and time of day)? Are they increasing or - decreasing?
- What is the total number of service requests and closed cases?
- What percentage of total service requests are closed?
- What is the most common service request type?
- What are the top 3 methods used to submit service requests (e.g., phone, app)?
- Which city department handles the most service requests?
- What percentage of service requests are closed, open, or transferred?
- How many cases are currently open?
- Are monthly closed cases meeting the target?
- What is the gap between closed cases and the target?


# Data Source & Methodology 

**Data Source:** The dataset for this analysis was sourced from [“Customer Service Requests | City of Seattle Open Data portal”](https://data.seattle.gov/City-Administration/Customer-Service-Requests/5ngg-rpne/about_data). The data was exported as a CSV file and transformed in Power BI.

**Data Cleaning:** 
- The dataset originally contained 16 columns; unnecessary and redundant ones were removed.
- Blank values were addressed using **mode imputation**, replacing missing values with the most frequently occurring value in the column.
- The **date and time column was split** intp separate columns for better time intelligence analysis.
- All columns were formatted correctly to prevent potential data discrepancies.

**Data Model:** The dataset follows a **flat file schema**, making it simple to analyze without requiring additional dimension tables.

**Analysis Approach:** 
-  **Power Query Editor** was used for data cleaning and transformation.
-  The **profiling tool** in Power Query was used to identify and fix potential data issues.
-  **Date and time lookup tables** were created for more accurate analysis.
-  **DAX measures and calculated tables** were created to support performance indicators (KPIs) and data Visualizations.

# Dashboard Features & KPIs

**Key Metrics:**
- **Total Service Requests**
- **Total Closed Cases**
- **Total Open Cases**
- **Monthly Cases vs Target**
- **% of Total Closed Cases**

**Visualizations:**
- **Bar Graphs** - Display the top 3 service request methods.
- **Line Graphs** - Show the distribution of total transactions by year and time category.
- **Treemap** - Visualize the proportion of total transactions by status.
- **Gauge Chart** - Display the percentage of closed cases vs. the target.


# Conclusion & Recommendations

**Summary:**

- **Seattle’s customer service request system has achieved a 70% closure rate** for service requests from 2021 to 2025, showing significant progress in resolving cases.
- **The "Find It, Fix It" app emerged as the most popular method for service requests**, with a total of **756K transactions** out of **956K requests**.
- **Most service requests were made during daytime hours**, as shown by the line graph analysis.
- **The most requested service type was "Abandoned Vehicle / 72-hour Parking Ordinance.**"
- **The Seattle Police Department (SPD) handled the highest number of service requests (232,830), closing 192,713 cases**. This department made a significant contribution to overall service performance in the city.

**Recommendations:**
- **Investigate the reasons behind unresolved cases: There are still 19K open cases (1.95% of total requests)** that have remained unresolved over the years. Further analysis should be conducted to understand the delays and potential obstacles to resolution.
- **Examine the rising trend in service requests:** The data shows a year-over-year increase in service requests. Possible contributing factors include:
  - Changes in policy implementation.
  - Population growth.
  - Increased customer dissatisfaction.
  - Repeat service requests from the same users.
  
Further investigation is needed to determine the root cause of this increase. Additional data collection, including customer feedback and service request history, can provide deeper insights.


# Dashboard

![Screenshot 2025-02-04 085116](https://github.com/user-attachments/assets/3e2fa93f-9eb0-4e10-bc21-84479d08c6ed)





