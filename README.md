# Superstore-Business-Insights
Power BI dashboard analyzing sales performance, customer behavior, and operational insights with actionable business recommendations.

# 📊 Sales Performance & Business Insights Dashboard | Power BI

## 🔍 Project Overview
This project presents an end-to-end business analysis using Power BI to evaluate sales performance, customer behavior, product trends, and operational efficiency.  
The dashboard is designed to support data-driven decision-making by identifying key insights, business challenges, and actionable recommendations.

---

## 📂 Dataset Description
The dataset contains transactional sales data with the following key dimensions:
- Customers (Customer ID, Segment, Activity Status)
- Products (Category, Sub-Category, Product Name)
- Orders (Order Date, Ship Date, Order ID)
- Geography (Country, State, Region)
- Shipping (Ship Mode)
- Financials (Sales, Profit, Discount, Quantity)

---

## 🔧 Feature Engineering & Business Logic

To enable deeper customer and operational analysis, several calculated columns and business-driven features were created, including:

- **Customer Activity Status**: Classifies customers as Active or Inactive based on their last purchase date.
- **Order Frequency Segment**: Segments customers into Occasional, Regular, Frequent, and Very Frequent based on purchase behavior.
- **Calendar Dimensions**: Extracted date-based attributes (Year, Month, Day Type, ...) to support trend and seasonality analysis.
- **Customer Sales & Order Metrics**: Aggregated customer-level sales and order counts for behavioral analysis.
- **Delivery Days Calculation**: Calculated delivery duration between order and ship dates to evaluate operational performance.
- **Customer Type (Old vs New)**: Identifies new customers as those whose first purchase was within the last.
- **Order & Cohort Month**: Extracted directly from the Orders table to support trend, seasonality, and cohort analysis.

These features enabled cohort analysis, retention measurement, customer segmentation, and operational efficiency evaluation.


---

## 📌 Key KPIs
- Total Sales  
- Total Profit  
- Profit Margin  
- Number of Customers  
- Total Orders  
- Retention Rate  
- Churn Rate  
- Repeat Purchase Rate  
- Average Order Value (AOV)  
- Average Delivery Days  

---

## 📈 Dashboard Structure

### 1️⃣ Business Overview
Focuses on overall business performance and trends:
- Sales & Profit over time
- Sales by Category
- Geographical Sales Performance
- High-level financial KPIs

### 2️⃣ Customer Analysis
Analyzes customer behavior and engagement:
- Retention & Churn Rates
- Repeat Purchase Behavior
- Customer Activity Status
- Customer Cohort Analysis
- Order Frequency Segmentation

### 3️⃣ Product & Operations Insights
Evaluates product performance and operational efficiency:
- Sales by Category & Sub-Category
- Top Products by Sales
- Weekend vs Weekday Sales
- Shipping Mode Performance
- Average Delivery Time

---

## 💡 Key Business Insights
- Low profit margin due to some high-sales products/orders being unprofitable.  
- High customer churn and risk of losing top customers.
- Heavy reliance on existing customers, limited new customer acquisition.
- Revenue is concentrated in specific regions and customer segments  
- Technology category is the top revenue contributor  
- Delivery performance is acceptable but can be optimized, especially for standard shipping  

---

## 🚀 Business Recommendations
- Optimize pricing and discount strategies to improve profitability  
- Implement retention and loyalty programs to reduce churn  
- Focus marketing efforts on high-margin and high-performing products  
- Improve delivery efficiency and encourage faster shipping options
- Focus on high-margin and high-demand products; bundle slow-moving items. 
- Expand sales presence in underperforming regions  

---

## 📊 Dashboard Preview
Take a look at the Power BI dashboard screenshots:
![Dashboard Overview](Dashboards/Page1.png)  
*Figure 1: Overview of sales performance and KPIs*

![Customer Insights](Dashboards/Page2.png)  
*Figure 2: Customer behavior*

![Product & Operations Insights](Dashboards/Page3.png)  
*Figure 3: Product & Operations Insights*

---

## 🎯 Conclusion
The dashboard highlights that while the business demonstrates strong revenue and repeat purchase behavior, there are clear opportunities to enhance customer retention, profit optimization, and operational performance through targeted, data-driven strategies.

---

## 👤 Author
**Merna Hatem**  
Data Analyst  
