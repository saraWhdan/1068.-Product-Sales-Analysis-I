# 1068.-Product-Sales-Analysis-I
Problem Link: https://leetcode.com/problems/product-sales-analysis-i/?envType=study-plan-v2&envId=top-sql-50

## Solution

```sql
 SELECT p.product_name,s.year,s.price
  FROM Sales s
INNER JOIN Product p
ON p.product_id =s.product_id


