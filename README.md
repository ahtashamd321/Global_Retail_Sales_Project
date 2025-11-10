# Global Retail Sales Analysis

A comprehensive business intelligence solution for analyzing global retail sales performance, leveraging transactional data to calculate key performance indicators (KPIs) and visualize sales, profit, and customer metrics.

## 📋 Overview

This project provides interactive dashboards and analytics to help identify trends, top performers, and areas for improvement across the retail business. Built with Microsoft Power BI, it transforms raw sales data into actionable insights.

## 🎯 Key Performance Indicators (KPIs)

The dashboard tracks and visualizes the following core business metrics:

| KPI | Calculation | Purpose |
|-----|-------------|---------|
| **Total Sales** | Sum of all sales amounts | Overall revenue performance |
| **Total Profit** | Sum of profit for all orders (Sales - Cost) | Bottom-line profitability |
| **Average Profit Margin** | (Total Profit / Total Sales) × 100 | Efficiency of operations |
| **Total Orders** | Count of orders placed | Sales volume indicator |
| **Total Quantity Sold** | Sum of all quantities sold | Inventory movement |
| **Average Order Value (AOV)** | Total Sales / Total Orders | Transaction value metric |
| **Average Quantity per Order** | Total Quantity / Total Orders | Basket size metric |
| **Average Rating** | Sum of ratings / Number of ratings | Customer satisfaction |
| **Return Rate** | (Returned Orders / Total Orders) × 100 | Product quality indicator |

## 📊 Data Source

The analysis uses **`Retail_Sales.csv`**, which contains detailed transactional records with the following structure:

### Data Schema

| Column | Description |
|--------|-------------|
| `Order_ID` | Unique order identifier |
| `Order_Date` | Transaction timestamp |
| `Customer_Name` | Customer identification |
| `Segment` | Customer type (Consumer, Corporate, Home Office) |
| `Country` | Country of sale |
| `Region` | Geographic region |
| `City` | City of sale |
| `Category` | Product category (e.g., Electronics, Furniture) |
| `Sub_Category` | Product subcategory |
| `Product_Name` | Specific product name |
| `Sales_Channel` | Channel (Online, Retail Store, Wholesale) |
| `Sales_Rep` | Sales representative name |
| `Sales` | Transaction sales amount |
| `Cost` | Product cost |
| `Profit` | Transaction profit (Sales - Cost) |
| `Return_Status` | Whether order was returned |
| `Return_Reason` | Reason for return (if applicable) |
| `Customer_Rating` | Customer satisfaction score |

## 🛠️ Tools and Technologies

- **Business Intelligence**: Microsoft Power BI
- **Data Format**: CSV
- **Main Files**:
  - `Dashboard.pbix` - Power BI dashboard file
  - `Retail_Sales.csv` - Source data file

## 📈 Dashboard Visualizations

The Power BI dashboard includes the following interactive visualizations:

### Performance Analysis
- **Total Profit by Quantity** - Bubble chart showing product/category performance based on volume and profitability
- **Sales by Category** - Bar chart comparing sales across major categories (Electronics, Furniture, Home & Kitchen)
- **Top 10 Products by Sales** - Bar chart highlighting best-selling products

### Sales Team Performance
- **Top 10 Sales Reps** - Horizontal bar chart ranking representatives by total sales

### Channel Analysis
- **Profit by Sales Channel** - Donut chart detailing profit contribution from each channel (Online, Retail, Wholesale)

### Trend Analysis
- **Sales & Profit Over Time** - Combined line and area chart displaying temporal trends (year-over-year or month-over-month)

### Geographic Insights
- **Geographic Performance Map** - Interactive map showing profit by region
- **Top 10 Countries by Sales** - Bar chart of highest-performing countries

### Customer Segmentation
- **Sales by Customer Segment** - Column chart and donut chart showing distribution across Consumer, Corporate, and Home Office segments

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (latest version recommended)

### Installation
1. Clone this repository or download the project files
2. Ensure `Retail_Sales.csv` is in the same directory as `Dashboard.pbix`
3. Open `Dashboard.pbix` with Power BI Desktop

### Usage
1. Open the Power BI file to view pre-built dashboards
2. Use interactive filters to drill down into specific:
   - Time periods
   - Geographic regions
   - Product categories
   - Customer segments
   - Sales channels
3. Export reports as needed for presentations or further analysis

## 📁 Project Structure

```
global-retail-sales-analysis/
├── README.md
├── Dashboard.pbix          # Power BI dashboard file
└── Retail_Sales.csv        # Source data file
```

## 💡 Key Insights

This dashboard helps answer critical business questions:
- Which products and categories drive the most revenue and profit?
- How do sales channels compare in terms of profitability?
- Who are the top-performing sales representatives?
- What are the geographic trends in sales performance?
- How do customer segments differ in purchasing behavior?
- What is the quality of customer experience (ratings, returns)?
- How have sales and profit trends evolved over time?

## 🔄 Data Refresh

To update the dashboard with new data:
1. Replace `Retail_Sales.csv` with updated file (maintaining the same schema)
2. Open `Dashboard.pbix` in Power BI Desktop
3. Click **Refresh** in the Home ribbon
4. Save the updated dashboard

## 📝 Notes

- Ensure data consistency in the CSV file (matching column names and data types)
- The dashboard is optimized for monthly and quarterly analysis
- Custom date ranges can be applied using Power BI's built-in filters

## 🤝 Contributing

Contributions to enhance the dashboard or add new visualizations are welcome. Please ensure any modifications maintain data integrity and follow Power BI best practices.


## 📧 Contact

[ahtashamd321@gmail.com]

