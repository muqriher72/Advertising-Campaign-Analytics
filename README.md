# Advertising Campaign Performance Analytics

The primary objective of marketing agencies is to maximize the return on investment (ROI) for the client's advertising campaigns. In this project, we determine whether Facebook or AdWords yields better results in terms of conversions, clicks, and overall cost-effectiveness. 
By identifying the most effective platform, the marketing agency can allocate resources more efficiently to optimize advertising strategies and yield better results for clients.

The project invovles the following technical concepts:
- Python: Numpy, Pandas, Matplotlib, Seaborn, Scikit-Learn
- Hypothesis Testing
- Regression Analysis
- A/B Testing
- Time Series Analysis

## Research Question
Which ad platform is more effective in terms of conversions, clicks, and overall cost-effectiveness?

## Data
This dataset contains 2019 performance metrics for two ad campaigns: one on Facebook and one on Google AdWords. It provides daily data for each campaign, totaling 365 rows, allowing for an analysis of their effectiveness and efficiency throughout the year. The dataset includes various performance metrics for each ad campaign, providing insights into their effectiveness and efficiency over time.

Key features included in the dataset are as follows:

- Date: The date corresponding to each row of campaign data, ranging from January 1st, 2019, to December 31st, 2019.

- Ad Views: The number of times the ad was viewed.

- Ad Clicks: The number of clicks received on the ad.

- Ad Conversions: The number of conversions resulting from the ad.

- Cost per Ad: The cost associated with running the Facebook ad campaign.

- Click-Through Rate (CTR): The ratio of clicks to views, indicating the effectiveness of the ad in generating clicks.

- Conversion Rate: The ratio of conversions to clicks, reflecting the effectiveness of the ad in driving desired actions.

- Cost per Click (CPC): The average cost incurred per click on the ad.

## Approach


## Project Organization

```
├── LICENSE                 <- Open-source license if one is chosen
├── README.md               <- The top-level README for developers using this project.
├── data
│   ├── begin_inventory.csv     <- A CSV file that contains information on the initial inventory of a vendor.
│   ├── end_inventory.csv       <- A CSV file that contains information on the final inventory of a vendor.
│   ├── purchase_prices.csv     <- A CSV file that contains information on the purchase prices of a vendor.
│   ├── purchases.7z            <- A CSV file that contains information on the purchases of a vendor.
│   ├── sales.7z                <- A CSV file that contains information on the sales of a vendor.
│   └── vendor_invoice.csv      <- A CSV file that contains information on the invoice for a vendor.
│
├── logs                
│   └── ingestion_db.log        <- A log file that maintains the time taken to ingest the data files into the database.
│
├── powerbi                 
│   ├── BrandPerformance.xls         <- A CSV file created in PowerBI using a query and information from the inventory file.
│   ├── LowTurnoverVendor.xls        <- A CSV file created in PowerBI using a query and information from the inventory file.
│   ├── inventory.xls                <- A CSV file containing information from the vendor_sales_summary table.
│   ├── purchase_contributions.xls   <- A CSV file created in PowerBI using a query and information from the inventory file.
│   ├── vendorperformance.pbix       <- A PowerBI that contains a dashboard of the overall analysis results.
│   └── vendorperformance.pdf        <- A PDF file of the PowerBI dashboard.
│
├── Vendor Performance Report.pdf       <- A PDF report summarizing insights and reccomendations based on data analysis. 
│
├── exploratory_data_analysis.ipynb     <- A Jupyter Notebook file that contains the initial EDA performed on the data using Python and SQL queries.
│                         
├── get_vendor_summary.ipynb            <- A Jupyter Notebook file that contains the vendor summary table made using Python and SQL.
│
├── ingest_db.ipynb                     <- A Jupyter Notebook file that contains a Python script to ingest the data into the database and maintain logs.
│
└── vendor_performance_analysis.ipynb   <- A Jupyter Notebook file that contains the initial EDA performed on the data.
    
```

--------
