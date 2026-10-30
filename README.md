# Mini-project-PowerBI-visualization--DA
Mini project in PowerBI
# Project Work Summary – E-Commerce Customer Analysis

## 1. Data Preparation
- Imported the E-Commerce Customer Dataset into Power BI.
- Selected the `Data cleaned` worksheet.
- Checked missing values, duplicate records, and data types.
- Performed data preparation using Power Query.
- Created DAX measures for KPI calculations.

## 2. Dashboard 1 – Customer Demographics

**Cards:**
- Total Customers
- Average Customer Age
- Total City

**Charts and Fields Used:**
- **Clustered Bar Chart:** State – Customer Count.
- **Donut Chart:** Gender – Customer Count.
- **Clustered Column Chart:** Age_Group – Customer Count.
- **Treemap:** City – Customer Count.
- **100% Stacked Column Chart:** Age_Group, Gender – Customer Count.

**Slicers:** State, Gender, Customer_Tier.

## 3. Dashboard 2 – Customer Segmentation

**Cards:**
- Total Spending
- Total Orders
- Average Spending per Customer

**Charts and Fields Used:**
- **Stacked column Chart:** Customer_Tier, Gender – Customer Count.
- **Scatter Chart:** Total_Orders , Total_Spent , Customer_ID , Customer_Tier.
- **Ribbon Chart:** Registration_Date , Total_Spent, Customer_Tier.
- **Line Chart:** Age_Group , Average Total_Spent , Gender.
- **Funnel Chart:** Customer_Tier – Customer Count.

**Slicers:** Gender, Age_Group, Registration_Date.

## 4. Dashboard 3 – Customer Value & Geographic Insights

**Cards:**
- Total Customers
- Average Spending per Customer
- Average Orders per Customer

**Charts and Fields Used:**
- **Map:** State & city, Customer Count , Total_Spent and Total_Orders .
- **Area Chart:** Registration_Date , Customer Count.
- **Waterfall Chart:** Customer_Tier , Total_Spent.
- **Clustered Column Chart:** City , Average Total_Spent, Customer Count.
- **Matrix Heatmap:** Age_Group, Customer_Tier, Average Total_Spent.

**Slicers:** State, City, Customer_Tier.

- Created DAX measures using `DISTINCTCOUNT`, `SUM`, `AVERAGE`, and `DIVIDE`.
- Added interactive slicers to filter dashboard data.
- Analyzed customer demographics, spending behaviour, customer segmentation, registration trends, and geographic distribution.
