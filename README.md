# Northwind SQL Analysis Project

This repository packages a 10-question SQL analysis project based on the Northwind dataset. The uploaded Excel workbooks were reorganized into a cleaner project structure with separate folders for raw data extracts, SQL queries, visuals, and the original source workbooks.

## Project structure

```text
northwind-sql-analysis-project/
|-- README.md
|-- raw_data_sheet/        # CSV exports from each workbook's raw-data sheet
|-- sql_queries/           # SQL extracted from each workbook's SQL sheet
|-- visuals/               # PNG exports rendered from each workbook's visualization sheet
|-- source_workbooks/      # Original Excel files as provided
```

## Included analyses

### Q1 - list of unique countries where customers are located

- Raw data: `raw_data_sheet/q1_list_of_unique_countries_where_customers_are_located.csv`
- SQL query: `sql_queries/q1_list_of_unique_countries_where_customers_are_located.sql`
- Visuals: `visuals/q1_list_of_unique_countries_where_customers_are_located/`
- Source workbook: `source_workbooks/Q1_list of unique countries where customers are located.xlsx`
- Chart titles: Global Distribution of Customers, Total Number of Customers by Country

### Q2 - customers who do not have a region assigned

- Raw data: `raw_data_sheet/q2_customers_who_do_not_have_a_region_assigned.csv`
- SQL query: `sql_queries/q2_customers_who_do_not_have_a_region_assigned.sql`
- Visuals: `visuals/q2_customers_who_do_not_have_a_region_assigned/`
- Source workbook: `source_workbooks/Q2_customers who do not have a region assigned.xlsx`
- Chart titles: Geographic Distribution of Customers with No Assigned Region, Total Customers per Rgion

### Q3 - total business activity

- Raw data: `raw_data_sheet/q3_total_business_activity.csv`
- SQL query: `sql_queries/q3_total_business_activity.sql`
- Visuals: `visuals/q3_total_business_activity/`
- Source workbook: `source_workbooks/Q3_total business activity.xlsx`
- Chart titles: Total business activity, Total number of orders placed

### Q4 - Total Revenue Generated

- Raw data: `raw_data_sheet/q4_total_revenue_generated.csv`
- SQL query: `sql_queries/q4_total_revenue_generated.sql`
- Visuals: `visuals/q4_total_revenue_generated/`
- Source workbook: `source_workbooks/Q4_Total Revenue Generated.xlsx`
- Chart titles: Total Revenue Generated, Estimate of Revenue Generated

### Q5 - ProductbyCategory

- Raw data: `raw_data_sheet/q5_productbycategory.csv`
- SQL query: `sql_queries/q5_productbycategory.sql`
- Visuals: `visuals/q5_productbycategory/`
- Source workbook: `source_workbooks/Q5_ProductbyCategory.xlsx`
- Chart titles: Product Performance by Category, Count of Products by Category

### Q6 - High-Value Customers

- Raw data: `raw_data_sheet/q6_high_value_customers.csv`
- SQL query: `sql_queries/q6_high_value_customers.sql`
- Visuals: `visuals/q6_high_value_customers/`
- Source workbook: `source_workbooks/Q6_High-Value Customers.xlsx`
- Chart titles: High Value Customers, Customers who have placed more than 10 orders

### Q7 - Average Order Value by Customer

- Raw data: `raw_data_sheet/q7_average_order_value_by_customer.csv`
- SQL query: `sql_queries/q7_average_order_value_by_customer.sql`
- Visuals: `visuals/q7_average_order_value_by_customer/`
- Source workbook: `source_workbooks/Q7_Average Order Value by Customer.xlsx`
- Chart titles: Average Order Value by Customer

### Q8 - Suppliers with Multiple Products

- Raw data: `raw_data_sheet/q8_suppliers_with_multiple_products.csv`
- SQL query: `sql_queries/q8_suppliers_with_multiple_products.sql`
- Visuals: `visuals/q8_suppliers_with_multiple_products/`
- Source workbook: `source_workbooks/Q8_Suppliers with Multiple Products.xlsx`
- Chart titles: Suppliers with 5 Products and above, Suppliers with multiple products (5 products and above)

### Q9 - Countries with High Customer Base

- Raw data: `raw_data_sheet/q9_countries_with_high_customer_base.csv`
- SQL query: `sql_queries/q9_countries_with_high_customer_base.sql`
- Visuals: `visuals/q9_countries_with_high_customer_base/`
- Source workbook: `source_workbooks/Q9_Countries with High Customer Base.xlsx`
- Chart titles: Countries with High Customer Base, Countries that have more than 5 customers

### Q10 - Orders Without Shipment

- Raw data: `raw_data_sheet/q10_orders_without_shipment.csv`
- SQL query: `sql_queries/q10_orders_without_shipment.sql`
- Visuals: `visuals/q10_orders_without_shipment/`
- Source workbook: `source_workbooks/Q10_Orders Without Shipment.xlsx`
- Chart titles: Orders Without Shipment, orders that have not been shipped yet

## Summary table

| Question | Topic | Raw rows | Raw columns | Visual pages |
|---|---|---:|---:|---:|
| Q1 | list of unique countries where customers are located | 91 | 2 | 2 |
| Q2 | customers who do not have a region assigned | 60 | 3 | 2 |
| Q3 | total business activity | 1 | 2 | 2 |
| Q4 | Total Revenue Generated | 1 | 2 | 2 |
| Q5 | ProductbyCategory | 8 | 2 | 2 |
| Q6 | High-Value Customers | 28 | 3 | 2 |
| Q7 | Average Order Value by Customer | 91 | 3 | 2 |
| Q8 | Suppliers with Multiple Products | 2 | 3 | 1 |
| Q9 | Countries with High Customer Base | 5 | 2 | 1 |
| Q10 | Orders Without Shipment | 3 | 3 | 1 |

## Notes

- SQL files were extracted as provided from the uploaded workbooks and were not edited.
- Raw data sheets were exported to CSV for easier review and version control.
- Visuals were rendered from each workbook's visualization sheet and saved as PNG files.
- The original Excel workbooks are preserved unchanged in `source_workbooks/`.


