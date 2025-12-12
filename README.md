# Sales Performance Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-005C84?style=for-the-badge&logo=googleanalytics&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-FFA500?style=for-the-badge&logo=sap&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Author:** Sai Vineeth Reddy Suravi  
**Role:** Data Analyst / BI Specialist

## 📊 Project Overview

This project features a comprehensive **Sales Performance Dashboard** built using **Microsoft Power BI**. It allows stakeholders to track key performance indicators (KPIs), visualize sales trends across different regions, and analyze product profitability.

The goal of this project was to transform raw sales transaction data into an interactive tool that supports strategic decision-making by identifying:
*   High-growth regions and states.
*   Top-performing product categories.
*   Seasonal sales patterns.
*   Customer payment preferences.

## 🚀 Key Features

*   **Dynamic Filtering:** Slicers for Date, Region, Category, and Payment Mode allow for deep-dive analysis.
*   **KPI Cards:** Instant view of Total Sales, Total Profit, Quantity Sold, and Profit Margin.
*   **Geospatial Analysis:** Interactive map visuals showing sales distribution across states and cities.
*   **Trend Analysis:** Line charts depicting Month-over-Month (MoM) and Year-over-Year (YoY) growth.
*   **Decomposition Tree:** Root cause analysis for profit drivers.

## 📂 Repository Structure

```
sales-performance-dashboard/
├── Datasets/
│   ├── Orders.csv          # Transaction metadata (Date, Customer, Location)
│   ├── Details.csv         # Line-item metrics (Sales, Profit, Product)
├── Background Image.png    # Custom UI background for the report
├── Sales_Performance_Dashboard.pbix  # The main Power BI file
├── DATA_DICTIONARY.md      # Detailed description of data fields
├── LICENSE                 # MIT License
└── README.md               # Project documentation
```

## 🛠️ Tools & Technologies

*   **Data Visualization:** Microsoft Power BI Desktop
*   **Data Transformation:** Power Query (ETL)
*   **Calculations:** DAX (Data Analysis Expressions)
*   **Data Modeling:** Star Schema (One-to-Many relationships)

## 📈 Insights Summary

*   **Electronics** is the highest revenue-generating category, driven largely by sub-categories like Phones and Printers.
*   **COD (Cash on Delivery)** remains the preferred payment method, accounting for 40% of transactions.
*   **Q4 (October - December)** shows a consistent spike in sales volume, indicating strong seasonality.
*   **Maharashtra** and **Madhya Pradesh** are the top-performing states in terms of total profit.

## 🔮 Future Enhancements

*   **Forecasting:** Implement Time Series Forecasting (ARIMA or Exponential Smoothing) to predict sales for the next quarter.
*   **Customer Segmentation:** Use clustering techniques (K-Means) to identify high-value customer groups (RFM Analysis).
*   **Row-Level Security (RLS):** Add role-based access for regional managers to view only their specific region's data.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improving the dashboard or find any issues, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/NewFeature`).
3.  Commit your changes.
4.  Push to the branch.
5.  Open a Pull Request.

## 💻 How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/saivineethreddysuravi/sales-performance-dashboard.git
    ```
2.  **Open the Report:**
    *   Launch **Microsoft Power BI Desktop**.
    *   Open `Sales_Performance_Dashboard.pbix`.
3.  **Refresh Data (Optional):**
    *   If you modify the CSV files in the `Datasets` folder, click "Refresh" in Power BI to update the visuals.

---
*Developed by Sai Vineeth Reddy Suravi.*