# Online Shopping & Customer Behavior Analysis

A Power BI analysis exploring online shopping and customer behavior patterns — including spending habits, purchase activity, and customer segmentation — built on a dataset of ~1,800 customers.

## 📁 Repository Contents

| File | Description |
|---|---|
| `online_shopping_and_customer_behavior.pbix` | Power BI report file with data model, DAX measures, and interactive dashboard visuals |
| `shopping_and_customer_behavior.xlsx` | Source dataset used to build the report |

## 📊 Dataset Overview

The dataset contains customer-level records with the following fields:

- **Customer ID** — unique identifier per customer
- **Gender**
- **Age** / **Age Group**
- **Country**
- **Device Type** *(e.g., Tablet, Mobile, Desktop)*
- **Product Category** *(e.g., Clothing, Electronics)*
- **Time Spent (Minutes)** — time spent browsing per session
- **Items Viewed**
- **Items Purchased**
- **Total Spent (USD)**
- **Spending Status** *(e.g., High Spender, Low Spender)*
- **Buyer Status** *(e.g., Buyer, Non-Buyer)*

## 🎯 Key Analysis Areas

- Customer segmentation by spending behavior (High vs. Low Spenders)
- Purchase conversion patterns (Items Viewed vs. Items Purchased)
- Demographic breakdowns (age, gender, country)
- Product category performance
- Device usage trends
- Time-spent-to-purchase correlation

## 🛠️ Tools Used

- **Microsoft Power BI** — data modeling, DAX calculations, and dashboard visualization
- **Excel** — raw data storage and preprocessing

## 🚀 How to Use

1. Clone or download this repository.
2. Open `online_shopping_and_customer_behavior.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download).
3. Explore the interactive report — use slicers and filters to drill into specific segments (country, category, device, etc.).
4. The underlying data is available in `shopping_and_customer_behavior.xlsx` if you'd like to reproduce or extend the analysis.

## 📌 Notes

- Power BI Desktop (Windows only) is required to open and edit the `.pbix` file.
- To refresh the report with updated data, point the Power BI data source to a new copy of the Excel file and click **Refresh**.

## 📄 License

Feel free to specify a license (e.g., MIT) here if you'd like others to reuse this work.
