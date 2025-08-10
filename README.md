<p align="center">
  <img src="https://img.shields.io/badge/Tool-Jupyter-orange?logo=jupyter&logoColor=white" alt="Jupyter Badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Completed Badge" />
</p>

<h1 align="center">Exploratory Data Analysis (EDA) - Python Mini Project</h1>
<p align="center"><em>Graded assignment for the Data Science &amp; Business Analytics Program by IIT Guwahati</em></p>

---

## Learning Outcomes Addressed
- Understand the purpose and importance of Exploratory Data Analysis (EDA) in data science.
- Apply statistical summaries and visualizations to describe the key features of a dataset.
- Identify data patterns, correlations, and anomalies through graphical and quantitative methods.
- Formulate and test hypotheses based on EDA findings to inform further analysis.
---
# TO ASSIST DATASET 
## 📊 Dataset

This project uses a dataset hosted on Kaggle.  
You can access it [here](https://www.kaggle.com/datasets/kanakbaghel/retail-transactions-dateset/data).

---

## Introduction
A nationwide retail chain is exploring customer behavior and seasonal trends to improve its strategic decision-making. You have been hired as a data analyst to help the company uncover actionable insights from a sample of past transaction records. The leadership team is particularly interested in patterns related to purchases, customer segments, promotional impact, and seasonal performance. 

---

## Data Description
You are provided with a CSV file titled 'Retail_Transactions_Dataset.csv'. Each row corresponds to a unique customer transaction. Below are the columns available in the dataset: 
| Column Name         | Description                                      |
|---------------------|--------------------------------------------------|
| Transaction_ID      | Unique identifier for each transaction           |
| Date                | Timestamp of the transaction                     |
| Customer_Name       | Name of the customer                             |
| Product             | List of items bought in the transaction          |
| Total_Items         | Number of different items purchased              |
| Total_Cost          | Total cost paid by the customer                  |
| Payment_Method      | Mode of payment used                             |
| City                | City in which the transaction took place         |
| Store_Type          | Type of store (e.g., Supermarket, Warehouse Club)|
| Discount_Applied    | Whether a discount was used                      |
| Customer_Category   | Segment the customer belongs to                  |
| Season              | Season in which the transaction happened         |
| Promotion           | Type of promotion applied, if any                |
---

## Task to be performed
Conduct a comprehensive analysis of the retail dataset to address critical business questions. 

### Task 1: Data Preparation 
- Read the CSV file. 
- Parse and convert the Date column into appropriate format. 
- Extract additional useful information like Year, Month, or DayOfWeek from the Date. 
- Clean and preprocess the data if required. 
### Task 2: Basic Exploration 
- How many total transactions are there? 
- How many unique customers are in the dataset? 
- What are the top 5 most common products sold across all transactions? 
- Which cities have the highest number of transactions? 
### Task 3: Customer Behavior Analysis 
- Which customer categories spend the most on average? 
- Do certain customer categories prefer specific payment methods? 
- What is the average number of items bought per transaction per store type? 
### Task 4: Promotion & Discount Impact 
- What is the average cost of transactions where a discount was applied vs not applied? 
- Compare the average number of items purchased for different promotion types. 
- Which promotion type seems to be most effective in terms of increasing total cost? 
### Task 5: Seasonality Trends 
- Which season has the highest total revenue? 
- Are there seasonal preferences for certain store types or product categories? 
- Create a plot showing average spending per season. 
### Task 6: Visualization Dashboard 
- Bar plot of number of transactions per city 
- Pie chart showing distribution of payment methods 
- Line chart of monthly revenue trends (grouped by year if applicable) 
- Heatmap or stacked bar showing revenue by season and customer category 
---
## Reflections of Performing Tasks

---
<img width="891" height="419" alt="image" src="https://github.com/user-attachments/assets/e74aa587-3ad7-436e-a2ec-9c5a8c51b5c5" />
<p align="center"><strong>--- Retail Transactions Dataset ---</strong></p>

---
<img width="881" height="631" alt="image" src="https://github.com/user-attachments/assets/7e3366b3-eb07-485c-8a58-9e0c4edbe61a" />
<p align="center"><strong>--- Plot average spending per season ---</strong></p>

---
<img width="871" height="732" alt="image" src="https://github.com/user-attachments/assets/44c893de-ece8-45f3-a688-0673e1e12f79" />
<p align="center"><strong>--- Heatmap showing revenue by season and customer category ---</strong></p>

---
> _“Data becomes meaningful when it tells a story that leads to better decisions.”_  
<p align="center"><em>Crafted with ♥ by <strong>Kanak Baghel</strong> | <a href="https://www.linkedin.com/in/kanakbaghel">LinkedIn</a></em></p>
