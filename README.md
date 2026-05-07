## 📊 Project Overview
Comprehensive data analysis of coffee shop transactions across multiple NYC locations, including data cleaning, exploratory analysis, pivot table creation, and interactive dashboard development.

**Dataset**: Coffee shop transactions (Jan - June)
**Locations**: Astoria, Hell's Kitchen, Lower Manhattan
**Records**: 17,314 transactions | **Columns**: 18 dimensions

---

## 🎯 Objectives
- Clean and prepare raw transaction data
- Identify sales trends by location, hour, and day
- Analyze product category performance
- Create actionable visualizations for business insights

---

## 📁 Project Structure
```
coffee-shop-sales-analysis/
├── README.md                      # Project overview
├── data/
│   └── coffee_shop_sales.xlsx    # Raw and cleaned data
├── analysis/
│   ├── Data_Cleaning_Process.md  # Data preparation documentation
│   └── Analysis_Findings.md       # Key insights and findings
└── visualizations/
    ├── Dashboard_Overview.png     # Dashboard screenshot
    └── Sample_Charts.png          # Key charts
```

---

## 🔍 Key Findings

### Sales Performance
- **Total Revenue**: $10,523.26
- **Total Transactions**: 17,314
- **Average Bill**: $4.61
- **Top Location**: Astoria ($3,582.38)

### Peak Hours
- **Highest Traffic**: 11 AM - 2 PM (lunch hours)
- **Weekend Impact**: 30% lower transactions on Sundays
- **Best Day**: Tuesday (2,766 transactions)

### Product Analysis
- **Top Category**: Coffee ($4,250.70 revenue)
- **High-Margin Items**: Gourmet brewed coffee, Hot chocolate
- **Popular Sizes**: Large (660 transactions), Regular (721 transactions)

### Store Comparisons
- Astoria: Most consistent performance, high morning traffic
- Hell's Kitchen: Strong lunch hour performance
- Lower Manhattan: Balanced distribution, larger off-peak sales

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Excel** | Data cleaning, Pivot tables, Dashboard creation |
| **Formulas** | SUMIF, COUNTIF, VLOOKUP, Data validation |
| **Pivot Tables** | Cross-tabulation analysis, Trend analysis |
| **Charts** | Line, Column, Pie, Gauge charts |
| **Data Types** | Transaction ID, Date, Time, Location, Product category, Pricing |

---

## 📊 Analysis Breakdown

### Data Cleaning
- ✓ Date/Time parsing and normalization
- ✓ Category standardization
- ✓ Duplicate removal
- ✓ Missing value handling
- ✓ Derived fields (Hour, Day of Week, Month Name)

### Pivot Tables
1. **Sales by Hour** - 6 AM to 7 PM hourly breakdown
2. **Transactions by Day** - Weekly traffic patterns
3. **Revenue by Product Category** - Performance ranking
4. **Store Location Analysis** - Comparative metrics
5. **Size Distribution** - Product size preferences

### Dashboard Features
- **KPI Cards**: Total Revenue, Transaction Count, Avg Bill
- **Interactive Charts**: 
  - Hourly sales trend line
  - Category performance bar chart
  - Day-wise transaction distribution
  - Location comparison matrix
- **Filters**: Location, Product Category, Time Period

---

## 📈 How to Use the Files

### Opening the Excel File
1. Download `coffee_shop_sales.xlsx`
2. Enable macros/content if prompted
3. Navigate between sheets:
   - **Sheet1**: Raw data with all transactions
   - **Pivot**: Aggregated analysis and pivot tables
   - **Dashboard**: Interactive visualizations

### Key Sheets
- **Data Sheet**: Original 17,314 records with 18 columns
- **Pivot Tables**: Pre-calculated summaries for quick insights
- **Dashboard**: Visual analytics with charts and KPI metrics

---

## 🎓 Skills Demonstrated

**Data Analytics**
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Time-series analysis
- Categorical analysis

**Excel Advanced**
- Pivot table creation and configuration
- Conditional formatting
- Formula writing (IF, SUMIF, COUNTIF, etc.)
- Chart design and formatting
- Dashboard assembly

**Business Intelligence**
- KPI definition and tracking
- Trend identification
- Pattern recognition
- Data-driven insights

---

## 💡 Key Insights

1. **Peak Performance Window**: 11 AM - 2 PM generates 35% of daily revenue
2. **Location Strategy**: Astoria shows strongest consistency; consider staffing adjustments in Lower Manhattan
3. **Product Mix**: Coffee category dominates (40% revenue) - focus promotional efforts here
4. **Size Preference**: Large sizes preferred 3:1 ratio over small
5. **Weekly Patterns**: Midweek (Tues-Fri) outperforms weekends by 25-30%

---
