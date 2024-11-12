# *LITA-Class-Documentation*

### *Project Title: E commerce Sales Analysis*

[Project Overview](#project-overview)

[Data Sources](#data-sources) 

[Tools Used](#tools-used) 

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

### *Sales Performance and Customers Analysis*
------------
### *Project Overview*
-------------

During the process of this project, I focused on two main areas:
1. Sales Performance Analysis for a retail store

2. Customer Segmentation for a subscription based service

The goal was go deeper into each data set to find insights on sales trend, customers behavior and regional performance. To achieve this,i used SQL,EXCEL and Power BI to analyze my data and visualize the findings.

### *Data Sources* 
---------------

For this project, I worked with two datasets:
- **Sales Data**: Details on transactions, products,regions and revenue.

- **Customer Data**: Informations about customer,their start and end dates,their revenue, subscription and cancellation status. 

### *Tools Used*
----------

- SQL Server: I used sql queries to transform data,clean, explore. Extracting key insights directly from the database.
  
- Excel: I loaded the data into excel for exploration. Using pivot tables,i summarized matrice like total sales by products, months and regions

- Power BI: I built an interactive power bi dashboard to visualize the findings and enable further explorations.

### *Data Cleaning and Preparations*
----------------

### Step 1: Data Preparation 
 I started by loading both datasets into SQL server. After some basic data cleaning, i was able to generate some calculated fields that could help with my analysis.
 
 In Excel,i added a few additional calculations such as monthly trends and average sales by products. Doing this above mentioned gave me a quick overview of what the data looked like before diving into detailed queries.
   
### Step 2: SQL Analysis
----------------

Using SQL queries, I stumbled on various key questions,such as;

- How many transactions occured in each region?
- What are the top selling products and highest revenue regions?
- Which subscription type was the most popular?
- How long on average did customer's stay subscribed?

I explored the third and the fourth question based on the subscription of data

### Step 3: Building the POWER BI dashboard 

From my knowledge in SQL,i moved to power Bi to create a dashboard. I visualized the key metrics: 

- Sales Performance:

```SQL
SELECT * FROM TABLE1
WHERE CONDITION = TRUE
```

### *Data Visualization* 

https://github.com/Boluwatife312/LITA-Class-Documentation/blob/main/Text%20Cleaning%202%20Assignment.jpg

### *How to create a table*

|Table 1|Table 2|Table 3|Table 4|
|---------|---------|---------|---------|
|**Name**|**Age**|**Subject**|**Score**|
|*Temi*|16|*Chemistry*|39|
|*Grace*|15|*Maths*|70|
|*Kathy*|17|*English*|90|
|*Tope*|17|*Physics*|56|
