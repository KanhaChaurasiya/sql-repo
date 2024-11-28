Check status of your order.
SELECT * FRON Products
ORDER BY Price;

Find total amount of your order.
SELECT customer_id,SUM(total_amount)FROM orders GROUP BY customer_id;

Update your city.
UPDATE table_name
SET column1=value1, column2=value2,
WHERE condition;

Change Product Description.
ALTER TABLE table_name
RENAME COLUMN
old_column_name TO
new_column_name;

Display returnable products.
CREATE OR REPLACE VIEW view_name
AS
SELECT column1, column2,
FROM table_name
WHEREcondition;
