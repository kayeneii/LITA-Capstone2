# LITA-Capstone2
This data analysis and report was created for the Ladies in Tech Africa (LITA).

[Overview](overview)
[Dataset](dataset)
[Methods](methods)
[Findings and Recommendations](findings-and-recommendations)
[Visualizations](visualizations)
[Conclusion](conclusion)


## Customer Segmentation for a Subscription Service 

### Overview
---
This project aims to analyze and report the customer data for a subscription service through the data provided, to identify segments and trends. The goal is to understand customer behavior, track subscription types, identify key trends in cancellations and renewals, and communicate these insights in a manner that best informs the decisions pertinent to the Subscription Service.


### Dataset
---
The dataset used in generating this report was the Customer Data.xlsx obtained from the _Ladies in Tech Africa_ Data Analysis Program. For more info, see [the Incubator Hub](http://www.theincubatorng.org/).


### Methods
---
The following tools were used in the creation of this report.
- **Microsoft Excel:** For data cleaning and preparation, initial exploration, and visualization.
  1. Data Cleaning and Preparation:
     - Data loading and inspection
     - Data cleaning and formatting

  2. Initial Exploration or Exploratory Data Analysis:
     This involved an exploration of the data to derive answers to questions such as,
     - What is the average subscription duration?
     - What is the most popular subscription type?
     - What is the regional revenue generated for each product?
     - What is the annual revenue per product?
     - What is the total number of customers per product?
     - Who are the top 10 customers?
     - What is the percentage revenue by region?

  3. Data Visualization: Pivot Tables was utilized in providing answers to the questions that surfaced during the initial data exploration. 

       
- **Microsoft Power BI:** For,
  1. Further Data Processing:
     - Data loading and quality inspection
     - Data transformation

  2. Analysis:
    During the analysis, additional columns were created using DAX functions. A Conditional Column titled Active Subscription;
    
     ```DAX
     If Canceled equals FALSE Then 1
     Else 0
     ```

  and a Custom Column called, No of Customer.

     ```DAX
     = [CustomerName] = 1     
     ```

      
  3. Data Visualizations: Matrices, Line, Pie and Donut Charts was used to visually plot out the subscription trend and other summarized data.

   
- **GitHUb:** For,
  1. Portfolio Building
  2. Communication


### Findings and Recommendations
---
1. **Findings:** The following key findings were made following a thorough analysis of the Customer Data based on the last entry in July, 
   - The total number of active subscribers fluctuated between 0 and 3,750.
   - The most popular subscription type is the 'Basic,' with a total number of 26,250 active subscribers and contributing approximately 50 per cent to the total revenue generated in 2023 and 2024.
   - Total number of active subscribers dropped to 15, 000 in 2024.
   - Total number of customers also dropped to 30, 000 in 2024.
   - Regional revenue ranged between 37.36 Million and 37.58 Million.
   - The annual revenue for each product in 2023 was: Basic, 44.9M; Premium, 22.5M; and Standard, 22.4M.
   - In 2024, the total revenue per product was: Basic, 29.8M; Premium, 15M; and Standard 15M.
   - The South generated the highest revenue at 38 Million.
   - Of the top 10 customers, 4 were from the West, 3 from the South, and 2 from the East. The North didn't make it to the ranks. 

2. **Recommendations:** Based on the above findings, it is recommended that,
   - a further research be made to better ascertain the cause of repeated cancelations.
   - a proper customer behavior analysis be conducted to better understand customer behavior;
   - the marketing and sales strategy be redesigned to properly reflect these customer behavior and interests;
   - attractive offers be created for the Premium and Standard products to boost sales;
   - regions be incentivized to encourage higher revenue generation and sales quota.


### Visualizations
---

### Conclusion
---
