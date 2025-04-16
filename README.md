#  Task 6: Sales Trend Analysis Using Aggregations

##  Objective

Analyze *monthly revenue* and *order volume trends* using SQL aggregation techniques.

---

##  Tools & Technologies

- SQL (PostgreSQL / MySQL / SQLite)
- Dataset: online_sales  
  - Table: orders  
  - Columns: order_date, amount, product_id, order_id

---

##  Deliverables

- SQL script: sales_trend_analysis.sql
- Result table (output of the query showing monthly revenue and order volume)

---

##  Task Breakdown

| Step | Description |
|------|-------------|
| a.   | Extract *month* and *year* from order_date using EXTRACT() or strftime() depending on the SQL dialect. |
| b.   | Use SUM(amount) to calculate *monthly revenue*. |
| c.   | Use COUNT(DISTINCT order_id) to calculate *monthly order volume*. |
| d.   | Use GROUP BY year, month to aggregate data accordingly. |
| e.   | Sort results with ORDER BY year, month to visualize trends. |
| f.   | Apply LIMIT or WHERE clause to filter results for specific time frames (e.g., a specific year or quarter). |

---

##  Outcome

You’ll gain hands-on experience in:

- Using SQL date functions for *time-based aggregation*
- Analyzing *sales trends over time*
- Understanding customer behavior using *monthly revenue and order volume metrics*

---

##  Sample Output Format

| Year | Month | Total Revenue | Order Volume |
|------|-------|----------------|---------------|
| 2023 | 01    | 15000.00       | 345           |
| 2023 | 02    | 17300.50       | 367           |
| ...  | ...   | ...            | ...           |

---
