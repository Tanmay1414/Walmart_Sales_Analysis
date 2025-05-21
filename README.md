# Walmart_Sales_Analysis 🛒 
![image](https://github.com/user-attachments/assets/cb9a79de-643c-4218-9878-9e918721708c)

## 📊 Project Overview
This project explores and analyzes sales data from Walmart using SQL. The goal is to uncover insights related to customer behaviour, product performance, revenue trends, and operational metrics.

## 🧰 Tools & Technologies
- **Database**: MySQL
- **Language**: SQL
- **Dataset**: Walmart sales transactional data (`WalmartSalesData.csv`)

## 🗂️ Dataset Details
The dataset includes:
- Branch and city info
- Customer demographics (type, gender)
- Sales details (unit price, quantity, total)
- Temporal data (date, time)
- Product line and payment method
- Ratings and computed columns (gross margin, income)

## 🔍 Key Features & Analysis
- **Data Cleaning & Preprocessing**
  - Created columns for `time_of_day`, `day_name`, `month_name`
- **Exploratory Data Analysis**
  - Revenue trends by city, product line, and time
  - Sales performance across branches and customer types
  - Customer behavior analysis by gender, day, and time
  - Product line ratings and VAT distribution
- **Business Insights**
  - Identified peak sales times and top-performing product lines
  - Assessed branch-level performance
  - Analyzed correlations between customer types, revenue, and feedback

## 📈 Sample Insights
- Evening hours generate the most sales.
- Branch C has higher customer engagement.
- Product lines vary in performance by gender and time.
- Certain days (e.g., Friday) receive better average ratings.

## 📁 Files Included
- `WalmartSalesData.csv` – Raw sales dataset
- `SQL_queries.sql` – All SQL queries for analysis, cleaning, and transformation

## 📌 How to Use
1. Import `WalmartSalesData.csv` into MySQL.
2. Run `SQL_queries.sql` sequentially to recreate the full analysis.
3. Modify queries to perform additional EDA or generate new insights.

## 📬 Contact
For any suggestions or feedback, feel free to reach out via [GitHub Issues](https://github.com/your-username).
