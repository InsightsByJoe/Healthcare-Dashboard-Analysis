# Healthcare Dashboard Analysis

## Project Overview
The **Healthcare Dashboard Analysis** project aims to provide an insightful overview of healthcare metrics by analyzing patient data across various demographics and medical conditions. The dashboard tracks key indicators such as the frequency of treated medical conditions, billing patterns by hospitals, insurance coverage, and gender distribution. This project serves as a tool for decision-making, enabling healthcare providers to understand trends and allocate resources efficiently. 

The analysis focused on visualizing patient data using **Microsoft Excel** to create a user-friendly dashboard, providing stakeholders with actionable insights.

![Healthcare dashboard](https://github.com/user-attachments/assets/36159fc5-7017-4c22-9a5a-ccd037fa3024)

### Key Objectives:
- Visualize medical conditions and billing across age groups.
- Analyze insurance coverage by age group.
- Examine hospital billing and doctor treatment trends.
- Understand blood group distribution and its correlation to treated conditions.
- Investigate average billing patterns by patient demographics.

## Data Source
The dataset used in this analysis can be found [here](https://github.com/eyowhite/Messy-dataset/blob/main/cleaned_healthcare_messy_data.csv).

## Tools Used
- **Microsoft Excel**:[Download here(https://microsoft.com) Data cleaning, visualization, and dashboard creation.
- **CSV File**: Raw dataset obtained from the above GitHub link.

## Process Overview
1. **Data Loading and Inspection**:
    - The dataset was first loaded into Excel.
    - A quick scan was performed to understand the basic structure, data types, and completeness.

2. **Removing Duplicates**:
    - All duplicate entries were identified and removed to avoid skewing the results.

3. **Data Cleaning**:
    - Handled missing values by either filling or removing them based on the context.
    - Ensured that numeric data like billing amounts and age were properly formatted.
    - Standardized age groups and medical condition categories.

4. **Analysis**:
    - Medical conditions were segmented by age groups (Young, Middle-Age, Old).
    - Billing patterns were analyzed across different hospitals and conditions.
    - Gender distribution was computed to understand demographic representation.
    - Blood group distribution was analyzed, linking it to condition frequency.

5. **Findings**:
    - **Top 5 Conditions**: Hypertension, Obesity, and Diabetes are the most treated conditions.
    - **Billing**: The middle-age group incurs the highest average billing.
    - **Hospital Billing**: Johnson PLC had the highest total billing across multiple conditions.
    - **Insurance Coverage**: The middle-age group has the highest insurance coverage, while the young age group is least covered.

## Results
- **Gender Distribution**: Males and females were almost equally represented in the dataset.
- **Medical Conditions by Age**: Middle-aged patients had the highest incidence of treated conditions.
- **Insurance Coverage**: Nearly half of the patients were middle-aged, followed by the old and young age groups.
- **Billing by Age**: Middle-aged patients incurred the highest average bills compared to younger and older patients.

## Recommendations
- **Targeted Preventive Care**: Focus on hypertension and obesity for middle-aged patients to reduce long-term costs.
- **Insurance Initiatives for Youth**: Increase insurance penetration among younger patients, as they are underrepresented.
- **Hospital Resource Allocation**: Allocate more resources to hospitals like Johnson PLC that handle higher billing and patient volumes.

## Limitations
- **Data Completeness**: Some records had missing data, which might affect the precision of the analysis.
- **Limited Scope**: The analysis was done using only available attributes in the dataset; further insights could be drawn if more variables, like geographic location or patient lifestyle, were included.
- **Static Dashboard**: The current dashboard is not interactive; future versions can leverage tools like Power BI or Tableau for dynamic insights.

## Conclusion
The analysis provides a comprehensive overview of healthcare utilization across demographics. The middle-aged population dominates the dataset in terms of medical conditions treated and billing amounts, with a focus on chronic conditions like hypertension and obesity. Hospitals and doctors with higher billing and patient volumes can benefit from improved resource allocation. Addressing the underrepresentation of the younger age group in insurance coverage and preventive care efforts for middle-aged patients could lead to significant cost savings and better health outcomes.

This dashboard serves as a valuable tool for healthcare administrators to make data-driven decisions. However, improvements in data quality, integration of more variables, and the use of interactive tools could further enhance the insights derived from this analysis.

## References
- Dataset used: [Cleaned Healthcare Messy Data](https://github.com/eyowhite/Messy-dataset/blob/main/cleaned_healthcare_messy_data.csv)
- Tools and Methodology: **Microsoft Excel** for data cleaning, visualization, and analysis.
- Other resources: General knowledge of healthcare data analysis, best practices for dashboard design, and Excel data manipulation techniques.


