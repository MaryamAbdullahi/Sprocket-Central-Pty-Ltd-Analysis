# Sprocket Central Pty Ltd Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Result Findings](#result-findings)
  

### Project Overview

This project aims to identify all data quality issues in the dataset provided by Sprocket Central Pty Ltd, create an approach to identify the target customers based on the dataset provided and develop a dashbooard to display data summary and result of analysis.

### Data Sources

The primary dataset used for this analysisis is the "KPMG_VI_Module_3_Model_Work.csv" file, containing detailed information about the company.

### Tools

- Excel - Data Cleaning and creating reports
- Powerpoint - Presentation


### Data Cleaning/Preparation

  Dear Manager,
	I hope this message finds you well. I am writing to bring to your attention some data quality issues identified in the datasets provided by your client. The issues are mainly related to incomplete and inconsistent information and it is crucial that we address them to ensure the accuracy and reliability of our analysis.
1. Transaction Sheet

 - Blank cells in columns for online orders, brands, product line, product class, product size, standard cost and product first sold date.

 - The same set of customers has emptied the above-listed columns.
 
 - List price column changed to “Currency”.
 
 - 	Product first sold date changed to "Text”.

2. New Customer List Sheet

 - Blank cells in columns for last name, date of birth, and job title.
 
 - Different blank cells not filled by different customers.
 
 - Tenure and property valuation columns changed to "Text”.
 
 - Value column changed to "Currency”.

3. Customer Demographic Sheet

 - Blank cells and incomplete dataset in columns for last name, date of birth, job title, default, and tenure.

 - Incomplete dataset in the gender column (includes Femal, F, M, U).
 
 - Past 3 years bike-related column changed to "Text”.

4. Customer Address Sheet

 - All data in this dataset is complete.

It is recommended that we work on improving the data quality by:

- Identifying and contacting customers with missing information to fill in the blanks.

- Ensuring consistency in data types (e.g., keeping currency values as currency, dates as dates).

- Correcting incomplete or inaccurate entries in the datasets.

Addressing these issues will significantly enhance the reliability of our analysis and decision-making processes. Please let me know if you have any further instructions or if you would like to discuss this matter in more detail.

Thank you for your attention to this matter.

Best Regards,

Maryam Abdullahi.


### Results/Findings

This analysis focuses on data cleaning processes and result analysis of transaction, customer, and address sheets. The key findings indicate discrepancies in data formats, profit variations across brands and customer demographics. Recommendations include targeting female customers and emphasizing the sale of the WeareA2B brand.

1.Data Cleaning Process:

Transaction Sheet:

- Identified formatting issues in D.O.B, list price, and standard cost.
  
- Calculated profit by subtracting standard cost from list price.

New Customer List Sheet:

- Concatenated first and last names to create the full name.

Customer Demographic:
- Deleted the default column.
- Standardized the gender column.
-	Derived age from D.O.B, grouped into age ranges.

Customer Address Sheet:
- Abbreviated state names to VIC, QLD, and NSW.

2. Result Analysis:

Profit Analysis:

- WeareA2B brand generated the highest profit; Norco bicycles had the least.

- Customers aged 40-50 contributed the most profit, while 80-90 had the least.

Customer Demographic:

- Female customers showed a higher preference than males.
  
- Standard product line yielded the highest profit; mountain line had the lowest.

Time-Based Analysis:

- 2011 marked the highest profit, focusing on the top 10 years of the first purchase.

Age group Analysis:

- Females aged 40-50 made the highest bike purchases in the last 3 years.

Wealth Segment and Job Category:

- Mass customers in the wealth segment had the highest purchase rate.

- Manufacturing category showed the highest purchase, while telecommunication had the least.

3. Recommendations:

Target Market:

- Focus marketing efforts on female customers, considering their higher purchase rates.

Product Emphasis:

- Emphasize the sale of the WeareA2B brand, given its higher profitability and customer preference.

### Recommendation:
- The analysis provides valuable insights into customer demographics, product performance, and profit trends.
- Implementing the recommendations can enhance marketing strategies, potentially increasing overall profitability.
- Consider further analysis on customer preferences within specific demographics and explore strategies to expand the customer base.

