# 📊 Customer Behavior & Revenue Intelligence Dashboard

## Project Summary

The Customer Behavior & Revenue Intelligence Dashboard is an end-to-end Data Analytics project built using the Brazilian E-Commerce Public Dataset by Olist.
The project aims to transform raw transactional data into actionable business insights by analyzing revenue performance, customer behavior, delivery efficiency, and customer satisfaction.

Using Python for data cleaning and analysis and Power BI for visualization, the project delivers interactive dashboards that help stakeholders identify growth opportunities, monitor operational performance, and make data-driven business decisions.

---

## Business Problem

E-commerce businesses generate large volumes of transactional data, making it difficult to identify patterns and opportunities without proper analysis.

Key business challenges addressed in this project:

- Lack of visibility into revenue performance and sales trends.
- Limited understanding of customer purchasing behavior.
- Difficulty measuring customer satisfaction and its drivers.
- Inability to track delivery performance effectively.
- Revenue leakage caused by canceled and unavailable orders.
- Need for a centralized reporting solution for decision-making.

---

## Dataset Summary

### Dataset Source

Brazilian E-Commerce Public Dataset by Olist

### Tables Used

- Customers
- Orders
- Order Items
- Payments
- Products
- Reviews
- Product Category Translation

### Dataset Scale

- 100K+ Orders
- 96K+ Customers
- Multiple years of transaction history
- Nationwide customer and seller coverage across Brazil

### Data Modeling

A Star Schema data model was implemented in Power BI to ensure efficient reporting and accurate KPI calculations.

- Fact Tables:
  - Orders
  - Order Items
  - Payments
  - Reviews

- Dimension Tables:
  - Customers
  - Products
  - Calendar

---

## Dashboards

### Revenue Performance Dashboard

![Revenue Dashboard](images/revenue-dashboard.png)

#### Dashboard Focus

- Total Revenue Analysis
- Revenue Trends Over Time
- Revenue by Product Category
- Revenue by State
- Total Orders
- Total Customers
- Average Order Value (AOV)
- Revenue Loss Due to Failed Orders

---

### Customer Behavior Dashboard

![Customer Dashboard](images/customer-dashboard.png)

#### Dashboard Focus

- Customer Segmentation
- Review Score Analysis
- Customer Satisfaction Tracking
- Repeat Customer Analysis
- Late Delivery Analysis
- Lowest Rated Categories
- Lowest Rated States
- Impact of Delivery Delays on Reviews

---

## Tech Stack

### Data Analysis

- Python
- Pandas

### Business Intelligence

- Power BI
- DAX

### Data Modeling

- Star Schema Modeling
- Relationship Modeling
- Calendar Table

### Visualization

- Power BI

## Workflow

### 1. Data Preparation

- Imported and explored multiple datasets.
- Handled missing values and duplicates.
- Converted date columns into appropriate formats.
- Validated data quality and consistency.

### 2. Data Analysis

- Performed exploratory data analysis (EDA).
- Calculated business KPIs.
- Analyzed revenue, customer behavior, reviews, and delivery performance.

### 3. Data Modeling

- Designed a Star Schema model.
- Created relationships between fact and dimension tables.
- Developed a Calendar Table for time intelligence analysis.

### 4. Dashboard Development

- Built interactive Power BI dashboards.
- Developed DAX measures and KPIs.
- Created dynamic visualizations and filters.

---

## Insights & Business Decisions

### Revenue Insights

- Generated over R$16M in total revenue.
- Average Order Value reached approximately R$161.
- Revenue was concentrated among a small number of product categories.

### Customer Insights

- Most customers were one-time buyers.
- Repeat customer percentage remained relatively low.
- Customer retention presents a strong growth opportunity.

### Customer Satisfaction Insights

- Average review score remained above **4.0/5**.
- Customer ratings varied significantly across product categories.
- Satisfaction was strongly influenced by delivery performance.

### Delivery Insights

- Approximately **6.5%** of deliveries were delayed.
- Late deliveries consistently received lower review scores.

### Operational Insights

- Failed orders resulted in over **R$100K** in lost revenue.
- Improving fulfillment processes could significantly reduce revenue leakage.

### Business Recommendations

- Improve logistics performance to reduce delivery delays.
- Launch retention campaigns targeting one-time customers.
- Focus marketing efforts on high-performing categories.
- Investigate root causes of canceled and unavailable orders.
- Continuously monitor customer satisfaction trends.

---

## Conclusion

This project demonstrates how data analytics can transform raw e-commerce data into actionable business insights. By combining Python-based analysis, Power BI dashboarding, DAX calculations, and Star Schema modeling, the solution provides a comprehensive view of revenue performance, customer behavior, delivery efficiency, and customer satisfaction.

The dashboards enable stakeholders to make informed decisions, identify growth opportunities, and improve overall business performance through data-driven strategies.
