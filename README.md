**Dataset Description :-**

| Column Name     | Description                                                                                           |
| --------------- | ----------------------------------------------------------------------------------------------------- |
| **InvoiceNo**   | Unique identifier for each invoice. Duplicate values indicate multiple items in a single transaction. |
| **StockCode**   | Product (item) code for each sold item.                                                               |
| **Description** | Product name or description.                                                                          |
| **Quantity**    | Number of units sold per item. Negative values indicate returns.                                      |
| **InvoiceDate** | Date and time when the transaction occurred.                                                          |
| **UnitPrice**   | Price per unit (in pounds sterling).                                                                  |
| **CustomerID**  | Unique numeric identifier for each customer.                                                          |
| **Country**     | Country where the customer resides or where the order was billed/shipped.                             |


**Data Notes :-**

1. Contains over 500,000 transaction records.

2. Includes some negative values in Quantity and UnitPrice (representing returns or errors).

3. Includes missing values in CustomerID which may require cleaning.
   
4. Time Period: December 2010 – December 2011

5. Primary Market: United Kingdom (with international transactions included).

**Dashboard Story :-**

1. This dashboard provides a comprehensive analysis of online retail sales transactions (2010–2011), focusing on revenue, customer behavior, and geographic performance.
2. This dashboard utilizes summary cards to show Key performance indicators as Total Revenue, Total customer purchases and Total Invoices.
3. It shows the "Monthly Revenue Trend", "Revenue and Quantity Sold over Country" and "Top-N Customers and their Total Spend".
4. This Dashboard gives the flexibility to users to filter the data based on Date Hierarchy, Country, Customers & Product which provides the detailed analysis.
