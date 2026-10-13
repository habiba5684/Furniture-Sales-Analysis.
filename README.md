# 🪑 Furniture Sales & Profitability Analysis

## 📌 Project Overview
This project analyzes furniture sales data to understand sales performance, profitability, customer segments, regional performance, and shipping efficiency.

Using Python and Exploratory Data Analysis (EDA), it explores numerical and categorical features to identify sales patterns, evaluate business performance, and uncover where profit is being lost.

## 🎯 Project Objectives
**Goal:** Understand how the furniture business performs and identify where profit is being lost.

- Analyze total revenue, profit, quantity sold, and number of orders
- Calculate profit margin and average order value
- Explore the relationship between sales and profit
- Identify the most loss-making orders
- Compare sales performance across regions
- Identify the best-performing product sub-categories
- Analyze monthly sales trends
- Explore sales across states and customer segments
- Compare shipping modes by average delivery duration
- Evaluate profitability across regions

## 🗂️ Dataset
- **Source:** Superstore-style furniture sales data (`Dataset.xlsx`)
- **Size:** 2,121 rows × 20 columns (1 duplicate row removed)
- **Period:** January 2014 – December 2017
- **Key columns:** Order Date, Ship Date, Ship Mode, Segment, Region, State, Sub-Category, Sales, Quantity, Profit

## 🛠️ Tools & Technologies
- **Python** — Data analysis and manipulation
- **Pandas** — Data cleaning, aggregation, and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **Jupyter Notebook** — Interactive analysis and documentation

## 📊 Project Workflow

### 1. Data Loading
- Loaded the Excel file into a Pandas DataFrame

### 2. Data Inspection & Cleaning
- Inspected the dataset structure and data types
- Checked for missing values (none found)
- Generated descriptive statistics and checked dimensions
- Identified and removed the duplicate record
- Converted `Duration` (text such as `"3- days"`) into a numeric `Duration_days` column

### 3. Exploratory Data Analysis (EDA)

**Numerical Analysis**
- Calculated key performance indicators (KPIs)
- Examined numerical feature distributions
- Visualized the relationship between sales and profit
- Identified the five most loss-making orders

**Categorical Analysis**
- Explored shipping modes, segments, regions, sub-categories, and delivery duration
- Compared sales across regions and identified the top sub-category
- Analyzed monthly sales trends
- Examined sales by state and customer segment
- Compared average delivery duration across shipping modes
- Evaluated regional profitability

## 📈 Key Performance Indicators (KPIs)

| KPI | Value |
|---|---|
| Total Revenue | $741,999.80 |
| Total Profit | $18,451.27 |
| Total Orders | 1,764 |
| Total Quantity Sold | 8,028 |
| Profit Margin | 2.49% |
| Average Order Value | $420.63 |

<!-- TODO: after Restart & Run All, update the values above if they changed after removing the duplicate -->

## 🔍 Key Findings
- Revenue reached **$742K**, but the profit margin is only **2.49%**. Volume is not the problem; losses are.
- **Chairs** are the top sub-category by sales (~$328K).
- **4 of the 5 most loss-making orders are Tables**, and 3 of them are in the **South** region. The worst single order lost about **$1,862** on $4,298 in sales.
- Profit per order ranges from **-$1,862 to +$1,013**, so a small number of heavy-loss orders drag down overall profit.

<!-- TODO: add 2-3 bullets from your charts: best months, top region by sales/profit, fastest ship mode, top state-segment -->

## ✅ Recommendations
1. **Review pricing and discounts on Tables**, especially in the South region, where the heaviest losses occur.
2. **Set a discount cap** on high-value orders so large sales don't turn into large losses.
3. **Prioritize sub-categories with healthy margins** instead of pushing volume alone.

## 📂 Project Structure

```text
furniture-sales-eda-python/
│
├── Furniture_data.ipynb
├── Dataset.xlsx
└── README.md
```

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn openpyxl jupyter
```

3. Keep `Dataset.xlsx` in the same folder as the notebook.
4. Open `Furniture_data.ipynb` in Jupyter Notebook or JupyterLab.
5. Run the cells sequentially to reproduce the analysis.

## 📚 Skills Demonstrated
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Aggregation and Grouping
- KPI Calculation
- Statistical Summaries
- Data Visualization
- Business-Oriented Data Analysis
- Python Programming

## 👩‍💻 Author
**Habiba Mostafa**: Business Information Systems graduate, aspiring Junior Data Analyst / BI Analyst.

🔗 [LinkedIn](https://www.linkedin.com/in/YOUR-LINK) · [GitHub](https://github.com/habibamostafa2235)
