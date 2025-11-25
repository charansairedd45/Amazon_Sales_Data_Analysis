# 🛒 Amazon Sales Data Analysis - SQL Project

## 📋 Project Overview

This project demonstrates advanced SQL querying and data analysis techniques using Amazon sales data. It covers 20 comprehensive business problems ranging from basic sales analysis to complex analytical queries involving window functions, CTEs, subqueries, and stored procedures.

## 🎯 Project Objectives

- Analyze sales performance across different product categories and regions
- Identify customer purchasing patterns and lifetime value
- Optimize inventory management through stock analysis
- Evaluate shipping and payment performance metrics
- Implement automated inventory management using stored procedures

## 🗂️ Database Schema

The project uses a relational database with the following tables:

- **customers** - Customer information (ID, name, email, state, registration date)
- **sellers** - Seller details
- **category** - Product categories
- **products** - Product information (ID, name, category, price, COGS)
- **orders** - Order details (ID, date, customer, seller, status)
- **order_items** - Individual items in orders (product, quantity, price)
- **payments** - Payment information (ID, order, status, amount)
- **shippings** - Shipping details (provider, dates, delivery status)
- **inventory** - Stock levels (product, warehouse, quantity, last restock date)

## 🔍 Business Problems Solved

### 📊 Sales Analysis
1. **Top Selling Products** - Identify top 10 products by sales value
2. **Revenue by Category** - Calculate revenue contribution by category
3. **Monthly Sales Trend** - Analyze month-over-month sales patterns
4. **Revenue Decrease Analysis** - Compare YoY revenue changes

### 👥 Customer Analysis
5. **Average Order Value (AOV)** - Compute AOV for customers with 5+ orders
6. **Customer Lifetime Value (CLTV)** - Rank customers by total purchase value
7. **Customers with No Purchases** - Identify inactive registered users
8. **Customer Segmentation** - Categorize customers as Returning vs New
9. **Top Customers by State** - Top 5 customers per state by order volume
10. **Cross-Sell Opportunities** - Identify product pairing opportunities

### 📦 Inventory & Operations
11. **Inventory Stock Alerts** - Products below reorder threshold
12. **Orders Pending Shipment** - Paid but unshipped orders
13. **Shipping Delays** - Orders with 3+ day shipping delays
14. **Inactive Sellers** - Sellers with no sales in 6 months

### 💰 Financial Analysis
15. **Product Profit Margin** - Calculate and rank profit margins
16. **Payment Success Rate** - Analyze payment status distribution
17. **Revenue by Shipping Provider** - Performance metrics by carrier
18. **Most Returned Products** - Top 10 products by return rate

### 🏆 Performance Analysis
19. **Top Performing Sellers** - Top 5 sellers with success rates
20. **Least-Selling Categories by State** - Underperforming categories

### ⚙️ Automation
**Stored Procedure** - Automated inventory update on product sale

## 💡 Key SQL Techniques Used

- ✅ **Aggregate Functions** - SUM, COUNT, AVG, MAX, MIN
- ✅ **Window Functions** - ROW_NUMBER, RANK, DENSE_RANK, LAG, LEAD
- ✅ **Common Table Expressions (CTEs)** - For complex query organization
- ✅ **Subqueries** - Nested and correlated subqueries
- ✅ **Joins** - INNER, LEFT, RIGHT joins across multiple tables
- ✅ **Date Functions** - DATEDIFF, YEAR, MONTH, DATE_ADD
- ✅ **Conditional Logic** - CASE statements
- ✅ **String Functions** - CONCAT_WS
- ✅ **Stored Procedures** - Automated inventory management
- ✅ **Transaction Handling** - Data integrity in procedures

## 📁 Project Structure

```
Amazon_Sales_Data_Analysis/
│
├── Data/                    # SQL scripts for database setup
│
├── Problems.md             # 20 business problems with descriptions
│
├── Solution.md             # Complete SQL solutions with screenshots
│
└── README.md               # Project documentation (this file)
```

## 🚀 Getting Started

### Prerequisites
- MySQL 8.0 or higher (or compatible RDBMS)
- Basic understanding of SQL and relational databases

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/charansairedd45/Amazon_Sales_Data_Analysis.git
cd Amazon_Sales_Data_Analysis
```

2. **Set up the database**
- Create a new database: `CREATE DATABASE amazon_analysis;`
- Import the data from the `Data/` folder
- Execute table creation and data insertion scripts

3. **Run the queries**
- Open `Problems.md` to understand each business problem
- Check `Solution.md` for complete SQL solutions
- Execute queries in your MySQL environment

## 📊 Sample Insights

Based on the analysis, key findings include:

- **Top product categories** contribute to majority of revenue
- **Customer segmentation** reveals returning vs new customer patterns
- **Shipping delays** identified for operational improvement
- **Inventory alerts** help prevent stockouts
- **Profit margin analysis** guides pricing strategy
- **Payment success rates** indicate payment gateway performance

## 🛠️ Technologies Used

- **Database**: MySQL 8.0
- **Query Language**: SQL
- **Tools**: MySQL Workbench, DBeaver (or any SQL client)

## 📈 Skills Demonstrated

- Advanced SQL querying and optimization
- Data analysis and business intelligence
- Database design and normalization
- Stored procedure development
- Performance metrics calculation
- Complex join operations
- Window function mastery

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/charansairedd45/Amazon_Sales_Data_Analysis/issues).

## 👤 Author

**Charan Sai Reddy**
- GitHub: [@charansairedd45](https://github.com/charansairedd45)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/charan-reddy-a1520a32b/)

## 📝 License

This project is open source and available for educational purposes.

## 🌟 Acknowledgments

- Inspired by real-world e-commerce analytics challenges
- Thanks to the SQL community for best practices
- Special thanks to everyone who provides feedback

---

⭐ **If you find this project helpful, please consider giving it a star!** ⭐

**Happy Querying! 🚀**
