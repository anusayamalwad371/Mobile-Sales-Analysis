# Mobile Sales Analysis - Power BI Project

## 1. Project Overview
This is a Power BI dashboard project analyzing mobile sales data. The dashboard provides insights into sales, profit, brands, models, and regional performance to help in business decision making.

## 2. Dataset
File: mobile_sales.csv
Columns: Date, Brand, Model, RAM, Storage, OS, Price, Quantity, Total_Sales, Profit, Region, Rating

## 3. Tools Used
- Power BI Desktop
- Power Query (for Data Cleaning)
- DAX (for Measures)

## 4. Data Cleaning in Power Query
- Removed duplicates and null values
- Changed Date format to Date type
- Created new columns: `Year = YEAR(Date)`, `Month = MONTH(Date)`, `Price_Range`

## 5. DAX Measures
dax
Total Sales = SUM('Sales'[Total_Sales])
Total Profit = SUM('Sales'[Profit])
Units Sold = SUM('Sales'[Quantity])
Profit Margin = DIVIDE([Total Profit], [Total Sales])

## 6. Key Insights

Apple & Samsung = Highest Revenue
8GB/128GB = Most selling configuration
North Region = Top in sales
Q4 = Highest sales season.

## 7. Conclusion

This Power BI dashboard provides a complete 360° view of mobile sales performance, helping to track top products and profitable regions for better business planning.

## 8. Author

[ Malwad Anusaya ] 
| Power BI Project |
| Pune | 




