# Stock Forecast Pipeline

Academic Project: End-to-End Medallion Architecture pipeline (Bronze → Silver → Gold) with Stock Forecasting Model (K-means, ARIMA, Linear Regression, XGBoost)

**Languages used:**
- PySpark  
- Python

**Note:** Data files are excluded due to academic restrictions—these notebooks are for review only.

## Notebooks Structure

```text
notebooks/
├── 01_Raw_data_ingestion/
│   ├── Ingest_raw_cities_data.ipynb
│   ├── Ingest_raw_product_data.ipynb
│   └── Ingest_raw_sales_data.ipynb
├── 02_Clean_data/
│   ├── Clean_cities.ipynb
│   ├── Clean_products.ipynb
│   └── Clean_sales_data.ipynb
├── 03_Rich_data/
│   ├── rich_dim_date.ipynb
│   ├── rich_dim_product.ipynb
│   ├── rich_dim_promotion.ipynb
│   ├── rich_dim_stores.ipynb
│   └── rich_fact_sales.ipynb
├── 04_EDA/
│   ├── EDA_agg_data.ipynb
│   ├── EDA_Cities.ipynb
│   ├── EDA_Products.ipynb
│   └── eda_sales.ipynb
├── 05_Machine_Learning/
│   ├── Analysis/
│   │   ├── Arima_products_demand_data.ipynb
│   │   ├── Data_Quantity_By_Product-Store_Analysis.ipynb
│   │   ├── model_products_with_data.ipynb
│   │   ├── Results.ipynb
│   │   └── Store_Open-Close_Period_Analysis.ipynb
│   ├── Features/
│   │   └── Weekly_features.ipynb
│   ├── Filtering/
│   │   ├── 01_Filter_Stores_By_Active_Period.ipynb
│   │   ├── 02_Filter_Stores_By_Demand.ipynb
│   │   └── 03_Filter_Stores_By_Amount_of_Data.ipynb
│   ├── Models/
│   │   ├── ARIMA_for_Products_w_demand_w_data.ipynb
│   │   ├── K-Means_Store_Clusters.ipynb
│   │   ├── Model_For_Products_WITH_data-ARIMA.ipynb
│   │   ├── Model_For_Products_WITHOUT_data-BASELINE-MEAN.ipynb
│   │   ├── Model_For_Products_WITHOUT_data-LINEARREGRESSION.ipynb
│   │   └── Model_For_Products_WITHOUT_data-XGBOOST.ipynb
│   └── Predict_Stock/
│       └── Predict_Data_from_results.ipynb
└── 06_Business_Intelligence/
    └── Gold_DATA_to_BI.ipynb
