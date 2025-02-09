# Marketing Campaign Analysis

## Project Overview
This project analyzes customer data to understand factors influencing customer acquisition and campaign performance. The dataset includes information on demographics, product spending, sales channels, and campaign responses. The goal is to provide actionable insights to optimize marketing strategies and improve customer engagement.

## Dataset
The dataset (`marketing_data.csv`) contains the following columns:
- **ID**: Unique customer ID.
- **Year_Birth**: Customer's birth year.
- **Education**: Education level of the customer.
- **Marital_Status**: Marital status of the customer.
- **Income**: Annual income of the customer.
- **Kidhome**: Number of children in the household.
- **Teenhome**: Number of teenagers in the household.
- **Dt_Customer**: Date of customer enrollment.
- **Recency**: Number of days since the last purchase.
- **MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds**: Amount spent on products in the last 2 years.
- **NumWebPurchases, NumCatalogPurchases, NumStorePurchases**: Number of purchases made through different channels.
- **NumWebVisitsMonth**: Number of visits to the company's website in the last month.
- **AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5**: Whether the customer accepted the offer in the respective campaign.
- **Response**: Whether the customer responded to the last campaign.
- **Complain**: Whether the customer lodged a complaint in the last 2 years.
- **Country**: Country where the customer resides.

## Project Structure

```
Marketing-Campaigns/
├── data/                # Folder for datasets
│   └── marketing_data.csv  # Dataset file
├── notebooks/           # Folder for Jupyter notebooks
│   └── marketing_campaign_analysis.ipynb  # Main analysis notebook
├── scripts/             # Folder for Python scripts (optional)
├── outputs/             # Folder for analysis outputs (e.g., plots, reports)
├── README.md            # Project description and instructions
└── requirements.txt     # List of dependencies 

