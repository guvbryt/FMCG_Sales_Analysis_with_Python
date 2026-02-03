## **Exploratory Data Analytics and Sales Prediction Modeling for FMCG Dataset**

### **FMCG Dataset – Overview**

This dataset simulates daily-level transactional data for products sold in the Fast-Moving Consumer Goods (FMCG) sector between 2022 and 2024.

This is designed to support analysis of:

- Seasonality and product lifecycle
- Promotion and holiday effects
- Stockouts and inventory dynamics
- Demand forecasting and feature engineering

Each row corresponds to a single SKU on a specific day, making it suitable for time-series analysis and real-world FMCG use-case simulations. This project is intended strictly for educational and portfolio-building purposes.

#### **Data Source**

The original dataset was obtained from Kaggle:
🔗 FMCG Daily Sales Data (2022–2024)
https://www.kaggle.com/datasets/beatafaron/fmcg-daily-sales-data-to-2022-2024?select=FMCG_2022_2024.csv

#### **Data Modification Notice**

After downloading, the dataset was augmented and modified to include additional fields that were not present in the original version. These enhancements were necessary to support deeper analytics and ensure consistency across the analysis.

As a result, the insights generated in this project represent a hypothetical analysis and should not be interpreted as real-world business outcomes.

- For our columns, each record includes;

- date: Date of the sales record
- sku: Stock Keeping Unit (unique product ID)
- brand: Brand name of the product
- segment: Product segment (e.g., premium, standard, economy)
- category: Product category (e.g., Beverages, Snacks)
- channel: Sales channel (e.g., Retail, E-commerce)
- region: Region where the sale occurred
- pack_type: Packaging type
- price_unit: Price per single unit
- promotion_flag: Whether the sale occurred under promotion (1 = Yes, 0 = No)
- delivery_days: Number of days taken to deliver
- stock_available: Units available in stock
- delivered_qty: Number of units delivered
- units_sold: Total units actually sold

The goal is to understand the company’s performance and uncover insights that can help improve sales strategies and stock management.
