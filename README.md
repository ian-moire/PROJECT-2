# PROJECT-2
DASHBOARD LINK (https://public.tableau.com/app/profile/ian.moire/viz/ehealth_facilities/Dashboard1)

PRESENTATION LINK (https://docs.google.com/presentation/d/1_sZAPgVsAzKIJ_sRDUna8udZ7g7zCOX8-kTxzqpN-GA/edit?usp=sharing)
# Analysis of Healthcare Facility in Kenya

## Background
The healthcare sector in Kenya is rapidly evolving, with an increasing demand for quality healthcare services and improved health outcomes. The management and analysis of healthcare data are essential to enhance service delivery, optimize resource allocation, and ensure equitable access to healthcare services across the country. This project aims to provide insights into the distribution and characteristics of healthcare facilities in Kenya.

## Objective
The objective of this project is to analyze the healthcare facilities in Kenya, focusing on their geographic distribution, ownership, operational status, and key metrics such as the number of beds and cots. The analysis aims to identify trends and patterns for improvement in the healthcare sector.

## Data Description
The dataset used for this project, ehealth_facilities_repaired.xls, which was found on the openAFRICA website, contains data on 10,505 healthcare facilities in Kenya. The dataset includes various attributes such as facility code, name, province, county, district, type, owner, location details, number of beds and cots, operational status, and availability of specific services. The dataset also contains some columns with missing values, which were addressed during the data cleaning process.

## Methodology
### 1.Data Cleaning and Preprocessing:

-->Dropped columns with zero non-null values.

-->Imputed missing values for numerical columns using the median.

-->Imputed missing values for categorical columns using the mode.

-->Verified data consistency and completeness.

### 2.Exploratory Data Analysis (EDA):

-->Analyzed key statistics and distributions of numerical and categorical variables.

-->Visualized the geographic distribution of healthcare facilities across provinces and counties.

-->Examined the distribution of facility ownership and operational status.

-->Created visualizations to compare key metrics such as the number of beds and facility types.

### 3.Data Visualization:

-->Used Python libraries (Matplotlib, Seaborn) to create visualizations.

-->Generated histograms, bar plots, and count plots to effectively communicate findings.

## Significance
The analysis of healthcare facility data in Kenya provides valuable insights into the current state of the healthcare sector. The findings can help healthcare administrators make informed decisions to improve healthcare services.
## Summary of Key Findings
1. **Geographic Distribution**:
     The distribution of healthcare facilities varies significantly across different provinces and counties in Kenya. Certain regions have a higher concentration of facilities, while others are underserved.
2. **Facility Ownership**:
     The majority of healthcare facilities are owned by specific categories, such as public and private entities. The distribution of ownership provides insights into the management and operation of these facilities.
3. **Operational Status**:
     Most facilities are operational, with a few marked as non-functional. This information helps understand the readiness and availability of healthcare services in different regions.
  
## Implications
The findings can inform policymakers and healthcare administrators about regions that require more resources and attention. Addressing disparities in facility distribution can improve healthcare access and equity. Understanding the operational status of facilities can help optimize resource utilization. Efforts can be directed towards reviving non-functional facilities or enhancing the capacity of existing ones.

## Limitations
The dataset contained missing values and potential inaccuracies, which were addressed to the best of my ability. However, some residual issues may remain that could affect the analysis. The analysis focused on the available data and did not account for other potential factors influencing healthcare facility distribution and service availability, such as socio-economic conditions or patient demand.

## Future Work
Continuously improve the data quality by addressing any remaining issues and validating the accuracy of the dataset. Incorporate additional datasets and factors, such as patient outcomes, socio-economic data, and healthcare infrastructure, to provide a more comprehensive analysis. Develop specific policy recommendations based on the findings to guide decision-makers in improving healthcare services and resource allocation.
