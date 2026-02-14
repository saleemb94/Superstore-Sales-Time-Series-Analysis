# Superstore-Sales-Time-Series-Analysis
A data analysis project optimizing retail KPIs and forecasting trends using Time Series analysis

# 📈 Superstore Sales & Profit Analysis

## 📌 Project Overview
This project analyzes a retail "Superstore" dataset to identify critical business trends, optimize Key Performance Indicators (KPIs), and diagnose regional performance issues. 

The analysis focuses on **Data Preprocessing**, **Schema Integration**, and **Time-Series Analysis** to answer questions regarding sales volatility, profit margins, and return rates across different time granularities (Weekly, Monthly, Quarterly, Yearly).

## 🚀 Key Features & Methodology

### 1. Data Cleaning & Engineering
- **Inconsistency Handling:** Detected and standardized inconsistent region labels (e.g., correcting 'est' to 'East', 'wsr' to 'West') to ensure accurate aggregations.
- **Null Handling:** Imputed missing values in the `Returns` dataset to distinguish between non-returned items and missing data.
- **Schema Merging:** Integrated three disparate datasets (`Orders`, `Returns`, `People`) into a unified analytical dataset using Left Joins to preserve transactional integrity.

### 2. Time-Series Analysis
Performed temporal aggregation using **Pandas Resampling** to visualize trends:
- **Sales & Profit:** Analyzed revenue vs. profit streams to identify high-performance quarters.
- **Discount Impact:** Evaluated average discount rates over time to correlate promotional periods with volume spikes.
- **Quantity Dynamics:** Tracked inventory turnover rates on a granular weekly basis.

## 🛠️ Tech Stack
- **Python** (Core Logic)
- **Pandas** (Data Manipulation & Merging)
- **Matplotlib & Seaborn** (Data Visualization)
- **Jupyter Notebook** (Interactive Analysis Environment)

## 📊 Visualizations
*(Note: I recommend taking screenshots of the graphs generated in your notebook—specifically the Multi-plot Time Series grid—and pasting them here. Visuals prove you can communicate data).*

## 💻 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Superstore-Sales-Time-Series-Analysis.git](https://github.com/YOUR_USERNAME/Superstore-Sales-Time-Series-Analysis.git)
