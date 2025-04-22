# Healthcare_Analysis

### Table of Contents:
- [Project Overview](#project-overview)
- [Business Objective](#business-objective)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Understanding](#data-understanding)
- [KPIs](#kpis)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Power BI Optimization](#power-bi-optimization)
- [Data Analysis (Power BI Visuals)](#data-analysis-power-bi-visuals)
- [Screenshot](#screenshot)
- [Project Insights](#project-insights)
- [Recommendations](#recommendations)
- [How to Use This Report](#how-to-use-this-report)
- [Contact](#contact)

### Project Overview:
This project is a Power BI healthcare dashboard that analyzes billing, cost, insurance coverage, and patient data. It includes demographic-based filtering, billing trends, and key procedure insights. Interactive visuals help identify cost patterns and operational metrics.

### Business Objective:
Healthcare providers often struggle to track treatment costs, procedure-based billing, and patient liability. This dashboard aims to provide a clear breakdown of medical billing and insurance metrics across departments and procedures. It also helps identify high-billing months and cost-heavy services. Ultimately, this improves financial transparency and supports strategic planning.

### Data Source:
The dataset contains 8 CSV files:
  - Fact Table: visit.csv
  - Dimension Tables: cities.csv, department.csv, diagnoses.csv, insurance.csv, patients.csv, procedures.csv, providers.csv

### Tools Used:
  - Microsoft Excel (Data Cleaning)
  - Power BI (Modeling, Analysis & Visualization)

### Data Understanding:
  - The dataset captures details of hospital visits, including visit ID, date, and service type (inpatient, outpatient, emergency).
  - It includes patient demographics such as gender, race, and location (linked through city and provider tables).
  - Medical procedures performed during visits are tracked, such as MRI, X-ray, and blood tests.
  - Financial metrics include billing amount, medication cost, treatment cost, room charges, insurance coverage, and patient liability.
  - Data spans across multiple years, allowing time-based analysis, with racial segmentation for demographic-based insights.

### KPIs:
  1. What are the total medication cost, total treatment cost and total billing amount?
  2. What are the average of total medication cost, total treatment cost and total billing amount per patient?
  3. Which department generated the highest billing?
  4. What’s the gender distribution?
  5. How does insurance coverage vary by race?
  6. Which procedure is most common?
  7. What’s the monthly billing trend?
  8. What’s the billing amount by service type?
  9. Which city and state has the most visits?
  10. Interactive Dashboard [View Dashboard](https://github.com/user-attachments/assets/583ecc3f-f3b5-41ed-98b2-4ff4657b5edd)

### Data Cleaning:
  1. Removed irrelevant columns for optimization
  2. Handled missing values in key fields
  3. Columns were formatted to ensure consistent date/time formats
  4. Corrected data types for text, numeric fields and dates
  5. Created new calculated columns (e.g., Year, Month, Customer Age)

### Exploratory Data Analysis:
  - Analyzed the distribution of hospital visits across different service types—emergency, inpatient, and outpatient.
  - Explored cost patterns by breaking down billing amount, treatment, and medication costs by department and procedure.
  - Identified high-billing procedures like MRI, CT scan, and X-ray contributing significantly to overall costs.
  - Assessed demographic insights, such as gender split (nearly equal) and race-based service utilization.
  - Examined monthly billing trends to spot peak and low activity periods, aiding resource planning.

### Power BI Optimization:
To improve the performance and efficiency of my Power BI report, I applied the following best practices:
  1. **Used a star schema:** Structured the data model with fact and dimension tables instead of flat tables to reduce redundancy and optimize query performance.
  2. **Removed unnecessary columns and rows:** Imported only the required columns and filtered out irrelevant rows to minimize memory usage and improve refresh speed.
  3. **Turned off Auto Date/Time:** Disabled the Auto Date/Time feature to prevent Power BI from creating unnecessary hidden date tables that impact performance.
  4. **Optimized DAX by using measures:** Replaced calculated columns with DAX measures wherever possible to improve calculation performance and reduce memory load.

### Data Analysis (Power BI Visuals):
  - Card visuals for callout and reference KPIs
  - Donut chart for gender ratio
  - Stacked bar charts for billing by procedure and department
  - Line chart for billing trend by month
  - 100% stacked chart for service type by diagnosis

Snap of Healthcare Analysis Dashboard

![Image](https://github.com/user-attachments/assets/583ecc3f-f3b5-41ed-98b2-4ff4657b5edd)

### Screenshot:

Snap of Star Schema

![Image](https://github.com/user-attachments/assets/ddf5bca0-3c91-405a-be49-286a6a040072)

### Project Insights:
  - January sees the highest billing activity
  - MRI, CT, and X-ray contribute most to costs
  - Cardiology and orthopedics departments drive top billing
  - Hypertension and appendicitis are common high-billing diagnoses
  - Gender distribution is almost equal

### Recommendations:
  - **Optimize Resource Allocation:** Increase staffing and operational readiness during peak billing months (e.g., January, March, April) to ensure efficient patient care and service delivery.
  - **Review Insurance Coverage Policies:** Conduct periodic reviews of insurance coverage limits, particularly for high-cost procedures such as MRI and CT scans, to reduce patient liability and financial strain.
  - **Enhance Departmental Efficiency:** Implement process improvements in high-billing departments like Cardiology and Orthopedics to streamline workflows and reduce unnecessary costs.
  - **Strengthen Outpatient Service Management:** Improve scheduling, patient flow, and billing processes in outpatient services to increase throughput and enhance patient experience.
  - **Implement Data-Driven Financial Planning:** Leverage data insights from billing trends and diagnosis patterns to inform budgeting, pricing strategies, and future healthcare service investments.

### How to Use This Report:
  - **Utilize Interactive Filters:** Apply the slicers for Year and Race to segment the data and analyze demographic-specific and time-based healthcare trends.
  - **Monitor Key Performance Indicators (KPIs):** Review the KPI cards for a quick overview of essential metrics such as total costs, average charges, insurance coverage, and patient liability.
  - **Analyze Procedure and Diagnosis Trends:** Examine the stacked bar and 100% stacked visuals to assess billing contributions across various procedures, diagnoses, and service types.
  - **Evaluate Departmental and Monthly Patterns:** Use visual insights to identify high-performing departments and recognize billing fluctuations throughout the year for operational planning.
  - **Support Decision-Making with Data:** Leverage insights from patient demographics, cost distribution, and billing trends to inform policy adjustments, resource allocation, and financial strategies.

### Contact:
For further information or inquiries regarding this project, feel free to reach out:
  - Email     : pauljohnson2094@gmail.com
  - LinkedIn  : www.linkedin.com/in/pauljohnson2094
  - GitHub    : https://github.com/pauljohnson20



