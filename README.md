
# Maven Market Power BI Project

This Power BI project involves analyzing data from Maven Market, a multi-national grocery chain with locations in Canada, Mexico, and the United States. The project encompasses the entire business intelligence workflow, including connecting and shaping data, building a relational model, adding calculated fields, and designing an interactive report. The goal is to provide insightful visualizations and analysis of Maven Market's operations and performance.

## Report Screenshots
![image](https://github.com/user-attachments/assets/d5f77424-0ca4-440c-8a2d-94de7391f264)


## Project Overview

1. **Connecting and Shaping the Data**:
    - Connected to multiple CSV files containing data on customers, products, stores, regions, calendar dates, returns, and transactions.
    - Cleaned and transformed data using Power Query Editor, ensuring correct data types, merging columns, and adding calculated columns.

2. **Building the Relational Model**:
    - Created relationships between tables based on primary and foreign keys.
    - Ensured one-to-many cardinality and one-way filter flow from lookup tables to data tables.
    - Implemented a snowflake schema by connecting stores to regions.

3. **Adding Calculated Columns and Measures**:
    - Added various calculated columns such as `Weekend`, `End of Month`, `Current Age`, `Priority`, `Short_Country`, `House Number`, `Price_Tier`, and `Years_Since_Remodel`.
    - Created measures to calculate key metrics like `Quantity Sold`, `Quantity Returned`, `Total Transactions`, `Total Returns`, `Return Rate`, `Weekend Transactions`, `%Weekend Transactions`, `All Transactions`, `All Returns`, `Total Revenue`, `Total Cost`, `Total Profit`, `Profit Margin`, `Unique Products`, `YTD Revenue`, `60-Day Revenue`, `Last Month Transactions`, `Last Month Revenue`, `Last Month Profit`, `Last Month Returns`, and `Revenue Target`.

4. **Designing the Interactive Report**:
    - Created a comprehensive report named "Topline Performance" with various visualizations including a matrix, KPI cards, map, treemap, column chart, and gauge chart.
    - Applied conditional formatting, filters, and slicers to enhance data interaction and readability.
    - Implemented bookmarks and navigation buttons to highlight key insights and findings.

## Key Visuals and Analysis

- **Matrix Visual**: Displays total transactions, total profit, profit margin, and return rate by product brand with conditional formatting and Top N filter.
- **KPI Cards**: Show current month transactions, profit, and returns compared to the previous month.
- **Map Visual**: Illustrates total transactions by store city, with a slicer for store country.
- **Treemap Visual**: Breaks down total transactions by store country, state, and city.
- **Column Chart**: Shows weekly revenue trending for the year 1998.
- **Gauge Chart**: Compares total revenue against the revenue target.

## How to Use This Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Mohamed-Laymouna/maven-market-power-bi.git
    ```

2. **Open the Power BI Report**:
    - Ensure you have Power BI Desktop installed on your machine.
    - Open `MavenMarket_Report_Final.pbix` file in Power BI Desktop.

3. **Explore the Report**:
    - Navigate through the "Topline Performance" tab to explore the various visualizations.
    - Use slicers and drill-down features to interact with the data.
    - Check the "Notes" page for key insights and bookmarks.

## Conclusion

This project showcases the ability to handle end-to-end business intelligence tasks using Power BI, from data connection and transformation to model building and interactive report design. It demonstrates advanced data modeling, DAX calculations, and visualization techniques to provide actionable insights for a multi-national grocery chain.

## Repository Structure

```
maven-market-power-bi/
│
├── data/
│   ├── MavenMarket_Customers.csv
│   ├── MavenMarket_Products.csv
│   ├── MavenMarket_Stores.csv
│   ├── MavenMarket_Regions.csv
│   ├── MavenMarket_Calendar.csv
│   ├── MavenMarket_Returns.csv
│   ├── MavenMarket_Transactions_1997.csv
│   ├── MavenMarket_Transactions_1998.csv
│
├── images/
│   └── Maven_Market.png
│
├── MavenMarket_Report_Final.pbix
│
└── README.md
```

## Contact

For any questions or further information, feel free to reach out via [Mohamed.Laymouna@gmail.com].
