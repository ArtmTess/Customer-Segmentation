# Customer-Segmentation
Customer Segmentation analysis

## Content:
1. [Project Overview](#Project_Overview)
2. [Data Source](#Data_Source)
3. [Analysis_Process](#Analysis_Process)
   3.1 [Tools](#Tools)
   3.2 [Python_code_and_output](#Python_code_and_output)
   3.3 [Data_Cleaning_and_Preparation](#Data_Cleaning_and_Preparation)
   3.4 [Exploratory_Data_Analysis](#Exploratory_Data_Analysis)
5. [Results](#Results)

## Project_Overview
In this project was performed clustering on customer records from a food retailer's database. 
Customer segmentation is dividing customers into groups that reflect the similarities between the customers in each cluster.

## Data_Source
The primary dataset used for this analysis is the "marketing_campaign.csv" and can be downloaded [here] (https://github.com/ArtmTess/Customer-Segmentation/blob/main/marketing_campaign.csv)
This dataset includes 29 columns, which provide comprehensive details about customer demographics, spending habits, campaign responses, and engagement.

## Analysis_Process
### Tools
- Python Notebook in [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/code/anastasiaartemova/customer-segmentation-analysis)) was used for Data Analysis.
- Data Analysis Expressions (DAX) and M language Data Cleaning and Clastering Customers;
- Data Visualization was performed via Power BI.

### Python_code_and_output
Python code for data analysis can be checked [here] ([https://www.kaggle.com/code/anastasiaartemova/customer-segmentation-analysis](https://github.com/ArtmTess/Customer-Segmentation/blob/main/customer-segmentation-analysis.ipynb))
  

### Data_Cleaning_and_Preparation
In the data preparation phase the performed steps: 
- Data loading and data exploration.
- Handling errors / missing values: performed filtering out rows with year <=1900 year(3 rows), with empty income (24 rows) as final got 2213 rows for analysis. 
- Data cleaning, and formatting: calculated age of customers and divided by age groups; calculated family size; formatted educational level and total spending.

  
### Exploratory_Data_Analysis
- Distribution of clients' income by education level, age, and family size. 
- Amount spent by product categories
- Number of purchases made through various channels.
- Comparing web visits vs web purchases

### Results
- The average age of the analyzed cohort of customers is 55 years old (from Python code). In Power BI, I divided customers into three groups by age: 40-60, >60, and <40.
- The maximum income belongs to the group of customers 40-60 years.
- The maximum income by family size falls on families consisting of 2–3 people.
- By education level, the maximum income belongs to customers who  graduated and the minimum for undergraduates.
- Customers spent maximum for wines and meat. The minimum was spent on fruits, on the same level of sweets, and a little more on fish.
- Most purchases (46%) were made via a store, 33% via a website, and 21% via a catalog.
- Visiting the website resulted in a purchase in 77% of cases.
![Screenshot 2025-02-23 174430](https://github.com/user-attachments/assets/3f526f49-2a7e-45b2-8884-68044b37273f)



