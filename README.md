# Global SuperStore Business Intelligence Project

## 📊 Project Overview
This BI project analyzes sales performance for Global SuperStore (2012-2015) using Power BI. The solution transforms raw Excel data into interactive dashboards revealing key commercial insights across regions, product categories, and customer segments.

## 🔍 Key Features

### Data Pipeline
- **ETL with Power Query**:
  - Cleaned 3 Excel sheets (Sales, Returns, Personnel)
  - Fixed missing values, standardized formats
  - Added calculated columns (delivery time, fiscal periods)
- **Data Modeling**:
  - Star schema with Sales as fact table
  - Relationships to dimension tables (Products, Customers, Regions)

### Core Metrics (DAX)
- `Total Sales = SUM(Sales)` ($2.3M)
- `Total Profit = SUM(Profit)` ($286K)
- `Return Rate = DIVIDE(COUNT(Returns), COUNT(Orders))`

## 📈 Dashboard Highlights

### 1. Performance Overview
- **Geographic Map**: Sales concentration in Western US (CA, TX)
- **Time Trends**: Q4 sales spikes (+23% YoY)
- **Category Breakdown**: Technology leads revenue (42% share)

### 2. Regional Analysis
- **Comparative Bars**: CA favors tech, NY prefers office supplies
- **Dynamic Filters**: Drill-down by year/region
- **Profit Heatmap**: Corporate segment dominates in major cities

### 3. Operational Insights
- **Delivery Metrics**: Home offices experience 15% longer delays
- **Return Patterns**: Furniture has highest return rate (8.7%)

## 🛠️ Technical Stack
- **Tools**: Power BI (Power Query, DAX)
- **Data Source**: Excel (Global SuperStore.xlsx)
- **Model**: Star Schema with 1 fact + 4 dimensions

## 📂 Repository Structure

```
/Global_SuperStore_BI
├── Data/ # Original Excel files
├── Power BI Dashboard/ # PBIX files
├── Documentation/ # Project report (PDF)
└── README.md # This file
```

## 🎓 Academic Context
Developed as part of ENSA's Business Intelligence module (CI-ISBD/S8 - May 2025) under Prof. Hamid Hrimech's guidance.
*"Transforming raw data into strategic insights for retail decision-making."*
