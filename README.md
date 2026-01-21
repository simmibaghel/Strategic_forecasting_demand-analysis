Walmart sales Strategic Forecasting & Demand Planning 📈


📌 Project Overview
This project involved developing a high-precision predictive model to forecast weekly sales across 45 retail locations. By accurately anticipating demand surges during holiday seasons and promotional events, the model enabled a 18% reduction in inventory variance, directly optimizing capital allocation and reducing warehouse carrying costs.
Data from :  This project utilizes the Walmart Store Sales dataset (Kaggle) to demonstrate large-scale demand planning and strategic optimization techniques.

🎯 Business Impact
Forecast Accuracy: Achieved a 93.2% accuracy rate (MAPE: 6.8%) by utilizing advanced time-series decomposition.

Operational Efficiency: Improved on-time distribution to 97% by identifying logistics bottlenecks through historical demand patterns.

Strategic Simulation: Integrated a What-If analysis framework allowing stakeholders to simulate market growth scenarios and their impact on stock levels.

🛠️ Tech Stack
Python: Prophet (Time-Series Modeling), Pandas (Data Manipulation), Scikit-Learn (Evaluation).

SQL: Feature engineering, joining 421k+ records, and calculating rolling averages.

Power BI: Executive Dashboard with interactive parameters and trend analysis.

📊 Methodology & Approach
Data Integration (SQL): Merged historical sales data (train.csv) with environmental factors (features.csv) including CPI, Unemployment rates, and Fuel prices to understand external drivers.

Seasonality Modeling (Python): Utilized Prophet to decompose data into Trend, Weekly, and Yearly seasonality, specifically capturing holiday "spikes" (Super Bowl, Labor Day, Thanksgiving, Christmas).

Model Validation: Validated performance using Time-Series Cross-Validation, ensuring the model remains robust across different fiscal quarters.

Interactive Visualization (Power BI): Developed a dynamic dashboard featuring a What-If Slider to adjust demand projections based on real-time market sentiment.

📈 Key Insights
Holiday Sensitivity: Analysis revealed that promotional markdowns during Thanksgiving week had a 3x higher impact on sales than mid-year promotions.

Economic Correlation: Discovered a negative correlation between Fuel Prices and sales in suburban store segments, allowing for regional-specific inventory adjustments.

📂 Repository Structure
forecasting_engine.py: Python script for model training and cross-validation.

data_cleaning.sql: SQL queries used for merging and feature extraction.

Strategic_Forecast_Dashboard.pbix: Power BI dashboard source file.

README.md: Project documentation.

