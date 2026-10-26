# 🍽️ Food App Data Analysis — Power BI Dashboard

## 📌 Project Overview

This project uses **Microsoft Power BI** to analyze food-app orders, restaurant performance, customer activity, revenue, ratings, and delivery performance.

The dashboard turns the food-app dataset into interactive reports that help explore business performance and identify areas that may need attention.

## 🎯 Objectives

- Track key business metrics such as revenue, orders, customers, and restaurants.
- Analyze restaurant performance by cuisine, city, and location.
- Explore customer activity and order patterns.
- Monitor delivery time, late orders, and cancellations.
- Compare KPIs over time using interactive visuals.

## 🛠️ Tools & Technologies

- **Power BI Desktop** — dashboard creation and visualization
- **Power Query** — data preparation and transformation
- **DAX** — measures and calculated columns
- **Microsoft Excel** — source dataset
- **GitHub** — project versioning and documentation

## 📂 Dataset

- **File:** `FOOD APP DATASET.xlsx`
- **Format:** Excel workbook
- **Contents:** Food-app order, restaurant, and customer-related data used by the dashboard

> The original dataset source was not identifiable from the Power BI file alone. Add the source link here if the dataset came from Kaggle or another website. If you redistribute the dataset, make sure its license allows it.

## 📊 Dashboard Pages

The Power BI report contains five pages:

### 1. General Overview Analysis Dashboard
Provides a high-level overview of business performance, including:
- Total Revenue
- Total Orders
- Total Customers
- Total Restaurants
- Average Order Value
- Revenue trends over time
- Revenue by online-order status
- Orders by delivery type
- Customer type and cuisine-level analysis

### 2. Restaurants Analysis Dashboard
Explores restaurant performance through:
- Average Rating
- Average Votes
- Revenue per Restaurant
- Repeat Customers
- Orders by cuisine
- Revenue by city and location
- Average cost for two people
- Revenue by online-order status

### 3. Customer Analysis Dashboard
Focuses on customer and order outcomes, including:
- Average Delivery Time
- Cancelled Orders and Cancellation %
- Late Orders
- Orders per Customer
- Cancelled and late orders by year
- City-level delivery and cancellation analysis

### 4. Advanced Insights
Supports deeper analysis using:
- A KPI selector with a dynamic KPI trend
- Quarterly KPI comparisons
- Restaurant-level comparisons
- Scatter plots to explore relationships between order value, date, and other fields

### 5. Restaurant Details
A drill-through page for exploring an individual restaurant, with:
- Restaurant name
- Average Rating and Average Votes
- Total Revenue
- Average Order Value
- Average Delivery Time
- Revenue trends and quarterly revenue growth

## 🧹 Data Preparation & Analysis

The report includes fields and calculations for analysis such as cleaned city values, cost categories, delivery status, order month/year, and KPI measures.

Data preparation and calculations should be described according to the steps actually performed in Power Query and DAX. Review the applied steps in Power Query before adding more specific claims here.

## 📈 Key Metrics

| Metric | Purpose |
|---|---|
| Total Revenue | Measures revenue across the selected data |
| Total Orders | Tracks order volume |
| Total Customers | Measures customer count |
| Total Restaurants | Measures restaurant count |
| Average Order Value | Shows average value per order |
| Average Rating | Summarizes restaurant ratings |
| Average Votes | Shows average customer votes |
| Average Delivery Time | Tracks delivery duration |
| Cancelled Orders | Counts cancelled orders |
| Cancellation % | Measures the cancellation rate |
| Late Orders | Tracks orders classified as late |
| Revenue per Restaurant | Compares revenue against restaurant count |
| Repeat Customers | Tracks returning customers |
| Revenue Growth % | Shows revenue growth over time |

## 🎛️ Interactive Features

- KPI selection and dynamic KPI trends
- Time-based analysis by date, month, year, and quarter
- Restaurant drill-through details
- Category and location comparisons
- Interactive Power BI filtering and cross-highlighting where supported by the report

## 🔍 Business Questions Explored

- How does revenue change over time?
- Which cuisines, cities, and locations contribute most to revenue or orders?
- How do online-order and delivery-type categories compare?
- How do ratings and votes vary across restaurants?
- How many orders are cancelled or delivered late?
- How does delivery performance vary by city?
- How do selected KPIs change across dates and quarters?

## 📁 Repository Structure

```text
FOOD-APP-DA-POWER-BI-PROJECT/
├── README.md
├── FOOD APP DA POWER BI PROJECT.pbix
└── FOOD APP DATASET.xlsx
```

## 🚀 How to Use

1. Clone or download this repository.
2. Open `FOOD APP DA POWER BI PROJECT.pbix` in **Power BI Desktop**.
3. If Power BI asks for the source file location, reconnect it to `FOOD APP DATASET.xlsx`.
4. Refresh the data if needed.
5. Explore the dashboard pages and interactive visuals.

## 👨‍💻 Author

**Saurav Kumar Singh**

- GitHub: [sauravverma3210-hub](https://github.com/sauravverma3210-hub)
- LinkedIn: [www.linkedin.com/in/saurav-kumar-3035a4383](https://www.linkedin.com/in/saurav-kumar-3035a4383)

---

*This project is intended for learning and portfolio demonstration. Dataset ownership and usage rights remain subject to the original dataset's license.*
