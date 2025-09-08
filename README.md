# Optimization of Medical Inventory
## Project Details
- Business Understanding – Identified the project’s business problem: inefficient raw material procurement leading to overpaying and surplus inventory, increasing costs. - Defined objectives to minimize inventory costs and optimize stock utilization.
- Data Collection – Gathered data from various sources, including research articles, industry reports, company databases, and Excel files. After collection, prepared a CSV file and then loaded it into SQL for structured storage and basic operations.
- Data Cleaning & Preparation – Performed initial data corrections in SQL, then loaded the dataset into Python for advanced processing.
- Exploratory Data Analysis (EDA) – Analyzed column-wise statistics (data type, null count, average, median, min, max, standard deviation, sum, skewness, and kurtosis) using Pandas, SciPy, and NumPy.
- Data Visualization (Power BI & Excel) – Built interactive dashboards to track inventory levels, procurement trends, and cost inefficiencies.
- Insights & Recommendations – Suggested stock optimization strategies to reduce waste and improve procurement efficiency.

## Achievements 
- ✅Reduced underutilized inventory by 20%, optimizing stock utilization.
- ✅Cut storage and management costs by 25%, enhancing cost efficiency.
- ✅Improved procurement planning using data-driven insights.

## Dashboards for this project

### 1. Stock Levels Overview

#### Key Metrics:

- **Available Balance**: ₹357.92M
- **Available Quantity**: 211,000 units
- **Total Procured Quantity (2020-2024)**: 2,028,000 units

#### Key Insights:

- Only **10.4%** of total procured stock is available, indicating high consumption or inefficiencies.
- **Yearly Consumption Trends**:
  - Peak consumption in **2022** (-523K units) and **2023** (-522K units).
  - Significant decline in **2024** (-105K units, an 80% decrease), suggesting improved utilization or reduced demand.
- **Yearly Procurement Trends**:
  - Peak procurement in **2023** (590K units) with a sharp **79% decline** in 2024 (125K units).
#### Stock Level - Overview
![Stock Level - Overview](https://github.com/pranayjoshi0711-svg/Optimization_of_Medical_Inventory-MySQL-Python/blob/main/Images/Stock%20Level%20-%20Overview.png)
---

### 2. Procurement Insights

#### Procurement by Plant:

- **Plant A**: Dominated procurement with **1.84M units (90.8%)** of total procurement.
  - Key Insight: Central hub for procurement, critical for inventory optimization and cost control.

#### Top Materials by Total Procurement:

- **High-Speed Diesel**: 581,000 liters (**28.7%** of total stock).
- **Cable Ties (150mm)**: 85,000 units.
- **Chemical-Chlorination**: 74,000 kilograms.
  - Key Insight: High-Speed Diesel is the most critical material for cost monitoring and optimization.

#### Procurement by Storage Location:

- **Electrical Supplies**: 626,621 units (**30.9%** of total procurement).
- **Procurement Storage**: 182,147 units.
- **Road Delivery**: 179,094 units.
  - Key Insight: Electrical Supplies dominate, requiring a targeted approach for better utilization.

#### Procurement Movement Type Breakdown:

- **Goods Receipt (GR)**: **87.91%** of movements, totaling 1.78M units.
- **Transfer Within Plant**: **5.12%**.
- **Goods Receipt for Account Assignment**: **6.65%**.
  - Key Insight: Majority of procurement movements involve Goods Receipts.

#### Procurement Insights
![Procurement Insights](https://github.com/pranayjoshi0711-svg/Optimization_of_Medical_Inventory-MySQL-Python/blob/main/Images/Procurement%20Insights.png)
---

### 3. Financial Insights

#### Cost Impact on Inventory (2020-2024):

- **2020**: ₹756M.
- **2024**: ₹159M (**78.99% reduction**).
  - Key Insight: Reflects significant improvements in cost control and operational efficiencies.

#### Total Cost by Unit of Entry Category:

- **Quantity**: ₹60.4M (**42.83%**).
- **Weight**: ₹56.3M (**40.76%**).
- **Packaging**: ₹16.8M (**11.98%**).
- **Measurement**: ₹6.2M (**4.43%**).
  - Key Insight: Quantity and Weight contribute most to costs; optimizing these can drive savings.

#### Total Cost by Plant:

- **Plant A**: ₹781M (**88.54%**).
- **Plant C**: ₹58M (**6.55%**).
- **Other Plants (B, D, E, F)**: ₹42M (**5.91%**).
  - Key Insight: Focusing on Plant A could achieve significant cost reductions.

#### Financial Insights
![Procurement Insights](https://github.com/pranayjoshi0711-svg/Optimization_of_Medical_Inventory-MySQL-Python/blob/main/Images/Financial%20Insights.png)
---
