# Mega Mart Sales Performance Analysis

## Project Overview
This project contains a comprehensive analysis of Mega Mart's sales performance data, providing insights into product performance, regional sales patterns, customer behavior, and profitability metrics. The analysis covers 300 sales transactions across multiple product categories, regions, and customer segments.

### Dataset Overview
- **Order Information**: Order ID, Date, Status
- **Customer Data**: Customer ID, Name, Segment, Region
- **Product Details**: Category, Name, Quantity, Unit Price
- **Financial Metrics**: Total Sales, Profit Amount, Profit Margin

## Key Findings

### 1. **Product Category Performance**
- **Electronics** leads with the highest total sales ($104,870.26) and 79 products
- **Furniture** follows closely with $102,547.52 in sales across 88 products
- **Clothing** generates $94,851.93 from 71 products
- **Groceries** contributes $89,539.42 from 62 products

### 2. **Regional Sales Distribution**
- **West Region**: $103,651.94 (28.5% of total sales)
- **South Region**: $102,874.07 (28.3% of total sales)
- **East Region**: $96,761.56 (26.6% of total sales)
- **North Region**: $88,521.56 (24.4% of total sales)

### 3. **Customer Segment Analysis**
- **Corporate** customers show the highest average profit margin at 18.20%
- **Retail** customers have a 17.56% profit margin
- **Wholesale** customers maintain a 17.55% profit margin

### 4. **Sales vs. Profit Correlation**
- Strong positive correlation (0.8219) between Total Sales and Profit Amount
- Higher sales volumes generally lead to increased profitability

### 5. **Order Size Distribution**
- Most common order quantities: 4 units (43 orders), 1 unit (33 orders), 8 units (33 orders)
- Order sizes range from 1 to 10 units, with balanced distribution across quantities

### 6. **Payment Method & Order Status Insights**
- **PayPal** shows the highest completion rate for orders
- **Cash** payments have the second-highest completion rate
- **Bank Transfer** and **Credit Card** show higher cancellation rates

## Project Structure

```
Mega Mart Sales/
├── megamart_sales_analysis.ipynb          # Exploratory data analysis 
├── megamart_sales_data_cleaning.ipynb     # Data cleaning and preprocessing
├── megamart_sales_cleaned_data.csv        # Cleaned dataset
├── megamart_sales.db                      # SQLite database
├── Megamart_Sales_Performance_Dataset.xlsx # Original dataset
├── megamart_dashboard.pbix                # Power BI dashboard
└── megamart_dashboard.pdf                 # Dashboard export
```

## Analysis Methodology

### Data Cleaning Process
- **Dataset Size**: 300 records with 15 columns
- **Data Quality**: No missing values or duplicates detected
- **Data Types**: Properly formatted with datetime, numeric, and categorical variables

### Analytical Approach
1. **Descriptive Statistics**: Category-wise performance analysis
2. **Regional Analysis**: Geographic sales distribution
3. **Temporal Analysis**: Monthly and daily sales patterns
4. **Customer Segmentation**: Profitability by customer type
5. **Correlation Analysis**: Sales-profit relationship
6. **Payment Analysis**: Order completion rates by payment method

## Key Insights for Business Strategy

### 1. **Product Strategy**
- Focus on Electronics and Furniture categories for revenue growth
- Consider expanding product offerings in high-performing categories
- Monitor Groceries category for potential optimization opportunities

### 2. **Regional Focus**
- West and South regions are primary revenue drivers
- North region shows potential for growth initiatives
- Consider regional marketing strategies based on performance

### 3. **Customer Relationship Management**
- Corporate customers provide the highest profit margins
- Develop targeted strategies for Retail and Wholesale segments
- Focus on customer retention in high-value segments

### 4. **Operational Improvements**
- Optimize order fulfillment processes to reduce cancellations
- Review payment method preferences and security measures
- Implement inventory management based on order size patterns

## Technical Details

### Technologies Used
- **Python**: pandas, numpy, matplotlib, seaborn
- **Database**: SQLite for data storage and querying
- **Visualization**: Matplotlib and Seaborn for charts and graphs
- **Data Processing**: Pandas for data manipulation and analysis

## Dashboard Features
The Power BI dashboard provides interactive visualizations for:
- Sales performance by category and region
- Sales peformance of products
- Sales trends over time
