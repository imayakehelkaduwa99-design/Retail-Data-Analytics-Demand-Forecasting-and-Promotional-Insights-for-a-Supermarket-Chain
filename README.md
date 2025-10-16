**Retail Data Analytics – Demand Forecasting & Business Insights**
**Forecasting Weekly Sales and Optimising Inventory Across 45 Stores**

**Project Overview**
This project analyzes sales performance across 45 retail stores using real-world data from the Kaggle Retail Data Analytics dataset.
The goal is to forecast weekly sales, understand key sales drivers, and generate data-driven inventory recommendations to reduce overstock and stockout risks.
This project forms part of my data analytics portfolio, demonstrating skills in Python, data wrangling, feature engineering, time series forecasting, and business insight generation.

**Business Problem**
Retail chains face challenges in:

1. Predicting weekly sales accurately for each department and store
2. Managing promotions and seasonal effects efficiently
3. Balancing inventory to minimize lost sales and holding costs

**Objective:**
Develop a predictive model that forecasts weekly sales and produces actionable inventory insights (e.g., reorder points, safety stock) to improve supply chain efficiency.

**Key Questions Answered**

- What are the overall sales trends across stores and departments?
- Which features (lags, rolling averages, holidays, months) most strongly influence sales?
- How accurately can weekly sales be predicted using historical data?
- What reorder points and safety stock levels are optimal for each store and department?

**Methodology**

**1. Data Sources**
The project uses three CSV files from Kaggle’s Retail Data Analytics dataset:

- sales data-set.csv – weekly sales data by department and store
- Features data set.csv – includes holidays, CPI, temperature, and promotion data
- stores data-set.csv – store types and sizes

**2. Tools and Libraries**
   
- pandas, numpy – data manipulation and feature engineering
- matplotlib – exploratory data analysis and visualization
- xgboost – forecasting weekly sales
- scikit-learn – evaluation and preprocessing
- joblib – model serialization

**Business Insights**

1. Lagged sales and rolling averages are the most significant predictors of future performance.
2. Store size and holiday effects play important roles in demand spikes.
3. Inventory recommendations based on model uncertainty help maintain a 95% service level (z = 1.65).

**Acknowledgements**
- Dataset: Kaggle Retail Data Analytics (45 Stores)
