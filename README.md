# E-commerce_Sales_Analysis

### Project Overview
This Data Analysis Project aims to Provide insight into the sales performance of Fintech based in Lagos, in the 2nd & 3rd quarters of the year 2021. By analysing various aspects of the sales data, 
we seek to identify trends, make data-driven recommendation and gain a deeper understanding of the company's performance.

### Data source
The Dataset used for this Analysis is the "Service Provider New version.xlsx" file
[Download here](https://github.com/user-attachments/files/17993088/Service.Provider.New.Version.working.Recovered.xlsx)

### Tools
- Excel - Data cleaning
   - [Download here](https://microsoft.com)
- MySQL- Data Analysis
- PowerBI- Data Visualization
  
### Data Cleaning
In the preparation of the dataset for analysis, we performed the following task:
1. Removal of the duplicates
2. Handled missing values with XLOOKUP
3. Changed values to their appropriate format

### Exploratory Data Analysis
The data was explored to answer key questions such as:
-What was the monthly sales trend?
-What were the top performing categories?
-What were the peak sales periods?

### Data Analysis

```MySQL
SELECT payment_date, Amount FROM service_provioder_table
Where category = 'betting'
```

### Dashboard

![Screenshot (5)](https://github.com/user-attachments/assets/984c7cc5-9dfb-4f9b-aa64-f0cc7fed5a30)
### Result/Findings
### Recommendations
