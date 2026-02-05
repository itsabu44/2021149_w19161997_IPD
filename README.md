Demand Forecasting to optimize inventory in supermarket chain

This project forecasts daily demand for supermarket products using historical sales data. The Prophet time series model was used to predict future sales at product levels.

Project Overview

Data Cleaning & Structuring: Sales and product data were cleaned, missing dates handled, and sales values calculated.
Product Categorization: Products were manually assigned to categories using predefined rules. Unlisted products were labeled as "Other". Numeric category IDs were also assigned.
Data Aggregation: Sales were aggregated daily by product and category. Average discounts and total sales were calculated.
Exploratory Analysis: Category-level and product-level demand trends were visualized to understand patterns and seasonality.
Forecasting: Prophet model was used to forecast daily demand. Features like Avg_Discount and is_weekend were added as regressors. Forecasts were generated for a representative product and then extended to all products.
Evaluation: Model accuracy was measured using MAE, RMSE, and MAPE.

Dataset

The full dataset is not included in the public repository due to size limits. Instead, it has been uploaded to Google Drive: "https://drive.google.com/drive/folders/160N9aRHFl056gvkfHhppmQmN2uYXNFIS?usp=sharing" 

Although the dataset consists of seven related files, only Sales, Categories, and Products files need to be downloaded to run the project successfully.

