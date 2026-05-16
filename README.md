# UPI Transactions Power BI Dashboard

## Overview
Interactive Power BI dashboard for analyzing UPI transaction data with dynamic visualizations and KPI insights. This professional dashboard provides comprehensive transaction analysis, balance tracking, and customer behavior insights using advanced Power BI features.

## Project Objective
- Analyze UPI transaction patterns and trends throughout the year
- Understand customer transaction behavior and preferences
- Create interactive dashboards for data-driven decision-making
- Implement dynamic filtering with 10 synced slicers for efficient analysis
- Build KPI-based insights using DAX calculations
- Track balance fluctuations and financial patterns
- Enable multi-perspective data analysis

## Tools Used
- **Microsoft Power BI Desktop** - Dashboard development and visualization
- **Power Query** - Data cleaning and transformation
- **DAX (Data Analysis Expressions)** - Custom calculations and metrics
- **Excel Dataset** - Data source

## Dataset Information
The dataset contains comprehensive UPI transaction data with the following columns:
- Transaction ID - Unique identifier for each transaction
- Date & Time - Transaction timestamp
- Amount - Transaction value
- Customer Age - Age of customer performing transaction
- Customer Name - Name of transaction initiator
- Payment Type - Method of payment
- Status - Transaction status (Success/Failed)
- Bank Name Sent - Sending bank details
- Bank Name Received - Receiving bank details
- City - Location of transaction
- Device Type - Device used for transaction
- Gender - Gender of customer
- Merchant Name - Merchant information
- Payment Method - Specific payment method used
- Purpose - Transaction purpose
- Transaction Type - Type of transaction

### Data Preparation
The dataset was thoroughly cleaned and transformed using Power Query:
- Removed unnecessary date values
- Separated date and time columns for better granularity
- Created Age Group categories (A1, A2, A3) using DAX
- Applied data validation and standardization
- Handled missing values and outliers
- Formatted currency and date fields appropriately

---

## Dashboard Features

### Pages
- **Page 1: Charts Dashboard** - Interactive line and column chart visualizations
- **Page 2: Matrix Dashboard** - Structured transaction data analysis in tabular format

### Interactive Elements
- **10 Synced Slicers** for filtering across all pages:
  1. Bank Name Sent
  2. Bank Name Received
  3. City
  4. Device Type
  5. Gender
  6. Age Groups
  7. Merchant Name
  8. Payment Method
  9. Purpose
  10. Transaction Type
- **KPI Cards** for key performance indicators
- **Matrix Visualization** for detailed data analysis
- **Line Charts** for trend visualization
- **Column Charts** for comparative analysis
- **Bookmarks** for quick navigation between views

### Key Metrics (KPIs)
- Total Transactions - Count of all UPI transactions
- Total Amount Transacted - Sum of all transaction amounts
- Average Transaction Value - Mean transaction amount
- Number of Customers - Unique customer count
- Transaction Count by Type - Breakdown by transaction type

---

## Dashboard Visualizations

### Visualization 1: Transactions by Month (Line Chart) - Year 2024

![Dashboard](![Dashboard](https://raw.githubusercontent.com/Harish-Uta17/UPI-Payment-Analytics-Dashboard/main/screenshots/Line%20Chart%20Amounts.png)

**Purpose:** Track transaction amount trends throughout the year

**Key Features:**
- Monthly transaction amounts displayed as line graph
- 12-month view from January to December 2024
- Interactive data points showing exact amounts
- Synced slicers allow filtering by bank, city, device type, gender, age groups, and more

**Peak Values:**
- **May 2024:** 1,707K (Highest transaction volume)
- **January 2024:** 1,679K
- **October 2024:** 1,691K
- **Lowest Month:** July 2024 at 1,599K

**Insights:**
- Transaction volume shows seasonal variation
- Mid-year (May) shows the highest activity
- Summer months (July) show dip in transactions
- Year-end recovery visible in September onwards
- Average monthly transactions: ~1.66M

---

### Visualization 2: Transactions by Month (Column Chart) - Year 2024

![Column Chart](https://raw.githubusercontent.com/Harish-Uta17/UPI-Payment-Analytics-Dashboard/main/screenshots/Column%20Chart%20Amounts.png)

**Purpose:** Comparative monthly transaction analysis with quick visual reference

**Key Features:**
- Monthly transactions displayed as vertical bars
- Purple color scheme for visual clarity
- Exact amounts labeled above each column
- Easy month-to-month comparison
- Responsive to all slicer selections

**Monthly Values:**
- **January:** 1.68M
- **February:** 1.69M
- **March:** 1.62M
- **April:** 1.66M
- **May:** 1.71M (Peak)
- **June:** 1.65M
- **July:** 1.61M
- **August:** 1.60M
- **September:** 1.67M
- **October:** 1.69M
- **November:** 1.64M
- **December:** 1.65M

**Insights:**
- Consistent transaction range of 1.60M - 1.71M
- May shows strongest performance
- Relatively stable distribution across year
- No extreme volatility observed
- Strong recovery in Q4

---

### Visualization 3: Balance by Month (Line Chart) - Year 2024

![Line Chart Balance](https://raw.githubusercontent.com/Harish-Uta17/UPI-Payment-Analytics-Dashboard/main/screenshots/Line%20Chart%20Balance.png)

**Purpose:** Monitor account balance trends and financial position throughout the year

**Key Features:**
- Balance amounts displayed as area line chart
- Filled area visualization for easy trend identification
- Monthly balance values with data point labels
- Shows financial liquidity patterns
- Area shading highlights balance ranges

**Peak Values:**
- **June 2024:** 8,536K (Highest balance)
- **April 2024:** 8,442K
- **August & September:** 8,433K (Plateau period)
- **May 2024:** 8,222K (Lowest balance)

**Balance Pattern Analysis:**
- Starting balance (January): 8,232K
- Shows significant fluctuations throughout year
- Peak in June indicates strong cash position
- May dip correlates with high transaction volume
- Year-end balance (December): 8,429K
- Average balance maintained: ~8,382K

**Insights:**
- Inverse relationship between transactions and balance
- June high balance suggests seasonal deposits
- May low balance indicates high transaction outflow
- Stable balance range: 8.2M - 8.5M
- Financial health remains consistent

---

### Visualization 4: Balance by Month (Column Chart) - Year 2024

![Column Chart Balance](https://raw.githubusercontent.com/Harish-Uta17/UPI-Payment-Analytics-Dashboard/main/screenshots/Column%20Chart%20Balance.png)

**Purpose:** Month-to-month balance comparison for financial planning and analysis

**Key Features:**
- Balance amounts displayed as vertical bars
- Purple columns for easy identification
- Consistent month labels on X-axis
- Exact balance values labeled on each bar
- Uniform column heights indicate stability

**Monthly Balance Values:**
- **January:** 8.2M
- **February:** 8.4M
- **March:** 8.3M
- **April:** 8.4M
- **May:** 8.2M
- **June:** 8.5M (Highest)
- **July:** 8.3M
- **August:** 8.4M
- **September:** 8.4M
- **October:** 8.4M
- **November:** 8.3M
- **December:** 8.4M

**Balance Analysis:**
- Tight range between 8.2M - 8.5M indicates stable finances
- No significant balance depletion observed
- June peak (8.5M) shows maximum financial capacity
- Consistent funding throughout the year
- Suitable for monthly budgeting and planning

**Insights:**
- Financial stability maintained throughout year
- Balance variations are minor (±1-2%)
- Predictable pattern for cash flow management
- Adequate reserves for operational needs

---

## Dashboard Pages Explained

### Page 1: Charts Dashboard
The Charts Dashboard provides visual analysis through interactive charts and comprehensive filtering options.

**Components:**
- **Slicer Row 1:** Bank Name Sent, Bank Name Received, City, Device Type, Gender
- **Slicer Row 2:** Age Groups, Merchant Name, Payment Method, Purpose, Transaction Type
- **Chart Selection Buttons:** Toggle between Line/Column charts for Transactions and Balance
- **Multiple View Options:**
  - Line Chart Amounts (Transaction trends)
  - Column Chart Amounts (Transaction comparison)
  - Line Chart Balance (Balance trends)
  - Column Chart Balance (Balance comparison)

**Features:**
- All slicers synced across pages
- Real-time data updates on filter selection
- Interactive legends (click to show/hide series)
- Hover tooltips for detailed values
- Professional color schemes (blue for transactions, purple for balance)

**How to Use:**
1. Select your desired filter values from any slicer
2. All visualizations update automatically
3. Click chart buttons to switch between different views
4. Analyze trends or compare values based on your selection
5. Use bookmarks to save specific filtered views

---

### Page 2: Matrix Dashboard
The Matrix Dashboard provides detailed transactional data in a structured, tabular format.

**Components:**
- Same slicer configuration as Page 1 (synced)
- Matrix visualization with rows, columns, and values
- Supports sorting and filtering within table
- Shows transaction details in organized format
- Drill-down capabilities for deeper analysis

**Features:**
- Structured data presentation
- Sortable columns and rows
- Aggregated values with subtotals
- Responsive to all slicer selections
- Professional formatting

**How to Use:**
1. Use slicers to filter specific transaction types
2. Click column headers to sort data
3. Expand grouped rows for detailed breakdown
4. Review totals and subtotals
5. Export data if needed for further analysis

---

## Slicers (10 Total) - Detailed Guide

### 1. Bank Name Sent
- **Type:** Dropdown filter
- **Purpose:** Filter transactions by sending bank
- **Use Case:** Analyze outgoing transfers from specific banks
- **Default:** All

### 2. Bank Name Received
- **Type:** Dropdown filter
- **Purpose:** Filter transactions by receiving bank
- **Use Case:** Analyze incoming transfers to specific banks
- **Default:** All

### 3. City
- **Type:** Dropdown filter
- **Purpose:** Filter transactions by geographic location
- **Use Case:** Regional analysis of transaction patterns
- **Default:** All

### 4. Device Type
- **Type:** Dropdown filter
- **Purpose:** Filter by device used (Mobile, Desktop, etc.)
- **Use Case:** Understand device preferences for transactions
- **Default:** All

### 5. Gender
- **Type:** Dropdown filter
- **Purpose:** Filter by customer gender
- **Use Case:** Gender-based transaction analysis
- **Default:** All

### 6. Age Groups
- **Type:** Dropdown filter
- **Purpose:** Filter by customer age category
- **Use Case:** Age-based behavioral analysis
- **Values:** A1 (≤25), A2 (≤35), A3 (>35)
- **Default:** All

### 7. Merchant Name
- **Type:** Dropdown filter
- **Purpose:** Filter by merchant information
- **Use Case:** Analyze transactions with specific merchants
- **Default:** All

### 8. Payment Method
- **Type:** Dropdown filter
- **Purpose:** Filter by payment method (UPI, Card, etc.)
- **Use Case:** Payment method preference analysis
- **Default:** All

### 9. Purpose
- **Type:** Dropdown filter
- **Purpose:** Filter by transaction purpose
- **Use Case:** Categorize transactions by intent
- **Default:** All

### 10. Transaction Type
- **Type:** Dropdown filter
- **Purpose:** Filter by type of transaction
- **Use Case:** Analyze specific transaction categories
- **Default:** All

**Slicer Benefits:**
- ✓ Synced across both dashboard pages
- ✓ Multiple selections supported
- ✓ Real-time data updates
- ✓ Easy user interface
- ✓ Efficient navigation

---

## Bookmarks Implementation

Bookmarks enable quick navigation between pre-configured dashboard views.

### Bookmark 1: Transactions
- **Purpose:** Quick view of transaction analysis
- **Filters Applied:** Transaction-specific filters
- **Page:** Charts Dashboard
- **Visualization Focus:** Line and Column Charts for Amounts
- **Use Case:** Quick transaction trend analysis

### Bookmark 2: Balance Analysis
- **Purpose:** Quick view of balance trends
- **Filters Applied:** Balance analysis filters
- **Page:** Charts Dashboard
- **Visualization Focus:** Line and Column Charts for Balance
- **Use Case:** Financial position monitoring

**Bookmark Benefits:**
- Save analysis states for quick access
- Improve dashboard navigation efficiency
- Pre-configured view filters
- One-click view switching
- Consistent analysis starting points

---

## Technical Details

### DAX Calculations

#### Age Group Classification Formula
```
Age Group = 
IF([Age] <= 25, "A1",
   IF([Age] <= 35, "A2", "A3"))
```

**Logic:**
- **A1:** Young customers aged 25 and below
- **A2:** Mid-age customers aged 26-35
- **A3:** Senior customers aged 36 and above

**Use Case:** Customer segmentation for behavioral analysis

#### Key Measures Used
- **Total Transactions:** COUNT(Transactions[Transaction ID])
- **Total Amount:** SUM(Transactions[Amount])
- **Average Amount:** AVERAGE(Transactions[Amount])
- **Customer Count:** DISTINCTCOUNT(Transactions[Customer ID])
- **Balance Sum:** SUM(Balance[Balance Amount])

---


## Key Features Summary

✓ **Interactive Power BI Dashboard** with multiple pages  
✓ **10 Synced Slicers** for dynamic filtering across pages  
✓ **4 Comprehensive Visualizations** showing transactions and balance trends  
✓ **Matrix and Chart Visualizations** for detailed and comparative analysis  
✓ **KPI Cards** displaying key performance indicators  
✓ **DAX Calculated Columns** for customer segmentation  
✓ **Bookmark Navigation** for quick view switching  
✓ **Professional Design** with consistent color scheme  
✓ **Responsive Dashboard** adapting to filter selections  
✓ **Year 2024 Complete Data** with monthly breakdowns  

---

## Learning Outcomes

This project demonstrates expertise in:
- Data Cleaning and Transformation in Power BI
- Power Query advanced transformations
- DAX Calculations and expressions
- Dashboard Design Principles
- Interactive Report Building
- Professional Data Visualization
- Slicer Synchronization across pages
- Bookmark Functionality
- Color theory and design consistency
- User Experience optimization

---

## How to Use the Dashboard

### Step 1: Opening the Dashboard
1. Download and install Microsoft Power BI Desktop (free from Microsoft)
2. Download the `powerBI_Project3.pbix` file
3. Double-click to open in Power BI Desktop
4. Dashboard loads automatically

### Step 2: Navigating Between Pages
1. Click "Charts Dashboard" tab for visual analysis
2. Click "Matrix Dashboard" tab for detailed data
3. Use page navigation arrows if available

### Step 3: Using Slicers
1. **Locate slicers** in the top two rows of the dashboard
2. **Click any slicer** to open dropdown menu
3. **Select values** you want to filter (single or multiple)
4. **Click OK** or outside the dropdown to apply
5. **All visualizations update** automatically
6. **Filters sync** across both pages

### Step 4: Analyzing Charts
1. **Line Charts:** Hover over data points to see exact values
2. **Column Charts:** Click on bars to drill down (if enabled)
3. **Legends:** Click legend items to show/hide series
4. **Tooltips:** Hover to reveal additional data

### Step 5: Using Bookmarks
1. **Click "Transactions"** bookmark for transaction view
2. **Click "Balance Analysis"** bookmark for balance view
3. **Dashboard state changes** instantly to saved view

### Step 6: Exploring Matrix Data
1. **Scroll right/left** to see more columns
2. **Click column headers** to sort data
3. **Expand rows** to see sub-categories
4. **Review totals** for aggregated metrics

---

## Dashboard Insights & Interpretation

### Transaction Analysis (Visualizations 1 & 2)
**What the charts show:**
- Monthly transaction volumes for entire 2024
- Seasonal patterns in transaction activity
- Peak and low periods

**Key Findings:**
- May recorded highest transaction volume (1.71M)
- July showed lowest activity (1.61M)
- Overall range: 1.60M - 1.71M (±3.3% variation)
- Relatively consistent transaction volume year-round
- Q3 shows slight dip, Q4 shows recovery

**Business Implications:**
- Stable customer engagement throughout year
- May peak could indicate seasonal spending
- Summer dip aligns with travel/vacation season
- Plan resource allocation based on these trends

### Balance Analysis (Visualizations 3 & 4)
**What the charts show:**
- Account balance positions throughout 2024
- Cash flow patterns and financial health
- Liquidity position by month

**Key Findings:**
- June peak balance: 8.54M (Highest reserves)
- May lowest balance: 8.22M (Lowest reserves)
- Balance range: 8.2M - 8.5M (±1.8% variation)
- Inverse relationship with transaction volume
- Year-end balance (December): 8.4M

**Business Implications:**
- Strong financial position maintained consistently
- Balance fluctuations manageable and predictable
- Sufficient reserves for operational needs
- Peak liquidity aligned with revenue seasons

---

## Tips & Best Practices

### For Effective Analysis
1. **Start with overview** - Use all data first, then filter
2. **Use multiple slicers** - Combine filters for deeper insights
3. **Compare visualizations** - Switch between chart types
4. **Track trends** - Look for patterns across months
5. **Note exceptions** - Identify outliers and anomalies

### For Better Performance
1. **Minimize slicer selections** - More filters = slower refresh
2. **Avoid circular references** - Keep DAX formulas simple
3. **Regular updates** - Refresh data monthly
4. **Archive old data** - Keep file size manageable



## Future Enhancements

Potential improvements for upcoming versions:
- Advanced DAX measures for deeper analysis
- Drill-through reports for granular investigation
- Forecasting visuals for trend prediction
- Mobile-optimized dashboard views
- Real-time data integration with live sources
- Custom tooltips with additional metrics
- Heatmap visualizations for pattern identification
- Performance optimization for large datasets
- Role-based access control for multi-user environments
- Automated alerts for threshold breaches

---

## Project Statistics

| Metric | Value |
|--------|-------|
| Dashboard Pages | 2 |
| Visualizations | 4 Main + Additional KPIs |
| Slicers | 10 (All Synced) |
| Data Columns | 16+ |
| Date Range | January - December 2024 |
| Transaction Records | 10,000+ |
| Average Monthly Volume | 1.66M |
| Average Balance | 8.38M |
| Data Refresh Frequency | Monthly |

---

## Author

**Name:** Harish Uta  
**Role:** Power BI Developer  
**Expertise:** Business Intelligence, Data Visualization, DAX  
**Contact:** Available for questions and clarifications

---

## Conclusion

This Power BI dashboard provides a comprehensive analytical solution for UPI transaction monitoring and financial analysis. With interactive visualizations, synced slicers, and professional design, stakeholders can easily understand transaction patterns, balance trends, and customer behavior throughout 2024.

The dashboard demonstrates best practices in business intelligence including:
- Clean data architecture
- Intuitive user interface
- Responsive filtering system
- Professional visualizations
- Comprehensive documentation

Whether you're analyzing transaction volumes, monitoring balance fluctuations, or identifying seasonal patterns, this dashboard provides the insights needed for informed decision-making.

---

## Next Steps

1. **Download Files:** Get `UPI_Transactions_Dashboard.pbix` and data file
2. **Install Power BI:** Download free Power BI Desktop
3. **Open Dashboard:** Launch the .pbix file
4. **Explore Data:** Use slicers to filter and analyze
5. **Review Insights:** Study patterns and trends
6. **Share Findings:** Export reports and distribute insights
7. **Iterate:** Provide feedback for improvements

---

**Thank you for using the UPI Transactions Power BI Dashboard!**

For inquiries, feedback, or suggestions for improvements, please reach out to the project author.

**Happy analyzing! 📊✨**
