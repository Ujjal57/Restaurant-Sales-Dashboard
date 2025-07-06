# 🍽️ Restaurant Sales Dashboard - Power BI

This interactive Power BI dashboard offers a comprehensive overview of restaurant sales between January 1, 2023 – April 30, 2023. It allows users to analyze key performance metrics like total customers, orders, food category demand, delivery rates, and payment preferences.

Designed with clean visuals and slicers, this dashboard helps stakeholders make informed decisions about customer behavior, top-performing dishes, and operational efficiency.

## 📊 Key Features

- 👥 Total Customers & Total Orders
- 📈 Food Category Analysis (Bar Chart)
- 🎯 Quantity Gauge Chart (Min, Max, and Total Quantity)
- 📊 Customer Type Split – Gold vs Regular (Pie Chart)
- 🔄 Order Status Split – Delivered vs Cancelled (Donut Chart)
- 🍛 Cuisine-Type Popularity – Treemap (North, South, Mughlai)
- 💳 Payment Method Preferences – UPI, COD, Card (Bar Chart)
- 📆 Date Range Slicer for dynamic filtering

## 📁 Project Structure
📁 Restaurant-Sales-Dashboard
│── Dashboard.png      # Main dashboard preview image
│── Dashboard.xlsx     # Excel file with pivot tables and dashboard
│── main.png           # Duplicate or alternate view of dashboard (optional)
│── pivot.png          # Screenshot of pivot table setup
│── Source.csv         # Raw data used for the analysis
│── source.png         # Screenshot of raw data structure (optional)
│── README.md          # Project documentation (this file)

## 🚀 How to Use the Dashboard


> ⚠️ The Power BI `.pbix` file is not included in this repository to prevent unauthorized use.  
> However, you can recreate the dashboard using the raw Excel files provided.
> 
### 🔹 Step 1: Prepare the Dataset in Power BI

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Open Power BI and click on **"Get Data" → "Folder"**.
3. Browse to the `Orders/` folder containing monthly Excel files (Jan.xlsx, Feb.xlsx, Mar.xlsx, Apr.xlsx).
4. Load and combine the data using **Power Query**.

> 💡 Power BI will automatically detect and combine all the sheets into a single unified dataset.

### 🔹 Step 2: Build the Dashboard (Using Power BI)

Once the data is loaded:

- Clean and transform columns using **Power Query Editor** (e.g., remove blanks, fix headers).
- Create relationships and a data model if needed.
- Use **DAX** to calculate:
  - Total Customers
  - Total Orders
  - Quantity Stats
  - Delivery Status %
  - Customer Types (Gold vs Regular)
  - Payment Method Breakdown
- Build visuals:
  - Bar Charts for Food Type and Payment Methods
  - Pie/Donut Charts for Customer Types and Order Status
  - Gauge Chart for Total Quantity
  - Treemap for Cuisine Categories
  - Date Range Slicer for filtering (e.g., Jan–Apr)

### 🔹 Step 3: Customize and Publish

- Apply themes, title cards, and shadow effects for a clean look.
- Export as PDF or publish to **Power BI Service** (if needed).


## 🖼️ Screenshots

<p align="center">
  <img src="main.png" alt="Intro Animation" width="700"/>
  <br><em>Dashboard</em>
</p>

<p align="center">
  <img src="pivot.png" alt="Home Page" width="700"/>
  <br><em>Pivot Tables</em>
</p>

<p align="center">
  <img src="transform.png" alt="Info Page" width="700"/>
  <br><em>Transformed Data</em>
</p>

<p align="center">
  <img src="source.png" alt="Info Page" width="700"/>
  <br><em>Raw Data</em>
</p>

## 📊 Key Insights

- 👥 Total patients: 4,338 (2023) → 4,878 (2024)
- ⏳ Average wait time: 35.5 minutes
- 🚻 Gender distribution: fairly balanced in both years
- 🧑‍⚕️ Most visited department: General
- 📈 Most common age group: 20–29 years
- 🏥 Admission rate slightly dropped from 49.8% to 49.1%

 ## 🛠️ Tools Used

- Microsoft Excel – Pivot tables, charts, and slicers 
- CSV Dataset – Raw ER data

## 🔮 Future Scope

- Publish as an interactive web dashboard using Power BI

- Add filters for age group, year, and department

- Automate real-time data refresh using Power Query


## 👨‍💻 Contributors

- **Ujjal** - *Developer*
